# Pakistani-Vehicle-Number-Plate-Detection
Streamlined a Number Plate Detection and Recognition Model for Pakistan-based Vehicle using custom Dataset.

We've used our custom dataset that includes data of Cars, Rikshaws, Bikes and all possible vehicles that contain NumberPlate and Trained a model after labeling the data that shows 100% accuracy with more than 98% precision.
- The process includes fetching model, and drawing bounding box on image through the model prediction, 
- Then the image is cropped before sending to OCR (easyOCR)
- Once the OCR returns the characters, the JSON response can be used to perform further operations.

Some of the example predictions are as follows:

<img src="https://user-images.githubusercontent.com/86932331/226811282-051dcfee-970f-49c3-88ee-b04c97a89705.png" width="500" height="500">
<img src="https://user-images.githubusercontent.com/86932331/226811327-049a46a0-af58-4cfe-ba41-a769f986e5dc.png" width="500" height="500">

<img src="https://user-images.githubusercontent.com/86932331/226811388-368d569c-e54f-45cd-b395-72c7dafd8e67.png" width="500" height="500">

<img src="https://user-images.githubusercontent.com/86932331/226811431-5d1eef23-2efa-4154-883c-48221f94efc6.png" width="500" height="500">

<img src="https://user-images.githubusercontent.com/86932331/226811480-f95767ae-5611-4d68-8a66-88308854959a.png" width="500" height="500">



