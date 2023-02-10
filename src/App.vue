<template>
  <div class="container my-5">
    <h1 class="title text-center">Weather in</h1>
    <form class="search-location">
      <input
        type="text"
        class="form-control text-muted form-rounded p-4 shadow-sm"
        placeholder="What City?"
        autocomplete="off"
      />
    </form>
    <div class="card rounded my-3 shadow-lg back-card overflow-hidden">
      <div class="card-top text-center" style="margin-bottom: 15rem">
      <div class="city-name my-3">
        <p>Phuket</p>
        <span>...</span>
        <p class="">TH</p>
      </div>
    </div>
   

    <div class="card-body">
      <!-- card middle starts here -->
      <div class="card-mid">
        <div class="row">
          <div class="col-12 text-center temp">
            <span>20&deg;C</span>
            <p class="my-4">Clouds everywhere</p>
          </div>
        </div>
        <div class="row">
          <div class="col d-flex justify-content-between px-5 mx-5">
            <p>
              <img src="./assets/down.svg" alt="" />
              18&deg;C
            </p>
            <p>
              <img src="./assets/up.svg" alt="" />
              25&deg;C
            </p>
          </div>
        </div>
      </div>
      <!-- card bottom starts here -->
      <div class="card-bottom px-5 py-4 row">
        <div class="col text-center">
          <p>20&deg;C</p>
          <span>Feels like</span>
        </div>
        <div class="col text-center">
          <p>55%</p>
          <span>humidity</span>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
</style>
