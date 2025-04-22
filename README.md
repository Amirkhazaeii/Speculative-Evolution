# Speculative-Evolution

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
This project explores the use of cellular automata (CA) as a generative tool for form-finding in 3D spaces. Inspired by Conway's Game of Life, this investigation applies its fundamental rules to voxel grids to evolve complex, organic shapes. By utilizing a 3D CA system with rules for under-population, survival, over-population, and reproduction, dynamic forms emerge, evolving through iterative processes. This exploration aims to demonstrate how mathematical principles can inform creative design and generate both stable and evolving structures. The process, analysis, and results showcase the potential of CA in digital design workflows.


<!-- Introduction and Related Works -->
## Introduction and Related Works

Cellular automata (CA) have long been used in design and computational art, with notable works like those by John Conway and later applications in generative design and architecture. Conway’s Game of Life, a 2D CA, has been widely used in demonstrating how simple rules can result in complex, emergent patterns. Recent works in generative design, such as Neri Oxman’s studies on nature-inspired computational design, show how algorithms can mimic biological processes. This project extends Conway’s Game of Life into the third dimension, exploring voxel-based grids and the rule set’s application in 3D modeling. The evolution of forms through CA has been explored in multiple art forms and architectural design, where simple rules evolve into complex structures, often mirroring natural forms. The work of Refik Anadol, in data-driven design, further enhances this approach, generating organic and fluid forms through digital processes. This project builds upon these ideas, applying CA to form-finding for architectural and artistic purposes.

## Methodology

[![4-comma][Methodology1]](https://example.com)
Figure 2. 72 iterations of 3D Game of Life with 6 different seeds.

[![4-comma][Canvas]](https://example.com)
Figure 3. Grasshopper Script




This project utilizes a 3D cellular automata system to explore the generative design of complex forms. The system is based on Conway’s Game of Life but extended into three dimensions, where each cell (voxel) has 26 potential neighbors. The system follows four fundamental rules:

Under-population: A live cell with fewer than two live neighbors dies.

Survival: A live cell with two or three live neighbors survives to the next generation.

Over-population: A live cell with more than three live neighbors dies.

Reproduction: A dead cell with exactly three live neighbors becomes alive.

In Grasshopper, the voxel grid is created using parameters for grid size, voxel resolution, and initial randomness. A random seed initializes the grid, with cells assigned a state of either alive or dead based on probability. The neighbor states are calculated using Euclidean distance, and each iteration applies the rules to evolve the grid’s state. This process is repeated across multiple generations to form complex, organic structures. The resulting forms are visualized through varying colors to represent alive and dead cells. Additionally, the system’s flexibility allows for the exploration of various parameters, such as grid size, neighbor radius, and mutation rates, which influence the final shapes."


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
[Main]: Images/Main.jpg
[Methodology1]: Images/Methodology1.jpg
[Canvas]: Images/Canvas.PNG
[Future]: Images/Future.jpg
[0]: Images/0.jpg
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
