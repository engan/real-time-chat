<template>
  <div class="navbar">
    <nav class="nav-extended">
      <div class="nav-content">
        <router-link :to="{ name: 'Index' }">
          <span class="nav-title">Neoweb Chat - Firestore real time capabilities</span>
        </router-link>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
    name: 'Navbar',
    data() {
        return {

        }
    }
}
</script>


<style>
.navbar nav {
    padding: 0 20px;
}
.nav-extended {
    background-color: #009688;
}
</style>
