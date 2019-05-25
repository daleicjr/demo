<template lang="html">
  <div class="page">
    <div class="words">
      <h1 class="first-words">你好</h1>
      <h1 class="second-words">如果你正在经历心魔</h1>
      <h1 class="third-words">请继续前行</h1>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
.words {
  margin: 0 auto;
}
/*自定义一个透明度从0到1的动画，它的名称是fade-in*/
@keyframes fade-in{
    0%{ opacity: 0;}
    100%{opacity:1;}
}
@-webkit-keyframes fade-in{
    0%{ opacity: 0;}
    100%{opacity:1;}
}
@-ms-keyframes fade-in{
    0%{ opacity: 0;}
    100%{opacity:1;}
}
@-o-keyframes fade-in{
    0%{ opacity: 0;}
    100%{opacity:1;}
}
@-moz-keyframes fade-in{
    0%{ opacity: 0;}
    100%{opacity:1;}
}
.first-words {
  opacity: 0;           /*实现规定文字的状态是不显示的*/

  /*调用名称为fade-in的动画，全程动画显示时间4s，进入方式为ease，延时0s进入，播放次数1次*/
  animation: fade-in 5s ease 0s 1;
  -webkit-animation: fade-in 5s ease 0s 1;
  -moz-animation: fade-in 5s ease 0s 1;
  -o-animation: fade-in 5s ease 0s 1;
  -ms-animation: fade-in 5s ease 0s 1;

  /*规定动画的最后的状态为结束状态*/
  animation-fill-mode: forwards;
  -webkit-animation-fill-mode: forwards;
  -o-animation-fill-mode: forwards;
  -ms-animation-fill-mode: forwards;
  -moz-animation-fill-mode: forwards;
}
.second-words {
  /*实现规定文字的状态是不显示的*/
  opacity: 0;

  /*调用名称为fade-in的动画，全程动画显示时间4s，进入方式为ease，延时0s进入，播放次数1次*/
  animation: fade-in 5s ease 2s 1;
  -webkit-animation: fade-in 5s ease 2s 1;
  -moz-animation: fade-in 5s ease 2s 1;
  -o-animation: fade-in 5s ease 2s 1;
  -ms-animation: fade-in 5s ease 2s 1;

  /*规定动画的最后的状态为结束状态*/
  animation-fill-mode: forwards;
  -webkit-animation-fill-mode: forwards;
  -o-animation-fill-mode: forwards;
  -ms-animation-fill-mode: forwards;
  -moz-animation-fill-mode: forwards;
}
.third-words {
  /*实现规定文字的状态是不显示的*/
  opacity: 0;

  /*调用名称为fade-in的动画，全程动画显示时间4s，进入方式为ease，延时0s进入，播放次数1次*/
  animation: fade-in 5s ease 4s 1;
  -webkit-animation: fade-in 5s ease 4s 1;
  -moz-animation: fade-in 5s ease 4s 1;
  -o-animation: fade-in 5s ease 4s 1;
  -ms-animation: fade-in 5s ease 4s 1;

  /*规定动画的最后的状态为结束状态*/
  animation-fill-mode: forwards;
  -webkit-animation-fill-mode: forwards;
  -o-animation-fill-mode: forwards;
  -ms-animation-fill-mode: forwards;
  -moz-animation-fill-mode: forwards;

}
</style>
