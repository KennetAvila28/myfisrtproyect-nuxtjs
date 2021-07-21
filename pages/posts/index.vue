<template>
  <div>
    <h1>Posts</h1>
    <Post :name="post.title" :id="post.id" v-for="post of posts" :key="post.id"/>
  </div>
</template>
<script>
import axios from 'axios'
import Post from '../../components/Post'
export default {
  components: {
    Post,
  },
  data() {
    return {
      posts: [],
    }
  },
  async created() {
    try {
      //create a const variable to hold axios get request jsonplaceholder
      const res = await axios.get('https://jsonplaceholder.typicode.com/posts')
      //print the response
      this.posts = res.data
    } catch (e) {
      console.log(e)
    }
  },
}
</script>
