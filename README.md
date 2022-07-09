# Assessment
## Object Detection Using YOLO and MobileSSD

## How to use?

* Clone the repository.
```
git clone https://github.com/hasnainali659/Assessment.git
```
* Download Yolo weight file
```
https://drive.google.com/open?id=1PaYnSWfcMSD5rgXkdZe9qBNBURETKiTJ
```
* Place Yolo weight file in the Yolo directory and rename as.
```
yolov3.weights
```
* Open command line like Anconda prompt/CMD/Gitbash/Terminal and traverse to the assessment folder. In my case using

```
 C:\Users\Hasnain\Downloads\Assessment>
```
* Create a virtual environment named 'assessment'.
```
conda create --name assessment
```
* Install requirement.txt file
```
pip install -r requirements.txt
```
* To run Mobile SSD directly run command.
``` 
python detection_SSD.py
```
* To run YOLO run command
```
python Yolo.py --image Hasnain.jpg
```
Hasnain.jpg can be replaced with any other file in the Yolo folder.
