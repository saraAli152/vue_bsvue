

<template>
    <header>
   <NavBarItems/>
   <b-container >
    <b-row class="text-light  text-lg-start text-md-center  py-5">
      <b-col col lg="6" md="12"  class="py-5 "> 
        <h1  class="py-5">t's a Big World Out There,Explore</h1>
        <p class="fs-6 py-5 ">Image
                            It's a Big World Out There, Go Explore
                            A small river named Duden flows by their place and supplies it with
                             the necessary regelialia. 
                             It is a paradisematic country, in which roasted
                              parts of sentences fly into your mouth.
                            </p>
                            <div  >
                              <b-icon icon="caret-left-square-fill"></b-icon>
                     <b-link href="#foo" class="text-light m-1">watch video</b-link>
                    
                    </div>
      </b-col>
   
  </b-row>
  </b-container>

    </header>
</template>
<script>
import NavBarItems from './NavBarItems.vue'

export default {
  name: 'Content_Header',
  components: {
    NavBarItems
  }
}
</script>
<style>
header {
    background-image:linear-gradient(rgba(0, 0, 0, 0.25) ,rgba(0, 0, 0, 0.25)) ,url('../assets/hero_1.jpg');
    background-attachment: fixed;
    background-size:  cover;
    width:100%

}
b-link{
  text-decoration: none;
  color: #f17945;;
}
</style>
