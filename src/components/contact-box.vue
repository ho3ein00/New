<template>
  <div class="box">
      <div class="box__title">
        <h3>حسین</h3>
      </div>
      <div class="box__description">
        <p>
          لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می طلبد، 
        </p>
      </div>
      <div class="box__button">
        <button>دکمه</button>
      </div>
    </div>
</template>
<style scoped>
*{
  direction: rtl;
}
.box {
  box-shadow: 1px 1px .7rem #999;
  background-image: linear-gradient(rgba(109, 73, 6, 0.349),rgba(29, 15, 29, 0.555));
}
.box__title {
  display: flex;
  align-items: center;
  font-size: 1.5rem;
}
.box__title{
  width: 2rem;
  height: 4px;
  background-color: #666;
  display: inline-block;
  border-radius: 0 1rem 1rem 0;
}
.box__button {
  display: flex;
  justify-content: center;
}
.box__button>button {
  outline: none;
  border: 1px solid #999;
  background-color: rgb(245, 58, 1);
  padding: .5rem 1rem;
  border-radius: .3rem;
  color: white;
  letter-spacing: .05rem;
}
.box__description{
  direction: rtl;
  color: white;
}
</style>