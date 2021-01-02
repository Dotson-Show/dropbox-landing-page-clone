<template>
     <div class="navbar">
          <div class="brand">
               <img id="logo" src="../assets/dropb-log.svg" />
               <img id="brand-name" src="../assets/wordmark_white.svg" />
          </div>
          <nav>
               <ul class="nav-link">
                    <li id="for-teams" class="nav-item">
                         <a href="">For Teams</a>
                    </li>
                    <li class="nav-item">
                         <a href="">For Individuals</a>
                    </li>
               </ul>
               <ul class="nav-link">
                    <li id="signin-btn" class="nav-item">
                         <a href="">Sign In</a>
                    </li>
                    <li class="nav-item">
                         <a href="">Sign Up</a>
                    </li>
               </ul>

          </nav>
     </div>
</template>

<script>
     export default {
          name: 'NavBar',
     }
</script>

<style scoped>
.navbar {
     font-family: 'Atlas Grotesk Web', 'Open Sans', sans-serif;
     font-size: 16px;
     height: 90px;
     width: 100%;
     background-color: transparent;
     display: flex;
     padding: 0px 60px;
     align-items: center;
     position: fixed;
}

ul {
     list-style: none;
     display: flex;
     color: #ffffff;
}

a {
     text-decoration: none;
     color: white;
}

#logo {
     margin-right: 5px;
     height: 32px;
     width: 36px;
}

#brand-name {
     height: 29px;
     width: 118px;
}

nav {
     font-size: 16px;
     font-weight: 600px;
     display: flex;
     width: 83%;
     margin-left: auto;
     color: #ffffff;
     padding: 0px 20px;
     justify-content: space-between;
}

nav a:hover {
     text-decoration: underline;
}

#for-teams {
     margin-right: 30px;
}

#signin-btn {
     margin-right: 30px;
}
</style>