<script>
  import cardPic from "../../assets/cardPic.jpeg";
  import "./style.css";
</script>

<nav class="py-4 px-6 flex justify-between items-center">
  <div class="text-white explore-txt">Explore NFTs</div>
  <div>
    <button class="mr-2 create-btn">Create Account</button>
    <button class="px-4 py-2 rounded-lg login-btn">Log in</button>
  </div>
</nav>

<div class="flex justify-between">
  <div class="flex gap-4 ml-4 mt-3 wearText">
    <p>Womenswear NFTs</p>
    <p>Menswear NFTs</p>
    <p>Kidswear NFTs</p>
    <p>Beauty NFTs</p>
    <p>Hobbies NFTs</p>
    <p>Homewear NFTs</p>
  </div>
  <div class="flex mr-6 mt-3 items-center justify-center">
    <button class="sell-nfts">Sell NFTs</button>
    <svg
      class="hover:cursor-pointer"
      style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 24 24"
      ><path d="M0 0h24v24H0z" fill="none" /><path
        d="M7 18c-1.1 0-1.99.9-1.99 2S5.9 22 7 22s2-.9 2-2-.9-2-2-2zM1 2v2h2l3.6 7.59-1.35 2.45c-.16.28-.25.61-.25.96 0 1.1.9 2 2 2h12v-2H7.42c-.14 0-.25-.11-.25-.25l.03-.12.9-1.63h7.45c.75 0 1.41-.41 1.75-1.03l3.58-6.49A1.003 1.003 0 0 0 20 4H5.21l-.94-2H1zm16 16c-1.1 0-1.99.9-1.99 2s.89 2 1.99 2 2-.9 2-2-.9-2-2-2z"
      /></svg
    >
  </div>
</div>

<div class="cardCollection">
  <p class="py-10 hot-col-text">Hot Collection of India</p>
</div>

<div class="flex justify-between">
  <div class="flex gap-4 ml-4 mt-3 btn">
    <button>Size</button>
    <button>Color</button>
    <button>Brand</button>
    <button>Price</button>
  </div>
  <!-- <div class="flex mr-6 mt-3 items-center justify-center">
    <p>On Sale</p>
    <div class="switch" />
    <div class="switch" />
  </div> -->
</div>

<div
  class="grid grid-cols-1 gap-2 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4"
>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p class="indian-art-txt">Indian Traditional Artwork</p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p class="indian-art-txt">Indian Traditional Artwork</p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p class="indian-art-txt">Indian Traditional Artwork</p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p class="indian-art-txt">Indian Traditional Artwork</p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p class="indian-art-txt">Indian Traditional Artwork</p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p class="indian-art-txt">Indian Traditional Artwork</p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p class="indian-art-txt">Indian Traditional Artwork</p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p class="indian-art-txt">Indian Traditional Artwork</p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
</div>

<center>
  <button class="learn-btn">Learn More</button>
</center>

<!-- <style>
</style> -->
