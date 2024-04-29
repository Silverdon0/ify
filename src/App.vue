<template>
  <header class="flex flex-wrap lg:justify-start lg:flex-nowrap z-50 w-full py-4 backdrop-blur-md
    relative bg-white/80 lg:bg-transparent lg:backdrop-blur-none  ">
    <nav class="max-w-[85rem] flex flex-wrap basis-full items-center w-full mx-auto px-4 sm:px-6 lg:px-8">

      <div class="flex items-center sm:gap-x-2 lg:gap-x-0 xl:gap-x-3">

        <a class="flex-none rounded-md" href="#">
          <div class="w-28 h-auto" width="116" height="32">

          </div>
        </a>


        <!--Nav Links -->
        <div class="hidden sm:flex p-0.5 space-x-0.5 items-center border border-gray-200 rounded-full ">
          <a class="py-1 px-2 inline-flex items-center gap-x-3 text-white text-xs font-medium rounded-full bg-gray-800 hover:bg-gray-900 hover:text-white  "
            href="#">
            Open Source
          </a>
          <a class="py-1 px-2 inline-flex items-center gap-x-3 text-gray-800 text-xs font-medium rounded-full hover:text-gray-600    "
            href="#">
            Preline Pro
            <span class="text-xs text-green-500 relative -ms-1">
              <span class="flex absolute top-[5px] size-1.5">
                <span class="animate-ping absolute inline-flex size-full rounded-full bg-green-400 opacity-75  "></span>
                <span class="relative inline-flex rounded-full size-1.5 bg-green-500"></span>
              </span>

              <span class="ps-2.5">Live</span>
            </span>
          </a>
        </div>
        <!-- End Links -->
      </div>
      

      <div class="flex items-center lg:gap-x-1 ms-auto lg:order-3">
        
        <button type="button" class="" aria-label="Search"><span class=""><svg width="20" height="20" class=""
              viewBox="0 0 20 20" aria-hidden="true">
              <path
                d="M14.386 14.386l4.0877 4.0877-4.0877-4.0877c-2.9418 2.9419-7.7115 2.9419-10.6533 0-2.9419-2.9418-2.9419-7.7115 0-10.6533 2.9418-2.9419 7.7115-2.9419 10.6533 0 2.9419 2.9418 2.9419 7.7115 0 10.6533z"
                stroke="currentColor" fill="none" fill-rule="evenodd" stroke-linecap="round" stroke-linejoin="round">
              </path>
            </svg></span></button>
      

        <div
          class="flex items-center relative z-10 before:hidden lg:before:block before:w-px before:h-4 before:bg-gray-300  ">
          <div class="lg:ms-1 flex">
            <a class="inline-flex flex-shrink-0 justify-center items-center size-9 font-medium rounded-full text-gray-800 hover:bg-gray-200 "
              href="#" target="_blank">
              <svg class="flex-shrink-0 size-4" width="19" height="18" viewBox="0 0 19 18" fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M6.875 18C8.531 18 9.875 16.656 9.875 15V12H6.875C5.219 12 3.875 13.344 3.875 15C3.875 16.656 5.219 18 6.875 18Z"
                  fill="#0ACF83"></path>
                <path d="M3.875 9C3.875 7.344 5.219 6 6.875 6H9.875V12H6.875C5.219 12 3.875 10.656 3.875 9Z"
                  fill="#A259FF"></path>
                <path d="M3.875 3C3.875 1.344 5.219 0 6.875 0H9.875V6H6.875C5.219 6 3.875 4.656 3.875 3Z"
                  fill="#F24E1E"></path>
                <path d="M9.87501 0H12.875C14.531 0 15.875 1.344 15.875 3C15.875 4.656 14.531 6 12.875 6H9.87501V0Z"
                  fill="#FF7262"></path>
                <path
                  d="M15.875 9C15.875 10.656 14.531 12 12.875 12C11.219 12 9.87501 10.656 9.87501 9C9.87501 7.344 11.219 6 12.875 6C14.531 6 15.875 7.344 15.875 9Z"
                  fill="#1ABCFE"></path>
              </svg>
            </a>
            <a class="inline-flex flex-shrink-0 justify-center items-center size-9 font-medium rounded-full text-gray-800 hover:bg-gray-200    "
              href="#" target="_blank">
              <svg class="flex-shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                fill="currentColor" viewBox="0 0 16 16">
                <path
                  d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z">
                </path>
              </svg>
            </a>
            <a class="inline-flex flex-shrink-0 justify-center items-center size-9 font-medium rounded-full text-gray-800 hover:bg-gray-200    "
              href="#" target="_blank">
              <svg class="flex-shrink-0 size-3.5" width="48" height="50" viewBox="0 0 48 50" fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M28.5665 20.7714L46.4356 0H42.2012L26.6855 18.0355L14.2931 0H0L18.7397 27.2728L0 49.0548H4.23464L20.6196 30.0087L33.7069 49.0548H48L28.5655 20.7714H28.5665ZM22.7666 27.5131L5.76044 3.18778H12.2646L42.2032 46.012H35.699L22.7666 27.5142V27.5131Z"
                  fill="currentColor"></path>
              </svg>
            </a>
          </div>


          <span class="group inline-flex flex-shrink-0 justify-center items-center size-9 font-medium rounded-full text-gray-800 hover:bg-gray-200 dark:text-neutral-200 dark:hover:bg-neutral-800">
              <svg class="flex-shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <path d="M12 3a6 6 0 0 0 9 9 9 9 0 1 1-9-9Z"></path>
              </svg>
            </span>
          
        </div>

        
      </div>

      <!-- Link -->
      <div id="docs-navbar"
        class="hs-collapse hidden overflow-hidden transition-all duration-300 basis-full grow ms-auto lg:block lg:w-auto lg:basis-auto lg:order-2">
        <div class="flex flex-col mt-5 lg:flex-row lg:items-center lg:justify-end lg:mt-0">
          <a class="inline-flex items-center text-gray-800 p-2 text-sm font-medium rounded-lg hover:text-blue-600 focus:outline-none focus:text-blue-600    "
            href="#">
            <svg class="flex-shrink-0 size-4 me-3 block lg:hidden" xmlns="http://www.w3.org/2000/svg" width="24"
              height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
              stroke-linejoin="round">
              <path d="m3 9 9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path>
              <polyline points="9 22 9 12 15 12 15 22"></polyline>
            </svg>
            Home
          </a>
          <a class="inline-flex items-center text-gray-800 p-2 text-sm font-medium rounded-lg hover:text-blue-600 focus:outline-none focus:text-blue-600   "
            href="#">
            <svg class="flex-shrink-0 size-4 me-3 block lg:hidden" xmlns="http://www.w3.org/2000/svg" width="24"
              height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
              stroke-linejoin="round">
              <path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"></path>
              <path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"></path>
            </svg>
            Documentation
          </a>
          <a class="inline-flex items-center text-gray-800 p-2 text-sm font-medium rounded-lg hover:text-blue-600 focus:outline-none focus:text-blue-600  active-link "
            href="#">
            <svg class="flex-shrink-0 size-4 me-3 block lg:hidden" xmlns="http://www.w3.org/2000/svg" width="24"
              height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
              stroke-linejoin="round">
              <rect width="18" height="7" x="3" y="3" rx="1"></rect>
              <rect width="9" height="7" x="3" y="14" rx="1"></rect>
              <rect width="5" height="7" x="16" y="14" rx="1"></rect>
            </svg>
            Examples
          </a>
          <a class="inline-flex items-center text-gray-800 p-2 text-sm font-medium rounded-lg hover:text-blue-600 focus:outline-none focus:text-blue-600    "
            href="#">
            <svg class="flex-shrink-0 size-4 me-3 block lg:hidden" xmlns="http://www.w3.org/2000/svg" width="24"
              height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
              stroke-linejoin="round">
              <rect width="18" height="18" x="3" y="3" rx="2" ry="2"></rect>
              <line x1="3" x2="21" y1="9" y2="9"></line>
              <line x1="9" x2="9" y1="21" y2="9"></line>
            </svg>
            Templates <span
              class="ms-1 inline bg-blue-50 border border-blue-300 text-blue-600 text-[.6125rem] leading-4 uppercase align-middle rounded-full py-0.5 px-2 ">New</span>
          </a>
          <a class="inline-flex items-center text-gray-800 p-2 text-sm font-medium rounded-lg hover:text-blue-600 focus:outline-none focus:text-blue-600      "
            href="#">
            <svg class="flex-shrink-0 size-4 me-3 block lg:hidden" xmlns="http://www.w3.org/2000/svg" width="24"
              height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
              stroke-linejoin="round">
              <rect width="7" height="7" x="14" y="3" rx="1"></rect>
              <path d="M10 21V8a1 1 0 0 0-1-1H4a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-5a1 1 0 0 0-1-1H3">
              </path>
            </svg>
            Plugins
          </a>
          <a class="inline-flex items-center text-gray-800 p-2 text-sm font-medium rounded-lg hover:text-blue-600 focus:outline-none focus:text-blue-600      "
            href="#">
            <svg class="flex-shrink-0 size-4 me-3 block lg:hidden" xmlns="http://www.w3.org/2000/svg" width="24"
              height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
              stroke-linejoin="round">
              <path d="M5 5.5A3.5 3.5 0 0 1 8.5 2H12v7H8.5A3.5 3.5 0 0 1 5 5.5z"></path>
              <path d="M12 2h3.5a3.5 3.5 0 1 1 0 7H12V2z"></path>
              <path d="M12 12.5a3.5 3.5 0 1 1 7 0 3.5 3.5 0 1 1-7 0z"></path>
              <path d="M5 19.5A3.5 3.5 0 0 1 8.5 16H12v3.5a3.5 3.5 0 1 1-7 0z"></path>
              <path d="M5 12.5A3.5 3.5 0 0 1 8.5 9H12v7H8.5A3.5 3.5 0 0 1 5 12.5z"></path>
            </svg>
            Figma
          </a>
          <a class="sm:hidden inline-flex items-center gap-x-3 text-gray-800 p-2 text-sm font-medium rounded-lg hover:text-blue-600 focus:outline-none focus:text-blue-600 "
            href="#">
            <svg class="block size-4 md:hidden text-violet-500" xmlns="http://www.w3.org/2000/svg" width="24"
              height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
              stroke-linejoin="round">
              <path
                d="M21 8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16Z">
              </path>
              <path d="m3.3 7 8.7 5 8.7-5"></path>
              <path d="M12 22V12"></path>
            </svg>
            <span class="bg-clip-text bg-gradient-to-tl from-blue-500 to-violet-500 text-transparent">
              Preline Pro
            </span>
          </a>
        </div>
      </div>
      <!-- End Link -->
    </nav>
  </header>


  <main id="content">
    <!-- Hero Section -->
    <div class="">
      <div class="max-w-3xl mx-auto relative text-center px-4 sm:px-6 lg:px-8 py-10 md:py-24">
        <div class="inline-block bg-gradient-to-tl from-blue-600 via-transparent to-purple-400 p-px rounded-xl mb-3">
          <div class="bg-white rounded-xl py-1.5 px-3 text-3xl font-bold md:text-4xl lg:text-5xl lg:leading-tight ">
            <span class="bg-clip-text bg-gradient-to-tl from-blue-600 to-purple-400 text-transparent">
              185+
            </span>
          </div>
        </div>

        <h1 class="text-3xl font-bold md:text-4xl lg:text-5xl lg:leading-tight  ">Starter Pages &amp;
          Examples</h1>
        <p class="mt-4 md:text-lg text-gray-600  ">Kick-start your project effortlessly with Preline
          UI's wide range of examples, using pre-built UI parts, custom components and layouts using Tailwind CSS.</p>
      </div>
    </div>
    <!--  /Hero Section  -->

    <!-- Components Section -->
    <div class="max-w-[85rem] mx-auto pb-12 px-4 sm:px-6 lg:px-8 divide-y divide-gray-200  ">
      <div class="pt-10 lg:pt-10">
        <div class="mb-10 lg:mb-14">
          <h2 id="marketing" class="scroll-mt-12 mb-2">
            <a class="text-blue-600 hover:text-blue-500 text-2xl font-semibold " href="#">
              Marketing
            </a>
          </h2>

          <p class="text-sm text-gray-600  ">
            Premium grade comprehensive components and website solutions to create stunning marketing websites
          </p>
        </div>
      </div>

      <div class="py-10 lg:py-14">
        <div id="marketing-page-sections" class="scroll-mt-12 mb-5">
          <a class="text-gray-800 hover:text-gray-600 text-lg font-semibold    " href="#">
            Page Sections
          </a>
        </div>

        <!-- Grid section start here -->
        <div class="text-start grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 xl:gap-6">
          <!-- Card Start-->
          <a class="relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-blue-600 before:hover:shadow-lg      "
            href="#">
            <div class="relative pt-[50%]">
              <img class="size-full absolute top-0 start-0 object-cover rounded-t-xl "
                src="https://preline.co/assets/thumbnails/examples-dark/hero-sections.webp" alt="Hero Sections">

            </div>
            <div class="bg-white py-3.5 px-4 rounded-b-xl  ">
              <h3 class="text-sm text-gray-900 font-medium  ">Hero Sections <span
                  class="inline bg-blue-50 border border-blue-300 text-blue-600 text-[.6125rem] leading-4 uppercase align-middle rounded-full py-0.5 px-2 ">+2
                  new</span></h3>
              <p class="mt-0.5 text-sm text-gray-400  ">10 components</p>
            </div>
          </a>

          <!-- Card section ends here -->

           <!-- Card Start-->
          <a class="relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-blue-600 before:hover:shadow-lg      "
            href="#">
            <div class="relative pt-[50%]">
              <img class="size-full absolute top-0 start-0 object-cover rounded-t-xl "
                src="https://preline.co/assets/thumbnails/examples/hero-forms.webp" alt="Hero Forms">

            </div>
            <div class="bg-white py-3.5 px-4 rounded-b-xl  ">
              <h3 class="text-sm text-gray-900 font-medium  ">Hero Forms </h3>
              <p class="mt-0.5 text-sm text-gray-400  ">4 components</p>
            </div>
          </a>
          <!-- Card section ends here -->

           <!-- Card Start-->
          <a class="relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-blue-600 before:hover:shadow-lg      "
            href="#">
            <div class="relative pt-[50%]">
              <img class="size-full absolute top-0 start-0 object-cover rounded-t-xl "
                src="https://preline.co/assets/thumbnails/examples/icon-sections.webp" alt="Icon Sections">

            </div>
            <div class="bg-white py-3.5 px-4 rounded-b-xl  ">
              <h3 class="text-sm text-gray-900 font-medium  ">Icon Sections </h3>
              <p class="mt-0.5 text-sm text-gray-400  ">10 components</p>
            </div>
          </a>
          <!-- Card section ends here -->

           <!-- Card Start-->
          <a class="relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-blue-600 before:hover:shadow-lg      "
            href="#">
            <div class="relative pt-[50%]">
              <img class="size-full absolute top-0 start-0 object-cover rounded-t-xl "
                src="https://preline.co/assets/thumbnails/examples/pricing-sections.webp" alt="Pricing Sections">

            </div>
            <div class="bg-white py-3.5 px-4 rounded-b-xl  ">
              <h3 class="text-sm text-gray-900 font-medium  ">Pricing Sections </h3>
              <p class="mt-0.5 text-sm text-gray-400  ">4 components</p>
            </div>
          </a>
          <!-- Card section ends here -->

           <!-- Card Start-->
          <a class="relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-blue-600 before:hover:shadow-lg      "
            href="#">
            <div class="relative pt-[50%]">
              <img class="size-full absolute top-0 start-0 object-cover rounded-t-xl"
                src="https://preline.co/assets/thumbnails/examples/faq-sections.webp" alt="FAQ Sections">

            </div>
            <div class="bg-white py-3.5 px-4 rounded-b-xl ">
              <h3 class="text-sm text-gray-900 font-medium  ">FAQ Sections </h3>
              <p class="mt-0.5 text-sm text-gray-400  ">4 components</p>
            </div>
          </a>
          <!-- Card section ends here -->

           <!-- Card Start-->
          <a class="relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-blue-600 before:hover:shadow-lg"
            href="#">
            <div class="relative pt-[50%]">
              <img class="size-full absolute top-0 start-0 object-cover rounded-t-xl"
                src="https://preline.co/assets/thumbnails/examples/blog-sections.webp" alt="Blog Sections">

            </div>
            <div class="bg-white py-3.5 px-4 rounded-b-xl  ">
              <h3 class="text-sm text-gray-900 font-medium  ">Blog Sections <span
                  class="inline bg-blue-50 border border-blue-300 text-blue-600 text-[.6125rem] leading-4 uppercase align-middle rounded-full py-0.5 px-2 ">+2
                  new</span></h3>
              <p class="mt-0.5 text-sm text-gray-400  ">11 components</p>
            </div>
          </a>
          <!-- Card section ends here -->

           <!-- Card Start-->
          <a class="relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-blue-600 before:hover:shadow-lg "
            href="#">
            <div class="relative pt-[50%]">
              <img class="size-full absolute top-0 start-0 object-cover rounded-t-xl "
                src="https://preline.co/assets/thumbnails/examples/blog-articles.webp" alt="Blog Articles">

            </div>
            <div class="bg-white py-3.5 px-4 rounded-b-xl ">
              <h3 class="text-sm text-gray-900 font-medium ">Blog Articles </h3>
              <p class="mt-0.5 text-sm text-gray-400 ">2 components</p>
            </div>
          </a>
          <!-- Card section ends here -->

           <!-- Card Start-->
          <a class="relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-blue-600 before:hover:shadow-lg "
            href="#">
            <div class="relative pt-[50%]">
              <img class="size-full absolute top-0 start-0 object-cover rounded-t-xl  "
                src="https://preline.co/assets/thumbnails/examples/team-sections.webp" alt="Team Sections">

            </div>
            <div class="bg-white py-3.5 px-4 rounded-b-xl ">
              <h3 class="text-sm text-gray-900 font-medium  ">Team Sections </h3>
              <p class="mt-0.5 text-sm text-gray-400  ">4 components</p>
            </div>
          </a>
          <!-- Card section ends here -->
        </div>
      </div>
    </div>
  </main>
</template>

<script>

</script>

<style></style>
