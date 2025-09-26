<template>
  <div>
    <!-- Carousel -->
    <div class="carousel-container">
      <div class="carousel-slide">
        <img src="" alt="Banner" />
        
      </div>
    </div>

    <!-- Sección con métricas -->
    <section class="stats-section">
      <div class="stat"><span>+30</span><p>YEAR REALIZED TRACK RECORD</p></div>
      <div class="stat"><span>+200</span><p>INVESTMENTS</p></div>
      <div class="stat"><span>7</span><p>INVESTMENT VEHICLES</p></div>
      <div class="stat"><span>+5.0</span><p>BILLION AUM</p></div>
    </section>

    <!-- Testimonial con imagen de fondo -->
    <section class="testimonial-section">
      <div class="overlay">
        <blockquote>
          <p>
            "Through Noble’s institutional real estate funds, we have acquired
            and developed hotels and flexible accommodations..."
          </p>
          <cite>
            <img src="" alt="CEO" />
            <span>MITT SHAH – Senior Managing Principal & Chief Executive Officer</span>
          </cite>
        </blockquote>
      </div>
    </section>

    <!-- imagen izquierda, texto derecha -->
    <section class="alt-section">
      <div class="image-side">
        <img src="" alt="Building" />
      </div>
      <div class="text-side">
        <h2>Vertically Integrated Sector Specialist</h2>
        <p>
          Noble is a leading alternative asset manager, investing in the future
          of travel, hospitality...
        </p>
      </div>
    </section>

    <!--texto izquierda, imagen derecha -->
    <section class="alt-section reverse">
      <div class="text-side">
        <h2>Operators Not Allocators</h2>
        <p>
          Research and data are cornerstones of the Noble platform...
        </p>
      </div>
      <div class="image-side">
        <img src="" alt="Building" />
      </div>
    </section>

    <!-- sección alternada -->
    <section class="alt-section">
      <div class="image-side">
        <img src="" alt="Building" />
      </div>
      <div class="text-side">
        <h2>Responsible Investing</h2>
        <p>
          The name, Noble, was born out of the ethos of our commitment to
          responsible investment...
        </p>
        <NuxtLink to="/learn-more" class="btn">Learn More</NuxtLink>
      </div>
    </section>
  </div>
</template>


<script setup>
import '../assets/css/index.css'  
</script>
