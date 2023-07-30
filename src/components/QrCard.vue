<template>
  <div class="container">
    <div class="d-flex flex-column align-center">
      <v-img class="qr-img" src="../assets/image-qr-code.png" />
      <p class="title">Improve your front-end skills by building projects</p>
      <p class="paragraph">
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </div>
</template>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Outfit:wght@300;700&display=swap");
.container {
  margin: auto;
  background-color: hsl(0, 0%, 100%);
  padding: 1rem;
  align-content: center;
  width: 20rem;
  border-radius: 1rem;
}
.qr-img {
  width: 20rem;
  border-radius: 1.5rem;
  margin-bottom: 2rem;
}
.title {
  color: hsl(218, 44%, 22%);
  font-family: "Outfit", sans-serif;
  font-size: 1.5rem;
  font-weight: bold;
  text-align: center;
}
.paragraph {
  color: hsl(220, 15%, 55%);
  font-size: 0.8rem;
  font-family: "Outfit", sans-serif;
  font-weight: bold;
  text-align: center;
  margin-top: .5rem;
  margin-bottom: 2rem;

}
</style>
