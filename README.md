# Introduction to Homomorphic Cryptosystems - HE Lecture
---
This repository contains the lecture materials for the lecture that provides an introduction to homomorphic cryptosystem.
It was published at [CSECS'25](https://csecs-conf.eai-conferences.org/2025/) as _"Oratio Homomorphico: Creating a Lecture for Homomorphic Encryption by applying Design-Based Research"_

## Authors
| Name                | Affiliation                                  | E-Mail                               |
| ------------------- | -------------------------------------------- | ------------------------------------ |
| Thomas Prantl       | University of Würzburg                       | thomas.prantl@uni-wuerzburg.de       |
| Tobias Schneider    | University of Würzburg                       | tobias.schneider@uni-wuerzburg.de    |
| Lukas Horn          | University of Würzburg                       | lukas.horn@uni-wuerzburg.de          |
| Simon Engel         | University of Würzburg                       | simon.engel@uni-wuerzburg.de         |
| Lukas Iffländer     | HTW Dresden - University of Applied Sciences | lukas.ifflander@htw-dresden.de       |
| Christian Krupitzer | University of Hohenheim                      | christian.krupitzer@uni-hohenheim.de |
| Rafael Bonilla      | Escuela Superior Politecnica del Litoral     | rabonilla@espol.edu.ec               |
| Samuel Kounev       | University of Würzburg                       | samuel.kounev@uni-wuerzburg.de       |

---
## Structure
The design of the lecture follows a form that is typical in Germany. There is one lecture per week with one exercise sheet that aims to deepen the understanding of the content of the lecture.
We suggest handing out the exercise sheet right after the lecture and then discuss it in a separate session in the following week.
However, it is also possible to do the lecture as a block course with multiple lectures and exercise sheets a day. It is possible to discuss the whole content within one week.

The content of the repository is structured as follows:
- `lectures` &rarr; Lecture Units
  - For each lecture there is the PowerPoint source file
  - There further is a small slide set `OpenFHE_Code_Example.ptx` that contains a brief example for the usage of the [OpenFHE library](https://github.com/openfheorg/openfhe-development)
  - The lecture contains a set of toy examples. They are provided in the files starting with `Toy_`. The presentation slides contain a note in the top right-hand corner indicating where we consider it appropriate to present them during the leture
- `exercises` &rarr; Exercise Sheets
  - For each exercise sheet there is one directory
  - Each directory contains the LaTeX source file for the exercises. There is no LaTeX preamble but the sources can be easily copied into any template for exercise sheets
  - Each directory also contains a PDF file that gives an idea how the exercises can look like. It is a slightly modified design from the one that was used for the original three courses in 2024/25

## Lecture Hold
| Date              | Type           | Place                                   | Lecturers                        |
| ----------------- | -------------- | --------------------------------------- | -------------------------------- |
| Oct. 24 - Feb. 25 | Regular Course | University of Würzburg, Germany        | Tobias Schneider & Thomas Prantl |
| Feb. 25           | Block Course   | University of Hohenheim, Germany        | Tobias Schneider & Thomas Prantl |
| Mar. 25           | Block Course   | Goethe University of Frankfurt, Germany | Tobias Schneider & Thomas Prantl |

---

## Call for Contributions/Usage

We welcome all usage and contributions to this lecture.
If you hold the lecture we encourage you to open an [issue](todo) so that we are able to include it in the [Lecture Hold](#lecture-hold) section.
Furthermore, if you post about on LinkedIn we encourage you to notify us or tag [Descartes Research](https://de.linkedin.com/company/descartes-research) and we will be happy to repost it.

---
## License


This lecture is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.  
You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

**Under the following terms:**

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.  
  You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

**⚠️ Exception:**  
> The slide titled **"Original Lecture Team"** (Slide 2) in the first lecture (`lectures/Lecture_1.pptx`) must remain **unaltered** in all uses and adaptations.  
> This specific slide may not be modified, removed, or repurposed in derivative works.

For proper attribution, please refer to the [How to cite](#how-to-cite) section below



🔗 **License Link**: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)



---
## How to cite
If you use or adapt this lecture, please cite it using the following **BibTeX** entry:
```
@inproceedings{Oratio_Sardinen_2025,
  author = {Prantl, Thomas and Schneider, Tobias and Horn, Lukas and Engel, Simon and Iffländer, Lukas and Krupitzer, Christian and Bonilla, Rafael and Kounev, Samuel},
  booktitle = {Proceedings of the 4th EAI Conference on Computer Science and Education in Computer Science},
  month = {07},
  publisher = {Springer},
  series = {EAI CSECS 2025},
  title = {Oratio Homomorphico: Creating a Lecture for Homomorphic Encryption by applying Design-Based Research},
  year = 2025
}

```

Example:
```
Oratio Homomorphico: Creating a Lecture for Homomorphic Encryption by applying Design-Based Research. Prantl, Thomas; Schneider, Tobias; Horn, Lukas; Engel, Simon; Iffländer, Lukas; Krupitzer, Christian; Bonilla, Rafael; Kounev, Samuel; in _Proceedings of the 4th EAI Conference on Computer Science and Education in Computer Science_ (2025).
