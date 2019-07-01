<template>
  <div class="container">
    <ul>
      <li>
        <AppLink href="/" label="Home" />
        <AppLink href="/404" label="404" >About</AppLink>
      </li>
    </ul>

    <slot></slot>
  </div>
</template>

<script>
import AppLink from '../atoms/AppLink'
  export default {
    components: {
      AppLink
    }
  }
</script>

<style scoped>
  .container {
    max-width: 600px;
    margin: 0 auto;
    padding: 15px 30px;
    background: #f9f7f5;
  }
</style>