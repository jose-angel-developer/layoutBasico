<template>
  <!--Pagina de ionic-->
  <ion-page>
    <h1>Grid en Ionic</h1>
    <ion-grid>
      <ion-row>
        <ion-col size="4" offset="1">
          <div class="image-container">
            <img src="/rayo.png" alt="" srcset="">
            <p>Lorem ipsum dolor sit, amet consectetur 
              adipisicing elit. Tempora harum vitae, nobis 
              iure porro cupiditate voluptas impedit 
              esse molestias? Dolores nulla praesentium 
              quisquam, incidunt eius laudantium quam 
              commodi labore repudiandae!</p>
          </div>
        </ion-col>
        <ion-col size="6">
          <div class="image-container">
            <img src="/mater.png" alt="" srcset="">
            <p>Lorem ipsum dolor sit, amet consectetur 
              adipisicing elit. Tempora harum vitae, nobis 
              iure porro cupiditate voluptas impedit 
              esse molestias? Dolores nulla praesentium 
              quisquam, incidunt eius laudantium quam 
              commodi labore repudiandae!
              Lorem ipsum dolor sit, amet consectetur 
              adipisicing elit. Tempora harum vitae, nobis 
              iure porro cupiditate voluptas impedit 
              esse molestias? Dolores nulla praesentium 
              quisquam, incidunt eius laudantium quam 
              commodi labore repudiandae!
              Lorem ipsum dolor sit, amet consectetur 
              adipisicing elit. Tempora harum vitae, nobis 
              iure porro cupiditate voluptas impedit 
              esse molestias? Dolores nulla praesentium 
              quisquam, incidunt eius laudantium quam 
              commodi labore repudiandae!
            </p>
          </div>
        </ion-col>
      </ion-row>
    </ion-grid>
  </ion-page>
</template>

<script>

  import {IonPage, IonGrid, IonRow, IonCol} from '@ionic/vue';

export default {
  name: 'HomePage',
  components:{
    IonCol,
    IonPage,
    IonGrid,
    IonRow

  }

}
</script>

<style>
ion-grid{
  margin: auto;
  border: 1px solid black;
}
.image-container{
  max-width: 100%;
  max-height: 100%;
  display: block;
  margin: auto;
  border: 1px solid black;
}

img{
  max-width: 80%;
  height: 90px;
}
ion-row{
  text-align: center;
  height: 100px;
}

h1{
  text-align: center;
}
</style>