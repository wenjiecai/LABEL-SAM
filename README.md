# LABEL-SAM: 3D Slicer Plugin for Segment Anything in Annotation of Aortic Dissection

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) 
<a href="https://pytorch.org/get-started/locally/"><img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white"></a>

This is the official implementation of [LABEL-SAM](). (ICASSP 2025)

we will release the code in December ~

## Introduction

![](/figs/interface.png)

**LABEL-SAM** is a Annotation model towards solving Aortic dissection and vascular labeling issues in CT images. Our semi-automatic annotation LABEL-SAM model is based on [Meta AI](https://segment-anything.com/) to label AD objects in 3D medical images. At the same time, LABEL-SAM is integrated into the 3D slicer software as a plug-and-play plug-in for AD annotation work. LABEL-SAM can annotate in any view: coronal, axial or sagittal.

## Demo Video

A demonstration of annotation an Aortic Dissection case:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.youtube.com/watch?v=R3Fzgl1b4JQ" style="text-decoration: none;">
  <img src="/figs/YouTube.png" alt="Image 1" width="280"/>
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.bilibili.com/video/BV1QXtwepEQA/?vd_source=4eb5fca2d5207ec68d662e71ae2745e3" style="text-decoration: none;">
  <img src="/figs/bibili.png" alt="Image 2" width="320"/>
</a>



## License

The models are licensed under the [Apache 2.0 license](./LICENSE).
