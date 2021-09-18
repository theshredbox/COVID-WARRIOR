# COVID-WARRIOR
The project aims at developing a face mask and social distancing detector.
As the corona virus continues to impact communities across the globe, it has become quite a necessity to reinforce the guidlelines laid down by the WHO with high precision.

In an attempt to aid this, we built a ML and Deep Learning based model to detect face masks and social distancing among public.

**NOTE- Since github does not support files over 25MB; download the yolo.weights and facemask dataset from [MY DRIVE](https://drive.google.com/drive/folders/1qRscxcBgJfMiNjmFXB8AEyxBQFLBtoPc?usp=sharing).**

## TO RUN THIS PROJECT IN YOUR SYSTEM:
* **Open your terminal**
* ***Change the directory to where you have downloaded this code***
* ***Install python3. (I prefer to use an older version of python like 3.6 to aid the functioning of certain modules)***
* **Run**  `  python3 -m venv venv  ` ***to create a virtual environment named venv.***
* **Run**   `  source venv/bin/activate  ` 
***This activates your environment***
* **Follow up with**   `  pip install -r requirements.txt  ` 
***to install the python dependencies related to this project like opencv,numpy,scipy etc.***
* **Run the command** `time python social_distance_detector.py --input pedestrians.mp4 --output output.avi --display 1
` ***to run the project.*** (FOR SOCIAL DISTANCING DETECTION)
* **Run the command** `time python FACE_MASK_DETECTOR.py --display 1
` ***to run the project.*** (FOR FACE MASK DETECTION).

![social distancing gif](https://user-images.githubusercontent.com/36481036/133897438-61c122ea-7697-427b-aad8-c38e1371f4c0.gif)

![Screenshot (315)](https://user-images.githubusercontent.com/36481036/133897444-bf67f7af-54ad-4091-9e50-209dff2d2171.png)

![Screenshot (316)](https://user-images.githubusercontent.com/36481036/133897448-9adf08d3-feb7-45c5-88ce-37e0b08956f6.png)

## Contacts:
* **Created by: [Aryan Ahuja](https://github.com/theshredbox)**
* **Email:[asafebruary@gmail.com](https://asafebruary@gmail.com)**
* **LinkedIn: [Aryan Ahuja](https://www.linkedin.com/in/aryan-ahuja-013443190/)**






