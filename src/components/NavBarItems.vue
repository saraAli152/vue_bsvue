<template>

<div>
  <b-navbar toggleable="lg" type="dark"  class="px-5">
    <b-navbar-brand href="#">
      <b-img :src= "require('../assets/LogoMakr-444lpX.png')" alt="Traveling"></b-img>
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item  href="#">Home</b-nav-item>
        <b-nav-item href="#" >About Us </b-nav-item>
        <b-nav-item href="#" >Content </b-nav-item>
        <b-nav-item-dropdown text="Services" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-button size="md" class="my-4 my-sm-0" style="background-color:#f17945;" type ="submit">primary</b-button>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>

</template>
<script>
export default {
  name: 'NavBarItems',
 
}
</script>
<style>
#nav-collapse{
    justify-content: flex-end;
}
b-button{
  background-color: #f17945;;
}

</style>