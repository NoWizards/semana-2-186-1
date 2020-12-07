<template>
     
  <div style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSP2N_w1Rr0E6yWGOX0bJa_OWpUQkT978pteQ&usqp=CAU'); background-size: cover; ">
<div class="text-center text-white  bg-secondary bi bi-newspaper">
       <h4>NOTICIAS</h4>   
    </div>
  <div class="row mt-md-5 mt-sm-5 mt-xs-5">
      <div
        class="col-lg-6 col-xs-12"
        v-for="(noticia, index) of noticias"
        :key="index"
      >
        <div>
          <h3 class="bg-info text-white">
            {{ noticia.title }}
          </h3>
          <small class="font-italic">{{ noticia.description }}</small>
                   <hr class="my-4">
        </div>

        <div class="d-flex justify-content-center align-items-center">
          <div class="p-3">
            <img
              :src="noticia.urlToImage"
              alt="Imagen noticia"
              width="200"
              height="270"
              class="rounded"
            />
          </div>

          <div class="p-2">
           
              {{ noticia.content}}
              <br>     <br>
                 <a class="btn btn-outline-info" :href="noticia.url" target="_blank">Ver Noticia completa
                      <span class="bi bi-alarm-fill"></span>
            </a>

            <br>    
                               <hr class="my-4">
            <dl class="row">
              <dt class="col-sm-3">Autor:</dt>
              <dd class="col-sm-9">
                  {{noticia.author}}
              </dd>

              <dt class="col-sm-3">Fecha:</dt>
              <dd class="col-sm-9">
                <p>
                {{noticia.publishedAt}}
                </p>
                </dd>

            </dl>
          </div>
      
          
        </div>
       
       
      </div>
    </div>
           <hr class="my-4">

  </div>
</template>

<script>
import axios from "axios";
export default {
  name: "NoticiasApi",
  data() {
    return {
      noticias: null,
    };
  },
  mounted() {
    axios
      .get(
        "https://newsapi.org/v2/everything?q=perros&gatos&apiKey=3a15b514ec814f41a63f2071a55e9ae6"
      )
      .then((response) => {
        this.noticias = response.data.articles.slice(0, 4);
        console.log(this.noticias);
      });
  },
};
</script>

<style scooped>

</style>