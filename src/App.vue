<template>
  <div class="container">
    <AddUser />
    <Users />
  </div>
</template>

<script>
import AddUser from './components/AddUser'
import Users from './components/Users'

export default {
  name: 'App',
  components: {
   	AddUser,
    Users
  }
}
</script>

<style>
  .container {
    max-width: 500px;
    padding-top: 50px;
  }
</style>