# Golam Ishtiak

Third-year undergraduate at [Nanyang Technological University (NTU)](https://www.ntu.edu.sg/), pursuing a Bachelor of Science in Physics with a Second Major in Data Analytics. My primary interests lie in theoretical physics, specifically quantum dynamics, statistical mechanics, and general relativity. I am expected to graduate in January 2028.

I was born and raised in Kushtia, Bangladesh. I initially began my undergraduate studies in Mechanical Engineering at [Bangladesh University of Engineering and Technology (BUET)](https://www.buet.ac.bd/), but quickly realized my passion lay in understanding fundamental laws and not applied mechanics. This drive led me to withdraw from BUET and move to NTU to pursue my passion. 

Beyond my coursework and research, I have a strong interest in problem-solving and teaching. I was an active participant in the Bangladesh Physics Olympiad (BdPhO) until 2023 and later mentored at multiple national training camps for the Bangladesh Physics Olympiad and Bangladesh Junior Science Olympiad. I have previously worked with Mercor Intelligence to design adversarial, Olympiad-level physics problem sets to test and train AI models. Teaching competitive physics inspired me to compile extensive study notes in both Bengali and English to make physics concepts more accessible.

<a href="CV_Ishtiak_Golam.pdf" target="_blank"><b>Curriculum Vitae (PDF)</b></a> | **Email:** <a href="mailto:isht0001@e.ntu.edu.sg">isht0001@e.ntu.edu.sg</a>

---

## Research & Projects

**1D Bosonic Quantum Gases (URECA Project):** For my ongoing URECA project under the supervision of [Professor Nelly Ng Huei Ying](https://dr.ntu.edu.sg/entities/person/Nelly-Ng-Huei-Ying), I am conducting a theoretical and computational investigation into the relaxation dynamics and thermalization of 1D bosonic quantum gases. This research uses Python to model and simulate these systems using the exact solutions of the Lieb-Liniger model.

**Review of Gauge Field Theories (Odyssey Research Project):** I am conducting a rigorous review of quantum mechanical formalism and relativistic matter fields, with a specific focus on the Klein-Gordon and Dirac equations. The primary objective of this work is to study in depth the theoretical formulation of Abelian and non-Abelian gauge field theories, establishing a mathematical foundation for advanced quantum mechanics. This project is supervised by [Dr. Leek Meng Lee](https://dr.ntu.edu.sg/entities/person/Leek-Meng-Lee). 


## Notes & Resources

**Olympiad & Competitive Physics Outreach**
The following notes are parts of an incomplete Physics Olympiad textbook project. More chapters are to be uploaded soon. For any suggestions or to report any mistakes, please reach out to me via social media or personal <a href="mailto:ishtiakk10@gmail.com">email.</a> 
Although I studied under the Bengali medium curriculum, I learned most physics concepts through English textbooks. I have tried to make the Bengali translations as clear as possible, but if any terminology seems out of place, please refer to the English version of the PDF.
* Translational Dynamics  <a href="chapter3 bn.pdf" target="_blank"><b> (Bengali)</b></a> <a href="chapter3 en.pdf" target="_blank"><b> (English)</b></a>
* Oscillations  <a href="chapter6 bn.pdf" target="_blank"><b> (Bengali)</b></a> <a href="chapter6 en.pdf" target="_blank"><b> (English)</b></a>
* Central Force  <a href="chapter7 bn.pdf" target="_blank"><b> (Bengali)</b></a> <a href="chapter7 en.pdf" target="_blank"><b> (English)</b></a>

---
> **Copyright & Distribution:** All materials linked above are open-source and provided completely free of cost for educational purposes. Commercial use, reproduction for profit, or distribution in paid coaching programs is strictly prohibited under the [CC BY-NC 4.0 License](http://creativecommons.org/licenses/by-nc/4.0/).




<script>
  document.addEventListener("DOMContentLoaded", function() {
    // 1. Create the button dynamically
    const toggleBtn = document.createElement("button");
    toggleBtn.id = "theme-toggle";
    document.body.appendChild(toggleBtn);

    // 2. Default to Dark Mode unless they explicitly chose "light"
    if (localStorage.getItem("theme") !== "light") {
      document.body.classList.add("dark-mode");
      toggleBtn.innerHTML = "☀️ Light Mode";
    } else {
      toggleBtn.innerHTML = "🌙 Dark Mode";
    }

    // 3. Listen for clicks to switch modes
    toggleBtn.addEventListener("click", function() {
      document.body.classList.toggle("dark-mode");
      
      // Save the preference and change the icon
      if (document.body.classList.contains("dark-mode")) {
        localStorage.setItem("theme", "dark");
        toggleBtn.innerHTML = "☀️ Light Mode";
      } else {
        localStorage.setItem("theme", "light");
        toggleBtn.innerHTML = "🌙 Dark Mode";
      }
    });
  });
</script>
