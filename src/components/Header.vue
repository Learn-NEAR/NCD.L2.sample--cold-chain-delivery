<template>
  <header class="bg-indigo-50 py-10">
        <TopMenu/>
        <Profile/>
        <Banner/>
    </header>
</template>

<script>
import TopMenu from '../components/TopMenu.vue'
import Profile from '../components/Profile.vue'
import Banner from '../components/Banner.vue'
export default {
    components: {
        TopMenu,
        Profile,
        Banner
    }
}
</script>
