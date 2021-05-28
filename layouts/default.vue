<template>
  <div>
    <nav class="bg-red-400">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex items-center justify-between h-16">
          <div class="flex items-center">
            <div class="flex-shrink-0">
              <img
                class="h-14"
                src="https://image.flaticon.com/icons/png/512/387/387388.png"
                alt="the-movie"
              />
            </div>
            <div class="hidden md:block">
              <div class="ml-10 flex items-baseline space-x-4">
                <a
                  href="#"
                  class="
                    bg-red-500
                    text-white
                    px-3
                    py-2
                    rounded-md
                    text-sm
                    font-medium
                  "
                  >Movie Listing</a
                >
                <!--                <a-->
                <!--                  href="#"-->
                <!--                  class="-->
                <!--                    text-gray-300-->
                <!--                    hover:bg-gray-700-->
                <!--                    hover:text-white-->
                <!--                    px-3-->
                <!--                    py-2-->
                <!--                    rounded-md-->
                <!--                    text-sm-->
                <!--                    font-medium-->
                <!--                  "-->
                <!--                  >Team</a-->
                <!--                >-->
              </div>
            </div>
          </div>
          <div class="-mr-2 flex md:hidden">
            <!-- Mobile menu button -->
            <button
              type="button"
              class="
                bg-gray-800
                inline-flex
                items-center
                justify-center
                p-2
                rounded-md
                text-gray-400
                hover:text-white
                hover:bg-gray-700
                focus:outline-none
                focus:ring-2
                focus:ring-offset-2
                focus:ring-offset-gray-800
                focus:ring-white
              "
              aria-controls="mobile-menu"
              aria-expanded="false"
            >
              <span class="sr-only">Open main menu</span>
              <!--
                Heroicon name: outline/menu

                Menu open: "hidden", Menu closed: "block"
              -->
              <svg
                class="block h-6 w-6"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M4 6h16M4 12h16M4 18h16"
                />
              </svg>
              <!--
                Heroicon name: outline/x

                Menu open: "block", Menu closed: "hidden"
              -->
              <svg
                class="hidden h-6 w-6"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M6 18L18 6M6 6l12 12"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>

      <!-- Mobile menu, show/hide based on menu state. -->
      <div id="mobile-menu" class="md:hidden">
        <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
          <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
          <a
            href="#"
            class="
              bg-gray-900
              text-white
              block
              px-3
              py-2
              rounded-md
              text-base
              font-medium
            "
            >Dashboard</a
          >

          <a
            href="#"
            class="
              text-gray-300
              hover:bg-gray-700
              hover:text-white
              block
              px-3
              py-2
              rounded-md
              text-base
              font-medium
            "
            >Team</a
          >

          <a
            href="#"
            class="
              text-gray-300
              hover:bg-gray-700
              hover:text-white
              block
              px-3
              py-2
              rounded-md
              text-base
              font-medium
            "
            >Projects</a
          >

          <a
            href="#"
            class="
              text-gray-300
              hover:bg-gray-700
              hover:text-white
              block
              px-3
              py-2
              rounded-md
              text-base
              font-medium
            "
            >Calendar</a
          >

          <a
            href="#"
            class="
              text-gray-300
              hover:bg-gray-700
              hover:text-white
              block
              px-3
              py-2
              rounded-md
              text-base
              font-medium
            "
            >Reports</a
          >
        </div>
      </div>
    </nav>

    <main>
      <div class="max-w-7xl mx-auto py-6">
        <!-- Replace with your content -->
        <Nuxt />
        <!-- /End replace -->
      </div>
    </main>

    <footer class="footer bg-red-400 pt-1">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="mt-2 flex flex-col items-center">
          <div class="sm:w-2/3 text-center py-6">
            <p class="text-sm text-white mb-2">
              © 2021 by Waziaq, Inc. All rights reserved.
            </p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
