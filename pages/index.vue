<template>
  <div>
    <header class="grid grid-cols-2 bg-black text-white">
      <div id="logo" class="flex flex-row my-auto">
        <img src="/logo.png" class="h-16 w-16 m-5" alt="" />
        <div class="flex flex-col">
          <p class="my-auto text-3xl font-bold"> Protein Folding </p>
          <p class="-mt-3 pb-3 text-lg">Turn genetic code into folded protein structures</p>
        </div>
      </div>
      <div id="navigation" class="grid grid-cols-4 my-auto text-white text-2xl font-bold">
        <span>nav item 1</span>
         <span>nav item 2</span>
         <span>nav item 3</span>
         <span>nav item 4</span>
      </div>
    </header>
    <div class="flex h-screen h-[100vh] bg-[url('/hero-bg3.jpg')] bg-cover align-middle text-white text-center">
      <div class="m-auto">
        <button class="absolute my-auto text-white text-5xl bg-white hover:bg-slate-300 bg-opacity-20 hover:bg-opacity-20 backdrop-blur-md z-10 py-10 px-16 rounded-lg ">Start Here</button>
        <section id="slideshow" class="z-0">
            <!--<img id="mySlides" src="/hero-bg1.jpg" class="w-screen" alt="" />
            <img id="mySlides" src="/hero-bg2.jpg" class="w-screen" alt="" />
            <img id="mySlides" src="/hero-bg3.jpg" class="w-screen h-screen" alt="" />-->
        </section>
      </div>
    </div>
    <footer class="bg-black text-white m-auto">
      <p class="py-3 text-2xl font-bold text-center"> Made in 2022 in Malaysia </p>
    </footer>
  </div>
</template>

<script>
/*
// Automatic Slideshow - change image every 3 seconds
let myIndex = 0;
carousel();

function carousel() {
  let i;
  const x = document.getElementsByClassName('mySlides');
  for (i = 0; i < x.length; i++) {
    x[i].style.display = 'none';
  }
  myIndex++;
  if (myIndex > x.length) { myIndex = 1 }
  x[myIndex - 1].style.display = 'block';
  setTimeout(carousel, 3000);
}
*/
</script>
