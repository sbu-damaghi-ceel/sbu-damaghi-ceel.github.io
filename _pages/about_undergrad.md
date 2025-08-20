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
  <img src="/assets/img/Portrait_Placeholder.png" alt="Soraya Rahni" class="student-photo">
  <div>
    <div class="student-name">Susoma Halder</div>
    <p class="student-desc">
      I am Susoma Halder, an undergraduate research assistant. My research focuses on comparative analysis of spatial metabolites in bat and human cancer spheroids to better understand interspecies difference in cancer biology. Outside of lab, I spend my leisure sketching and painting.
    </p>
  </div>
</div>

<!-- Soraya Rahni (no image provided) -->
<div class="student">
<img src="/assets/img/soraya_profile.jpg" alt="Soraya Rahni" class="student-photo">
  <div>
    <div class="student-name">Soraya Rahni</div>
    <p class="student-desc">
       Soraya is an undergraduate student at Stony Brook University, expected to graduate in June 2027. She is double majoring in Biology and Women’s Studies and plans to pursue a career as an OBGYN. Passionate about women’s health and patient advocacy, Soraya is especially excited about her current research on individualizing PARP inhibitor therapy in ovarian cancer. Outside of academics, she enjoys listening to Taylor Swift, spending time with friends, and is working on becoming a more consistent runner.
    </p>
  </div>
</div>

<!-- Saiful Samad (image provided) -->
<div class="student">
  <img src="/assets/img/saif_profile.jpg" alt="Saiful Samad" class="student-photo">
  <div>
    <div class="student-name">Saiful Samad</div>
    <p class="student-desc">
      Hi my name is Saiful Samad. I am a pre-medical student at Stony Brook University with strong research interests in cancer biology and treatment. My work has focused on understanding breast cancer resistance to radiation, as well as exploring potential strategies to overcome this challenge. I am also interested in mass spectrometry techniques, particularly MALDI, and their applications in cancer research alongside cryostat and analysis of data. Outside of academics, I enjoy traveling and have spent time in Pakistan and the Middle East, which has broadened my cultural perspective.
    </p>
  </div>
</div>

<!-- Arham Akhyer (image provided) -->
<div class="student">
  <img src="/assets/img/arham_profile.jpg" alt="Arham Akhyer" class="student-photo">
  <div>
    <div class="student-name">Arham Akhyer</div>
    <p class="student-desc">
      Hi my name is Arham, and I’m a junior undergraduate majoring in Biology on the pre-med track. I’m passionate about pursuing a career in medicine, and my studies have helped me stay motivated toward that goal. Outside of school, I enjoy traveling to new places and experiencing different cultures. In my free time, I like playing basketball and going to the gym, which help me stay active and balanced.
    </p>
  </div>
</div>

<!-- Jack Yang (no image provided) -->
<div class="student">
<img src="/assets/img/Portrait_Placeholder.png" alt="Jack Yang" class="student-photo">
  <div>
    <div class="student-name">Jack Yang</div>
    <p class="student-desc">
      I’m an undergraduate student at SBU majoring in Biochemistry. I have an interest in medicine and plan on pursuing graduate-level education in the future. On top of my interest in science, I also study music at SBU with the piano being my main instrument! I enjoy playing piano in my free time and accompanying other musicians at SBU.
    </p>
  </div>
</div>

