<script setup>
import { ref } from 'vue';
const questions = []
const a1 = ref('');
const a2 = ref('');
const a3 = ref('');
const a4 = ref('');
const a5 = ref('');
const a6 = ref('');
const a7 = ref('');
const a8 = ref('');
const a9 = ref('');
const a10 = ref('');
const a11 = ref('');
const a12 = ref('');
const a13 = ref('');
const a14 = ref('');
const a15 = ref('');
const a16 = ref('');
const a17 = ref('');
const a18 = ref('');
const a19 = ref('');
const a20 = ref('');

const msg = "hi"

console.log(a1);
</script>

<template>
<div class="container">
<div class="row">
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q1 Vous aimez réfléchir seul : {{ a1 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a1" class="form-select form-select-sm" aria-label=".form-select-sm example">
        <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q2 Vous changez facilement d'avis : {{ a2 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a2" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q3 Vous vous expliquez avec clart et simplicité : {{ a3 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a3" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q4 Vous faites facilement la synthèse de plusieurs idées : {{ a4 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a4" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q5 Vous accordez le l'importance aux détails : {{ a5 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a5" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q6 Vous n'aimez pas les conflits : {{ a6 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a6" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q7 Vous n'aimez pas etre seul : {{ a7 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a7" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q8 Vous vous adaptez facilement au changement : {{ a8 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a8" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q9 Vous aimez découvrir : {{ a9 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a9" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q10 Vous attachez de l'importance à la réaction des autres : {{ a10 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a10" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q11 Vous aimez réfléchir seul : {{ a11 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a11" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q12 Vous changez facilement d'avis : {{ a12 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a12" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q13 Vous vous expliquez avec clart et simplicité : {{ a13 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a13" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q14 Vous faites facilement la synthèse de plusieurs idées : {{ a14 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a14" class="form-select form-select-sm" aria-label=".form-select-sm example">
        <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q15 Vous accordez le l'importance aux détails : {{ a15 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a15" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q16 Vous n'aimez pas les conflits : {{ a16 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a16" class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title" >Q17 Vous n'aimez pas etre seul : {{ a17 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a17" class="form-select form-select-sm" aria-label=".form-select-sm example">
        <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q18 Vous vous adaptez facilement au changement : {{ a18 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a18" class="form-select form-select-sm" aria-label=".form-select-sm example">
        <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q19 Vous etes chaleureux et ouvert : {{ a19 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a19" class="form-select form-select-sm" aria-label=".form-select-sm example">
        <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="col-sm-6 mt-3">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Q20 Vous attachez de l'importance à la réaction des autres : {{ a20 }}</h5>
        <label for="my-select">Select an option:</label>
        <select id="my select" v-model="a20" class="form-select form-select-sm" aria-label=".form-select-sm example">
        <option value="jamais">Jamais</option>
        <option value="parfois">Parfois</option>
        <option value="souvent">Souvent</option>
        <option value="toujours">Toujours</option>
    </select>
      </div>
    </div>
  </div>
  <div class="text-center mt-5">
  <button class="btn btn-primary " type="submit" > <RouterLink to="/about">About</RouterLink></button>
</div>
</div>
</div>
</template>
