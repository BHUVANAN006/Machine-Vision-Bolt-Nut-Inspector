# Machine Vision-Based Bolt & Nut Assembly Inspector

## Overview

The **Machine Vision-Based Bolt & Nut Assembly Inspector** is an automated inspection system designed to verify the correct assembly of bolts and nuts using computer vision.

The system captures an image of the bolt and nut assembly, processes the image, identifies the required components, and determines whether the assembly condition is **OK** or **NOT OK**.

This project demonstrates the application of **Machine Vision, Image Processing, Python, and OpenCV** for automated manufacturing quality inspection.

---

## Objective

- Automate bolt and nut assembly inspection.
- Reduce manual inspection effort.
- Detect missing or incorrectly assembled components.
- Improve inspection consistency.
- Provide quick inspection results.
- Demonstrate machine vision in manufacturing quality control.

---

## Problem Statement

Manual inspection of bolt and nut assemblies can be time-consuming and may result in inconsistent inspection due to human error.

The proposed system uses a camera-based machine vision approach to inspect the assembly and identify whether the required bolt and nut components are correctly present.

---

## How the System Works

```text
Camera / Image Input
        ↓
Image Acquisition
        ↓
Image Pre-processing
        ↓
Bolt & Nut Detection
        ↓
Assembly Verification
        ↓
Inspection Decision
        ↓
OK / NOT OK Result
