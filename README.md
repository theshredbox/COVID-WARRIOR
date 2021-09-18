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





