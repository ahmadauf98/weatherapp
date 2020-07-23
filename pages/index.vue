<template>
  <div class="container">
    <b-row>
      <b-col cols="5">
        <b-card class="card">
          <b-row class="my-3 mx-3">
            <b-col class="pb-2"><b-button>Search for places</b-button></b-col>
            <b-col class="pb-2 d-flex justify-content-end">
              <b-button pill><BIconGeo /></b-button>
            </b-col>
          </b-row>

          <b-row class="background-pic my-3 mx-3">

          </b-row>
        </b-card>
      </b-col>

      <b-col cols="7"></b-col>
    </b-row>
  </div>
</template>

<script>
import { BIconGeo } from 'bootstrap-vue'
export default {
  components: {
    BIconGeo,
  },
}
</script>

<style>
.container {
  margin: 0;
  padding: 0;
  border: none;
  min-height: 100vh;
  color: white;
}

.card {
  background-color: #1e213a;
  min-height: 100vh;
  text-decoration: none;
}

.background-pic{
  background-image: url(~/);
}
</style>
