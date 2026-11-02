# nao-behavior-modeling 🤖

**Author:** Khulekani Hillary Mthethwa  
**Institution:** University of Parma | Robotics and Intelligent Machines Laboratory (RIMLab)

## Overview
This repository contains my B.Sc. Computer Science thesis, *"Dynamic Behavior Modeling in Social Robotics: Synchronizing Motor Kinematics and Emotion-Driven Logic for the NAO Platform"*. The research focuses on transforming the NAO robot from a static interface into a dynamic, socially assistive companion for clinical cognitive rehabilitation.

## Core Engineering Topics Covered
Inside the thesis document, you will find complete architectural breakdowns of:
* **Multithreaded Speech-Motor Synchronization:** Engineering a 0.4-second hardware spin-up buffer and pre-emptive callback locks to align neural `Edge-TTS` audio streams with physical actuator execution.
* **Emotion-Driven Logic:** Expanding declarative Answer Set Programming (ASP) via `feedback.asp` to map real-time facial emotion recognition to context-aware physical gestures.
* **Behavioral Sparsity Modeling:** Implementing a probabilistic 30/70 rule to balance high-amplitude emotional reactions with subtle human-like micro-gestures.
* **Custom Kinematics:** Exporting Bézier-interpolated joint keyframes via zero-stiffness kinesthetic teaching for execution through the `ALMotion` API.

## Codebase Status
*Note: The underlying Python and ASP codebase was developed as part of an ongoing clinical architecture at RIMLab. Code excerpts are available within the thesis PDF, and the full repository will be published pending academic clearance.*
