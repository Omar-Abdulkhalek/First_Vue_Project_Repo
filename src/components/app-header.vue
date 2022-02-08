<template>
  <div class="container text-center mt-3">
    <h2>طور متجرك ووسع آفاق تجارتك مع سوق تطبيقات زد</h2>
    <p>
      طور تجاربك من خلال تطبيقات وحلول سوق تطبيقات زد التي تساعدك <br />
      في نمو أرباحك عبر إدارة عمليات متحرك بشكل فعال واحترافي
    </p>
    <button class="btn">
      تصفح التطبيقات &nbsp;
      <span><i class="icon fas fa-chevron-left"></i></span>
    </button>

    <div class="img-container">
      <img class="ellipse" src="../assets/Ellipse 250.png" alt="" />
      <img class="main" src="../assets/product03 1.png" alt="" />
      <img class="dot" src="../assets/Dot Pattern 2.png" alt="" />
    </div>
  </div>
</template>

<style scoped>
h2 {
  font-size: 36px;
  font-weight: 700;
  color: #8d5da7;
}

p {
  margin-top: 30px;
  font-size: 18px;
}

button {
  font-weight: 700;
  font-size: 18px;
  color: #fdb515;
  background-color: #8d5da7;
  padding: 15px 70px;
  border-radius: 10px;
  margin-top: 30px;
  transition: background-color 1s, color 2s;
}

button:hover {
  background-color: #fdb515;
  color: #8d5da7;
}

.icon {
  color: #fdb515;
  animation: puls 2s infinite alternate-reverse;
  transform: scale(1);
}

@keyframes puls {
  0% {
    transform: scale(1);
  }
  25% {
    transform: scale(1.5);
  }
  75% {
    transform: scale(1);
  }

  100% {
    transform: scale(1.5);
  }
}

div.img-container {
  margin: 90px 0;
  position: relative;
}
div.img-container .main {
  width: 65%;
}

div.img-container .dot {
  position: absolute;
  left: 111px;
  top: -53px;
  z-index: -1;
}

div.img-container .ellipse {
  position: absolute;
  bottom: -91px;
  right: 100px;
  z-index: -1;
}

/* media query */
/*extra small screens */
@media all and (max-width: 576px) {
  h2 {
    font-size: 17px;
  }

  p {
    font-size: 10px;
  }

  button {
    font-size: 10px;

    padding: 10px 40px;

    margin-top: 30px;
  }

  div.img-container .main {
    width: 90%;
  }

  div.img-container .dot {
    position: absolute;
    left: -1px;
    top: -30px;
    z-index: -1;
    width: 25%;
  }

  div.img-container .ellipse {
    position: absolute;
    bottom: -44px;
    right: -15px;
    width: 50%;
    z-index: -1;
  }
}

/* small screen */
@media all and (min-width: 576px) and (max-width:786px){
  h2 {
    font-size: 20px;
    
  }

  p {
    font-size: 15px;
  }

  button {
    font-size: 15px;

    padding: 12px 50px;

    margin-top: 30px;
  }

  div.img-container .main {
    width: 90%;
  }

  div.img-container .dot {
    position: absolute;
    left: -1px;
    top: -30px;
    z-index: -1;
    width: 25%;
  }

  div.img-container .ellipse {
    position: absolute;
    bottom: -44px;
    right: -15px;
    width: 50%;
    z-index: -1;
  }
}



/* medium screen */
@media all and (min-width: 786px) and (max-width:992px){
  h2 {
    font-size: 30px;
    
  }

  p {
    font-size: 20px;
  }

  button {
    font-size: 20px;

    padding: 15px 60px;

    margin-top: 30px;
  }

  div.img-container .main {
    width: 90%;
  }

  div.img-container .dot {
    position: absolute;
    left: -1px;
    top: -30px;
    z-index: -1;
    width: 25%;
  }

  div.img-container .ellipse {
    position: absolute;
    bottom: -44px;
    right: -15px;
    width: 50%;
    z-index: -1;
  }
}

/* large screen */

@media all and (min-width: 992px) and (max-width:1200px){
  h2 {
    font-size: 36px;
    
  }

  p {
    font-size: 26px;
  }

  button {
    font-size: 26px;

    padding: 15px 50px;

    margin-top: 30px;
  }

  div.img-container .main {
    width: 90%;
  }

  div.img-container .dot {
    position: absolute;
    left: -1px;
    top: -30px;
    z-index: -1;
    width: 25%;
  }

  div.img-container .ellipse {
    position: absolute;
    bottom: -44px;
    right: -15px;
    width: 50%;
    z-index: -1;
  }
}

/* extra large screen */

@media all and (min-width: 1200px) {
  h2 {
    font-size: 36px;
  }

  p {
    font-size: 26px;
  }

  button {
    font-size: 26px;

    padding: 15px 50px;

    margin-top: 30px;
  }

  div.img-container .main {
    width: 70%;
  }

  div.img-container .dot {
    position: absolute;
    left: 101px;
    top: -50px;
    z-index: -1;
    width: 25%;
  }

  div.img-container .ellipse {
    position: absolute;
    bottom: -44px;
    right: -15px;
    width: 43%;
    z-index: -1;
  }
}


</style>

<script>
export default {};
</script>
