<script>
  import logo from "../assets/logo.jpeg";
  import dogeFather from "../assets/dogeFather.jpeg";
</script>

<div class="light">
  <main>
    <div class="h-full">
      <div class="bg-[#232830] text-white">
        <nav class="flex items-center justify-between py-8 px-8">
          <!-- <div> -->
          <a href="https://sentora.ai">
            <div class="flex items-center gap-4">
              <img src={logo} alt="Sentora Users" class="w-36" />
              <p class="font-serif" style="font-size: 2rem;">Carnival</p>
            </div>
          </a>
          <!-- </div> -->
          <div class="flex items-center space-x-4 md:space-x-8">
            <button
              class="bg-none hover:bg-blue-800 border-2 border-white shadow-gray-700 shadow-2xl text-white rounded-full py-2 px-4 md:py-3 md:px-6"
              >Login</button
            >
          </div>
        </nav>
        <section
          class="flex flex-col lg:flex-row items-center justify-center py-16 px-8"
        >
          <div class="lg:w-1/2 md:ml-8">
            <h1 class="text-4xl font-thin mb-4">Sentora</h1>
            <h2 class="text-2xl font-bold mb-6">Document Your Learning</h2>
            <p class="text-lg font-extralight mr-0 md:mr-32 mb-6">
              Effortlessly condense long videos into short summaries. Our
              AI-powered website saves you time by delivering concise
              information, making understanding easier.
            </p>
            <a href="https://forms.gle/Zizmm31omBkK6CCbA"
              ><button
                class="bg-none hover:bg-blue-800 border-2 border-white shadow-gray-700 shadow-2xl text-white rounded-full py-3 px-6"
                >Join Now</button
              ></a
            >
          </div>
          <div class="lg:w-1/2 mt-8 lg:mt-0">
            <img src={dogeFather} alt="Sentora Users" class="w-128" />
          </div>
        </section>
        <footer class="py-12 bg-[#191c21] px-auto center mx-auto text-center">
          <p class="text-lg text-gray-200">
            © 2023 <span class="text-blue-700 font-bold">Sentora</span>
            <br /><span class="font-bold"> All rights reserved.</span>
          </p>
        </footer>
      </div>
    </div>
  </main>
</div>
