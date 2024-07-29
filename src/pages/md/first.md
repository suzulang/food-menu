---
title: '西红柿炒鸡蛋'
layout: '../../layouts/Layout.astro'
image: '/images/menu/tomato_egg.jpg'
description: '黄金'
link: '/md/first'
price: '10￥'
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/menu/tomato_egg.jpg" alt="camiseta" />
   <div class='flex flex-col gap-4'>
      <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>西红柿炒鸡蛋</h2>
      <p class='max-w-md'>
      1. <strong>准备材料</strong>：西红柿切块，打几个鸡蛋（加水和盐，炒出来会嫩一点）<br>
      2. <strong>炒鸡蛋</strong>：锅中倒入油，鸡蛋炒碎，差不多就出锅<br>
      3. <strong>炒西红柿</strong>：再倒一些油，翻炒西红柿，炒出汁<br>
      4. <strong>合炒</strong>：把鸡蛋倒入锅中，和西红柿一起翻炒<br>
      5. <strong>调味</strong>：加淀粉、盐、酱油等，根据喜好调节
      </p>
   </div>
</section>

<style>
   section{
      width:100%;
      min-height: calc(100vh - 52px)
   }

</style>
