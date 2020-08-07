<template>
  <nav class="nav">
    <div class="nav-bar">
      <div class="nav-menu-wrapper">
          <div><img src="https://www.themoviedb.org/assets/2/v4/logos/v2/blue_short-8e7b30f73a4020692ccca9c88bafe5dcb6f8a62a4c6bc55cd9ba82bb2cd95f6c.svg" alt="The Movie Database (TMDb)" width="154" height="20"></div>
          <div class="nav-menu">
              <ul >
                  <li>
                     <a>Peliculas</a>
                  </li>
                  <li>
                     <a>Programas de Television</a>
                  </li>
                  <li>
                     <a>Personas</a>
                  </li>
                  <li>
                     <a>Mas</a>
                  </li>
              </ul>
          </div>

      </div>
      <div>Menu</div>
    </div>

    

  </nav>
 
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*HEADER*/

.nav {
    background-color: rgba(var(--tmdbDarkBlue), 1);
    color: white;
}

.nav-menu-wrapper{
    display: flex;
    flex-direction: row;
    justify-content:space-around;
    align-items: center;
}

.nav ul{
    list-style-type: none;
    display:flex;
    justify-content: space-around;
    
}

.nav ul li{
    margin:0px 1.5rem;
    font-weight: 600;
    font-size: .9rem;
}


.nav-bar {
  min-height: 3rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 0rem 6rem;
  align-items: center;
  height: 64px;
}

/*END HEADER*/
</style>
