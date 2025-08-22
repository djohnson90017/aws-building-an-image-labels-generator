# aws-building-an-image-labels-generator
image labels generator
This project is a Python script that uses AWS Rekognition to detect objects in an image stored in an Amazon S3 bucket. It then visualizes the detected objects by drawing bounding boxes around them using the matplotlib library. 🖼️

The project followed these steps:

Step 1: Code and Library Setup
The initial code was divided into two parts: one for the core logic and one for a testing main function. This created an organizational issue that was resolved by combining them into a single script. A syntax error was also found in the main function where variables for the photo and bucket were incorrectly assigned, which was fixed. The necessary Python libraries, including bot3, matplotlib, and pillow, were installed using pip.

Step 2: AWS Resource Creation
An Amazon S3 bucket, named infodjaybucket23, was created to store the image for analysis. The process was straightforward, and no issues were encountered.

Step 3: Local Environment Execution
The final Python script was run from the command line. A "File Not Found Error" occurred because the terminal was in the wrong directory. This was resolved by using the cd (change directory) command to navigate to the correct folder containing the script.

Final Result
The script successfully ran, producing two outputs:

A list of detected labels with their confidence scores displayed in the terminal.

A new window showing the image with bounding boxes drawn around the detected objects, such as a Person, Man, and Handbag.

This project demonstrates a foundational understanding of cloud computing services, specifically using S3 for storage and AWS Rekognition for AI-driven object detection, with visualization handled locally by Python libraries.
