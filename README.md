# Assessment
## Object Detection Using YOLO and MobileSSD

## How to use?

1. Clone the repository.
```
git clone https://github.com/hasnainali659/Assessment.git
```
2. Download Yolo weight file
```
https://drive.google.com/open?id=1PaYnSWfcMSD5rgXkdZe9qBNBURETKiTJ
```
3. Place Yolo weight file in the Yolo directory and rename as.
```
yolov3.weights
```
4. Open command line like Anconda prompt/CMD/Gitbash/Terminal and traverse to the assessment folder. In my case using

```
 C:\Users\Hasnain\Downloads\Assessment>
```
5. Create a virtual environment named 'assessment'.
```
conda create --name assessment
```
6. Install requirement.txt file
```
pip install -r requirements.txt
```
7. To run Mobile SSD directly run command.
``` 
python detection_SSD.py
```
8. To run YOLO run command
```
python Yolo.py --image Hasnain.jpg
```
**Note: Hasnain.jpg can be replaced with any other file in the Yolo folder.**
