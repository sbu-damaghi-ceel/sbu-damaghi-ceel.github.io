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

## **Master's Students**

<div class="student">
<img src="/assets/img/Portrait_Placeholder.png" alt="Jack Yang" class="student-photo">
  <div>
    <div class="student-name">Devin Marcheselli</div>
    <p class="student-desc">
      I received my B.S. in Biology and M.S. in Physiology and Biophysics from Stony Brook University. I work in Dr. Damaghi’s lab, where I am excited to continue my research experience. I plan on attending medical school in the near future, with the goal of integrating clinical practice and research. Outside of the lab, I enjoy playing soccer, traveling, and cooking.
    </p>
  </div>
</div>

<div class="student">
<img src="/assets/img/Portrait_Placeholder.png" alt="Jack Yang" class="student-photo">
  <div>
    <div class="student-name">Venkata Narayana Redrouthu</div>
    <p class="student-desc">
    I am a Master’s student in Data Science at Stony Brook University. I am currently working under the guidance of Professor Mehdi Damaghi and assisting Joon-Hyun Song with research on cancer evolution using single-cell multiome sequencing data. My work focuses on understanding how temporal fluctuations influence cancer cell populations in terms of global diversity and phenotypic changes. Outside of research, I enjoy playing video games and watching anime.
    </p>
  </div>
</div>
