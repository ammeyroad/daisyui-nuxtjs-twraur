<template>
  <div
    class="hero min-h-screen bg-primary pb-40 lg:pb-1 bg-cover"
    style="
      background-image: url(http://pixner.net/mosto/demo/ltr/light/assets/images/banner/banner-bg-1.jpg);
    "
  >
    <div class="hero-overlay bg-opacity-50 bg-primary"></div>
    <div
      class="hero-content grid grid-col-1 lg:grid-cols-3 md:grid-cols-1 gap-10"
    >
      <div
        class="
          carousel
          w-full
          carousel-center
          lg:col-span-2
          bg-white
          rounded-2xl
          hover:shadow-2xl
        "
      >
        <div id="slide1" class="carousel-item relative w-full">
          <div class="card w-full">
            <figure>
              <img
                src="https://clipan.co.id/wp-content/uploads/2022/06/slide-1.png"
                alt="Shoes"
              />
            </figure>
          </div>
          <div
            class="
              absolute
              flex
              justify-between
              transform
              -translate-y-1/2
              left-5
              right-5
              top-1/2
            "
          >
            <a href="#slide4" class="btn btn-circle shadow btn-secondary">❮</a>
            <a href="#slide2" class="btn btn-circle">❯</a>
          </div>
        </div>
        <div id="slide2" class="carousel-item relative w-full">
          <div class="card w-full">
            <figure>
              <img
                src="https://clipan.co.id/wp-content/uploads/2022/06/slide-2.png"
                alt="Shoes"
              />
            </figure>
          </div>
          <div
            class="
              absolute
              flex
              justify-between
              transform
              -translate-y-1/2
              left-5
              right-5
              top-1/2
            "
          >
            <a href="#slide1" class="btn btn-circle">❮</a>
            <a href="#slide3" class="btn btn-circle">❯</a>
          </div>
        </div>
        <div id="slide3" class="carousel-item relative w-full">
          <div class="card w-full">
            <figure>
              <img
                src="https://clipan.co.id/wp-content/uploads/2022/06/slide3.png"
                alt="Shoes"
              />
            </figure>
          </div>
          <div
            class="
              absolute
              flex
              justify-between
              transform
              -translate-y-1/2
              left-5
              right-5
              top-1/2
            "
          >
            <a href="#slide2" class="btn btn-circle">❮</a>
            <a href="#slide4" class="btn btn-circle">❯</a>
          </div>
        </div>
      </div>
      <div class="card hover:shadow-2xl bg-white">
        <div
          class="grid gap-4 grid-cols-2 p-5 lg:shadow-2xl shadow-lg bg-white"
        >
          <div class="form-control w-full">
            <label class="label">
              <span class="label-text">Domisili</span>
            </label>
            <select class="select select-bordered">
              <option disabled selected>Pick one</option>
              <option>Star Wars</option>
              <option>Harry Potter</option>
              <option>Lord of the Rings</option>
              <option>Planet of the Apes</option>
              <option>Star Trek</option>
            </select>
          </div>
          <div class="form-control w-full">
            <label class="label">
              <span class="label-text">Domisili</span>
            </label>
            <select class="select select-bordered">
              <option disabled selected>Pick one</option>
              <option>Star Wars</option>
              <option>Harry Potter</option>
              <option>Lord of the Rings</option>
              <option>Planet of the Apes</option>
              <option>Star Trek</option>
            </select>
          </div>
          <div class="form-control w-full col-span-2">
            <label class="label">
              <span class="label-text">Nominal</span>
            </label>
            <input
              type="text"
              placeholder="Type here"
              class="input input-bordered"
            />
          </div>
          <div class="form-control w-full">
            <label class="label">
              <span class="label-text">Uang Muka</span>
            </label>
            <select class="select select-bordered">
              <option disabled selected>25%</option>
              <option>Star Wars</option>
              <option>Harry Potter</option>
              <option>Lord of the Rings</option>
              <option>Planet of the Apes</option>
              <option>Star Trek</option>
            </select>
          </div>
          <div class="form-control w-full">
            <label class="label">
              <span class="label-text">Nominal</span>
            </label>
            <input
              type="text"
              placeholder="Type here"
              class="input input-bordered"
            />
          </div>

          <div class="form-control mt-6">
            <button class="btn btn-primary">Login</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
