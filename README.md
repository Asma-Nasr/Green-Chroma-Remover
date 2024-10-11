# Green Chroma Remover

This repository contains my implementation of the Green Chroma Remover task, where the goal is to remove green backgrounds from images. Provided by Intern2Grow as part of their Image Processing
 Virtual Internship Program.

## Task Overview

In this task, I developed a program that takes any image with a green background and removes the green color, effectively allowing for a transparent background where the green was present.

### Implementation Details

- The main code is contained in the Jupyter Notebook file `Green Chroma Remover.ipynb`.
- An example image is included in the repository as `11.jpg`, which demonstrates the effect of the green chroma removal.

### How It Works

1. **Input Image**: The program takes an input image with a predominant green background.
2. **Color Detection**: It detects the green color using color thresholds.
3. **Background Removal**: The detected green areas are made transparent, allowing the subject of the image to stand out.

### Usage Instructions

To run the program, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Asma-Nasr/Green-Chroma-Remover.git
   ```
2. Open the Jupyter Notebook:
  ```bash
  jupyter notebook Green Chroma Remover.ipynb
  ```

Run the cells in the notebook to execute the chroma removal on the provided image.

## Repository Structure
- `Green Chroma Remover.ipynb`: Jupyter Notebook containing the implementation.
- `11.jpg` : Example image used for chroma removal.
