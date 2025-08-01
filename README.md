**Road Lane Line Detection**

Overview:
Lane line detection is a critical task in developing autonomous driving systems. In this project, we use image processing techniques and OpenCV tools to identify lane lines on roads, enabling a vehicle to navigate its path safely and consistently.
This repository contains:
- 📓 P1.ipynb: The main project notebook with all processing steps
- 📝 writeup_template.md: A concise write-up explaining the pipeline and reflections
Dependencies:
Before running the code, ensure the following are installed via the CarND Term1 Starter Kit:
- Python 3
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook
* Launch the notebook with jupyter notebook


🧪 Pipeline Description
The lane detection pipeline includes:
- Grayscale conversion for image simplification
- Gaussian blurring to reduce noise
- Canny edge detection to identify sharp edges
- Region of interest masking to focus on the relevant lane area
- Hough Transform to detect line segments
- Line extrapolation and visualization
  
⚠️ Shortcomings
- Sensitivity to lighting and shadow variations
- Lane detection may fail on curves or worn-out roads
- Limited to basic lane detection—no handling of lane curvature or multiple lane lines

🚀 Potential Improvements
- Apply perspective transforms ("bird’s eye view")
- Use color thresholding to differentiate lane colors
- Integrate with video frames for temporal smoothing
- Expand pipeline to include lane curvature and vehicle offset estimation
