<template>
      <footer class="site-footer">
      <div class="container">
        <div>
          <div class="col-sm-12 col-md-6">
            <h6>درباره ما</h6>
            <p class="text-justify">فروشگاه اینترنتی وو آنلاین  ، فعالیت خود را بصورت جدی از سال 99 اغاز نموده و بطور تخصصی در زمینه عرضه بازیهای بلیزارد و استیم فعالیت دارد. لازم به ذکر است قبل از این ما مدت طولانی سابقه موفق فروش در فضای مجازی را داشته ایم.حال به پاس قدردانی از اعتماد شما مشتریان عزیز تصمیم گرفته ایم فعالیت خود را گسترش دهیم و در زمینه های تخصصی دیگر در حوزه گیم وارد شویم تا بتوانیم خدمات حرفه ای تری را به شما ارائه دهیم.یکی از این حوزه ها بررسی تخصصی بازی ها و پوشش اخبار مختلف در این باره است.از این که با ما همراهید از شما سپاسگذاریم.</p>
          </div>

          <div>
            <h6>لینک ها</h6>
            <ul class="footer-links">
              <li><RouterLink class="routerlink" to="/">Home</RouterLink></li>
              <li><RouterLink class="routerlink" to="/about">About Us</RouterLink></li>
              <li><RouterLink class="routerlink" to="/contact">Contact Us</RouterLink></li>
            </ul>
          </div>
        </div>
        <hr>
      </div>
      <div class="container">
      </div>
</footer>
</template>
<style>
.routerlink {
  color: #ffffff;
}
.site-footer
{
    padding:45px 0 20px;
  font-size:15px;
  line-height:24px;
  color:#fffcfc;
  text-align: center;
  background-image: linear-gradient(rgb(48, 115, 124), rgb(59, 27, 27))
}
.site-footer h6
{
  color:#000000;
  font-size:16px;
  text-transform:uppercase;
  margin-top:5px;
  letter-spacing:2px
}
.footer-links
{
  padding-left:0;
  list-style:none
}
.footer-links li
{
  display:block
}
@media (max-width:991px)
{
  .site-footer [class^=col-]
  {
    margin-bottom:30px
  }
}
@media (max-width:767px)
{
  .site-footer
  {
    padding-bottom:0
  }
}
</style>