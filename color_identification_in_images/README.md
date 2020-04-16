## Detection and clustering of colors in an image file and finding best match of the color to be tested

## What have we built: 
A command line utility to idnetify and cluster the colors in an image file and finding best match of the color to be tested

## What can this test framework do
1. Lets you choose and specify your image file detect the hex and rgb values of possible colors found in the image 

2. For QA purpose, lets you provide the HEX or RGB values of colors you want to test in the image

3. Returns the hex and rgb values of colors found and shows a pie chart for that.

## Instructions:
1. The project is built on python3. Please install python3 if not already installed.

2. Clone this repository.

3. Navigate to the directory and run the following commands
   ```
   pip3 install -r requirements.txt
   ```
   
4. For the purpose of hackathon, one sample image is included.

5. To execute the colors identification, run the following command:

   ```python3 identifier.py```
   
   Execution of this command will let you see the hex and rgb value of colors identified.
   

## What can this test can’t framework do as of now (But can do if developed as a full-fledged framework)

1. A web UI to upload the image and display results

2. The web UI shall be able to show color values at each pixel

3. Display color area fraction and color name

4. Batch files upload

5. Reports as a HTML file and JSON response

6. Provide a set of image files and searched colors, and image files containing above threshold amount of searched colors will be displayed

7. A deep learning model that would consider colors of all pixels in the image and classify the overall experience of the image quality
