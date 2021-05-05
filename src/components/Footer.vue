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

    </div>
  </footer>
</template>

<script>
export default {
name:'Footer'
}
</script >

<style scoped>
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
    margin-left: 90px;
}
.follow{
  heigth:200px;
  width:100%;
  background-color:rgba(0, 0, 0, 0.74); 
}

</style>