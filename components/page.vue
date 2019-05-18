<template>

  <div class="container">
   <div class="FirstBall"></div>
   <div class="MassMediaLinks">
      <i class="fab fa-linkedin-in"></i>
      <i class="fab fa-facebook-f"></i>
      <i class="fab fa-instagram"></i>
      <i class="fab fa-vk"></i>
   </div>
   <div class="Content">
     <div class="SecondBall"></div>
     <div class="Name">
       <h6>Elena Mikheeva</h6>
     </div>
   </div>
   <div class="Mail">
     <h3>eo.mikheeva@gmail.com</h3>
   </div>
   <div class="Phone">
      <h2>+7 (915) 369-43-96</h2>
   </div>
   <div class="OtherLinks">
     <div class="love">
        <p>In love with BI</p>
     </div>
     <div class="logo">
       <p>Founder & CEO of</p>
       <img src="/iw_logo_site.svg" alt="">
     </div>
   </div>
  </div>

</template>

<script>

</script>

<style lang="sass" scoped>
@import '../assets/variables'
@font-face
  font-family: Klaxons
  src: url(/Klaxons.otf)
@font-face
  font-family: AvenirNext
  src: url(/AvenirNextLTPro-Regular.otf)
@font-face
  font-family: AvenirNextLight
  src: url(/AvenirNextLTPro-UltLtCn.otf)
.container
  overflow: hidden
.FirstBall
  position: relative
  left: 86%
  width: 14%
  height: 200px
  border-radius: 0 0 15% 100% / 0 0 0% 100%
  background-color: #292929
  z-index: 1
.MassMediaLinks
  display: flex
  justify-content: center
  margin-top: 8%
.MassMediaLinks i
  font-size: 180%
  margin-right: 4%
  background: #646464
  border-radius: 50px
  padding: 10px
.MassMediaLinks i:nth-child(1)
  padding:
    left: 12px
    right: 12px
.MassMediaLinks i:nth-child(2)
  padding:
    left: 15px
    right: 15px
.MassMediaLinks i:nth-child(3)
  padding:
    left: 12px
    right: 12px
.Content
  display: flex
  margin-top: 7%
  align-items: center
.SecondBall
  position: absolute
  display: flex
  width: 200px
  height: 400px
  border-radius: 0 100% 100% 0 / 0 50% 50% 0
  background-color: #292929
  z-index: 1
.Name
  display: block
  margin-left: auto
  margin-right: auto
  z-index: 2
  justify-content: space-around
.Name h6
  color: #5199ff
  font-family: Klaxons
  font-size: 95px
  letter-spacing: 40px
  font-weight: normal
  flex-shrink: 0
.Mail
  display: flex
  justify-content: space-around
  margin-top: 6%
.Mail h3
  color: #A69F9F
  font-family: AvenirNext
  font-size: 39px
  font-weight: 200
  font-style: normal
  font-stretch: normal
  letter-spacing: normal
.Phone
  display: flex
  justify-content: space-around
  margin-top: 6%
.Phone h2
  color: #DCDADA
  font-family: AvenirNextLight
  font-weight: 200
  font-size: 51px
.OtherLinks
  display: flex
  font-family: AvenirNext
  color: white
  font-size: 20px
  margin:
    top: 8%
    bottom: 3%
  flex-direction: space-between
.love
  margin-left: 3%
  width: 100%
.love p
  margin-top: 2%
.logo
  display: flex
  align-items: center
  width: 100%
  margin:
     left: 63%
     right: 1%
.logo p
  margin-top: 2%
  flex-shrink: 0
.logo img
  margin-left: 3%
  width: 42px
</style>
