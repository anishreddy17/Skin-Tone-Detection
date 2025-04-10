# Skin-Tone-Detection
A Python-based skin tone and undertone detection tool using facial landmarks and KMeans clustering with Dlib and OpenCV.


# Generate a README.md file for the skin tone detector project

readme_content = """\
# Skin Tone & Undertone Detector

This project is a Python-based tool for detecting a person's skin tone and undertone using facial landmarks, OpenCV, and KMeans clustering in the LAB color space. It masks out facial features like eyes, lips, and eyebrows to isolate skin regions for more accurate classification.

---

## Features

- Uses **Dlib** to detect face and 68 facial landmarks.
- Masks non-skin regions (eyes, lips, brows) to isolate skin.
- Applies **KMeans clustering** to extract dominant skin color.
- Matches LAB values with reference tones (`Light`, `Medium`, `Dark`).
- Accepts user input for **undertone** (`Warm` or `Cool`).
- Displays visual output: original, masked, and clustered skin map.

---

## Output Example

Displays:
- Original cropped face
- Masked skin-only image
- Cluster-colored segmentation based on skin tones

---

##  Requirements

- Python 3.7+
- OpenCV
- Dlib
- Scikit-learn
- Matplotlib
- NumPy
- Scipy

Install dependencies:
```bash
pip install opencv-python dlib matplotlib scikit-learn scipy numpy

