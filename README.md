# Video-Denoising-Optimization
Improving existing traditional video denoising methods

# Optimizing Video Denoising Methods: Enhancements in Temporal, Spatial and DCT Color Preservation



## Abstract

This project introduces innovative approaches to video denoising, focusing on adaptive techniques without relying on deep learning. We address the balance between noise reduction and detail preservation through spatial, temporal, and DCT-based denoising methods. Our spatial techniques employ adaptive filtering to adjust to video characteristics dynamically, ensuring superior performance across diverse spatial contexts. Temporally, aggressive optimization techniques enhance processing pipelines, particularly beneficial for resource-limited devices. DCT-based denoising prioritizes color preservation through meticulous processing, enhancing visual fidelity and perceptual quality. Experimental evaluations demonstrate the efficacy of our methods in challenging scenarios, including dynamic scenes. Our code is accessible on Google Colab, promoting reproducibility and accessibility.
Published in IJARSE 2024-http://ijarse.com/images/fullpdf/1715421667_GU294.pdf

## Overview

Video denoising is crucial in applications like surveillance, digital cinematography, and video streaming, demanding high-fidelity multimedia content. Traditional methods struggle with noise reduction while preserving fine details and textures, motivating our exploration of novel denoising solutions. This project aims to advance denoising methodologies by integrating spatial, temporal, and transform-domain techniques. Our approach leverages insights from signal processing to design a framework exploiting spatial correlations, temporal dependencies, and frequency characteristics in video sequences. We address limitations by enhancing detail preservation, noise reduction efficiency, and computational scalability.

## Key Features

- **Adaptive Filtering**: Dynamic adjustment of filters to video characteristics for superior spatial denoising.
- **Optimization Techniques**: Aggressive optimizations in processing pipelines for enhanced temporal denoising.
- **Color Preservation**: DCT-based methods tailored for color video data to preserve visual fidelity.
- **Experimental Evaluation**: Comparative analysis demonstrating superiority in challenging scenarios.
- **Reproducibility**: Accessible code on Google Colab for transparency and accessibility.
Optimizations Over Each Method
In our research, we have focused on enhancing video denoising by improving upon existing traditional methods, namely spatial filtering, temporal filtering, and transform-domain processing. Our approach involves addressing the weaknesses identified in these methods to achieve superior denoising performance while maintaining computational efficiency and preserving visual fidelity.

Spatial Denoising
Adaptive Filtering: We dynamically adjust filter parameters to adapt to the specific characteristics of each video frame. This ensures superior performance across diverse spatial contexts.
Parallel Processing and Batch Serialization: By leveraging parallelization, we have accelerated the denoising process, enabling real-time or large-scale video processing.
Segmented Processing: Breaking the video into smaller segments allows for processing on devices with limited RAM, making the method more resource-efficient.
Histogram Equalization: Pre-processing techniques like histogram equalization were implemented to enhance the effectiveness of spatial denoising.
Temporal Denoising
Aggressive Optimization: We implemented aggressive optimization techniques that extend to all facets of the processing pipeline, maximizing performance on resource-limited machines.
Motion Compensation: By using motion-compensated temporal filtering, we effectively preserve sharp edges and reduce noise without introducing motion blur.
Segmented and Adaptive Filtering: Similar to spatial denoising, segmented processing and adaptive filtering parameters were used to balance noise reduction and temporal fidelity.
Parallel Processing and Memory Management: These techniques were applied to further enhance performance, ensuring efficient utilization of resources.
DCT-Based Denoising
Color Preservation: Our method prioritizes color preservation by meticulously processing individual channels, which enhances visual fidelity and perceptual quality.
Adaptive Denoising Parameters: We implemented adaptive denoising parameters to handle different noise profiles effectively.
Multithreaded Processing and Buffer Management: These optimizations improve the efficiency and effectiveness of DCT-based denoising, enabling faster and more accurate processing.
Segmented Processing: This allows for efficient handling of video data on devices with limited memory, further optimizing resource usage.

## Repository Structure

- two branches:main with stable code and experimental with unstable code which utilizes gpu accelaration and aggressive optimization that affects image quality

## Installation

Completely run on google colab so no version issues with python libraries and it can easily be recreated on any cloud environment

## Videos used for reference:
Drive link to folder which has videos(original,noisy,pre processed and denoised)-https://drive.google.com/drive/folders/1cDztznmIpzVRsU2UnCS_iwbYWQEyBwW3?usp=sharing


To view videos simultaneously I utilized GridPlayer which synchronizes up to four videos playing together which makes bisually comparing denoising methods easier
