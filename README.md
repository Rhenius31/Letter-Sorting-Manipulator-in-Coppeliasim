# Automated Letter Sorting System (CoppeliaSim)

## Overview
This project implements an autonomous letter sorting system using a robotic manipulator in CoppeliaSim. The system uses a vision sensor and OCR to read recipient information from letters and sort them into designated locations.

The pipeline integrates computer vision, text recognition, and robotic control to achieve fully automated pick-and-place sorting.

---

## Features
- Vision-based image acquisition  
- OCR for text extraction from letters  
- Robotic pick-and-place using an articulated arm  
- Automated decision-making for sorting  
- Simulation in CoppeliaSim  
- Lua and Python-based control  

---

## System Workflow
1. Capture image using a top-mounted vision sensor  
2. Detect Region of Interest (letter surface)  
3. Extract text using OCR  
4. Classify letter based on extracted information  
5. Plan motion for pick-and-place  
6. Robot sorts the letter into the correct bin  

---

## Technologies Used
- MATLAB for IK
- CoppeliaSim  
- Python (OCR processing)  
- OpenCV  

---

## Applications
- Postal automation  
- Document sorting systems  
- Smart logistics  

---


---

## Project Structure
