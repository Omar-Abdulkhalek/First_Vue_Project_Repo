<template>
  <div class="container-fluid text-center">
    <div class="text text-center">
      <h4>التطبيقات المميزه</h4>
      <p>تطبيقات تقدم حلول وخدمات مميزه نوصي بتجربتها</p>
    </div>
    <div class="row mt-4">
      <div class="col-xl-3 ">
        <div class="item">
          <div class="hero">
            <img
              src="../assets/bbaa6fd3-1070-4a1b-90c3-68c808870b26 1.png"
              alt=""
            />
            <div class="develope">
              <span class="main">قمرة</span>

              <i class="star fas fa-star"></i> 5
              <br />

              <span class="secondary">تطوير : عمر عبد الخالق </span>
            </div>
          </div>
          <p class="p1">نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك</p>
          <p>نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك</p>
        </div>
      </div>
      <div class="col-xl-3 ">
        <div class="item">
          <div class="hero">
            <img
              src="../assets/bbaa6fd3-1070-4a1b-90c3-68c808870b26 1.png"
              alt=""
            />
            <div class="develope">
              <span class="main">قمرة</span>

              <i class="star fas fa-star"></i> 5
              <br />

              <span class="secondary">تطوير : عمر عبد الخالق </span>
            </div>
          </div>
          <p class="p1">نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك</p>
          <p>نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك</p>
        </div>
      </div>

      <div class="col-xl-3 ">
        <div class="item">
          <div class="hero">
            <img
              src="../assets/bbaa6fd3-1070-4a1b-90c3-68c808870b26 1.png"
              alt=""
            />
            <div class="develope">
              <span class="main">قمرة</span>

              <i class="star fas fa-star"></i> 5
              <br />

              <span class="secondary">تطوير : عمر عبد الخالق </span>
            </div>
          </div>
          <p class="p1">نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك</p>
          <p>نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك</p>
        </div>
      </div>

      <div class="col-xl-3 ">
        <div class="item">
          <div class="hero">
            <img
              src="../assets/bbaa6fd3-1070-4a1b-90c3-68c808870b26 1.png"
              alt=""
            />
            <div class="develope">
              <span class="main">قمرة</span>

              <i class="star fas fa-star"></i> 5
              <br />

              <span class="secondary">تطوير : عمر عبد الخالق </span>
            </div>
          </div>
          <p class="p1">نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك</p>
          <p>نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك</p>
        </div>
      </div>
    </div>

    <button class="btn">
      تصفح التطبيقات &nbsp;
      <span><i class="icon fas fa-chevron-left"></i></span>
    </button>
  </div>
</template>

<style scoped>
.container-fluid {
  padding: 50px 80px;
  margin-top: 50px;
}

.text h4 {
  font-size: 24px;
  font-weight: 600;
}
.text p {
  font-size: 14px;
}
.item {
  padding: 20px;
  background-color: #f7f7f7;
  border-radius: 10px;
}
.item .hero {
  display: flex;
  align-items: center;
}

.item .develope {
  display: inline-block;
  margin: 0 20px 0 30px;
}
.item .develope .main {
  color: #8d5da7;
  font-weight: 600;
  display: inline-block;
  margin: 0 0 7px 25px;
}

.item .develope .star {
  color: #fdb515 ;
  
}
.item .develope .secondary {
  font-size: 10px;
  color: rgba(0, 0, 0, 0.56);
}

.item p {
    font-size:10px;
   
}

.item .p1{
     margin-top:20px;
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


/* media query */
/*extra small screens */
@media all and (max-width: 576px){

  .col-xl-3{
    margin-top:20px ;
  }

  
  button {
    font-size: 10px;
   
    padding: 10px 40px;

    margin-top: 30px;
  }
}

/* small screen */
@media all and (min-width: 576px) and (max-width: 786px){
   .col-xl-3{
    margin-top:20px ;
  }


  button {
    font-size: 15px;

    padding: 12px 50px;

    margin-top: 30px;
  }
}

/* medium screen */
@media all and (min-width: 786px) and (max-width: 992px){


 .col-xl-3{
    margin-top:20px ;
  }

  button {
    font-size: 20px;

    padding: 15px 60px;

    margin-top: 30px;
  }
}

/* large screen */

@media all and (min-width: 992px) and (max-width:1200px){


  .col-xl-3{
    margin-top:20px ;
  }

   button {
    font-size: 26px;

    padding: 15px 50px;

    margin-top: 30px;
  }
}


/* extra large screen */

@media all and (min-width: 1200px){
  button {
    font-size: 26px;

    padding: 15px 50px;

    margin-top: 30px;
  }
}




</style>

<script>
export default {};
</script>
