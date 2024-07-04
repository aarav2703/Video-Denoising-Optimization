# Video-Denoising-Optimization
Improving existing traditional video denoising methods

# Optimizing Video Denoising Methods: Enhancements in Temporal, Spatial and DCT Color Preservation



## Abstract

This project introduces innovative approaches to video denoising, focusing on adaptive techniques without relying on deep learning. We address the balance between noise reduction and detail preservation through spatial, temporal, and DCT-based denoising methods. Our spatial techniques employ adaptive filtering to adjust to video characteristics dynamically, ensuring superior performance across diverse spatial contexts. Temporally, aggressive optimization techniques enhance processing pipelines, particularly beneficial for resource-limited devices. DCT-based denoising prioritizes color preservation through meticulous processing, enhancing visual fidelity and perceptual quality. Experimental evaluations demonstrate the efficacy of our methods in challenging scenarios, including dynamic scenes. Our code is accessible on Google Colab, promoting reproducibility and accessibility.

## Overview

Video denoising is crucial in applications like surveillance, digital cinematography, and video streaming, demanding high-fidelity multimedia content. Traditional methods struggle with noise reduction while preserving fine details and textures, motivating our exploration of novel denoising solutions. This project aims to advance denoising methodologies by integrating spatial, temporal, and transform-domain techniques. Our approach leverages insights from signal processing to design a framework exploiting spatial correlations, temporal dependencies, and frequency characteristics in video sequences. We address limitations by enhancing detail preservation, noise reduction efficiency, and computational scalability.

## Key Features

- **Adaptive Filtering**: Dynamic adjustment of filters to video characteristics for superior spatial denoising.
- **Optimization Techniques**: Aggressive optimizations in processing pipelines for enhanced temporal denoising.
- **Color Preservation**: DCT-based methods tailored for color video data to preserve visual fidelity.
- **Experimental Evaluation**: Comparative analysis demonstrating superiority in challenging scenarios.
- **Reproducibility**: Accessible code on Google Colab for transparency and accessibility.

## Repository Structure

- two branches:main with stable code and experimental with unstable code which utilizes gpu accelaration and aggressive optimization that affects image quality

## Installation

Completely run on google colab so no version issues with python libraries
