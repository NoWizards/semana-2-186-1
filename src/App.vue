<template>
  <div id="app">
    <!-- Image and text -->
    <nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-dark ">
        <a class="navbar-brand " href="# ">
            <img src="https://getbootstrap.com/docs/4.5/assets/brand/bootstrap-solid.svg " width="30 " height="30
        " class="d-inline-block align-top " alt=" " loading="lazy "> Bootstrap
        </a>
        <div class="collapse navbar-collapse justify-content-end " id="navbarNav ">
            <ul class="navbar-nav ">
                <li class="nav-item active ">
                    <a class="nav-link " href="# ">Home <span class="sr-only ">(current)</span></a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link " href="# ">Features</a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link " href="# ">Pricing</a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link disabled " href="# " tabindex="-1 " aria-disabled="true ">Disabled</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- carousel -->
    <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="1" class=""></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="2" class=""></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <svg class="bd-placeholder-img bd-placeholder-img-lg d-block w-100" width="800" height="400" xmlns="http://www.w3.org/2000/svg"
                    preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: First slide"><title>Placeholder</title>
                    <rect
                        width="100%" height="100%" fill="#777"></rect><text x="50%" y="50%" fill="#555" dy=".3em">First slide</text></svg>
                <div class="carousel-caption d-none d-md-block">
                    <h5>First slide label</h5>
                    <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
                </div>
            </div>
            <div class="carousel-item">
                <svg class="bd-placeholder-img bd-placeholder-img-lg d-block w-100" width="800" height="400" xmlns="http://www.w3.org/2000/svg"
                    preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Second slide"><title>Placeholder</title>
                    <rect
                        width="100%" height="100%" fill="#666"></rect><text x="50%" y="50%" fill="#444" dy=".3em">Second slide</text></svg>
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
            </div>
            <div class="carousel-item">
                <svg class="bd-placeholder-img bd-placeholder-img-lg d-block w-100" width="800" height="400" xmlns="http://www.w3.org/2000/svg"
                    preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Third slide"><title>Placeholder</title>
                    <rect
                        width="100%" height="100%" fill="#555"></rect><text x="50%" y="50%" fill="#333" dy=".3em">Third slide</text></svg>
                <div class="carousel-caption d-none d-md-block">
                    <h5>Third slide label</h5>
                    <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>

<!-- services -->
<div class="container-fluid">
        <div class="row justify-content-center mb-5">
            <div class="col-sm-6 col-xs-12 col-lg-4 mt-5">
            
                <div class="card">
                        <div class="d-flex justify-content-center p-2">

                                <svg width="12em" height="12em" viewBox="0 0 16 16" class="bi bi-alarm-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" d="M6 .5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1H9v1.07a7.001 7.001 0 0 1 3.274 12.474l.601.602a.5.5 0 0 1-.707.708l-.746-.746A6.97 6.97 0 0 1 8 16a6.97 6.97 0 0 1-3.422-.892l-.746.746a.5.5 0 0 1-.707-.708l.602-.602A7.001 7.001 0 0 1 7 2.07V1h-.5A.5.5 0 0 1 6 .5zM.86 5.387A2.5 2.5 0 1 1 4.387 1.86 8.035 8.035 0 0 0 .86 5.387zM11.613 1.86a2.5 2.5 0 1 1 3.527 3.527 8.035 8.035 0 0 0-3.527-3.527zM8.5 5.5a.5.5 0 0 0-1 0v3.362l-1.429 2.38a.5.5 0 1 0 .858.515l1.5-2.5A.5.5 0 0 0 8.5 9V5.5z"
                                    />
                                </svg>
                            </div>
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            
            </div>
            <div class="col-sm-6 col-xs-12 col-lg-4 mt-5">
                <div class="card">
                    <div class="d-flex justify-content-center p-2">

                        <svg width="12em" height="12em" viewBox="0 0 16 16" class="bi bi-alarm-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M6 .5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1H9v1.07a7.001 7.001 0 0 1 3.274 12.474l.601.602a.5.5 0 0 1-.707.708l-.746-.746A6.97 6.97 0 0 1 8 16a6.97 6.97 0 0 1-3.422-.892l-.746.746a.5.5 0 0 1-.707-.708l.602-.602A7.001 7.001 0 0 1 7 2.07V1h-.5A.5.5 0 0 1 6 .5zM.86 5.387A2.5 2.5 0 1 1 4.387 1.86 8.035 8.035 0 0 0 .86 5.387zM11.613 1.86a2.5 2.5 0 1 1 3.527 3.527 8.035 8.035 0 0 0-3.527-3.527zM8.5 5.5a.5.5 0 0 0-1 0v3.362l-1.429 2.38a.5.5 0 1 0 .858.515l1.5-2.5A.5.5 0 0 0 8.5 9V5.5z"
                            />
                        </svg>
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
            <div class="col-sm-6 col-xs-12 col-lg-4 mt-5">
                    <div class="card">
                            <div class="d-flex justify-content-center p-2">

                                    <svg width="12em" height="12em" viewBox="0 0 16 16" class="bi bi-alarm-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                        <path fill-rule="evenodd" d="M6 .5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1H9v1.07a7.001 7.001 0 0 1 3.274 12.474l.601.602a.5.5 0 0 1-.707.708l-.746-.746A6.97 6.97 0 0 1 8 16a6.97 6.97 0 0 1-3.422-.892l-.746.746a.5.5 0 0 1-.707-.708l.602-.602A7.001 7.001 0 0 1 7 2.07V1h-.5A.5.5 0 0 1 6 .5zM.86 5.387A2.5 2.5 0 1 1 4.387 1.86 8.035 8.035 0 0 0 .86 5.387zM11.613 1.86a2.5 2.5 0 1 1 3.527 3.527 8.035 8.035 0 0 0-3.527-3.527zM8.5 5.5a.5.5 0 0 0-1 0v3.362l-1.429 2.38a.5.5 0 1 0 .858.515l1.5-2.5A.5.5 0 0 0 8.5 9V5.5z"
                                        />
                                    </svg>
                                </div>
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
            </div>
        </div>
    </div>

<!-- news -->
    <div class="container-fluid">
        <div class="row mt-md-5 mt-sm-5 mt-xs-5">
            <div class="col-lg-6 col-xs-12">
                <div class="d-flex justify-content-center align-items-center">
    
                    <div class="p-3">
                        <svg width="12em" height="12em" viewBox="0 0 16 16" class="bi bi-alarm-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M6 .5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1H9v1.07a7.001 7.001 0 0 1 3.274 12.474l.601.602a.5.5 0 0 1-.707.708l-.746-.746A6.97 6.97 0 0 1 8 16a6.97 6.97 0 0 1-3.422-.892l-.746.746a.5.5 0 0 1-.707-.708l.602-.602A7.001 7.001 0 0 1 7 2.07V1h-.5A.5.5 0 0 1 6 .5zM.86 5.387A2.5 2.5 0 1 1 4.387 1.86 8.035 8.035 0 0 0 .86 5.387zM11.613 1.86a2.5 2.5 0 1 1 3.527 3.527 8.035 8.035 0 0 0-3.527-3.527zM8.5 5.5a.5.5 0 0 0-1 0v3.362l-1.429 2.38a.5.5 0 1 0 .858.515l1.5-2.5A.5.5 0 0 0 8.5 9V5.5z"
                            />
                        </svg>
                    </div>
    
                    <div class="p-2">
                        <p>
                            1. Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore harum natus, aut, voluptate maiores saepe delectus
                            accusamus quibusdam officiis fugiat consequatur minus fugit, fuga asperiores! Eveniet alias doloremque
                            ratione dolorum!
                        </p>
                    </div>
    
                </div>
                <div class="d-flex container-fluid justify-content-end pb-2 mt-n2">
                    <button type="button" class="btn btn-outline-info">Info</button>
                </div>
            </div>
    
            <div class="col-lg-6 col-xs-12">
                <div class="d-flex justify-content-center align-items-center">
    
                    <div class="p-3">
                        <svg width="12em" height="12em" viewBox="0 0 16 16" class="bi bi-alarm-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M6 .5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1H9v1.07a7.001 7.001 0 0 1 3.274 12.474l.601.602a.5.5 0 0 1-.707.708l-.746-.746A6.97 6.97 0 0 1 8 16a6.97 6.97 0 0 1-3.422-.892l-.746.746a.5.5 0 0 1-.707-.708l.602-.602A7.001 7.001 0 0 1 7 2.07V1h-.5A.5.5 0 0 1 6 .5zM.86 5.387A2.5 2.5 0 1 1 4.387 1.86 8.035 8.035 0 0 0 .86 5.387zM11.613 1.86a2.5 2.5 0 1 1 3.527 3.527 8.035 8.035 0 0 0-3.527-3.527zM8.5 5.5a.5.5 0 0 0-1 0v3.362l-1.429 2.38a.5.5 0 1 0 .858.515l1.5-2.5A.5.5 0 0 0 8.5 9V5.5z"
                            />
                        </svg>
                    </div>
    
                    <div class="p-2">
                        <p>
                            2. Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore harum natus, aut, voluptate maiores saepe delectus
                            accusamus quibusdam officiis fugiat consequatur minus fugit, fuga asperiores! Eveniet alias doloremque
                            ratione dolorum!
                        </p>
                    </div>
    
                </div>
                <div class="d-flex container-fluid justify-content-end pb-2 mt-n2">
                    <button type="button" class="btn btn-outline-info">Info</button>
                </div>
            </div>
    
            <div class="w-100"></div>
    
            <div class="col-lg-6 col-xs-12">
                <div class="d-flex justify-content-center align-items-center">
    
                    <div class="p-3">
                        <svg width="12em" height="12em" viewBox="0 0 16 16" class="bi bi-alarm-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M6 .5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1H9v1.07a7.001 7.001 0 0 1 3.274 12.474l.601.602a.5.5 0 0 1-.707.708l-.746-.746A6.97 6.97 0 0 1 8 16a6.97 6.97 0 0 1-3.422-.892l-.746.746a.5.5 0 0 1-.707-.708l.602-.602A7.001 7.001 0 0 1 7 2.07V1h-.5A.5.5 0 0 1 6 .5zM.86 5.387A2.5 2.5 0 1 1 4.387 1.86 8.035 8.035 0 0 0 .86 5.387zM11.613 1.86a2.5 2.5 0 1 1 3.527 3.527 8.035 8.035 0 0 0-3.527-3.527zM8.5 5.5a.5.5 0 0 0-1 0v3.362l-1.429 2.38a.5.5 0 1 0 .858.515l1.5-2.5A.5.5 0 0 0 8.5 9V5.5z"
                            />
                        </svg>
                    </div>
    
                    <div class="p-2">
                        <p>
                            3. Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore harum natus, aut, voluptate maiores saepe delectus
                            accusamus quibusdam officiis fugiat consequatur minus fugit, fuga asperiores! Eveniet alias doloremque
                            ratione dolorum!
                        </p>
                    </div>
    
                </div>
                <div class="d-flex container-fluid justify-content-end pb-2 mt-n2">
                    <button type="button" class="btn btn-outline-info">Info</button>
                </div>
            </div>
    
            <div class="col-lg-6 col-xs-12">
                <div class="d-flex justify-content-center align-items-center">
    
                    <div class="p-3">
                        <svg width="12em" height="12em" viewBox="0 0 16 16" class="bi bi-alarm-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M6 .5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1H9v1.07a7.001 7.001 0 0 1 3.274 12.474l.601.602a.5.5 0 0 1-.707.708l-.746-.746A6.97 6.97 0 0 1 8 16a6.97 6.97 0 0 1-3.422-.892l-.746.746a.5.5 0 0 1-.707-.708l.602-.602A7.001 7.001 0 0 1 7 2.07V1h-.5A.5.5 0 0 1 6 .5zM.86 5.387A2.5 2.5 0 1 1 4.387 1.86 8.035 8.035 0 0 0 .86 5.387zM11.613 1.86a2.5 2.5 0 1 1 3.527 3.527 8.035 8.035 0 0 0-3.527-3.527zM8.5 5.5a.5.5 0 0 0-1 0v3.362l-1.429 2.38a.5.5 0 1 0 .858.515l1.5-2.5A.5.5 0 0 0 8.5 9V5.5z"
                            />
                        </svg>
                    </div>
    
                    <div class="p-2">
                        <p>
                            4. Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore harum natus, aut, voluptate maiores saepe delectus
                            accusamus quibusdam officiis fugiat consequatur minus fugit, fuga asperiores! Eveniet alias doloremque
                            ratione dolorum!
                        </p>
                    </div>
    
                </div>
                <div class="d-flex container-fluid justify-content-end pb-2 mt-n2">
                    <button type="button" class="btn btn-outline-info">Info</button>
                </div>
            </div>
    
        </div>
    </div>

<!-- members -->
<div class="container-fluid">
    <div class="row justify-content-center mb-5">
        <team-card v-for="(item, index) in team" :key="index" :member="item"></team-card>

    </div>
</div>  

<!-- Footer -->
<footer class="page-footer bg-secondary text-white pt-4">

    <!-- Footer Text -->
    <div class="container-fluid text-center text-md-left">

        <!-- Grid row -->
        <div class="row">

            <!-- Grid column -->
            <div class="col-md-6 mt-md-0 mt-3">

                <!-- Content -->
                <h5 class="text-uppercase font-weight-bold">Footer text 1</h5>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Expedita sapiente sint, nulla, nihil repudiandae
                    commodi voluptatibus corrupti animi sequi aliquid magnam debitis, maxime quam recusandae harum esse fugiat.
                    Itaque, culpa?</p>

            </div>
            <!-- Grid column -->

            <hr class="clearfix w-100 d-md-none pb-3">

            <!-- Grid column -->
            <div class="col-md-6 mb-md-0 mb-3">

                <!-- Content -->
                <h5 class="text-uppercase font-weight-bold">Footer text 2</h5>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Optio deserunt fuga perferendis modi earum commodi
                    aperiam temporibus quod nulla nesciunt aliquid debitis ullam omnis quos ipsam, aspernatur id excepturi
                    hic.</p>

            </div>
            <!-- Grid column -->

        </div>
        <!-- Grid row -->

    </div>
    <!-- Footer Text -->

    <!-- Copyright -->
    <div class="footer-copyright text-center py-1 bg-dark">© 2020 Copyright: DAD
    </div>
    <!-- Copyright -->

</footer>
<!-- Footer -->

  

  </div>
</template>

<script>
import TeamCard from './components/TeamCard.vue';

export default {
  name: 'App',
  components:{
    TeamCard
  },
  data(){
    return {
      team: [
        {
          codigo: 1,
          nombre: "Primer Integrante",
          descripcion: `Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus lobortis vel orci sed auctor. Nulla dignissim, ipsum eget volutpat congue, nunc magna dapibus nulla, fermentum hendrerit sapien metus faucibus leo. Maecenas accumsan a augue eu placerat.`,
          rol: "Tester",
          imagen: "./image/gabriel.png"
        },
                {
          codigo: 2,
          nombre: "Primer Integrante",
          descripcion: `Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus lobortis vel orci sed auctor. Nulla dignissim, ipsum eget volutpat congue, nunc magna dapibus nulla, fermentum hendrerit sapien metus faucibus leo. Maecenas accumsan a augue eu placerat.`,
          rol: "Arquitecto de Software",
          imagen: "./image/wizards.png"
        },
                {
          codigo: 3,
          nombre: "Primer Integrante",
          descripcion: `Esta obsesionada con las mascotas y con los perritos de tik-tok`,
          rol: "Desarrollador Backend",
          imagen: "./image/geraldine.jpeg"
        },
                {
          codigo: 4,
          nombre: "Primer Integrante",
          descripcion: `Antropologo egresado de la Universidad Nacional y en vista de que es muy malo jugando Age of Empires (1000 de mmr) decidió aprender a programar para darle un rumbo a su vida`,
          rol: "Desarrollador Frontend",
          imagen: "./image/juank.png"
        },
                        {
          codigo: 4,
          nombre: "El cxlon de JuanC",
          descripcion: `Antropologo egresado de la Universidad Nacional y en vista de que es muy malo jugando Age of Empires (1000 de mmr) decidió aprender a programar para darle un rumbo a su vida`,
          rol: "Desarrollador Frontend",
          imagen: "./image/juank.png"
        }
      ]
    }
  }
}
</script>

