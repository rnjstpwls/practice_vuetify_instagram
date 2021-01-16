<template>
  <div>
    <Profile />
    <Introduce />
    <hr>
    <UserStatus />
    <hr>
  </div>
</template>

<script>
import Introduce from '../components/user/Introduce.vue'
import Profile from '../components/user/Profile'
import UserStatus from '../components/user/UserStatus.vue'
export default {
  name: 'ProfilePage',
  
  components: {
    Profile,
    Introduce,
    UserStatus,
  }

}
</script>

<style>

</style>