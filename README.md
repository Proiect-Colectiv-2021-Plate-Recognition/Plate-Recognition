# Romanian Plate Recognition System
Plate recognition system for romanian number plates able to recognize number plates from photos or videos and compare to a database of number plates.

## Photo Plate Recognition
Results: https://github.com/Proiect-Colectiv/Plate-Recognition/blob/main/Photo%20Recognition/Plate%20recognition.ipynb
- Ideology:
  - Edge detection 
  - Contour detection
  - Mask creation
  - easyOCR for character recognition 
> Tools used
> - OpenCV
> - easyOCR

## Video Plate Recognition
- Ideology:
  - Custom in-house trained machine learning model to approximate the number plate's location. The model was trained with more than 1000+ images, assuring an accuracy of 96% rate of succes. The model returns the bounding box of the found license plate that's used for character recogntion
  - Pytesseract used for character recognition with character segmentation and morphological transformations. 
> Tools used
> - OpenCV
> - Pytesseract
> - Tensorflow
> - Tensorflow Object Dectection API

> Dependencies
> - Video resources: 
>   - Back license plate: https://drive.google.com/file/d/1ZHbzZV6medEsq-lZJmw1QV5MY2KUEjTZ/view?usp=sharing
>   - Front license plate: https://drive.google.com/file/d/1flcBnnNbapjxiKIplnxvH-SO9NZFiqK0/view?usp=sharing
> - ML model: https://drive.google.com/drive/folders/1ROKhdlX-Y-8NSvDPYA5UfxXpbG2quiwI?usp=sharing
> - Label map: https://drive.google.com/file/d/1CoIJ6g7Fc6wkXNGvy_hnJpA9ZN4GYtEE/view?usp=sharing

> Other resources
> - Image dataset & .xml label files used for training and validation: https://drive.google.com/drive/folders/1qhk_-NwiiQcqgLR9aPz0WBFsq288kJOT?usp=sharing
> - Variuos python scripts that might come in handy: https://drive.google.com/file/d/1NbCxqwzVFQADrNsraQJjdnpS3yrTxtXa/view?usp=sharing

To run this on your machine download the latest release. Do also make sure you have all the dependencies installed & working. 
If you are building this and need help, let's catch up at milovanarsul at gmail dot com

## Database integration
This system is able to connect to a database and check if the recognized number plate maches any result in the database.
> Dependencies
> - XAMPP & MySQL inside phpMyadmin
> - Download the database: (coming soon)
> - Import
> - Make sure to modify any database connections you might want to change.

If you are building this and need help, let's catch up at milovanarsul at gmail dot com
