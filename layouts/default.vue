<template>
  <div>
    <Navbar id="navbar" />
    <Nuxt />
    <Footer id="footer" />
  </div>
</template>

<style>
.whole{
  /*全体につける。index.vueで例を見るのが良いと思う*/
  margin:auto;
  padding:40px;
  background-color:white;
  box-shadow:0px 0px 5px 1px rgb(200, 200, 200);
  max-width:800px;
}
.whole h2{
  font-size:25px;
  margin-top:25px;
}
.whole h3{
  font-size: 20px;
  margin-top: 20px;
}
.whole article{
  margin-bottom: 3em;
}
@media screen and (max-width: 639px) {
  .whole{
    padding:40px 0.5em;
  }
}

.indent p{
  /*インデントをしたい記事の親要素につける*/
  text-indent: 1em;
}
.clearnum li{
  /*数字を消したいliの親要素のul/ol要素につける*/
  list-style: none;
  text-indent: -1.3em;
}
.hrLine{
  /*水平ライン(h2の下)*/
  width:102%;
  margin:0 -1% 1em;
}
</style>