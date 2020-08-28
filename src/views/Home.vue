  
<template>
  <div class="home">
    <div class="nav">
      <router-link to="/">前台頁面</router-link> |
      <router-link to='/products'>產品列表</router-link> |
      <router-link to='/Cart'>購物車</router-link> |
      
    </div>
    <router-view />
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Home',
  components: {
  }
}
</script>