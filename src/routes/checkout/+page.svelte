<script>
  import checkProImg from "../../assets/checkProImg.png";
  import checkAssetImg from "../../assets/checkAssetImg.png";
  import "./style.css";
</script>

<nav class="py-8 px-20 flex justify-between items-center max-sm:px-3">
  <div class="text-white nft-txt">Select NFTs</div>
  <div>
    <img src={checkProImg} alt="" class="w-10 h-10 rounded-full profile-img" />
  </div>
</nav>

<center>
  <img class="w-96 h-96 mt-4" src={checkAssetImg} alt="" />
</center>

<div class="px-48 flex flex-col gap-7 max-sm:p-3">
  <div>
    <p class="check-txt" style="">Checkout</p>
    <p class="art-txt">Artwork Details</p>
  </div>
  <div>
    <p class="delivery-txt">Delivery Method</p>
    <hr class="bg-gray-200 border-none" style="height: 0.1px;" />
  </div>
  <div class="flex items-center gap-5">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
      viewBox="0 0 640 512"
    >
      <path
        d="M624 384c8.75 0 16-7.25 16-16v-32c0-8.75-7.25-16-16-16h-608C7.25 320 0 327.3 0 336v32C0 376.8 7.25 384 16 384H64v64H16C7.25 448 0 455.3 0 464v32C0 504.8 7.25 512 16 512h608c8.75 0 16-7.25 16-16v-32c0-8.75-7.25-16-16-16H576v-64H624zM288 448H128v-64h160V448zM512 448h-160v-64h160V448z"
      />
    </svg>
    <div class="mt-2">
      <p class="chose-txt" style="">Choose a delivery method</p>
      <p class="enter-txt">Enter your shipping address</p>
    </div>
    <svg
      class="cls absolute right-48 max-sm:right-10 hover:cursor-pointer"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 320 512"
      style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
      ><path
        d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"
      /></svg
    >
  </div>
  <hr class="bg-gray-200 border-none" style="height: 0.1px;" />
  <div class="flex items-center gap-5">
    <div class="mt-2">
      <p class="meth-txt">Choose a delivery method</p>
      <p class="enter-txt">Specially delivery instruction</p>
    </div>
    <div class="relative hover:cursor-pointer">
      <div class="nfts-container" />

      <div class="absolute top-0 w-6 h-6 rounded-full bg-gray-700" />
    </div>
  </div>
  <div class="mt-5">
    <p class="delivery-txt">Selected NFTs</p>
    <hr class="bg-gray-200 border-none" style="height: 0.1px;" />
    <div class="flex gap-48 py-6">
      <div class="flex flex-col">
        <p class="delivery-txt">Artwork Name</p>
        <p class="chose-txt">Artwork Description</p>
      </div>
      <img class="checkout-img" src={checkAssetImg} alt="" />
    </div>
    <div class="flex gap-16">
      <p class="delivery-txt">Price</p>
      <button class="add-btn">Add</button>
    </div>
  </div>
  <hr class="bg-gray-200 border-none" style="height: 0.1px;" />
  <div class="flex gap-6 items-center">
    <svg
      class="hover:cursor-pointer"
      xmlns="http://www.w3.org/2000/svg"
      style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
      viewBox="0 0 448 512"
      ><path
        d="M416 208H272V64c0-17.67-14.33-32-32-32h-32c-17.67 0-32 14.33-32 32v144H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h144v144c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32V304h144c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z"
      /></svg
    >
    <p class="meth-txt">Add more nfts</p>
  </div>

  <hr class="bg-gray-200 border-none" style="height: 0.1px;" />

  <p class="mt-10 delivery-txt">Payment Details</p>
  <hr class="bg-gray-200 border-none" style="height: 0.1px;" />
  <div class="mt-2 flex items-center gap-6">
    <svg
      class="hover:cursor-pointer"
      xmlns="http://www.w3.org/2000/svg"
      style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
      viewBox="0 0 576 512"
      ><path
        d="M512 32C547.3 32 576 60.65 576 96V128H0V96C0 60.65 28.65 32 64 32H512zM576 416C576 451.3 547.3 480 512 480H64C28.65 480 0 451.3 0 416V224H576V416zM112 352C103.2 352 96 359.2 96 368C96 376.8 103.2 384 112 384H176C184.8 384 192 376.8 192 368C192 359.2 184.8 352 176 352H112zM240 384H368C376.8 384 384 376.8 384 368C384 359.2 376.8 352 368 352H240C231.2 352 224 359.2 224 368C224 376.8 231.2 384 240 384z"
      /></svg
    >
    <div>
      <p class="chose-txt">Choose a delivery method</p>
      <p class="enter-txt">
        Please add your Payment method to complete your order
      </p>
    </div>
  </div>
  <hr class="bg-gray-200 border-none" style="height: 0.1px;" />
  <div class="mt-2 flex items-center gap-6">
    <svg
      class="hover:cursor-pointer"
      xmlns="http://www.w3.org/2000/svg"
      style="width: 24px; height: 24px; overflow: visible; fill: rgb(255, 255, 255);"
      viewBox="0 0 512 512"
      ><path
        d="M480 128v208c0 97.05-78.95 176-176 176h-37.72c-53.42 0-103.7-20.8-141.4-58.58l-113.1-113.1C3.906 332.5 0 322.2 0 312C0 290.7 17.15 272 40 272c10.23 0 20.47 3.906 28.28 11.72L128 343.4V64c0-17.67 14.33-32 32-32s32 14.33 32 32l.0729 176C192.1 248.8 199.2 256 208 256s16.07-7.164 16.07-16L224 32c0-17.67 14.33-32 32-32s32 14.33 32 32l.0484 208c0 8.836 7.111 16 15.95 16S320 248.8 320 240L320 64c0-17.67 14.33-32 32-32s32 14.33 32 32l.0729 176c0 8.836 7.091 16 15.93 16S416 248.8 416 240V128c0-17.67 14.33-32 32-32S480 110.3 480 128z"
      /></svg
    >
    <div>
      <p class="chose-txt">Tip the artist</p>
      <p class="enter-txt">Optional tip for the artist</p>
    </div>
  </div>
  <hr class="bg-gray-200 border-none" style="height: 0.1px;" />
  <div class="total-card">
    <p class="m-10 delivery-txt">Price</p>
    <hr class="bg-gray-200 border-none" style="height: 0.06px;" />
    <div class="flex justify-between p-5 btn-container">
      <p>Sub Total</p>
      <p>Total Price</p>
    </div>
    <div class="flex justify-between p-5 btn-container">
      <p>Total</p>
      <p>Total</p>
    </div>
    <center>
      <button class="proceed-btn">Procced</button>
    </center>
  </div>
</div>
