<template>
    <!-- <section class="section section-lg section-shaped overflow-hidden my-0"> -->   
    <section>   
        <h1>BIENVENUE EN GUADELOUPE</h1>

                    <b-carousel id="carousel1"
                                controls
                                indicators>
                        <!-- Text slides with image -->
                         <b-carousel-slide class="font-primary"
                            caption=""
                            text="L'îLE PAPILLON"
                            img-src="img/brand/j4-9702.jpg">
                        </b-carousel-slide>
                         <b-carousel-slide class="font-primary"
                            caption=""
                            text="BESOIN D'ÉVASION?"
                            img-src="img/brand/thumb-1920-437755.jpg">
                        </b-carousel-slide>
                        <b-carousel-slide class="font-primary"
                            caption=""
                            text="ALORS N'HÉSITEZ PLUS!" 
                            img-src="img/brand/776838.jpg">
                        </b-carousel-slide>
                    </b-carousel>
            <p></p>



               
                <div class="container">
                <hr class="featurette-divider">
                <div class="row featurette">
                <div class="col-md-12 col-lg-6">
                    <h2 class="featurette-heading">"DES PAYSAGES À COUPER LE SOUFFLE"</h2>
                    <p class="lead">Partez en vacances en Guadeloupe, l'île papillon au cœur des Caraïbes.

          Au programme : plongez dans les eaux cristallines, partez en randonnée dans la forêt tropicale du nord, et goûtez aux spécialités locales comme par exemple : le fameux ti-punch accompagné d’acras de morue, ou alors le sorbet coco les pied dans l'eau.
          
          Mais le souvenir le plus intense que vous garderez de votre séjour en Guadeloupe, ce sont surtout les rencontres inoubliables avec sa population chaleureuse et accueillante.
            <br>
            <br>
           <button> Comment venir </button></p>
         
                </div>
                <div class="col-md-12 col-lg-6">
                    <img class="img" src="img/brand/rsz_volcan1.jpg" width="100%" height="100%"  alt="">
                </div>
                </div>
                <hr class="featurette-divider">        
                <div class="row featurette">
                <div class="order-1 col-md-12 order-2 col-lg-6">
                    <h2 class="featurette-heading">"UN ACCUEIL CONVIVIAL"</h2>
                    <p class="lead">La Guadeloupe mesure quatre-vingt kilomètres de long du nord au sud et trente-neuf kilomètres dans sa plus grande largeur.

          La célèbre Soufrière, son point le plus haut, s’élève à 1467 mètres, et offre des sentiers de randonnée à couper le souffle en plein cœur de la forêt tropicale !
          
          Les plages de sable blanc se situent principalement sur la Grange-Terre, réputé pour ses magnifiques anses et larges baies. Des eaux cristallines propices aux tortues, dauphins, étoiles de mer et autres merveilles sous-marines qu'offre la mer des Caraïbes.
          <br>
          <br>
          <button> Découvrir les plages </button></p>
                </div>
                <div class="order-2 col-md-12 order-1 col-lg-6 ">
                    <img src="img/brand/rectangle 10.png" width="100%" height="100%"  alt="">
                </div>
                </div>        
                <hr class="featurette-divider">            
                <div class="row featurette">
                <div class="col-md-12 col-lg-6">
                    <h2 class="featurette-heading">"DES RENCONTRES INATTENDUES"</h2>
                    <p class="lead">Un peu moins de quatre-cents mille habitants composent la population métissée guadeloupéenne.

          Cette diversité est l’illustration de l’histoire de l’ile, de son métissage et de ses occupants successifs : Indiens caraïbes, Européens, Africains, Indiens, Moyen-orientaux et Asiatiques.  
          
          Partout vous pourrez parler le français, langue officielle, mais aussi entendre les gualoupéens parler le créole, mélange de  vieux français, d’anglais, de dialectes africains et de quelques termes amérindiens.
          <br>
          <br>
          <button> Un peu d'histoire </button></p>
                </div>
                <div class="col-md-12 col-lg-6">
                    
                    <img src="img/brand/rsz_pa150282.jpg" width="100%" height="100%" alt="">
                </div>
                </div>
                </div>
                   
                 <div class="videodesk">
    <iframe width="460px" height="415px" src="https://www.youtube-nocookie.com/embed/fMySq5PzCho?start=1"
        frameborder="0"
        allow="accelerometer; autoplay=1&mute=0; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>
</div>
    </section>  
</template>

<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";
import { BCard } from "bootstrap-vue/esm/components/card";
import { BContainer, BCol, BRow } from "bootstrap-vue/esm/components/layout";

export default {
  components: {
    BCarousel,
    BCarouselSlide,
    BCard,
    BContainer,
    BCol,
    BRow
  },
  data () {
    return {
        message: 'Hello vue.js'
    }
  }
};
</script>