<template>
<div>
 
  <div id="awrap">
  
    <h2 class="et-title mt4">Application skeleton</h2>
    <div class="et-background-accent et-white-text p2">
      <slot name="testslot">I want this replaced</slot>
    </div>
    <p>You  might be thinking that using Exotypography would be hard.  Well,  we have solved that problem for you.  We make it easy for you to use ET in your project.  It is as simple as adding one line of code to your project in some cases.  More advanced elements will have ways of easily configuring them so that they work great.  The best thing is that you get total control over the elements and only use the ones you want when you want.  This will keep your project fast and beautiful.</p>
    <footer>
    <div class="row mt2" style="max-width:375px; float:right">
      <div class="col" style="width:65px;"><img src="./assets/logo.png" width="65" ></div>
      <div class="col" style="text-align: right; "><span class="et-headline">{{ msg }}</span><br><span class="et-caption">We combine technology with human intent</span></div>
     </div>
    </footer>
    
</div>
</template>
<script>

export default {
data () {
return {
msg: 'FINDBORG COOPERATION'
}
}
}
</script>
<style lang="stylus" >
/*  Require ET Styles Framework */
/* @import "et/et"; */
/*  End of ET Styles Framework */




.intro-header{
background-color: #E1E6EC;
background-image: -webkit-linear-gradient(top, #E1E6EC 2%, #F0F4F7 96%), -webkit-radial-gradient(at 50% 100%, rgba(255, 255, 255, 0.2) 0%, rgba(0, 0, 0, 0.5) 200%);
background-image: linear-gradient(-180deg, #E1E6EC 2%, #F0F4F7 96%), radial-gradient(at 50% 100%, rgba(255, 255, 255, 0.2) 0%, rgba(0, 0, 0, 0.5) 200%);
background-blend-mode: normal, color-burn; }
#awrap{
max-width: 740px;
margin-left: auto;
margin-right: auto;
}
</style>