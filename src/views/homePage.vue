<script setup>
import mainFooter from '@/components/main-footer.vue';
import landscapeImage from '@/components/landscape-image.vue'
</script>
<template>
<div class="grid-container">
  <div class="grid-child">
    <img src="@/assets/image1.jpg" alt="image" class="img-head">
    <h1 class="imgname">اساسین کرید</h1>
  </div>
  <div class="grid-child">
    <img style="height: 730px;width: 100%;" src="@/assets/image2.jpg" alt="image" class="img-headd">
  </div>
</div>
<div class="main-txt">
  اساسینز کرید (به انگلیسی: Assassin's Creed)
  <br>
   یک بازی ویدئویی در سبک ترکیبی مخفی‌کاری، اکشن-ماجراجویی و جهان باز است. این بازی توسط استودیوی یوبی‌سافت مونترآل توسعه یافته و به وسیلهٔ یوبی‌سافت منتشر شده‌است. اساسینز کرید در نوامبر ۲۰۰۷ برای کنسول‌های پلی‌استیشن ۳ و اکس‌باکس ۳۶۰ انتشار یافت و نسخهٔ مایکروسافت ویندوز آن نیز در ۸ آوریل ۲۰۰۸ منتشر شد. نسخهٔ تبدیل‌شده و پیش‌درآمد این بازی برای نینتندو دی‌اس به نام اساسینز کرید: تاریخچه الطائر در ۵ فوریه ۲۰۰۸ عرضه شد.

داستان این بازی در دو زمان، ۲۰۱۲ میلادی و جنگ صلیبی سوم (۱۱۹۱) در سرزمین مقدس رخ می‌دهد. شخصیت اول آن در زمان حال، فردی به نام دزموند مایلز و در زمان گذشته، یکی از اعضای گروه حشاشین به نام الطائر بن لا أحد است. دزموند زندگی جدش را با کمک دستگاهی به نام «آنیموس» شبیه‌سازی و بازآفرینی می‌کند. الطائر، از اجداد دزموند، یک حشاشی ماهر در دوران جنگ صلیبی سوم بوده، که به دلیل اشتباهش در یک ماموریت، رتبه و جایگاهش را از دست می‌دهد و برای رسیدن به جایگاه پیشینش، باید مأموریت‌های متفاوتی را انجام دهد. این بازی اولین نسخه از مجموعه بازی‌های اساسینز کرید است و در آن، فرد بازیکن آزادانه توانایی کنترل الطائر را در چهار شهر دمشق، اورشلیم، عکا و مصیاف دارد.
</div>
<landscapeImage />
<mainFooter />
</template>
<style scoped>
*{
  background-image: linear-gradient(rgba(109, 73, 6, 0.349),rgba(29, 15, 29, 0.555));
}
@media screen and (max-width: 485px) {
  .img-headd {
    display: none;
  }
}
.grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
.img-head {
  width: 100%;
}
.main-txt {
  font-style: 1.5rem;
  direction: rtl;
  color: #fff;
}
.imgname{
  text-align: center;
  font-size: 5rem;
  color: azure;
}
</style>