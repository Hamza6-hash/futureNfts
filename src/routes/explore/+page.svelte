<script>
  import cardPic from "../../assets/cardPic.jpeg";
</script>

<nav class="py-4 px-6 flex justify-between items-center">
  <div
    class="text-white"
    style="color: #ffffff;
    font-size: 24px;
    font-family: Source Sans Pro;
    line-height: 28px"
  >
    Explore NFTs
  </div>
  <div>
    <button class="mr-2 create-btn">Create Account</button>
    <button
      class="px-4 py-2 rounded-lg login-btn"
      style=" background-color: #282828;">Log in</button
    >
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
  <p
    class="py-10"
    style=" color: #ffffff;
  font-size: 36px;
  font-family: Source Sans Pro;
  font-weight: 700;
  line-height: 48px;
  text-align: center;"
  >
    Hot Collection of India
  </p>
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
      <p
        style="color: #ffffff;
          font-size: 14px;
          font-family: Source Sans Pro;
          line-height: 20px;"
      >
        Indian Traditional Artwork
      </p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p
        style="color: #ffffff;
          font-size: 14px;
          font-family: Source Sans Pro;
          line-height: 20px;"
      >
        Indian Traditional Artwork
      </p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p
        style="color: #ffffff;
          font-size: 14px;
          font-family: Source Sans Pro;
          line-height: 20px;"
      >
        Indian Traditional Artwork
      </p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p
        style="color: #ffffff;
          font-size: 14px;
          font-family: Source Sans Pro;
          line-height: 20px;"
      >
        Indian Traditional Artwork
      </p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p
        style="color: #ffffff;
          font-size: 14px;
          font-family: Source Sans Pro;
          line-height: 20px;"
      >
        Indian Traditional Artwork
      </p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p
        style="color: #ffffff;
          font-size: 14px;
          font-family: Source Sans Pro;
          line-height: 20px;"
      >
        Indian Traditional Artwork
      </p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p
        style="color: #ffffff;
          font-size: 14px;
          font-family: Source Sans Pro;
          line-height: 20px;"
      >
        Indian Traditional Artwork
      </p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
  <div class="card px-5 py-5">
    <img src={cardPic} alt="" />
    <div class="px-2 py-2 flex flex-col justify-between">
      <p
        style="color: #ffffff;
          font-size: 14px;
          font-family: Source Sans Pro;
          line-height: 20px;"
      >
        Indian Traditional Artwork
      </p>
      <p class="text-xl font-semibold">$99.99</p>
    </div>
  </div>
</div>

<center>
  <button
    style=" width: 150px;
  height: 40px;
  padding: 0px 8px;
  border: 0;
  box-sizing: border-box;
  border-radius: 24px;
  background-color: #000000;
  color: #ffffff;
  font-size: 14px;
  font-family: Source Sans Pro;
  font-weight: 500;
  line-height: 16px;
  outline: none;">Learn More</button
  >
</center>

<style>
  nav .login-btn {
    width: 104px;
    height: 36px;
    padding: 0px 8px;
    border: 0;
    box-sizing: border-box;
    border-radius: 24px;
    background-color: #282828;
    color: #ffffff;
    font-size: 14px;
    font-family: "Source Sans Pro";
    font-weight: 500;
    line-height: 16px;
    outline: none;
  }
  nav .create-btn,
  div .sell-nfts {
    width: 112px;
    height: 36px;
    border: 0;
    box-sizing: border-box;
    border-radius: 24px;
    background-color: #000000;
    color: #ffffff;
    font-size: 14px;
    font-family: "Source Sans Pro";
    font-weight: 500;
    line-height: 16px;
    outline: none;
  }
  .wearText {
    color: #ffffff;
    font-size: 14px;
    font-family: "Source Sans Pro";
    font-weight: 500;
    line-height: 20px;
  }
  .cardCollection {
    width: 100%;
    height: 144px;
    background-color: rgba(40, 40, 40, 0.8);
    border-radius: 24px;
  }
  .btn button {
    width: 80px;
    height: 36px;
    padding: 0px 8px;
    border-radius: 24px;
    background-color: #373737;
    color: #bdbdbd;
    font-size: 14px;
    font-family: "Source Sans Pro";
    font-weight: 500;
    line-height: 16px;
    outline: none;
  }
  .card img {
    width: 17em;
    height: 21em;
    border-radius: 24px;
    /* background-image: url(./image.jpeg); */
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
  }
  /* .switch {
    top: 479px;
    left: 1220px;
    width: 38px;
    height: 20px;
    border-radius: 40px;
    color: #161616;
    background-color: #282828;
  } */
</style>
