<template>
  <q-layout view="hHh lpR fff">

    <q-header bordered class="bg-transparent  text-white">
       <q-tabs class="" style="position: absolute; left:0%; margin-left:50px">
       <img  src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/white.png" alt="Xtrm" class="main-logo q-mr-xl">
          <router-link to="/">
             <q-tab name="images" label="Home" />
          </router-link>

          <router-link to="/newPage">
           <q-tab name="videos" label="Pages"  />
          </router-link>
          <q-tab name="c" label="showcases" />
          <q-tab name="x" label="blog" />
          <q-tab name="q" label="shop" />
          <q-tab name="m" label="pricing" />
          <q-tab name="y" label="contact us" />
          <q-icon class="q-ml-lg" name="search" style="width:100px; font-size:30px; cursor:pointer " ></q-icon>
          <q-icon name="shopping_bag" style=" font-size:30px; cursor:pointer " ></q-icon><p><sup>0</sup></p>

        </q-tabs>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer bordered class="bg-white text-black">
      <q-toolbar class="fit row wrap justify-evenly items-center content-center " >
        <q-toolbar-title class=" tolobar q-ml-xl text-h6">
        	   <span class="text-h6"> © XTRM</span>

            <span class="text-h6" >. AliXuB 2022.</span>



        </q-toolbar-title>
        <q-toolbar-title>
          <q-icon name="twitter" />
          <q-icon name="facebook" />
          <q-icon name="telegram" />
          <q-icon name="" />
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>

  </q-layout>
</template>
<style scoped>
.tolobar{
  margin-left: 200px;
}
</style>
