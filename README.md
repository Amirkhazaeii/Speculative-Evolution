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

  <h3 align="center">Speculative Evolution Through 3D Cellular Automata: Synthtic Bones </h3>

  <p align="center">
This is my final assignment for Generative Art and Design class that explores speculative evolution through a 3D implementation of Conway’s Game of Life, using procedural simulation to generate unfamiliar (extratrastrial)  organic forms
    <a 
    <br />
    <br />
    <a href="https://amirkhazaei.com">Amir Khazaei</a>
    &middot;
    <a href="https://sites.google.com/view/viza626/home">VIZA 626</a>
  </p>
</div>

[![4-comma][Main]](https://example.com)

Figure 1. Still Renders of the final Project/ Seed 49/ Iteration 60 that demonstrates the 3D implementation of Conway’s Game of Life, using procedural simulation to generate unfamiliar (extratrastrial) organic forms
<!-- Abstract -->
## Abstract
This project explores speculative evolution through a 3D implementation of Conway’s Game of Life, using procedural simulation to generate unfamiliar (extratrastrial)  organic forms. By applying a volumetric optimized workflow , the raw cellular structures are smoothed into unified, bone-like geometries that evoke alien biological systems. The resulting forms, (strange yet organic) are 3D printed as fossil-like artifacts, offering a tangible look into hypothetical generated structures. This process blurs the line between artificial life, evolutionary theory, and digital fabrication, suggesting a new direction for computational bio-art. The work demonstrates how simple rules can simulate complex biological emergence and challenge perceptions of the organic.




<!-- Introduction and Related Works -->
## Introduction and Related Works

The project draws inspiration from both computational science and speculative biology. Conway’s Game of Life (1970) has long been a symbol of emergent complexity from simple rules, while its extension into three dimensions opens new opportunities for spatial and biological interpretation. Dougal Dixon’s After Man (1981) laid the groundwork for speculative evolution as a genre, imagining post-human ecologies shaped by evolutionary pressures. In the digital arts, Refik Anadol’s data sculptures and generative environments influence this project’s aesthetic and conceptual foundation—particularly in translating data or simulations into spatial experiences. Ernst Haeckel’s Art Forms in Nature (1904) serves as a historical precedent in biologically-inspired form-making, emphasizing symmetry, complexity, and the underlying logic of nature. Contemporary artists working in procedural sculpture and bio-art, such as Neri Oxman, further bridge organic systems with computational design. In this context, the project positions itself as a hybrid merging cellular automata with speculative zoology, and uniting digital life with tangible outcomes through 3D printing. It also echoes the educational goals of fictional biology projects like All Yesterdays (2013), where speculative forms not only entertain, but invite reflection on evolution, morphology, and the potential of unseen life forms, past or future.

## Methodology

[![4-comma][Iteration]](https://example.com)
Figure 2. The result of the generative pipeline with three different seeds and the same iterationa(20)
[![4-comma][Can1]](https://example.com)
Figure 3. VDB process operations such as smoothing, erosion, and dilation were used to transform the cubic automata into more cohesive and lifelike surfaces

[![4-comma][Can2]](https://example.com)
Figure 4. The initial 3D Cellular Automota Conway's game of life script that has been developed for the previous assignment

[![4-comma][Can3]](https://example.com)
Figure 5. Grasshopper Script that demonstrates the result of the simuation with sed number 49 adn 60 iteraiotn (raw voxel cells)

[![4-comma][Can4]](https://example.com)
Figure 6. Grasshopper Script that demonstrates the smoothened result of the simuation with sed number 49 adn 60 iteraiotn (raw voxel cells)



The process begins with a custom 3D adaptation of Conway’s Game of Life (an algorithmic system in which simple local rules lead to emergent global complexity). In contrast to its traditional 2D grid, the simulation operates within a voxelized 3D environment, allowing for the formation of spatial structures that more closely resemble organic growth. The rules were adjusted experimentally to encourage the persistence of complex forms, mimicking the behavior of biological structures.

Once the deisred results with  determined seeds and  iterations were generated, the raw voxel data was optimized and by developing a script with different attributes like rotating the initial voxel cells, mirror cutting the final mesh (volumetric workflow using the VDB (Volumetric Data Block) system), applying smoothness and unifing the voxel cells. VDB operations such as smoothing, erosion, and dilation were used to transform the cubic automata into more cohesive and lifelike surfaces. This process enhanced the organic aesthetic while preserving the underlying logic of their formation.

The smoothed geometry were then prepared for 3D printing by converting form into high-resolution meshes and optimizing them for physical fabrication. The printed result exhibit forms that appear skeletal, coral-like, or alien fossils shapoe suggesting life forms shaped by unfamiliar evolutionary forces.

Throughout the process, the project maintained a speculative design lens, treating the generated artifacts not just as abstract sculptures, but as structures of fictional of species from an alternate biology. This narrative context deepened the work's relationship to speculative evolution, turning algorithmic outputs into conceptual artifacts. The project was exploriung the intersection of evolutionary biology, procedural design.

Mathematcial Models used in the Grasshopper script:
Anemone Loop: X(n+1) = f(X(n))
Proximity 2d Formula for findinfg the neighbours
PQ = d = √ [(x2 – x1)2 + (y2 – y1)2 + (z2 – z1)2].


## Digital Fabrication

The smoothed geometry were then prepared for 3D printing by converting form into high-resolution meshes and optimizing them for physical fabrication. The printed result exhibit forms that appear skeletal, coral-like, or alien fossils shapoe suggesting life forms shaped by unfamiliar evolutionary forces.

[![4-comma][F1]](https://example.com)
Figure 7. Still render that demonstrates thr Contoured Geometry

[![4-comma][F2]](https://example.com)
Figure 8. Still render that demonstrates thr Contoured Geometry



[![4-comma][Pic1]](https://example.com)
Figure 9. an image of the phyisical 3d printed form

[![4-comma][Pic2]](https://example.com)
Figure 10.  an image of the phyisical 3d printed form








## Result and Future Work



[![4-comma][Can6]](https://example.com)
Figure 11. The script that demonstrates the process of mesh optimization and contouring the shape for 3d printing

[![4-comma][Can7]](https://example.com)
Figure 12. The script that demonstrates the process of mesh optimization and contouring the shape for 3d printing with the rhino view port




The final artifacts produced through this method are physically 3D printed sculptures that resemble abstract biological remains. Their unfamiliar forms provoke curiosity, bone spurs, or exoskeletal armor from speculative life forms. These shapes are rooted in simple algorithms yet suggest a deep evolutionary history. The project successfully demonstrates that algorithmic systems can serve as a generative base for speculative biology—creating forms that, while not real, feel plausible within a biological framework.

Future directions include expanding the simulation rules to mimic ecological interactions, such as predation or symbiosis, potentially leading to even more complex morphologies. A system could also be introduced to simulate mutation and natural selection, allowing the digital organisms to evolve over time based on survival heuristics. These developments would move the project toward a more dynamic and self-driven model of artificial life as well as exploring digital fabrication and exploring methods to print solid and transparent layers at the same time.

[![4-comma][Future]](https://example.com)
Figure 13. Still image demonstrates the contoured 3D Form for showing the layers with more details


## Conclusion
This project demonstrates how simple computational rules can give rise to biologically suggestive and visually compelling forms. By combining 3D cellular automata, volumetric modeling, and digital fabrication, it transforms abstract data into tangible artifacts of fictional biology. Positioned within the speculative evolution genre, the work bridges art, science, and narrative—inviting reflection on how life could evolve under different conditions. It also showcases the potential of algorithmic design as both an artistic and scientific tool. These emergent forms not only provoke the imagination but also highlight the power of simulation to expand our understanding of life and complexity itself.

<!-- Bibliography -->
## Bibliography 
Conway, J. H. 1970. The Game of Life. Scientific American 223, 4 (1970), 120–123.

Dixon, D. 1981. After Man: A Zoology of the Future. St. Martin’s Press.

Anadol, R. Various Works. [Data Sculptures and Generative Environments]. Accessible via: https://refikanadol.com/

Haeckel, E. 1904. Art Forms in Nature. Bibliographisches Institut.

Oxman, N. Various Projects. [Procedural Design and Bio-Art]. Accessible via: https://neri.media.mit.edu/

Conway, J. H., Gardner, M. 1970. Mathematical Games: The fantastic combinations of John Conway’s new solitaire game “life.” Scientific American, 223, 4 (1970), 120–123.

Naish, D., Conway, J., and Kosemen, C. M. 2013. All Yesterdays: Unique and Speculative Views of Dinosaurs and Other Prehistoric Animals. Irregular Books.



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
[Canvas]: images/Canvas.PNG
[Can1]: images/Can1.png
[Can2]: images/Can2.png
[Can3]: images/Can3.png
[Can4]: images/Can4.png
[Can5]: images/Can5.png
[Can6]: images/Can6.png
[Can7]: images/Can7.png
[Pic1]: images/Pic1.png
[Pic2]: images/Pic2.png
[Iteration]: images/Iteration.png
[F1]: images/F1.png
[F2]: images/F2.png
[Future]: images/Future.png
[RenTest]: images/RenTest.png



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
