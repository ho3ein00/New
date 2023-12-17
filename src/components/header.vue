<template>
<div class="bgcolor">
  <div class="container">
    <div>
      <form>
        <input class="srchitem" type="search" id="searchcontent" placeholder="Search something">
      </form>
    </div>
    <div class="txtitem">
      New Game
    </div>
    <div class="amz item">
      <img src="@/assets/wow.jpg" alt="wow" class="wow">
    </div>
  </div>
</div>
</template>
<style scoped>
*{
  padding: 0;
  margin: 0;
}
.bgcolor {
  background-image: linear-gradient(rgb(48, 115, 124), rgb(59, 27, 27))
}
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 0;
  margin: 0 auto;
}
  .wow {
  border-radius:500px ;
  height: 4rem;
}
@media screen and (max-width: 1341px) {
  .container .wow {
    width: 4rem;
  }
}
@media screen and (max-width: 491px){
  .wow{
    display: none;
  }
}

@media screen and (max-width: 446px){
  .txtitem{
    display: none;
  }
}
.txtitem{
  color: white;
  font-size: 3rem;
}
.srchitem{
  background-color: rgb(255, 255, 255);
  border-radius: 20px;
  border-color: rgb(238, 0, 0);
  width: 300px;
  height: 40px;
}
</style>