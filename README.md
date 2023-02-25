# Open-Ended-Question-Marker
This TRAIVIS Project is focused on building a working model which would grade the students based on the answers they submit to a subjective question using Machine Learning, Natural Language Processing.

Download GoogleNews-vectors-negative300.bin which is used in the model:
https://www.kaggle.com/datasets/leadbest/googlenewsvectorsnegative300

## About the files:
- #### backend.ipynb
This file contains the code for working model to grade-the-students comparing the answer in ans-ml.txt (given by the student) and the text given by the instructor mentioned as key_ml variable . 
- #### complete-model.ipynb
This file contains the code of the model along with the frontend files in the templates folder. The frontend is built using Flask which will run on http://localhost:9000/ .

![image](https://user-images.githubusercontent.com/107244393/221377186-90bc1c97-4604-4808-9cf8-543b684c3607.png)
![image](https://user-images.githubusercontent.com/107244393/221377376-816f871e-1826-47c1-8f59-e66d2586e028.png)

- #### text_extraction.ipynb
This file contains code for extracting the text from the pdf. Further, the answers are seperated from the pdf in an array which can be further integrated with the model. 
