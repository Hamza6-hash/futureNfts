<script>
  import productImg from "../../assets/productImg.jpeg";
  import otherProdImg from "../../assets/otherProductImg.png";
  import profileImg from "../../assets/profileImg.png";
  import "./style.css";
</script>

<nav class="py-4 px-6 flex justify-between items-center">
  <div class="text-white shop-txt">Shop By</div>
  <div>
    <button class="mr-2 create-btn">Create Account</button>
    <button class="px-4 py-2 rounded-lg login-btn">Log in</button>
  </div>
</nav>

<div class="flex justify-between">
  <div class="flex gap-4 ml-4 mt-3 wearText">
    <p>Women's Fashion</p>
    <p>Men's Fashion</p>
    <p>Kid's Fashion</p>
    <p>Beauty &</p>
    <p>Hobbies & Crafts</p>
    <p>Home & Decor</p>
  </div>
  <div class="flex mr-6 mt-3 items-center justify-center">
    <button class="sell-nfts">Sell You Art</button>
    <svg
      class="hover:cursor-pointer"
      xmlns="http://www.w3.org/2000/svg"
      style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
      viewBox="0 0 24 24"
      ><path fill="none" d="M0 0h24v24H0z" /><path
        d="M18 6h-2c0-2.21-1.79-4-4-4S8 3.79 8 6H6c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2zm-8 4c0 .55-.45 1-1 1s-1-.45-1-1V8h2v2zm2-6c1.1 0 2 .9 2 2h-4c0-1.1.9-2 2-2zm4 6c0 .55-.45 1-1 1s-1-.45-1-1V8h2v2z"
      /></svg
    >
  </div>
</div>

<div class="flex gap-2 max-sm:flex-col max-md:flex-col p-3">
  <div class="p-3 flex flex-col gap-4 max-sm:flex-row max-md:flex-row">
    <img class="product-img" src={otherProdImg} alt="" />
    <img class="product-img" src={otherProdImg} alt="" />
    <img class="product-img" src={otherProdImg} alt="" />
  </div>
  <div class="p-2">
    <img class="actual-product-img" src={productImg} alt="" />
  </div>

  <div class="flex flex-col">
    <div class="flex gap-7 justify-center">
      <p class="colorful-txt">Colorful Dress</p>
      <p class="py-1 buy-txt">Buy Now</p>
    </div>
    <div class="flex gap-3 mt-2">
      <img class="rounded-full w-10 h-10" src={profileImg} alt="" />
      <div>
        <div class="details-txt">
          <p>Artist: Silly Petit</p>
          <p>Location: London, UK</p>
        </div>
        <div class="flex">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
            viewBox="0 0 576 512"
            ><path
              d="M381.2 150.3L524.9 171.5C536.8 173.2 546.8 181.6 550.6 193.1C554.4 204.7 551.3 217.3 542.7 225.9L438.5 328.1L463.1 474.7C465.1 486.7 460.2 498.9 450.2 506C440.3 513.1 427.2 514 416.5 508.3L288.1 439.8L159.8 508.3C149 514 135.9 513.1 126 506C116.1 498.9 111.1 486.7 113.2 474.7L137.8 328.1L33.58 225.9C24.97 217.3 21.91 204.7 25.69 193.1C29.46 181.6 39.43 173.2 51.42 171.5L195 150.3L259.4 17.97C264.7 6.954 275.9-.0391 288.1-.0391C300.4-.0391 311.6 6.954 316.9 17.97L381.2 150.3z"
            /></svg
          >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
            viewBox="0 0 576 512"
            ><path
              d="M381.2 150.3L524.9 171.5C536.8 173.2 546.8 181.6 550.6 193.1C554.4 204.7 551.3 217.3 542.7 225.9L438.5 328.1L463.1 474.7C465.1 486.7 460.2 498.9 450.2 506C440.3 513.1 427.2 514 416.5 508.3L288.1 439.8L159.8 508.3C149 514 135.9 513.1 126 506C116.1 498.9 111.1 486.7 113.2 474.7L137.8 328.1L33.58 225.9C24.97 217.3 21.91 204.7 25.69 193.1C29.46 181.6 39.43 173.2 51.42 171.5L195 150.3L259.4 17.97C264.7 6.954 275.9-.0391 288.1-.0391C300.4-.0391 311.6 6.954 316.9 17.97L381.2 150.3z"
            /></svg
          >
        </div>
      </div>
    </div>
    <div class="mt-14 flex flex-col gap-10 sixteen-twentyTwo-txt">
      <p>Basic white-T shirt for sale. Brand new with tags.</p>
      <div>
        <p>Size: M</p>
        <p>Material: 100% Cotton</p>
        <p>Brand: Thrifted</p>
      </div>
      <div class="flex items-center gap-6">
        <button class="addCart-btn">Add to Cart</button>
        <svg
          class="hover:cursor-pointer"
          xmlns="http://www.w3.org/2000/svg"
          style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
          viewBox="0 0 512 512"
          ><path
            d="M0 190.9V185.1C0 115.2 50.52 55.58 119.4 44.1C164.1 36.51 211.4 51.37 244 84.02L256 96L267.1 84.02C300.6 51.37 347 36.51 392.6 44.1C461.5 55.58 512 115.2 512 185.1V190.9C512 232.4 494.8 272.1 464.4 300.4L283.7 469.1C276.2 476.1 266.3 480 256 480C245.7 480 235.8 476.1 228.3 469.1L47.59 300.4C17.23 272.1 .0003 232.4 .0003 190.9L0 190.9z"
          /></svg
        >
      </div>
    </div>
  </div>
</div>
