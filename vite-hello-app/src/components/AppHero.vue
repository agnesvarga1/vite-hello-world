<script></script>
<template>
  <div class="jumbo-body">
    <!-- <img src="../assets/img/pic01.jpg" alt="building" /> -->
    <h1>This is a Jumbotron (kinda)</h1>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Enim animi
      minus, libero impedit reprehenderit mollitia perspiciatis dignissimos
      accusamus rerum illo, porro quae atque veritatis. Vel voluptatum optio ab
      quidem ipsam!
    </p>
    <button>Click here</button>
  </div>
</template>
<style scoped>
.jumbo-body {
  width: 100%;
  padding: 0.5rem 5rem 10rem;
  margin: 0 auto;
  border: 1px solid #888;
  border-radius: 20px;
  overflow: hidden;
  background-image: url("../assets/img/pic1.jpg");
  background-position: center;
  background-size: cover;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
h1,
p {
  text-align: start;
}
p {
  width: 50%;
  font-weight: 500;
}
button {
  background-color: #7dada2;
  color: #fff;
  font-weight: bold;
  margin-top: 1rem;
  box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px, rgba(0, 0, 0, 0.23) 0px 3px 6px;
}
</style>
