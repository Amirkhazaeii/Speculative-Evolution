# Speculative Evolution Through 3D Cellular Automata: Synthtic Bones

Assignment 3, VIZA 626 Generative Art &amp; Design ( Spring 2025)


<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- PROJECT LOGO -->
<br />
<div align="center">
  </a>

  <h3 align="center">Cellular Metamorphosis: Evolving 3D Patterns Through Rules </h3>

  <p align="center">
 This project is the exploration of form-finding through 3D cellular automata, leveraging Conway's Game of Life rules in a 3D space for generative design , which is a class assignment about creating a generative pipeline!
    <br />
    <a 
    <br />
    <br />
    <a href="https://amirkhazaei.com">Amir Khazaei</a>
    &middot;
    <a href="https://sites.google.com/view/viza626/home">VIZA 626</a>
  </p>
</div>

[![4-comma][Main]](https://example.com)

Figure 1. This image render is a represenation of some of the iterations of my scripts!
<!-- Abstract -->
## Abstract
This project explores speculative evolution through a 3D implementation of Conway’s Game of Life, using procedural simulation to generate unfamiliar (extratrastrial)  organic forms. By applying a volumetric optimized workflow , the raw cellular structures are smoothed into unified, bone-like geometries that evoke alien biological systems. The resulting forms, (strange yet organic) are 3D printed as fossil-like artifacts, offering a tangible look into hypothetical generated structures. This process blurs the line between artificial life, evolutionary theory, and digital fabrication, suggesting a new direction for computational bio-art. The work demonstrates how simple rules can simulate complex biological emergence and challenge perceptions of the organic.




<!-- Introduction and Related Works -->
## Introduction and Related Works

The project draws inspiration from both computational science and speculative biology. Conway’s Game of Life (1970) has long been a symbol of emergent complexity from simple rules, while its extension into three dimensions opens new opportunities for spatial and biological interpretation. Dougal Dixon’s After Man (1981) laid the groundwork for speculative evolution as a genre, imagining post-human ecologies shaped by evolutionary pressures. In the digital arts, Refik Anadol’s data sculptures and generative environments influence this project’s aesthetic and conceptual foundation—particularly in translating data or simulations into spatial experiences. Ernst Haeckel’s Art Forms in Nature (1904) serves as a historical precedent in biologically-inspired form-making, emphasizing symmetry, complexity, and the underlying logic of nature. Contemporary artists working in procedural sculpture and bio-art, such as Neri Oxman, further bridge organic systems with computational design. In this context, the project positions itself as a hybrid—merging cellular automata with speculative zoology, and uniting digital life with tangible outcomes through 3D printing. It also echoes the educational goals of fictional biology projects like All Yesterdays (2013), where speculative forms not only entertain, but invite reflection on evolution, morphology, and the potential of unseen life forms, past or future.

## Methodology

[![4-comma][Methodology1]](https://example.com)
Figure 2. 72 iterations of 3D Game of Life with 6 different seeds.

[![4-comma][Canvas]](https://example.com)
Figure 3. Grasshopper Script




The process begins with a custom 3D adaptation of Conway’s Game of Life (an algorithmic system in which simple local rules lead to emergent global complexity). In contrast to its traditional 2D grid, the simulation operates within a voxelized 3D environment, allowing for the formation of spatial structures that more closely resemble organic growth. The rules were adjusted experimentally to encourage the persistence of complex forms, mimicking the behavior of biological structures.

Once the deisred results with  determined seeds and  iterations were generated, the raw voxel data was optimized and by developing a script with different attributes like rotating the initial voxel cells, mirror cutting the final mesh (volumetric workflow using the VDB (Volumetric Data Block) system), applying smoothness and unifing the voxel cells. VDB operations such as smoothing, erosion, and dilation were used to transform the cubic automata into more cohesive and lifelike surfaces. This process enhanced the organic aesthetic while preserving the underlying logic of their formation.

The smoothed geometry were then prepared for 3D printing by converting form into high-resolution meshes and optimizing them for physical fabrication. The printed result exhibit forms that appear skeletal, coral-like, or alien fossils shapoe suggesting life forms shaped by unfamiliar evolutionary forces.

Throughout the process, the project maintained a speculative design lens, treating the generated artifacts not just as abstract sculptures, but as structures of fictional of species from an alternate biology. This narrative context deepened the work's relationship to speculative evolution, turning algorithmic outputs into conceptual artifacts. The project was exploriung the intersection of evolutionary biology, procedural design.

[![4-comma][0]](https://example.com)
Figure 4. Iteration: 0, Seed: 96  

[![4-comma][1]](https://example.com)
Figure 5. Iteration: 1, Seed: 96 

[![4-comma][2]](https://example.com)
Figure 6. Iteration: 2, Seed: 96 

[![4-comma][3]](https://example.com)
Figure 7. Iteration: 3, Seed: 96 

[![4-comma][4]](https://example.com)
Figure 8. Iteration: 4, Seed: 96 

[![4-comma][5]](https://example.com)
Figure 9. Iteration: 5, Seed: 96 

[![4-comma][6]](https://example.com)
Figure 10. Iteration: 6, Seed: 96 

[![4-comma][7]](https://example.com)
Figure 11. Iteration: 7, Seed: 96 

[![4-comma][8]](https://example.com)
Figure 12. Iteration: 8, Seed: 96 

[![4-comma][9]](https://example.com)
Figure 13. Iteration: 9, Seed: 96 

[![4-comma][10]](https://example.com)
Figure 14. Iteration: 10, Seed: 96 


Mathematcial Models used in the Grasshopper script:
Anemone Loop: X(n+1) = f(X(n))
Proximity 2d Formula for findinfg the neighbours
PQ = d = √ [(x2 – x1)2 + (y2 – y1)2 + (z2 – z1)2].





## Result and Future Work
[![4-comma][Future]](https://example.com)
The results of the 3D cellular automata system reveal intricate and organic forms, evolving through multiple generations based on the initial seed and rule set. The forms exhibit fractal-like growth patterns, with areas of stability and areas of continuous transformation, mirroring natural processes. These forms can be further explored in various design contexts, from architecture to digital art. The iterative nature of the system allows for the generation of both static and dynamic designs, which could be applied to installations or interactive exhibits. Future work could involve integrating additional mathematical models, such as reaction-diffusion systems or L-systems, to add more complexity and realism to the generated forms. Furthermore, the system can be expanded to include material properties and physics simulations to explore how these digital forms can be translated into physical structures.

## Conclusion
This project demonstrates the power of cellular automata in generating complex, organic forms through simple iterative rules. By extending Conway's Game of Life into 3D, new possibilities for form-finding in generative design are explored. The results showcase how computational design can draw inspiration from natural processes, creating structures that evolve and adapt over time. Through this exploration, the project highlights the potential for cellular automata as a versatile tool in both creative and architectural practices, with numerous possibilities for future expansion and refinement.

<!-- Bibliography -->
## Bibliography 
NConway, J. H. 1970. The Game of Life. Scientific American 223, 4 (1970), 120-123.
Wolfram, S. 2002. A New Kind of Science. Wolfram Media.



<!-- CONTACT -->
## Contact

Amir Khazaei - amirkhazaei@tamu.edu

Personal Website: [https://website.com](https://amirkhazaei.com)




<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This work is submitted as part of Assignment 1 for the VIZA 626 course at Texas A&M University, under the instruction of Professor You-Jin Kim, during the Spring 2025 semester.

VIZA 626 Class Website: [https://sites.google.com/view/viza626/](https://sites.google.com/view/viza626/home)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Main]: images/Main.png
[Methodology1]: Images/Methodology1.jpg
[Canvas]: Images/Canvas.PNG
[Future]: Images/Future.jpg
[Can1]: images/Can1.png
[1]: Images/1.jpg
[2]: Images/2.jpg
[3]: Images/3.jpg
[4]: Images/4.jpg
[5]: Images/5.jpg
[6]: Images/6.jpg
[7]: Images/7.jpg
[8]: Images/8.jpg
[9]: Images/9.jpg
[10]: Images/10.jpg
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
