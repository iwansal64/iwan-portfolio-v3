<div id="hero" class="flex items-center w-screen min-h-screen h-full">
      <div class="absolute w-full h-2/6 top-1/2 -translate-y-1/2 bg-(--background-2) -z-10">
      
      </div>
      <div class="flex flex-row gap-4 items-center h-full w-[80%] mx-auto *:w-full">
            <div class="flex flex-col py-24">
                  <h1 class="text-6xl font-bold uppercase">Ridwan</h1>
                  <div class="flex flex-row gap-2 items-center">
                        <div class="w-8 h-0.5 bg-white"></div>
                        <p class="text-2xl italic">Passionate Fullstack Developer</p>
                  </div>
                  <div class="flex mt-4 flex-row justify-between gap-2">
                        <div class="floating-anim icon-item">
                              <img src="/src/lib/assets/svelte-icon.png" alt="">
                        </div>
                        <div class="floating-anim icon-item">
                              <img src="/src/lib/assets/nodejs-icon.png" alt="">
                        </div>
                        <div class="floating-anim icon-item">
                              <img src="/src/lib/assets/react-icon.png" alt="">
                        </div>
                        <div class="floating-anim icon-item">
                              <img src="/src/lib/assets/rust-icon.png" alt="">
                        </div>
                        <div class="floating-anim icon-item">
                              <img src="/src/lib/assets/next-icon.png" alt="">
                        </div>
                        <div class="floating-anim icon-item">
                              <img src="/src/lib/assets/mysql-icon.png" alt="">
                        </div>
                        <div class="floating-anim icon-item">
                              <img src="/src/lib/assets/mongodb-icon.png" alt="">
                        </div>
                        <div class="floating-anim icon-item">
                              <img src="/src/lib/assets/postgres-icon.png" alt="">
                        </div>
                  </div>
            </div>
            <div class="flex justify-center items-center">
                  <div class="hero-image-background absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 h-screen aspect-square bg-[radial-gradient(circle_at_center,#1e2939cc_0%,transparent_70%)] bg-no-repeat bg-center -z-100"></div>
                  <div class="relative w-4/5 aspect-square overflow-visible rounded-4xl brightness-75">
                        <div class="rounded-2xl w-full h-full overflow-hidden">
                              <img src="/src/lib/assets/hero.jpg" class="w-full h-full object-cover" alt="">
                        </div>
                  </div>
            </div>
      </div>
</div>

<style lang="scss">
      .hero-image-background {
            animation-name: hero-image-background-anim;
            animation-duration: 5s;
            animation-timing-function: linear;
            animation-iteration-count: infinite;
            animation-direction: alternate;
      }

      @keyframes hero-image-background-anim {
            from {
                  background-size: 100% 100%;
            }
            to {
                  background-size: 80% 80%;
            }
      }
      
      .icon-item {
            animation-name: floating-anim;
            animation-duration: 3s;
      }

      @for $i from 1 to 8 {
            .icon-item:nth-child(#{$i}) {
                  animation-delay: -#{$i}s;
            }
      }
</style>