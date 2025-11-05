<template>
  <div class="bg-[#674BB1] min-h-full">
    <div
      class="h-full md:min-h-screen w-screen bg-[url(./bg-mobile.svg)] md:bg-[url(/public/bg-desktop.svg)] bg-no-repeat md:bg-center bg-size-[100%_auto] md:bg-size-[90%_100%] overflow-hidden"
    >
      <div class="m-[50px] md:m-20 overflow-hidden">
        <img src="/logo.svg" alt="Logo" />

        <div class="mt-36 md:mt-24 md:h-[493px] w-full md:flex md:gap-x-14">
          <div class="w-full md:h-full md:w-[700px] overflow-hidden mb-32 md:mb-0">
            <img
              src="/illustration-mockups.svg"
              alt="Illustration"
              class="w-full object-cover"
            />
          </div>

          <div
            class="w-full md:w-[616px] md:h-full md:flex md:flex-col md:justify-center"
          >
            <h1
              class="text-[55px] font-bold text-white text-center md:text-left mb-9"
            >
              Build The Community Your Fans Will Love
            </h1>
            <p
              class="text-white text-center md:text-left text-[34px] md:text-[22px] mb-8"
            >
              Huddle re-imagines the way we build communities. You have a voice,
              but so does your audience. Create connections with your users as
              you engage in genuine discussion.
            </p>
            <div class="flex justify-center md:justify-start">
              <button
                class="text-[#674BB1] bg-white rounded-full h-[60px] text-2xl md:text-base md:h-[50px] w-[420px] md:w-[250px] shadow-xl hover:bg-[#EA7FE7] hover:text-white border-none outline-none"
              >
                Register
              </button>
            </div>
          </div>
        </div>

        <div class="flex justify-center md:justify-end mt-28 md:max-w-[1440px]">
          <i
            class="fa-brands fa-facebook text-4xl rounded-full h-[50px] w-[50px] text-white hover:text-[#EA7FE7] mx-2"
          ></i>
          <i
            class="fa-brands fa-twitter text-4xl rounded-full h-[50px] w-[50px] text-white hover:text-[#EA7FE7] mx-2"
          ></i>
          <i
            class="fa-brands fa-instagram text-4xl rounded-full h-[50px] w-[50px] text-white hover:text-[#EA7FE7] mx-2"
          ></i>
        </div>

        
      </div>
     
        <div class="mt-20 md:mt-16 text-center">
          <p class="text-white text-lg md:text-xl font-semibold">
            Coded by&nbsp;
            <a
              href="https://github.com/fatintawsifhoque"
              target="_blank"
              rel="noopener noreferrer"
              class="text-[#FFD700] hover:underline hover:text-white transition text-2xl font-bold"
            >
              Fatin Tawsif Hoque
            </a>
          </p>
        </div>
    </div>
  </div>
</template>
