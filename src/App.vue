<script setup>
// Simple minimalist portfolio - no components needed
</script>

<template>
  <div class="min-h-screen flex flex-col font-light bg-gradient-to-br from-[#4f030d] via-[#720026] to-[#c83d52] relative overflow-hidden">
    <!-- Animated Line Art Decorations -->
    <svg class="absolute top-0 left-0 w-full h-full pointer-events-none" viewBox="0 0 1200 800">
      <!-- Animated flowing lines -->
      <path class="line-art-1" d="M100,150 Q300,100 500,150 T900,150" stroke="#ff9b55" stroke-width="1" fill="none" opacity="0.3" />
      <path class="line-art-2" d="M0,300 Q200,250 400,300 T800,300" stroke="#fb7b4c" stroke-width="1" fill="none" opacity="0.2" />
      <path class="line-art-3" d="M200,500 Q400,450 600,500 T1000,500" stroke="#ff9b55" stroke-width="1" fill="none" opacity="0.25" />

      <!-- Animated geometric shapes -->
      <circle class="circle-art-1" cx="950" cy="120" r="40" stroke="#ff9b55" stroke-width="1" fill="none" opacity="0.2" />
      <circle class="circle-art-2" cx="150" cy="600" r="25" stroke="#fb7b4c" stroke-width="1" fill="none" opacity="0.3" />

      <!-- Animated triangular lines -->
      <path class="triangle-art" d="M800,250 L850,200 L900,250 Z" stroke="#ff9b55" stroke-width="1" fill="none" opacity="0.2" />

      <!-- Floating dots -->
      <circle class="dot-1" cx="300" cy="200" r="2" fill="#ff9b55" opacity="0.4" />
      <circle class="dot-2" cx="700" cy="400" r="1.5" fill="#fb7b4c" opacity="0.3" />
      <circle class="dot-3" cx="500" cy="600" r="2" fill="#ff9b55" opacity="0.3" />
    </svg>

    <!-- Large blank space at top -->
    <div class="h-20 md:h-32"></div>

    <!-- Hero Section -->
    <main class="flex-1">
      <section id="home" class="flex items-center justify-center p-8 min-h-[90vh]">
        <div class="text-center text-[#ff9b55] max-w-3xl mx-auto">
          <!-- Main Identity -->
          <div class="mb-36 relative">
            <!-- Typographic decorations -->
            <div class="absolute -top-32 left-1/2 transform -translate-x-1/2 opacity-10 text-[200px] font-thin font-playfair select-none">A</div>

            <!-- Main Title -->
            <h1 class="text-7xl md:text-9xl font-thin tracking-[0.5em] relative font-playfair mb-6">ANN</h1>

            <!-- Typographic line -->
            <div class="flex items-center justify-center mb-16 mt-10 opacity-70">
              <div class="w-16 h-[1px] bg-[#ff9b55]"></div>
              <div class="mx-4 text-xs tracking-[0.8em] uppercase font-work-sans">•</div>
              <div class="w-16 h-[1px] bg-[#ff9b55]"></div>
            </div>

            <!-- Professional Title -->
            <h2 class="text-sm md:text-base font-light tracking-[0.6em] text-[#ffba86] opacity-80 font-work-sans uppercase">Artist & Storyteller</h2>
          </div>

          <!-- Minimal Statement -->
          <div class="mb-36 max-w-xl mx-auto">
            <p class="text-sm md:text-base font-light text-[#ffce9e] leading-relaxed mb-24 opacity-80 font-work-sans tracking-widest">creating visual poetry through <span class="border-b border-[#fb7b4c] border-opacity-40 pb-1">mythic</span> imagination</p>

            <!-- Minimal Quote -->
            <div class="relative">
              <div class="opacity-20 text-4xl font-serif absolute -top-5 -left-4">"</div>
              <blockquote class="text-xs md:text-sm italic text-[#ffba86] font-light tracking-wide leading-loose font-crimson">I am fire and earth. My art flows from sacred depths where ancient spirits dance.</blockquote>
              <div class="mt-6 flex justify-center items-center">
                <div class="w-8 h-[1px] bg-[#fb7b4c] opacity-40"></div>
                <p class="text-xs text-[#ff9b55] opacity-60 font-light tracking-[0.4em] font-work-sans mx-4">ANN</p>
                <div class="w-8 h-[1px] bg-[#fb7b4c] opacity-40"></div>
              </div>
            </div>
          </div>

          <!-- Minimal Specialties -->
          <div class="grid grid-cols-1 md:grid-cols-3 gap-20 max-w-2xl mx-auto mb-36">
            <div class="group text-center">
              <p class="text-2xl font-thin text-[#fb7b4c] mb-3 opacity-70 font-playfair">01</p>
              <h3 class="text-[10px] font-light tracking-[0.5em] uppercase text-[#ff9b55] opacity-70 font-work-sans">Ethereal Art</h3>
            </div>
            <div class="group text-center">
              <p class="text-2xl font-thin text-[#fb7b4c] mb-3 opacity-70 font-playfair">02</p>
              <h3 class="text-[10px] font-light tracking-[0.5em] uppercase text-[#ff9b55] opacity-70 font-work-sans">Wild Spirit</h3>
            </div>
            <div class="group text-center">
              <p class="text-2xl font-thin text-[#fb7b4c] mb-3 opacity-70 font-playfair">03</p>
              <h3 class="text-[10px] font-light tracking-[0.5em] uppercase text-[#ff9b55] opacity-70 font-work-sans">Sacred Vision</h3>
            </div>
          </div>

          <!-- Minimal Scroll Indicator -->
          <div class="flex flex-col items-center mt-16">
            <div class="text-xs tracking-[0.3em] text-[#ff9b55] opacity-40 font-light font-work-sans mb-4">EXPLORE</div>
            <div class="w-[1px] h-12 bg-[#ff9b55] opacity-20"></div>
          </div>
        </div>
      </section>

      <!-- Large blank space -->
      <div class="h-40 md:h-56"></div>

      <!-- Portfolio Section -->
      <section id="portfolio" class="py-32 px-8">
        <div class="max-w-5xl mx-auto">
          <div class="text-center mb-40">
            <div class="w-8 h-0.5 bg-[#fb7b4c] mx-auto mb-16 opacity-60"></div>
            <h2 class="text-2xl md:text-3xl font-extralight text-[#ff9b55] mb-10 tracking-[0.3em] font-playfair">PORTFOLIO</h2>
            <p class="text-sm font-light text-[#ffba86] opacity-60 tracking-[0.2em] font-work-sans">Selected Works</p>
          </div>

          <!-- Minimalist Grid Layout with more spacing -->
          <div class="grid grid-cols-1 md:grid-cols-2 gap-20 md:gap-24 max-w-4xl mx-auto">
            <!-- Image 1 -->
            <div class="group relative">
              <div class="aspect-square overflow-hidden bg-[#720026] bg-opacity-5 backdrop-blur-sm border border-[#ff9b55] border-opacity-15">
                <img src="/src/assets/1.jpg" alt="Illustration 1" class="w-full h-full object-cover transition-all duration-700 group-hover:scale-105 opacity-85 group-hover:opacity-100" />
              </div>
              <div class="mt-8 text-center">
                <div class="w-8 h-0.5 bg-[#fb7b4c] mx-auto mb-4"></div>
                <h3 class="text-xs font-light text-[#ff9b55] tracking-[0.3em] uppercase opacity-70 font-work-sans">01</h3>
              </div>
            </div>

            <!-- Large blank space between images -->
            <div class="hidden md:block h-16"></div>
            <div class="hidden md:block h-16"></div>

            <!-- Image 2 -->
            <div class="group relative">
              <div class="aspect-square overflow-hidden bg-[#720026] bg-opacity-5 backdrop-blur-sm border border-[#ff9b55] border-opacity-15">
                <img src="/src/assets/2.jpg" alt="Illustration 2" class="w-full h-full object-cover transition-all duration-700 group-hover:scale-105 opacity-85 group-hover:opacity-100" />
              </div>
              <div class="mt-8 text-center">
                <div class="w-8 h-0.5 bg-[#fb7b4c] mx-auto mb-4"></div>
                <h3 class="text-xs font-light text-[#ff9b55] tracking-[0.3em] uppercase opacity-70 font-work-sans">02</h3>
              </div>
            </div>

            <!-- Image 3 -->
            <div class="group relative">
              <div class="aspect-square overflow-hidden bg-[#720026] bg-opacity-5 backdrop-blur-sm border border-[#ff9b55] border-opacity-15">
                <img src="/src/assets/3.jpg" alt="Illustration 3" class="w-full h-full object-cover transition-all duration-700 group-hover:scale-105 opacity-85 group-hover:opacity-100" />
              </div>
              <div class="mt-8 text-center">
                <div class="w-8 h-0.5 bg-[#fb7b4c] mx-auto mb-4"></div>
                <h3 class="text-xs font-light text-[#ff9b55] tracking-[0.3em] uppercase opacity-70 font-work-sans">03</h3>
              </div>
            </div>

            <!-- Large blank space between images -->
            <div class="hidden md:block h-16"></div>
            <div class="hidden md:block h-16"></div>

            <!-- Image 4 -->
            <div class="group relative">
              <div class="aspect-square overflow-hidden bg-[#720026] bg-opacity-5 backdrop-blur-sm border border-[#ff9b55] border-opacity-15">
                <img src="/src/assets/4.jpg" alt="Illustration 4" class="w-full h-full object-cover transition-all duration-700 group-hover:scale-105 opacity-85 group-hover:opacity-100" />
              </div>
              <div class="mt-8 text-center">
                <div class="w-8 h-0.5 bg-[#fb7b4c] mx-auto mb-4"></div>
                <h3 class="text-xs font-light text-[#ff9b55] tracking-[0.3em] uppercase opacity-70 font-work-sans">04</h3>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Large blank space before footer -->
      <div class="h-40 md:h-56"></div>
    </main>

    <!-- Minimalist Footer -->
    <footer class="py-16 text-center">
      <div class="w-12 h-0.5 bg-[#ff9b55] bg-opacity-30 mx-auto mb-8"></div>
      <p class="text-xs font-light text-[#ff9b55] opacity-50 tracking-[0.4em] uppercase font-work-sans mb-12">Ann © 2024</p>
      
      <!-- Personal Statement -->
      <div class="max-w-md mx-auto px-8">
        <p class="text-[10px] italic text-[#ffba86] opacity-40 font-light tracking-wider font-crimson leading-relaxed">
          "I'm hot, I'm furry, I have a belief in neo-paganism"
        </p>
      </div>
    </footer>

    <!-- Bottom blank space -->
    <div class="h-20"></div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:wght@100;200;300;400;500;600;700;800;900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Work+Sans:wght@100;200;300;400;500;600;700;800;900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Crimson+Text:ital,wght@0,400;0,600;1,400;1,600&display=swap");

/* Font families */
.font-playfair {
  font-family: "Playfair Display", serif;
}

.font-work-sans {
  font-family: "Work Sans", sans-serif;
}

.font-crimson {
  font-family: "Crimson Text", serif;
}

/* Default font */
* {
  font-family: "Work Sans", sans-serif;
}

/* Line Art Animations */
.line-art-1 {
  stroke-dasharray: 1000;
  stroke-dashoffset: 1000;
  animation: drawLine 8s ease-in-out infinite;
}

.line-art-2 {
  stroke-dasharray: 800;
  stroke-dashoffset: 800;
  animation: drawLine 10s ease-in-out infinite 2s;
}

.line-art-3 {
  stroke-dasharray: 1200;
  stroke-dashoffset: 1200;
  animation: drawLine 12s ease-in-out infinite 4s;
}

.circle-art-1 {
  stroke-dasharray: 251;
  stroke-dashoffset: 251;
  animation: drawCircle 6s ease-in-out infinite;
}

.circle-art-2 {
  stroke-dasharray: 157;
  stroke-dashoffset: 157;
  animation: drawCircle 8s ease-in-out infinite 1s;
}

.triangle-art {
  stroke-dasharray: 300;
  stroke-dashoffset: 300;
  animation: drawLine 7s ease-in-out infinite 3s;
}

/* Floating dots animation */
.dot-1 {
  animation: float 4s ease-in-out infinite;
}

.dot-2 {
  animation: float 5s ease-in-out infinite 1s;
}

.dot-3 {
  animation: float 6s ease-in-out infinite 2s;
}

@keyframes drawLine {
  0% {
    stroke-dashoffset: 1000;
    opacity: 0;
  }
  20% {
    opacity: 0.3;
  }
  50% {
    stroke-dashoffset: 0;
    opacity: 0.3;
  }
  80% {
    opacity: 0.3;
  }
  100% {
    stroke-dashoffset: -1000;
    opacity: 0;
  }
}

@keyframes drawCircle {
  0% {
    stroke-dashoffset: 251;
    opacity: 0;
  }
  25% {
    opacity: 0.3;
  }
  50% {
    stroke-dashoffset: 0;
    opacity: 0.3;
  }
  75% {
    opacity: 0.3;
  }
  100% {
    stroke-dashoffset: -251;
    opacity: 0;
  }
}

@keyframes float {
  0%,
  100% {
    transform: translateY(0px);
    opacity: 0.3;
  }
  50% {
    transform: translateY(-10px);
    opacity: 0.6;
  }
}

/* Additional animations for hero improvements */
@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

h1 {
  animation: fadeInUp 1s ease-out;
}

h2 {
  animation: fadeInUp 1s ease-out 0.3s both;
}

blockquote {
  animation: fadeInUp 1s ease-out 0.6s both;
}

.grid > div {
  animation: fadeInUp 1s ease-out 0.9s both;
}

/* Additional Typography Animations */
@keyframes fadeInSlow {
  from {
    opacity: 0;
  }
  to {
    opacity: 0.1;
  }
}

.absolute.text-[200px] {
  animation: fadeInSlow 3s ease-out forwards;
}

/* Mobile responsive adjustments */
@media (max-width: 640px) {
  .grid {
    grid-template-columns: 1fr;
    gap: 8rem;
  }

  h1 {
    font-size: 3rem;
    letter-spacing: 0.3em;
  }

  h2 {
    font-size: 0.8rem;
  }

  .mb-36 {
    margin-bottom: 6rem;
  }

  .mb-24 {
    margin-bottom: 3rem;
  }

  .absolute.text-[200px] {
    font-size: 100px;
    top: -60px;
  }
}
</style>
