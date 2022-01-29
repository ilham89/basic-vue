<template>
  <div class="profile">
    <h1>This is a profile page</h1>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <div class="media d-flex align-items-center text-start">
            <img class="user-pic" src="../assets/logo.png" alt="logo" />
            <div class="media-body">
              <h5 class="mt-0">{{ firstName }} {{ lastName }}</h5>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa quo
              perferendis dolor rerum ipsum, recusandae tempore dolore.
              Voluptatibus minus, facilis in molestias autem architecto earum id
              praesentium deserunt doloribus nihil.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "profile",
  data: function () {
    return {
      firstName: "Ilham ",
      lastName: "Kukuh",
    };
  },
  components: {},
};
</script>

<style scoped>
.user-pic {
  height: 120px;
  width: 120px;
  border-radius: 200%;
}
.media-body {
  margin-left: 16px;
}
</style>
