<script>
  import dialogImg1 from "../../assets/dialogImg1.png";
  import dialogImg2 from "../../assets/dialogImg2.png";
  import "./style.css";
</script>

<div class="flex items-center justify-center py-10">
  <div class="m-10 checkout-container">
    <p class="m-10 checkout-txt">Checkout</p>
    <div class="flex justify-between checkout-txt">
      <p class="m-10">Items</p>
      <p class="m-10">Subtotal</p>
    </div>
    <div class="flex">
      <img class="m-10 checkout-imgs" src={dialogImg1} alt="" />
      <div class="mt-10 flex flex-col gap-4 textContainer">
        <p class="boldText">Artwork Size</p>
        <p class="textItem">Item #3333</p>
      </div>

      <div>
        <p class="priceText">$96</p>
      </div>
    </div>
    <div class="flex">
      <img class="m-10 checkout-imgs" src={dialogImg2} alt="" />
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
      <input class="check-box" type="checkbox" />
      <p>By checking the box I agree to the term of service</p>
    </div>
    <center>
      <button class="m-10 checkout-btn">Continue to Payment</button>
    </center>
  </div>
</div>
