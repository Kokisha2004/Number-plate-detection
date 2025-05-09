# Number Plate Recognition - Naan Mudhalvan Project

This project is developed as part of the **Naan Mudhalvan** skill development program under the subject **Deep Learning**. It uses image processing and Optical Character Recognition (OCR) to detect and extract text from vehicle number plates.

## Introduction

Number plate recognition is a crucial task in traffic surveillance and intelligent transport systems. In this project, OpenCV is used for image preprocessing and contour detection, while **Tesseract OCR** is used to recognize characters from the extracted number plate region.

## Project Structure

- `number_plate_recognition.ipynb` – Jupyter Notebook containing code for preprocessing, plate detection, and OCR.
- `README.md` – Project documentation.

## Technologies Used

- Python  
- Google Colab  
- OpenCV (Image Preprocessing & Contour Detection)  
- Tesseract OCR (Optical Character Recognition)  
- NumPy (Array Operations)

## How to Run

1. Open the notebook in **Google Colab**:  
   👉 [Click here to open in Colab](https://colab.research.google.com/github/Kokisha2004/Number-plate-detection/blob/main/Number_plate_detection.ipynb)

2. Upload an image containing a vehicle with a visible number plate.

3. The code will detect the number plate, extract the region, and use Tesseract to recognize and print the number.

## Future Enhancements

- Improve accuracy by fine-tuning OCR configurations.  
- Add support for detecting multiple plates in an image.  
- Integrate with a vehicle database for real-time search and verification.  
- Deploy as a web app using Gradio or Streamlit.

## License

This project is developed for educational purposes under the **Naan Mudhalvan** initiative.
