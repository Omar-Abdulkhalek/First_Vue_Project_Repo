<template>
  <div class="parent">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-5">
          <div class="text-icon-cont">
            <h5>كل ماتحتاجه لنمو متجرك في مكان واحد</h5>
            <p>
              مميزات سوق تطبيقات زد تساعدك في سهولة وسرعة الاستفاده من خدمات
              وحلول سوق التطبيقات لنمو متجرك وزيادة ارباحك
            </p>
            <div class="icons">
              <div class="item shadow">
                <i class="far fa-address-book"></i>
              </div>
              <div class="text">
                <p>سهولة ادارة وتفعيل تطبيقاتك من نفس لوحة تحكم متجرك</p>
              </div>
            </div>

            <div class="icons">
              <div class="item shadow">
                <i class="far fa-comment-dots"></i>
              </div>
              <div class="text">
                <p>دعم فني وتقني متكامل متوفر علي مدار الساعه</p>
              </div>
            </div>

            <div class="icons">
              <div class="item shadow">
                <i class="far fa-thumbs-up"></i>
              </div>
              <div class="text">
                <p>أسعار تنافسيه مع تجربه مجانيه وباقات اشتراك متنوعه</p>
              </div>
            </div>
            <div class="botn">
              <button class="btn">
                تصفح التطبيقات &nbsp;
                <span><i class="icon fas fa-chevron-left"></i></span>
              </button>
            </div>
          </div>
        </div>
        <div class="col-lg-7">
          <div class="imgs-cont">
            <img class="elipse" src="../assets/Ellipse 250.png" alt="" />
            <img class="main" src="../assets/zidapp_1-min 1.png" alt="" />
            <img class="dot-pattren" src="../assets/Dot Pattern 2.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
div.parent {
  margin-top: 160px;
  background-color: #fafafc;
}
div.col-md-5 {
  padding: 50px 90px 50px 0;
}

.text-icon-cont h5 {
  color: #8d5da7;
  font-size: 24px;
  font-weight: 700;
}

.text-icon-cont p {
  margin: 20px 0;
}
.text-icon-cont .icons {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}
.text-icon-cont .icons .item {
  width: 40px;
  height: 40px;
  background-color: #fff;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #8d5da7;
}

.text-icon-cont .icons .text {
  margin-right: 10px;
}

.text-icon-cont .icons .text p {
  font-size: 14px;
  font-weight: 600;
}

.imgs-cont {
  position: relative;
}

.imgs-cont .main {
  width: 90%;
  position: relative;
  z-index: 3;
}

.imgs-cont .dot-pattren {
  position: absolute;
  left: 30px;
  top: -43px;
  z-index: 0;
}

.imgs-cont .elipse {
  position: absolute;
  z-index: 0;
  right: -40px;
  bottom: -42px;
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
@media all and (max-width: 576px) {
  div.parent {
    margin-top: 100px;
    background-color: #fafafc;
  }

  .text-icon-cont h5 {
    font-size: 15px;
  }

  .text-icon-cont p {
    margin: 20px 0;
    font-size: 10px;
  }

  .text-icon-cont .icons .text p {
    font-size: 10px;
    font-weight: 600;
  }

  .imgs-cont {
    margin-top: 60px;
  }
  .imgs-cont .dot-pattren {
    width: 25%;
  }

  .imgs-cont .elipse {
    position: absolute;
    z-index: 0;
    right: -40px;
    bottom: -42px;
    width: 50%;
  }

  button {
    font-size: 10px;

    padding: 10px 40px;

    margin-top: 30px;
  }
}

/* small screen */
@media all and (min-width: 576px) and (max-width: 786px) {
  div.parent {
    margin-top: 100px;
    background-color: #fafafc;
  }

  .text-icon-cont h5 {
    font-size: 18px;
  }

  .text-icon-cont p {
    margin: 20px 0;
    font-size: 13px;
  }

  .text-icon-cont .icons .text p {
    font-size: 13px;
    font-weight: 600;
  }

  .imgs-cont {
    margin-top: 60px;
  }
  .imgs-cont .dot-pattren {
    width: 25%;
  }

  .imgs-cont .elipse {
    position: absolute;
    z-index: 0;
    right: -40px;
    bottom: -42px;
    width: 40%;
  }
  .imgs-cont .dot-pattren {
    position: absolute;
    left: 30px;
    top: -43px;
    z-index: 0;
  }

  button {
    font-size: 15px;

    padding: 12px 50px;

    margin-top: 30px;
  }
}

/* medium screen */
@media all and (min-width: 786px) and (max-width: 992px) {
  .imgs-cont {
    margin-top: 100px;
  }

  button {
    font-size: 20px;

    padding: 15px 60px;

    margin-top: 30px;
  }
}

/* large screen */

@media all and (min-width: 992px) and (max-width: 1200px) {
  .imgs-cont .elipse {
    position: absolute;
    z-index: 0;
    right: -40px;
    bottom: -42px;
    width: 45%;
  }

  button {
    font-size: 26px;

    padding: 15px 50px;

    margin-top: 30px;
  }
}

/* extra large screen */

@media all and (min-width: 1200px) {
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
