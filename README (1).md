# Face Recognition Attendance System

## 1. Project Objective

The objective of this project is to create a simple attendance system using face recognition. The system recognizes a registered person and records their attendance with the date and time.

## 2. Dataset

For this project, face images were collected with permission and used for training and testing the system.

The internship guidelines provided CelebA and LFW as reference datasets. The collected face images are kept locally and are not uploaded to GitHub for privacy reasons.

## 3. Technologies Used

- Python
- Jupyter Notebook
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- face_recognition
- Tkinter

## 4. Project Workflow

Face Images
↓
Image Preprocessing
↓
Image Augmentation
↓
Face Detection
↓
Facial Embeddings
↓
KNN Classifier
↓
Face Recognition
↓
Attendance Marking
↓
Date and Time
↓
Attendance CSV File

## 5. Image Preprocessing

The collected face images were resized to 160 × 160 pixels.

The pixel values were normalized by dividing them by 255.

Image augmentation was also performed using horizontal flipping and brightness changes.

## 6. Face Detection

Haar Cascade was used to detect faces from the images.

The detected face was cropped and resized before extracting facial features.

## 7. Facial Embeddings

The face_recognition library was used to extract facial embeddings from the detected faces.

These embeddings were used as input for the KNN classifier.

## 8. Classification

A K-Nearest Neighbors (KNN) classifier was used for face recognition.

The facial embeddings were used to train the KNN model.

## 9. Attendance

After recognizing the registered person, attendance is recorded in a CSV file.

The attendance file contains:

- Name
- Date
- Time
- Status

## 10. GUI

A simple Tkinter GUI was created for viewing the attendance records.

The attendance records can be viewed from the CSV file.

## 11. Testing

The system was tested using different face angles, facial expressions and lighting conditions.

The results were checked to see whether the registered person was recognized correctly.

## 12. Model Performance

The KNN model was tested using the available facial embeddings.

The accuracy obtained during testing is shown in the Jupyter Notebook.

Since the project currently uses one registered person, the result is mainly used to demonstrate the working of the system.

## 13. Limitations

- Currently, the system is tested with one registered person.
- More people can be added to make it a multi-person attendance system.
- Recognition can be affected by poor lighting or large changes in face angle.

## 14. Future Improvements

- Add multiple students to the system.
- Improve face recognition accuracy.
- Add a better attendance dashboard.
- Store attendance in a database.
- Generate daily or monthly attendance reports.

## 15. Conclusion

This project demonstrates how face recognition can be used for attendance. The project includes image preprocessing, augmentation, face detection, facial embeddings, KNN classification and attendance recording.