<!-- ===== Students section styles ===== -->
<style>
  /* Container for one student row */
  .student { 
    display: flex; 
    align-items: flex-start;  /* top-align name block with photo */
    gap: 12px; 
    margin: 12px 0 20px; 
  }
  /* Photo size (same as your current usage) */
  .student-photo { 
    width: 270px; 
    height: 338px; 
    object-fit: cover; 
    flex: 0 0 auto;
  }
  /* Name (with a tiny gap under it) */
  .student-name { 
    font-size: 1.5em; 
    line-height: 1.1; 
    margin: 0 0 6px 0;  /* << controls the "slight gap" under the name */
    font-weight: 600; 
  }
  /* Description text */
  .student-desc { 
    margin: 0; 
    max-width: 70ch;  /* keep readable line length */
  }
  /* Responsive: stack on narrow screens */
  @media (max-width: 700px) {
    .student { flex-direction: column; }
    .student-photo { width: 100%; height: auto; }
  }
</style>

## <strong>Undergraduate and High School students</strong>

<!-- Susoma Halder (no image provided) -->
<div class="student">
  <!-- If you later add an image, place <img> here -->
  <div>
    <div class="student-name">Susoma Halder</div>
    <p class="student-desc">
      <!-- Add Susoma's short bio here -->
    </p>
  </div>
</div>

<!-- Soraya Rahni (no image provided) -->
<div class="student">
  <div>
    <div class="student-name">Soraya Rahni</div>
    <p class="student-desc">
      <!-- Add Soraya's short bio here -->
    </p>
  </div>
</div>

<!-- Saiful Samad (image provided) -->
<div class="student">
  <img src="/assets/img/saif_profile.jpg" alt="Saiful Samad" class="student-photo">
  <div>
    <div class="student-name">Saiful Samad</div>
    <p class="student-desc">
      <!-- Add Saiful's short bio here -->
    </p>
  </div>
</div>

<!-- Arham Akhyer (image provided) -->
<div class="student">
  <img src="/assets/img/arham_profile.jpg" alt="Arham Akhyer" class="student-photo">
  <div>
    <div class="student-name">Arham Akhyer</div>
    <p class="student-desc">
      <!-- Add Arham's short bio here -->
    </p>
  </div>
</div>

<!-- Jack Yang (no image provided) -->
<div class="student">
  <div>
    <div class="student-name">Jack Yang</div>
    <p class="student-desc">
      I’m an undergraduate student at SBU majoring in Biochemistry. I have an interest in medicine and plan on pursuing graduate-level education in the future. On top of my interest in science, I also study music at SBU with the piano being my main instrument! I enjoy playing piano in my free time and accompanying other musicians at SBU.
    </p>
  </div>
</div>

<!-- Hugo (image + example description provided) -->
<div class="student">
  <img src="/assets/img/hugo_profile.jpg" alt="Hugo" class="student-photo">
  <div>
    <div class="student-name">Hugo</div>
    <p class="student-desc">
      
    </p>
  </div>
</div>
