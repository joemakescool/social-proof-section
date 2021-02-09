<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div class="wrapper">
      <div class="sin-team">
        <img src="../assets/images/image-anne.jpg" alt="">
        <h2>Anne</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Et ex fugit libero maxime minus, placeat quae totam! Aut ea error laudantium? Animi consequuntur molestiae possimus vel. Adipisci, eligendi modi obcaecati omnis quae quaerat qui? Alias amet aut commodi, consectetur consequatur, eligendi nam natus perspiciatis ratione recusandae repudiandae tempora velit voluptatem.</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.wrapper {
  width: 1000px;
  margin: 70px auto;
}

.sin-team {
  width: 28%;
  float: left;
  margin: 15px;
  box-shadow: 0 2px 20px rgba(0, 0, 0, .8);

  & img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    float: left;
    margin: 40px 20px 30px 0;
    border: 5px solid #ffffff;
    shape-outside: circle();
  }
}

</style>
