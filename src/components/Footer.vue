<template>
  <footer>
    <div class="hero">
       <ul>
         <li>
           <h3>DC COMICS</h3>
         </li>
           <li>Charcters</li>
            <li>Comics</li>
             <li>Movies</li>
              <li>TV</li>
               <li>Games</li>
                <li>Videos</li>
                 <li>News</li>
           <li>
             <h3> SHOP </h3>
             </li>
                <li>Shop DC</li>
                  <li>Shop Dc Collectibles</li>  
       </ul>
       <ul>
         <li>
           <h3>DC</h3>
         </li>
         <li>Term of Use</li>
           <li>Privacy policy (New)</li>
             <li>Ad Choises</li>
               <li>Advertising</li>
                 <li>Jobs</li>
                   <li>Subscriptions</li>
                  <li>Talent Workshop</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>  
            <li>Shop Help</li>
          <li>Contact Us</li>
       </ul>
       <ul>
         <li>
           <h3>SITES</h3>
         </li>
          <li>DC</li>
           <li>MAD Magazine</li>
            <li> DC Kids</li>
             <li>DC Universe</li>
              <li>DC Power Visa</li>
       </ul>
       <div>
         <img class="logo" src="../assets/dc-logo-bg.png" alt="">
       </div>
    </div>
    <div class="follow">
     <button>
       Sign-Up Now
     </button>
     <ul >
       <li class="partner">
         <h4>FOLLOW US</h4>
       </li>
       <li class="partner">
         <img src="../assets/footer-facebook.png" alt="">
       </li>
       <li class="partner">
         <img src="../assets/footer-twitter.png" alt="">
       </li>
       <li class="partner">
         <img src="../assets/footer-youtube.png" alt="">
       </li>
       <li class="partner">
         <img src="../assets/footer-pinterest.png" alt="">
       </li>
       <li class="partner">
         <img src="../assets/footer-periscope.png" alt="">
       </li>
     </ul>
    </div>
  </footer>
</template>

<script>
export default {
name:'Footer'
}
</script >

<style scoped>
footer{
  font-family:sans-serif ;
}
.hero{
  height:350px;
  width: 100%;
  background: green;
  background-image: url(../assets/footer-bg.jpg);
  display: flex;
  justify-content: initial;
  color:grey
}

li{
  list-style: none;
  margin:3px
}
ul:first-child{
  margin-left:200px
}
h3{
  color:white
}
.logo{
height: 350px;
    margin-left: 220px;
}
.follow{
  height:100px;
  width:100%;
  background: rgba(0, 0, 0, 0.801);
  display:flex;
 
  align-content: center;
}

button{
     border: 2px solid #0077d9;
    height: 50px;
    background: transparent;
    margin-top: 20px;
    margin-left: 200px;
    padding: 0px 15px;
    color:white
}
h4{
  color:#0077d9;
  margin-left: 600px;
  margin-bottom:10px
}
.partner{
  display: inline-block;
  list-style: none;
  margin:10px
}


</style>