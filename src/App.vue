<template>
  <div class="root">
    <Header/>
    <Slider/>
    <OurActivities/>
    <Blog/>
    <Team/>
    <Gallery/>
    <FooterForm/>
    <Footer/>
  </div>
</template>


<script>
import Header from "./components/Header.vue"
import Slider from "./components/Slider.vue"
import OurActivities from "./components/OurActivities.vue";
import Blog from "./components/Blog.vue";
import Team from "./components/Team.vue";
import Gallery from "./components/Gallery.vue";
import FooterForm from "./components/FooterForm.vue";
import Footer from "./components/Footer.vue";
export default{
  components:{
  Header,
  Slider,
  OurActivities,
  Blog,
  Team,
  Gallery,
  FooterForm,
  Footer
}
}

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
*{
  font-family: 'Montserrat', sans-serif;
  box-sizing: border-box;
}
</style>
