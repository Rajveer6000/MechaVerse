<template>
  <div>
    <Navbar />

    <div class="lg:h-40 h-28 lg:my-auto mt-10">
      <!-- Department info start here -->
      <div class="w-full h-10 font-bold text-xl lg:text-4xl text-center  lg:my-10">
        <h1>Department of Mechanical Engineering</h1>
      </div>
      <div class="w-full h-8 font-semibold text-ls lg:text-2xl text-center ">
        <p>Tezpur University</p>
      </div>

    </div>
    <!-- Department info ends -->
        <div>
          <div class="text-center block px-8 lg:px-72  py-16 " id="bg">
            <div class=" bg-[#ffffff] my-auto flex-auto w-full h-full py-8 lg:py-24 mb-0 text-center px-8 lg:px-16  ">
              <div>
                <div class="lg:h-25 flex-auto text-xl lg:text-6xl font-extrabold lg:mb-14">
                  <h1 class="fill-black">
                    Welcome to
                    <span class="font-extrabold text-xl lg:text-6xl">Mecha</span><span
                      class="font-extrabold text-xl lg:text-6xl text-[#56A856]">Verse</span>
                  </h1>
                </div>
                <div class="my-6 text-sm lg:text-xl font-medium lg:font-semibold">
                  <p>MechaVerse is an initiative from the student body of the Department of Mechanical Engineering at
                    Tezpur
                    University. Under this initiative, the students of the department aim to plan, manage and organise
                    various academic events and activities for the overall development of the student body and the
                    department.</p>
                </div>
              </div>
            </div>
          </div>

          <!-- corousal and notification  from here  -->
          <div class="mt-10">
            <div class="corousal grid grid-cols-3 mb-16 mx-7 space-x-5">
              <div class="col-span-2 ">
                <div id="carouselExampleCaptions" class="relative" data-te-carousel-init data-te-ride="carousel">
                  <!--Carousel indicators-->
                  <div class="absolute bottom-0 left-0 right-0 z-[2] mx-[15%] mb-4 flex list-none justify-center p-0"
                    data-te-carousel-indicators>
                    <button type="button" data-te-target="#carouselExampleCaptions" data-te-slide-to="0"
                      data-te-carousel-active
                      class="mx-[3px] box-content h-[3px] w-[30px] flex-initial cursor-pointer border-0 border-y-[10px] border-solid border-transparent bg-white bg-clip-padding p-0 -indent-[999px] opacity-50 transition-opacity duration-[600ms] ease-[cubic-bezier(0.25,0.1,0.25,1.0)] motion-reduce:transition-none"
                      aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-te-target="#carouselExampleCaptions" data-te-slide-to="1"
                      class="mx-[3px] box-content h-[3px] w-[30px] flex-initial cursor-pointer border-0 border-y-[10px] border-solid border-transparent bg-white bg-clip-padding p-0 -indent-[999px] opacity-50 transition-opacity duration-[600ms] ease-[cubic-bezier(0.25,0.1,0.25,1.0)] motion-reduce:transition-none"
                      aria-label="Slide 2"></button>
                    <button type="button" data-te-target="#carouselExampleCaptions" data-te-slide-to="2"
                      class="mx-[3px] box-content h-[3px] w-[30px] flex-initial cursor-pointer border-0 border-y-[10px] border-solid border-transparent bg-white bg-clip-padding p-0 -indent-[999px] opacity-50 transition-opacity duration-[600ms] ease-[cubic-bezier(0.25,0.1,0.25,1.0)] motion-reduce:transition-none"
                      aria-label="Slide 3"></button>
                  </div>

                  <!--Carousel items-->
                  <div class="relative w-full overflow-hidden after:clear-both after:block after:content-['']">
                    <!--First item-->
                    <div
                      class="relative float-left -mr-[100%] w-full transition-transform duration-[600ms] ease-in-out motion-reduce:transition-none"
                      data-te-carousel-active data-te-carousel-item style="backface-visibility: hidden">
                      <img src="https://tecdn.b-cdn.net/img/Photos/Slides/img%20(15).jpg" class="block w-full"
                        alt="..." />
                      <div class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-white md:block">
                        <h5 class="text-xl">First slide label</h5>
                        <p>
                          Some representative placeholder content for the first slide.
                        </p>
                      </div>
                    </div>
                    <!--Second item-->
                    <div
                      class="relative float-left -mr-[100%] hidden w-full transition-transform duration-[600ms] ease-in-out motion-reduce:transition-none"
                      data-te-carousel-item style="backface-visibility: hidden">
                      <img src="https://tecdn.b-cdn.net/img/Photos/Slides/img%20(22).jpg" class="block w-full"
                        alt="..." />
                      <div class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-white md:block">
                        <h5 class="text-xl">Second slide label</h5>
                        <p>
                          Some representative placeholder content for the second slide.
                        </p>
                      </div>
                    </div>
                    <!--Third item-->
                    <div
                      class="relative float-left -mr-[100%] hidden w-full transition-transform duration-[600ms] ease-in-out motion-reduce:transition-none"
                      data-te-carousel-item style="backface-visibility: hidden">
                      <img src="https://tecdn.b-cdn.net/img/Photos/Slides/img%20(23).jpg" class="block w-full"
                        alt="..." />
                      <div class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-white md:block">
                        <h5 class="text-xl">Third slide label</h5>
                        <p>
                          Some representative placeholder content for the third slide.
                        </p>
                      </div>
                    </div>
                  </div>

                  <!--Carousel controls - prev item-->
                  <button
                    class="absolute bottom-0 left-0 top-0 z-[1] flex w-[15%] items-center justify-center border-0 bg-none p-0 text-center text-white opacity-50 transition-opacity duration-150 ease-[cubic-bezier(0.25,0.1,0.25,1.0)] hover:text-white hover:no-underline hover:opacity-90 hover:outline-none focus:text-white focus:no-underline focus:opacity-90 focus:outline-none motion-reduce:transition-none"
                    type="button" data-te-target="#carouselExampleCaptions" data-te-slide="prev">
                    <span class="inline-block h-8 w-8">
                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                        stroke="currentColor" class="h-6 w-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
                      </svg>
                    </span>
                    <span
                      class="!absolute !-m-px !h-px !w-px !overflow-hidden !whitespace-nowrap !border-0 !p-0 ![clip:rect(0,0,0,0)]">Previous</span>
                  </button>
                  <!--Carousel controls - next item-->
                  <button
                    class="absolute bottom-0 right-0 top-0 z-[1] flex w-[15%] items-center justify-center border-0 bg-none p-0 text-center text-white opacity-50 transition-opacity duration-150 ease-[cubic-bezier(0.25,0.1,0.25,1.0)] hover:text-white hover:no-underline hover:opacity-90 hover:outline-none focus:text-white focus:no-underline focus:opacity-90 focus:outline-none motion-reduce:transition-none"
                    type="button" data-te-target="#carouselExampleCaptions" data-te-slide="next">
                    <span class="inline-block h-8 w-8">
                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                        stroke="currentColor" class="h-6 w-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
                      </svg>
                    </span>
                    <span
                      class="!absolute !-m-px !h-px !w-px !overflow-hidden !whitespace-nowrap !border-0 !p-0 ![clip:rect(0,0,0,0)]">Next</span>
                  </button>
                </div>
              </div>
              <div class="col-span-1 justify-center my-auto bg-slate-500 h-full">
                <p class=" text-center text-xl lg:text-3xl flex justify-center "> Notification</p>
              </div>
            </div>
          </div>
    </div>
    <Footer />



  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
#bg {
  background-image: url('../static/images/background8.jpg');
  background-size: cover;
  height: 1000 px;
  background-position: center center;

}</style>