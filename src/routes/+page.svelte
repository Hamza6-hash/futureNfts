<script>
  import logo from "../landing assets/logo-png-1.png";
  import monkeyPic from "../landing assets/1.png";
  import card1Pic from "../landing assets/image-18-20.png";
  import michaelPic from "../landing assets/michael.png";
  import uploadPic from "../landing assets/upload-2.png";
  import creat1 from "../landing assets/create-1.png";
  import "./style.css";
</script>

<nav>
  <div class="flex justify-between p-10">
    <img class="w-32 h-28" src={logo} alt="" />
    <button class="contact-btn"> Contact Us </button>
  </div>
</nav>

<div>
  <div class="flex justify-between">
    <svg
      class="mt-60"
      width="183"
      height="262"
      viewBox="0 0 183 262"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <g filter="url(#filter0_d_0_328)">
        <path
          d="M48.4378 100.608C53.3495 124.533 46.6864 132.934 22.2972 137.941C50.9546 132.057 55.6605 142.599 60.9061 161.341C56.2462 138.643 59.7427 131.532 82.0509 125.673C57.1579 128.227 52.7198 121.466 48.4378 100.608Z"
          fill="orange"
        />
      </g></svg
    >
    <img src={monkeyPic} alt="" />
  </div>

  <div>
    <div class="p-10">
      <p class="buySell-txt">Buy, Sell and Trade NFTs</p>

      <div class="flex gap-8 mt-7 px-7 items-center">
        <button class="message-btn" style=""> Leave Message </button>
        <button class="markt-btn"> Go to Market </button>
        <svg
          width="26"
          height="19"
          viewBox="0 0 26 19"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M25.654 8.52515L17.3812 0.685009C17.1583 0.480988 16.8597 0.368096 16.5499 0.370648C16.24 0.3732 15.9436 0.490991 15.7245 0.698652C15.5053 0.906313 15.381 1.18723 15.3784 1.48089C15.3757 1.77456 15.4948 2.05748 15.7101 2.26872L21.9655 8.19699H1.18183C0.868389 8.19699 0.567786 8.31499 0.34615 8.52503C0.124514 8.73508 0 9.01996 0 9.31701C0 9.61405 0.124514 9.89893 0.34615 10.109C0.567786 10.319 0.868389 10.437 1.18183 10.437H21.9655L15.7101 16.3653C15.5972 16.4686 15.5072 16.5922 15.4452 16.7288C15.3833 16.8655 15.3507 17.0125 15.3493 17.1612C15.3479 17.3099 15.3778 17.4574 15.4373 17.595C15.4967 17.7327 15.5844 17.8577 15.6954 17.9629C15.8064 18.068 15.9383 18.1512 16.0836 18.2075C16.2288 18.2638 16.3844 18.2922 16.5414 18.2909C16.6983 18.2896 16.8534 18.2587 16.9976 18.2C17.1417 18.1413 17.2721 18.056 17.3812 17.949L25.654 10.1089C25.8755 9.89883 26 9.61399 26 9.31701C26 9.02002 25.8755 8.73519 25.654 8.52515V8.52515Z"
            fill="white"
          />
        </svg>
      </div>
    </div>

    <p class="p-10 heading-text" style="">Trending NFTs this week</p>
    <div
      class="p-10 grid grid-cols-1 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-3 gap-4"
    >
      <div class="cont">
        <img src={card1Pic} alt="" />

        <div class="flex justify-between mt-3">
          <p class="text-wrapper-37">11h : 03m : 01s</p>
          <div class="flex gap-3">
            <svg
              width="22"
              height="18"
              viewBox="0 0 22 18"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M6.96508 9.19732C6.96508 11.3963 8.76515 13.1854 10.9876 13.1854C13.1999 13.1854 15 11.3963 15 9.19732C15 6.98837 13.1999 5.19921 10.9876 5.19921C8.76515 5.19921 6.96508 6.98837 6.96508 9.19732ZM16.9006 3.06017C18.6605 4.41953 20.1588 6.40859 21.2348 8.89741C21.3153 9.08732 21.3153 9.30722 21.2348 9.48713C19.0828 14.4648 15.2514 17.4434 10.9876 17.4434H10.9775C6.72372 17.4434 2.8923 14.4648 0.740269 9.48713C0.659819 9.30722 0.659819 9.08732 0.740269 8.89741C2.8923 3.91977 6.72372 0.951172 10.9775 0.951172H10.9876C13.1195 0.951172 15.1408 1.69082 16.9006 3.06017ZM10.9888 11.6838C12.3665 11.6838 13.4928 10.5644 13.4928 9.19502C13.4928 7.81567 12.3665 6.6962 10.9888 6.6962C10.8681 6.6962 10.7474 6.70619 10.6368 6.72619C10.5966 7.82566 9.6915 8.70525 8.57526 8.70525H8.52498C8.49481 8.86517 8.4747 9.0251 8.4747 9.19502C8.4747 10.5644 9.60099 11.6838 10.9888 11.6838Z"
                fill="white"
                fill-opacity="0.86"
              />
            </svg>
            <p class="txt-500">500</p>
          </div>
        </div>
        <hr />
        <div class="mt-2 flex justify-between">
          <div>
            <p class="card-title">Cool Guy 11</p>
            <p class="xrp-text">32.97 XRP</p>
          </div>
          <div>
            <button class="card-btn">Buy Now</button>
          </div>
        </div>
      </div>

      <div class="cont">
        <img src={card1Pic} alt="" />

        <div class="flex justify-between mt-3">
          <p class="text-wrapper-37">11h : 03m : 01s</p>
          <div class="flex gap-3">
            <svg
              width="22"
              height="18"
              viewBox="0 0 22 18"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M6.96508 9.19732C6.96508 11.3963 8.76515 13.1854 10.9876 13.1854C13.1999 13.1854 15 11.3963 15 9.19732C15 6.98837 13.1999 5.19921 10.9876 5.19921C8.76515 5.19921 6.96508 6.98837 6.96508 9.19732ZM16.9006 3.06017C18.6605 4.41953 20.1588 6.40859 21.2348 8.89741C21.3153 9.08732 21.3153 9.30722 21.2348 9.48713C19.0828 14.4648 15.2514 17.4434 10.9876 17.4434H10.9775C6.72372 17.4434 2.8923 14.4648 0.740269 9.48713C0.659819 9.30722 0.659819 9.08732 0.740269 8.89741C2.8923 3.91977 6.72372 0.951172 10.9775 0.951172H10.9876C13.1195 0.951172 15.1408 1.69082 16.9006 3.06017ZM10.9888 11.6838C12.3665 11.6838 13.4928 10.5644 13.4928 9.19502C13.4928 7.81567 12.3665 6.6962 10.9888 6.6962C10.8681 6.6962 10.7474 6.70619 10.6368 6.72619C10.5966 7.82566 9.6915 8.70525 8.57526 8.70525H8.52498C8.49481 8.86517 8.4747 9.0251 8.4747 9.19502C8.4747 10.5644 9.60099 11.6838 10.9888 11.6838Z"
                fill="white"
                fill-opacity="0.86"
              />
            </svg>
            <p class="txt-500">500</p>
          </div>
        </div>
        <hr />
        <div class="mt-2 flex justify-between">
          <div>
            <p class="card-title">Cool Guy 11</p>
            <p class="xrp-text">32.97 XRP</p>
          </div>
          <div>
            <button class="card-btn">Buy Now</button>
          </div>
        </div>
      </div>
      <div class="cont">
        <img src={card1Pic} alt="" />

        <div class="flex justify-between mt-3">
          <p class="text-wrapper-37">11h : 03m : 01s</p>
          <div class="flex gap-3">
            <svg
              width="22"
              height="18"
              viewBox="0 0 22 18"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M6.96508 9.19732C6.96508 11.3963 8.76515 13.1854 10.9876 13.1854C13.1999 13.1854 15 11.3963 15 9.19732C15 6.98837 13.1999 5.19921 10.9876 5.19921C8.76515 5.19921 6.96508 6.98837 6.96508 9.19732ZM16.9006 3.06017C18.6605 4.41953 20.1588 6.40859 21.2348 8.89741C21.3153 9.08732 21.3153 9.30722 21.2348 9.48713C19.0828 14.4648 15.2514 17.4434 10.9876 17.4434H10.9775C6.72372 17.4434 2.8923 14.4648 0.740269 9.48713C0.659819 9.30722 0.659819 9.08732 0.740269 8.89741C2.8923 3.91977 6.72372 0.951172 10.9775 0.951172H10.9876C13.1195 0.951172 15.1408 1.69082 16.9006 3.06017ZM10.9888 11.6838C12.3665 11.6838 13.4928 10.5644 13.4928 9.19502C13.4928 7.81567 12.3665 6.6962 10.9888 6.6962C10.8681 6.6962 10.7474 6.70619 10.6368 6.72619C10.5966 7.82566 9.6915 8.70525 8.57526 8.70525H8.52498C8.49481 8.86517 8.4747 9.0251 8.4747 9.19502C8.4747 10.5644 9.60099 11.6838 10.9888 11.6838Z"
                fill="white"
                fill-opacity="0.86"
              />
            </svg>
            <p class="txt-500">500</p>
          </div>
        </div>
        <hr />
        <div class="mt-2 flex justify-between">
          <div>
            <p class="card-title">Cool Guy 11</p>
            <p class="xrp-text">32.97 XRP</p>
          </div>
          <div>
            <button class="card-btn">Buy Now</button>
          </div>
        </div>
      </div>
    </div>
    <div class="flex justify-between max-md:flex-col max-lg:flex-col">
      <img
        style="width: 546px;
        height: 571px;"
        src={michaelPic}
        alt=""
      />
      <div class="mt-10 px-10">
        <p class="details-txt">Modern Concepts and Clean</p>
        <svg
          width="230"
          height="33"
          viewBox="0 0 230 33"
          fill="#E75480"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M2 31C61.5214 11.3669 176.274 -11.5635 228 11.9962"
            stroke="url(#paint0_linear_0_85)"
            stroke-width="4"
            stroke-linecap="round"
          />
        </svg>
        <p class="details-blur-text">
          We strive to provide a secure, trusted, and accessible platform that
          makes it easy for anyone to get involved in the world of NFTs.
        </p>
        <button class="message-btn mt-6">Leave Message</button>
      </div>
    </div>
    <div class="flex max-md:flex-col">
      <div class="p-10 flex flex-col gap-5">
        <p class="heading-text">Create And Sell Your NFTs</p>
        <svg
          width="230"
          height="33"
          viewBox="0 0 230 33"
          fill="#E75480"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M2 31C61.5214 11.3669 176.274 -11.5635 228 11.9962"
            stroke="url(#paint0_linear_0_85)"
            stroke-width="4"
            stroke-linecap="round"
          />
        </svg>
        <p class="details-blur-text">
          We are excited to offer a new perspective in digital ownership and
          bringing it to the masses
        </p>
        <section class="flex gap-10">
          <button class="message-btn">Crate New</button>
          <button class="wth-btn">Watch Video</button>
        </section>
      </div>
      <div>
        <img src={creat1} class="creat1-img" style="" alt="" />
        <img class="update1-img" src={uploadPic} alt="" />
      </div>
    </div>
    <div class="p-10 flex flex-col gap-16">
      <div class="flex justify-between max-md:flex-col">
        <p class="heading-text">Join the community</p>
        <p class="details-blur-text">
          We have a blog related to NFT so we can share thoughts and routines on
          our blog which is updated weekly.
        </p>
      </div>
      <div class="flex gap-10 items-center">
        <input
          class="p-6 input-emil"
          placeholder="Enter e-mail to join"
          type="text"
        />
        <button class="message-btn">Subscribe</button>
      </div>
    </div>
  </div>
</div>
