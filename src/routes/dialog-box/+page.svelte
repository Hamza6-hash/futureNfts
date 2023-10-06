<script>
  import dialogImg1 from "../../assets/dialogImg1.png";
  import dialogImg2 from "../../assets/dialogImg2.png";
</script>

<!-- 
<div class="flex items-center justify-center">
  <div
    class="m-10"
    style=" width: 600px;
        height: 785px;
        background-color: #161616;
        border-radius: 24px;
        border: 1px solid #282828;
        box-sizing: border-box;"
  >
    <p
      class="m-10"
      style="color: #ffffff;
        font-size: 32px;
        font-family: Source Sans Pro;
        font-weight: 700;
        line-height: 40px;"
    >
      Checkout
    </p>
    <div
      style=" color: #ffffff;
        font-size: 16px;
        font-family: Source Sans Pro;
        font-weight: 700;
        line-height: 22px;
        text-align: right;"
      class="flex justify-between"
    >
      <p class="m-10">Items</p>
      <p class="m-10">Subtotal</p>
    </div>
    <div class="flex">
      <img
        class="m-10"
        style=" width: 120px;
        height: 120px;
        border-radius: 24px;"
        src={dialogImg1}
        alt=""
      />

      <div class="mt-10 flex flex-col">
        <p class="boldText">Artwork Size</p>
        <p class="textItem">Item #3333</p>
      </div>
      <div>
        <p class="priceText">$96</p>
      </div>
    </div>
  </div>
  <hr class="bg-gray-200 border-none" style="height: 0.1px;" />
</div>

<style>
  .boldText {
    color: #ffffff;
    font-size: 16px;
    font-family: "Source Sans Pro";
    font-weight: 700;
    line-height: 22px;
  }
  .textItem {
    color: #ffffff;
    font-size: 16px;
    font-family: "Source Sans Pro";
    font-weight: 500;
    line-height: 22px;
  }
  .priceText {
    color: #ffffff;
    font-size: 16px;
    font-family: "Source Sans Pro";
    font-weight: 700;
    line-height: 22px;
  }
</style> -->

<!-- <div class="container"> -->
<div class="flex items-center justify-center py-10">
  <div
    class="m-10 mediaSmall"
    style="width: 600px;
          height: auto;
          background-color: #161616;
          border-radius: 24px;
          border: 1px solid #282828;
         "
  >
    <p
      class="m-10"
      style="color: #ffffff;
          font-size: 32px;
          font-family: Source Sans Pro;
          font-weight: 700;
          line-height: 40px;"
    >
      Checkout
    </p>
    <div
      style="color: #ffffff;
          font-size: 16px;
          font-family: Source Sans Pro;
          font-weight: 700;
          line-height: 22px;
          text-align: right;"
      class="flex justify-between"
    >
      <p class="m-10">Items</p>
      <p class="m-10">Subtotal</p>
    </div>
    <div class="flex">
      <img
        class="m-10"
        style="width: 120px;
          height: 120px;
          border-radius: 24px;"
        src={dialogImg1}
        alt=""
      />
      <div class="mt-10 flex flex-col gap-4 textContainer">
        <p class="boldText">Artwork Size</p>
        <p class="textItem">Item #3333</p>
      </div>

      <div>
        <p class="priceText">$96</p>
      </div>
    </div>
    <div class="flex">
      <img
        class="m-10"
        style="width: 120px;
          height: 120px;
          border-radius: 24px;"
        src={dialogImg2}
        alt=""
      />
      <div class="mt-10 flex flex-col gap-4 textContainer">
        <p class="boldText">
          Artwork Name Of Me asdiuh aos jsadoifiwukjsd sadih
          asjdoiahsfjskljdoije kjasd iaks diukja ns
        </p>
        <p class="textItem">Item #3333</p>
      </div>
      <p class="priceText">$96</p>
    </div>
    <div class="flex justify-between">
      <p class="totalText m-10">Total</p>
      <p class="totalText m-10">$192</p>
    </div>
    <div class="m-10 flex gap-4">
      <input
        style=" width: 20px;
      height: 20px;
      border-radius: 5px;
      color: #161616;
      background-color: #282828;"
        type="checkbox"
      />
      <p
        style="color: #ffffff;
      font-size: 16px;
      font-family: Source Sans Pro;
      font-weight: 500;
      line-height: 22px;"
      >
        By checking the box I agree to the term of service
      </p>
    </div>
    <center>
      <button
        class="m-10"
        style=" width: 504px;
      height: 48px;
      padding: 0px 8px;
      border-radius: 24px;
      background-color: #282828;
      color: #ffffff;
      font-size: 16px;
      font-family: Source Sans Pro;
      font-weight: 700;
      line-height: 22px;">Continue to Payment</button
      >
    </center>
  </div>
  <!-- <hr class="bg-gray-200 border-none" style="height: 0.1px;" /> -->
</div>

<!-- </div> -->

<style>
  .textContainer {
    max-width: 110px;
    white-space: wrap;
    text-overflow: ellipsis;
  }
  .boldText {
    color: #ffffff;
    font-size: 16px;
    font-family: "Source Sans Pro";
    font-weight: 700;
    line-height: 22px;
  }
  .textItem {
    color: #ffffff;
    font-size: 16px;
    font-family: "Source Sans Pro";
    font-weight: 500;
    line-height: 22px;
  }
  .priceText {
    color: #ffffff;
    font-size: 16px;
    font-family: "Source Sans Pro";
    font-weight: 700;
    line-height: 22px;
    position: relative;
    left: 233px;
    top: 60px;
  }
  .totalText {
    color: #ffffff;
    font-size: 20px;
    font-family: "Source Sans Pro";
    font-weight: 700;
    line-height: 24px;
  }
  /* @media screen and (max-width: 600px) {
    .mediaSmall {
      width: 100px;
    }
  } */
</style>
