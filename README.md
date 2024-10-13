<p align="center">
  <img width="500" alt="PictoLogo" src="https://github.com/user-attachments/assets/178e0373-7d9b-4dc0-8a50-55afba75d8ab">
  </br>
  </br>
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/y/EliaFantini/PICTO-Automating-Video-Thumbnails-Selection">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/EliaFantini/PICTO-Automating-Video-Thumbnails-Selection">
  <img alt="GitHub code size" src="https://img.shields.io/github/languages/code-size/EliaFantini/PICTO-Automating-Video-Thumbnails-Selection">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/EliaFantini/PICTO-Automating-Video-Thumbnails-Selection">
  <img alt="GitHub follow" src="https://img.shields.io/github/followers/EliaFantini?label=Follow">
  <img alt="GitHub fork" src="https://img.shields.io/github/forks/EliaFantini/PICTO-Automating-Video-Thumbnails-Selection?label=Fork">
  <img alt="GitHub watchers" src="https://img.shields.io/github/watchers/EliaFantini/PICTO-Automating-Video-Thumbnails-Selection?label=Watch">
  <img alt="GitHub star" src="https://img.shields.io/github/stars/EliaFantini/PICTO-Automating-Video-Thumbnails-Selection?style=social">
</p>

**Picto** is a software that automatizes video thumbnails selection and
generation with multimodal and multistage analysis. The approach includes a complex pipeline leveraging multiple AI models, and a user-friendly GUI to explore the output of such a pipeline. 

This research was realized as Master Project and Master Thesis for the faculty of MSc Data Science at EPFL. The thesis has benefited from the comprehensive guidance of the company supervisor Dr. Gabriel Autès, providing industry-specific insights and oversight. Academic supervision was provided by Prof. Dr. Sabine Süsstrunk, who leads the Image and Visual Representation
Lab at the School of Computer and Communication Sciences (IC).

This repository's aim is to showcase my thesis research process and outcomes, as well as its future progress as an internal tool for the company Play Suisse and SRG SSR. Therefore this repository will not contain the implementation's code, which will remain private.


Below is a video of a part of the final Thesis presentation slides, with the most important and representative slides. For all details of the research and implementation, look at the (Thesis report)[]

https://github.com/user-attachments/assets/b616cbd1-f800-451e-9fdd-f4a50e0afb2a






## Authors
- [Elia Fantini](https://github.com/EliaFantini)
## Abstract

This thesis presents an innovative approach to automate the selection of potential thumbnails for videos, encompassing movies, documentaries, and TV series, with a focus on traditional broadcast video production content. Our methodology is predicated on the establishment of stringent criteria that prioritize a broad and diverse array of proposals, ensuring that the selected thumbnails are not only aesthetically pleasing but also faithfully representative of the video content. Important factors in our selection process include ensuring sufficient space for logo placement, incorporating vertical aspect ratios, and accurately recognizing facial identities and emotions. In order to achieve these 
 objectives, we introduce a sophisticated multistage pipeline. This pipeline is designed to meticulously select candidate frames from the video while also generating novel images by blending different foregrounds and backgrounds—either sourced directly from the video or synthesized using diffusion models. The pipeline incorporates a suite of state-of-the-art models, including downsampling, redundancy reduction, automated cropping, face recognition, closed-eye and emotion detection, shot scale and aesthetic prediction, segmentation, matting, and harmonization models. Furthermore, it leverages large language models and visual transformers to ensure semantic consistency. A graphical user interface (GUI) tool is developed to facilitate a rapid and intuitive navigation of the pipeline’s output, significantly streamlining the selection process. To address the inherently subjective nature of thumbnail evaluation, we conducted comprehensive experiments. In an initial study comprising 69 videos, findings revealed that 53.6% of our proposed set included thumbnails chosen by professional designers. Moreover, in 73.9% of instances, the proposed thumbnails contained images at least resembling the professionally selected ones. A subsequent survey involving 82 participants indicated a preference for our method 45.77% of the time, compared to 37.99% for manually chosen thumbnails and  16.36% for an alternative thumbnail selection method. Tests from professional thumbnail designers highlighted a 3.57-fold increase in the percentage of valid candidates found among the proposed set compared to the alternative method, and their feedback indicates that the method effectively fulfills the established criteria. In conclusion, the findings of this thesis affirm that our proposed method not only accelerates the thumbnail creation process but also adheres to high-quality standards, thereby fostering greater user engagement.

## Trailer
This video showcase trailer aims to show the functionality of the tool for the final user, explaining its functionalities up to the date of the realization of the trailer ( September 2024 ). Since GitHub doesn't let upload videos bigger than 10MB, the video had to be compressed and the quality is much lower than the original. 


TODO: upload trailer


## Files description

```
├── Elia_Fantini_Master_Thesis.pdf    # The detailed report of the Master Thesis 
└── README.md                         # You are here
```


## 🛠 Skills and technologies used in this project

Python, C++, PyTorch, Tensorflow, Docker, Azure, AzureML Pipelines, Linux, Javascript, HTML, CSS, Photoshop, CapCut, and more. Academic research of all previous papers on the subject of thumbnail selection/extraction/generation and related research fields. Designing and implementing a novel AI approach to the research problem, validation of such solution via user testing and research survey, with statistical analysis of users' preferences. Python and C++ code optimization for scaling up and speeding up the original solution.  Designing and implementing the Picto web app backend and frontend, with UI/UX experience to improve the most the user-friendliness of the GUI interface. CapCut for the realization of the showcase trailer. Experience in specifications and functionalities design through discussions with the main project's stakeholders.

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://eliafantini.github.io/Portfolio/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/-elia-fantini/)
