<template>
  <div
    id="napigator"
    class="
      px-3
      z-30
      sticky
      navbar
      bg-white
      rounded-xl
      max-w-screen-lg
      mx-auto
      drop-shadow-xl
    "
  >
    <div class="navbar-start">
      <div class="dropdown">
        <label tabindex="0" class="btn btn-ghost lg:hidden">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h8m-8 6h16"
            />
          </svg>
        </label>
        <ul
          tabindex="0"
          class="
            menu menu-compact
            dropdown-content
            mt-3
            p-2
            shadow
            bg-base-100
            rounded-box
            w-52
          "
        >
          <li>
            <a>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
                />
              </svg>
              Tentang Clipan
            </a>
          </li>

          <li>
            <a>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"
                />
              </svg>
              Layanan
            </a>
          </li>
        </ul>
      </div>
      <a class=""
        ><img
          src="https://clipan.co.id/wp-content/uploads/2021/08/asset-09.png"
          alt=""
          class="w-48 ml-3"
      /></a>
    </div>
    <div class="navbar-center hidden lg:flex">
      <ul class="menu menu-horizontal p-0">
        <button class="hoverable">
          <a
            href="#"
            class="
              relative
              block
              py-3
              px-4
              text-lg
              font-semibold
              lg:p-6
              text-sm
              hover:bg-base-200 hover:rounded-t-lg
            "
            >Perusahaan</a
          >
          <div
            class="
              mega-menu
              mb-16
              sm:mb-0
              shadow-xl
              bg-base-100
              rounded-b-lg
              border-t-2 border-indigo-500
            "
          >
            <dl class="grid grid-cols-1 lg:grid-cols-2 md:grid-cols-2 p-4">
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Sejarah Perusahaan
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores
                  <br />
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Profile
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Komisaris & Direksi
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Struktur
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Penunjang
                  </div>
                </dd>
              </div>
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Tata Kelola Perusahaan
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores
                  <br />
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Pedoman
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Whistle Blowing
                  </div>
                </dd>
              </div>
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Hubungan Investor
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores
                  <br />
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Laporan tahunan
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Laporan keuangan
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">RUPS</div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Prospektus
                  </div>
                </dd>
              </div>
            </dl>
          </div>
        </button>
        <button class="hoverable">
          <a
            href="#"
            class="
              relative
              block
              py-3
              px-4
              text-lg
              font-semibold
              lg:p-6
              text-sm
              hover:bg-base-200 hover:rounded-t-lg
            "
            >Produk</a
          >
          <div
            class="
              mega-menu
              mb-16
              sm:mb-0
              shadow-xl
              bg-base-100
              rounded-b-lg
              border-t-2 border-indigo-500
            "
          >
            <dl class="grid grid-cols-1 lg:grid-cols-2 md:grid-cols-2 p-4">
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    KPM Panin
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores
                  <br />
                  <div class="btn btn-outline btn-sm btn-ghost m-1">Fleet</div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Mobil Baru
                  </div>
                </dd>
              </div>
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Mobil Bekas
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores
                  <br />
                </dd>
              </div>
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Duit Cair
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores
                  <br />
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Daftar Agen
                  </div>
                </dd>
              </div>
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Alat Berat
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores impedit perferendis suscipit eaque, iste dolor
                  cupiditate blanditiis ratione.
                </dd>
              </div>
            </dl>
          </div>
        </button>
        <button class="hoverable">
          <a
            href="#"
            class="
              relative
              block
              py-3
              px-4
              text-lg
              font-semibold
              lg:p-6
              text-sm
              hover:bg-base-200 hover:rounded-t-lg
            "
            >Layanan</a
          >
          <div
            class="
              mega-menu
              mb-16
              sm:mb-0
              shadow-xl
              bg-base-100
              rounded-b-lg
              border-t-2 border-indigo-500
            "
          >
            <dl class="grid grid-cols-1 lg:grid-cols-2 md:grid-cols-2 p-4">
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Tentang Kredit
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores

                  <br />
                  <div class="btn btn-sm btn-primary m-1">
                    Lihat Kontrak Digital
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Persyaratan
                  </div>

                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Pengajuan
                  </div>
                  <div href="#" class="btn btn-outline btn-sm btn-ghost m-1">
                    Simulasi
                  </div>
                </dd>
              </div>
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Layanan BPKB & STNK
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores

                  <br />

                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Pengambilan
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Denda Penyimpanan
                  </div>
                  <div href="#" class="btn btn-outline btn-sm btn-ghost m-1">
                    Atur Pertemuan
                  </div>
                  <div href="#" class="btn btn-outline btn-sm btn-ghost m-1">
                    Perpanjang STNK
                  </div>
                </dd>
              </div>
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Layanan Asuransi
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores

                  <br />

                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Klaim kehilangan
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Klaim Kematian
                  </div>
                  <div href="#" class="btn btn-outline btn-sm btn-ghost m-1">
                    Proses Pengajuan
                  </div>
                </dd>
              </div>
              <div
                class="
                  relative
                  hover:text-white
                  transition
                  duration-700
                  p-5
                  hover:bg-white hover:shadow-xl hover:scale-101
                  rounded-lg
                "
              >
                <dt>
                  <div
                    class="
                      absolute
                      flex
                      items-center
                      justify-center
                      h-12
                      w-12
                      rounded-md
                      bg-base-200
                      text-primary
                    "
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                      />
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                    Cara Pembayaran
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-gray-500">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Maiores

                  <br />
                  <div class="btn btn-sm btn-primary m-1">Autodebet Panin</div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">ATM</div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Virtual Akun
                  </div>
                  <div href="#" class="btn btn-outline btn-sm btn-ghost m-1">
                    BANK
                  </div>
                  <div href="#" class="btn btn-outline btn-sm btn-ghost m-1">
                    Mart
                  </div>
                  <div class="btn btn-outline btn-sm btn-ghost m-1">
                    Kantor Post
                  </div>
                </dd>
              </div>
            </dl>
          </div>
        </button>

        <li><a>Berita</a></li>
      </ul>
    </div>

    <div class="navbar-end">
      <label class="swap">
        <input type="checkbox" />
        <div class="swap-on">ID</div>
        <div class="swap-off">EN</div>
      </label>

      <button class="btn btn-ghost btn-circle bg-white">
        <div class="indicator">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
            />
          </svg>
          <span class="badge badge-xs badge-secondary indicator-item"></span>
        </div>
      </button>
    </div>
  </div>
</template>

<style>
.mega-menu {
  display: none;
  left: 0;
  position: absolute;
  text-align: left;
  width: 100%;
}

/* #hoverable Class Styles
  –––––––––––––––––––––––––––––––––––––––––––––––––– */
.hoverable {
  position: static;
}

.hoverable > a:after {
  content: '\25BC';
  font-size: 10px;
  padding-left: 6px;
  position: relative;
  top: -1px;
}

.hoverable:hover .mega-menu {
  display: block;
}

/* #toggle Class Styles
  –––––––––––––––––––––––––––––––––––––––––––––––––– */

.toggleable > label:after {
  content: '\25BC';
  font-size: 10px;
  padding-left: 6px;
  position: relative;
  top: -1px;
}

.toggle-input {
  display: none;
}
.toggle-input:not(checked) ~ .mega-menu {
  display: none;
}

.toggle-input:checked ~ .mega-menu {
  display: block;
}

.toggle-input:checked + label {
  color: white;
  background: #2c5282; /*@apply bg-blue-800 */
}

.toggle-input:checked ~ label:after {
  content: '\25B2';
  font-size: 10px;
  padding-left: 6px;
  position: relative;
  top: -1px;
}
</style>
