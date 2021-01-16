<template>
  <div>
    <Profile />
    <Introduce />
    <hr>
    <UserStatus />
    <hr>
    <ContentType />
    <ContentPreview />
  </div>
</template>

<script>
import ContentPreview from '../components/user/ContentPreview.vue'
import ContentType from '../components/user/ContentType.vue'
import Introduce from '../components/user/Introduce.vue'
import Profile from '../components/user/Profile'
import UserStatus from '../components/user/UserStatus.vue'
export default {
  name: 'ProfilePage',
  
  components: {
    Profile,
    Introduce,
    UserStatus,
    ContentType,
    ContentPreview,
  }

}
</script>

<style>

</style>