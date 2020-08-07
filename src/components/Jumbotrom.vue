<template>
 
  <div class="jumbotrom">
      <h1>Bienvenidos</h1>
      <h5>Millones de Peliculas, programas de television y personas por descubrir. Explora ahora</h5>
        <div class="jumbo-find">
            <input type="text" placeholder="Buscar una pelicula, programa de television, persona"/>
            <button>Search</button>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Jumbotrom',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*JUMBOTROM*/

.jumbotrom{
    background-image: linear-gradient(to right, rgba(var(--tmdbDarkBlue), 0.8) 0%, rgba(var(--tmdbDarkBlue), 0) 100%), url('https://image.tmdb.org/t/p/w1920_and_h600_multi_faces_filter(duotone,032541,01b4e4)/yGNnjoIGOdQy3douq60tULY8teK.jpg');
    height: 310px;
    background-size:cover;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    color:white;
    padding: 4rem 2rem;

}
.jumbotrom h1
{
    font-size: 3em;
    font-weight: 700;
    line-height: 1;
    

}

.jumbotrom h5{
    font-size: 1.6em;
    font-weight: 600;
    margin: 0;

}

.jumbo-find{
    width: 100%;
    display: flex;
    flex-direction: row;
    margin-top: 3rem;
}

.jumbotrom button{
    background:linear-gradient(to right, rgba(var(--tmdbLightGreen), 1) 0%, rgba(var(--tmdbLightBlue), 1) 100%);
    color:white;
    height: 3rem;
    width: 7rem;
    border: none;
    border-radius: 30px;
    position: relative;
    right: 40px;
    font-weight: bolder;
    font-size: 1rem;

}

.jumbotrom input{
    height: 3rem;
    border: none;
    margin-right: none;
    border-radius: 30px;
    width: 100%;
    padding: 1rem;
    
    
}

/*END JUMBOTROM*/

</style>
