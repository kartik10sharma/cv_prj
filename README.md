# Smile, Yawn, and Job Interview Performance Analysis

A computer vision and machine learning project implementing the framework from the paper:  
**"Automated Prediction and Analysis of Job Interview Performance: The Role of What You Say and How You Say It"**  

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Paper Link](#paper-link)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Project Overview

This repository contains an implementation of the automated interview analysis and prediction framework described in the referenced paper. The system analyzes audio-visual recordings of job interviews, extracting multimodal features (facial expressions, language, and prosody) to predict interview performance and key social traits such as excitement, friendliness, and engagement[2][5].

---

## Features

- Extraction of facial, lexical, and prosodic features from interview videos.
- Training regression models to predict interview performance and social traits.
- Real-time smile and yawn detection using OpenCV.
- Recommendations for improving interview performance based on model insights.

---

## Tech Stack

- Python 3.x
- Jupyter Notebook
- OpenCV
- NumPy
- Dlib
- Matplotlib

---

## Getting Started

**Prerequisites:**

- Python 3.x
- Jupyter Notebook
- Required Python libraries (see below)

**Installation:**

1. Clone the repository:

   ```bash
   git clone https://github.com/kartik10sharma/cv_prj.git
   cd cv_prj
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

   *(If `requirements.txt` is not present, install manually:)*

   ```bash
   pip install opencv-python numpy matplotlib tensorflow keras
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Smile_detection-Yawn_detection.ipynb
   ```

---

## Usage

- Run each cell in the notebook sequentially.
- Follow the instructions in the notebook to process data, train models, and evaluate predictions.
- Use your own audio-visual data or request access to the MIT Interview Dataset (see below).

---

## Project Structure

- `Smile_detection-Yawn_detection.ipynb` - Main Jupyter Notebook containing code, explanations, and results.


---

## Paper Link

This project is an implementation of the following paper:  
**Automated Prediction and Analysis of Job Interview Performance: The Role of What You Say and How You Say It**  
by Iftekhar Naim, M. Iftekhar Tanveer, Daniel Gildea, and Mohammed (Ehsan) Hoque.

**Read the paper here:**  
[https://www.cs.rochester.edu/u/gildea/pubs/naim-fg15.pdf](https://www.cs.rochester.edu/u/gildea/pubs/naim-fg15.pdf)[2]

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for suggestions, bug fixes, or new features.

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Acknowledgements

- Original authors of the referenced paper
- OpenCV and machine learning community
- MIT Interview Dataset (request access [here](https://goo.gl/forms/xF4DEsg9RIsto6nu1))[5]

---

> For more details, see the [Smile_detection-Yawn_detection.ipynb](https://github.com/kartik10sharma/cv_prj/blob/main/Smile_detection-Yawn_detection.ipynb) notebook and the [paper](https://www.cs.rochester.edu/u/gildea/pubs/naim-fg15.pdf)[2].
