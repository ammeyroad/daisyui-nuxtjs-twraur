<template>
  <div>
    <div
      class="
        grid grid-cols-1
        sm:grid-cols-2
        lg:grid-cols-3
        xl:grid-cols-4
        gap-6
        w-full
      "
    >
      <div class="relative mx-auto w-full">
        <a
          href="#"
          class="
            relative
            inline-block
            duration-300
            ease-in-out
            transition-transform
            transform
            hover:-translate-y-2
            w-full
            rounded-lg
            hover:shadow-xl
          "
        >
          <div class="shadow p-1 rounded-lg bg-white">
            <div
              class="
                flex
                justify-center
                relative
                rounded-lg
                overflow-hidden
                h-68
              "
            >
              <div
                class="
                  transition-transform
                  duration-500
                  transform
                  ease-in-out
                  hover:scale-110
                  w-full
                "
              >
                <img
                  src="https://clipan.co.id/wp-content/uploads/2022/04/KOTAK-MERCY-1350X1350-1.png"
                  alt=""
                />
              </div>

              <span
                class="
                  absolute
                  top-0
                  left-0
                  inline-flex
                  mt-3
                  ml-3
                  px-3
                  py-2
                  rounded-lg
                  z-10
                  bg-red-500
                  text-sm
                  font-medium
                  text-white
                  select-none
                "
              >
                Promosi
              </span>
            </div>

            <div class="mt-4 p-4">
              <h2 class="font-bold text-base text-xl text-primary">
                Judul disini
              </h2>
              <p class="mt-2 text-md text-gray-800">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s,
              </p>
            </div>

            <div class="grid grid-cols-2 mt-8 p-4">
              <div class="flex items-center">
                <div class="relative">
                  <div
                    class="rounded-full w-6 h-6 md:w-8 md:h-8 bg-gray-200"
                  ></div>
                  <span
                    class="
                      absolute
                      top-0
                      right-0
                      inline-block
                      w-3
                      h-3
                      bg-primary-red
                      rounded-full
                    "
                  ></span>
                </div>

                <p class="ml-2 text-gray-800 line-clamp-1">21 Juni 2022</p>
              </div>

              <div class="flex justify-end">
                <button class="btn btn-primary">Selengkapnya</button>
              </div>
            </div>
          </div>
        </a>
      </div>

    </div>
  </div>
</template>
