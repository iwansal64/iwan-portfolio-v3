<div id="tech-stack" class="w-screen h-full min-h-screen bg-(--background-2) pt-24 py-48 px-20">
      <h1 class="text-5xl font-thin w-full text-center">Meet my <span class="font-semibold">Tech Stack</span></h1>
      <div class="w-full h-full flex flex-row gap-4 mt-24">
            <div class="px-24 box-border w-1/2 flex flex-col justify-center">
                  <h3 class="text-5xl font-semibold">Backend</h3>
                  <div class="flex flex-row gap-2 mt-2 text-sm *:font-semibold *:border *:border-white *:px-2 *:py-1 *:rounded-lg">
                        <p>Design System</p>
                        <p>Performance</p>
                        <p>Efficiency</p>
                  </div>
                  <p class="text-md font-thin mt-4">I always want to achieve the fastest, most reliable system within my backend-side application</p>
            </div>
            <div class="w-1/2 flex justify-end items-center">
                  <div class="grid grid-cols-2 grid-rows-2 place-items-center w-fit aspect-square *:w-fit *:h-fit *:px-12 *:flex *:justify-center *:items-center *:relative">
                        <div class="relative translate-x-12">
                              <p class="font-thin absolute bottom-0 translate-y-full left-1/2 -translate-x-1/2">Node JS</p>
                              <div class="floating-anim-low floating-anim-low-1 p-4 bg-gray-700 rounded-2xl">
                                    <img class="w-16" src="/src/lib/assets/nodejs-icon.png" alt="">
                              </div>
                        </div>
                        <div class="relative translate-y-12">
                              <p class="font-thin absolute bottom-0 translate-y-full left-1/2 -translate-x-1/2">Rust</p>
                              <div class="floating-anim-low floating-anim-low-2 p-4 bg-gray-700 rounded-2xl">
                                    <img class="w-16" src="/src/lib/assets/rust-icon.png" alt="">
                              </div>
                        </div>
                        <div class="relative -translate-y-12">
                              <p class="font-thin absolute bottom-0 translate-y-full left-1/2 -translate-x-1/2">Mongo DB</p>
                              <div class="floating-anim-low floating-anim-low-3 p-4 bg-gray-700 rounded-2xl">
                                    <img class="w-16" src="/src/lib/assets/mongodb-icon.png" alt="">
                              </div>
                        </div>
                        <div class="relative -translate-x-12">
                              <p class="font-thin absolute bottom-0 translate-y-full left-1/2 -translate-x-1/2">PostgreSQL</p>
                              <div class="floating-anim-low floating-anim-low-4 p-4 bg-gray-700 rounded-2xl">
                                    <img class="w-16" src="/src/lib/assets/postgres-icon.png" alt="">
                              </div>
                        </div>
                  </div>
            </div>
      </div>
      <div class="w-full h-full flex flex-row-reverse gap-4 mt-60">
            <div class="px-24 box-border w-1/2 flex flex-col justify-center">
                  <h3 class="text-5xl font-semibold">Frontend</h3>
                  <div class="flex flex-row gap-2 mt-2 text-sm *:font-semibold *:border *:border-white *:px-2 *:py-1 *:rounded-lg">
                        <p>Design UI</p>
                        <p>SEO Optimization</p>
                        <p>User Experience</p>
                  </div>
                  <p class="text-md font-thin mt-4">I have a tendency to create a performant, delightful looking user interface regardless the target audience</p>
            </div>
            <div class="w-1/2 flex justify-start items-center">
                  <div class="grid grid-cols-2 grid-rows-2 place-items-center w-fit aspect-square *:w-fit *:h-fit *:px-12 *:flex *:justify-center *:items-center *:relative">
                        <div class="relative translate-x-12">
                              <p class="font-thin absolute bottom-0 translate-y-full left-1/2 -translate-x-1/2">Svelte</p>
                              <div class="floating-anim-low floating-anim-low-1 p-4 bg-gray-700 rounded-2xl">
                                    <img class="w-16" src="/src/lib/assets/svelte-icon.png" alt="">
                              </div>
                        </div>
                        <div class="relative translate-y-12">
                              <p class="font-thin absolute bottom-0 translate-y-full left-1/2 -translate-x-1/2">Astro</p>
                              <div class="floating-anim-low floating-anim-low-2 p-4 bg-gray-700 rounded-2xl">
                                    <img class="w-16" src="/src/lib/assets/astro-icon.png" alt="">
                              </div>
                        </div>
                        <div class="relative -translate-y-12">
                              <p class="font-thin absolute bottom-0 translate-y-full left-1/2 -translate-x-1/2">React JS</p>
                              <div class="floating-anim-low floating-anim-low-3 p-4 bg-gray-700 rounded-2xl">
                                    <img class="w-16" src="/src/lib/assets/react-icon.png" alt="">
                              </div>
                        </div>
                        <div class="relative -translate-x-12">
                              <p class="font-thin absolute bottom-0 translate-y-full left-1/2 -translate-x-1/2">Next JS</p>
                              <div class="floating-anim-low floating-anim-low-4 p-4 bg-gray-700 rounded-2xl">
                                    <img class="w-16" src="/src/lib/assets/next-icon.png" alt="">
                              </div>
                        </div>
                  </div>
            </div>
      </div>
</div>

<style lang="scss">
      .floating-anim-low {
            animation-duration: 2s;
      }

      @for $i from 1 to 4 {
            .floating-anim-low-#{4-$i} {
                  animation-delay: -#{$i*400}ms;
            }
      }
</style>