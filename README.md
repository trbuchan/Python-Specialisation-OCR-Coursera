# Python-Specialisation-OCR-Coursera
Project from Coursera Python Specialisation
The Assignment
Take a ZIP file of images and process them, using a library built into python that you need to learn how to use. 
A ZIP file takes several different files and compresses them, thus saving space, into one single file. 
The files in the ZIP file we provide are newspaper images (like you saw in week 3). 
Your task is to write python code which allows one to search through the images looking for the occurrences of keywords and faces. 
E.g. if you search for "pizza" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "pizza". 
This will test your ability to learn a new (library), your ability to use OpenCV to detect faces, your ability to use tesseract to do optical character recognition, and your ability to use PIL to composite images together into contact sheets.


Project
The function project takes 2 inputs of Zip file Name (zip_name) & The Keyword (key_word) search term.

It returns an image contact sheet of the faces located on images which mention the keyword search term.

1 - Open Images
The images were opened from the zipfile and saved to a dictionary

2 - Perform OCR
Perfrom OCR on the images to get the text from the images. If match found against key_word print result.

3 - Face Detection
Inputs for the detectMultiscale: A Scale factor of 1.31 Selected, after varying this value between 1.2 and 1.5 the final value of 1.31 was selected to give a match to the assignment.

Minimum neighbours - After some variance the value of 5 was chosen for this parameter.

4 - Contact Sheet
Create the thumbnails on the contact sheet

Thumbnail size to be 110x110 to match the example with 5 thumbnails per row.
