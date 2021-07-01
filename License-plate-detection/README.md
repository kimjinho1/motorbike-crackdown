# License plate detection

**You can download model.weights file from [this link](https://drive.google.com/file/d/1vXjIoRWY0aIpYfhj3TnPUGdmJoHnWaOc/).**  
**model.weights file should be in the weigths folder.**  

**reference: [alitourani](https://github.com/alitourani/yolo-license-plate-detection)**  


## Set up environment  
`pip install -r requirement.txt`  


## How to use
**--img_dir: input image directory, default="img/"  
--img_name: input file name  
--output_dir: output image directory, default="output/"**  
  
**EX)**   
If you want to detect license plate in "img/1.png" and save output file in "output/"   

`python License_plate_detection.py --img_dir=img/ --img_name=1.png --output_dir=output/`  

Or if your directory name is set to default, just use --img_name  

`python License_plate_detection.py --img_name=1.png`  


## Result   
![1_box](https://user-images.githubusercontent.com/29765855/124162202-39f44400-dad9-11eb-8f37-89b1f86b2d9a.png)  

![2_box](https://user-images.githubusercontent.com/29765855/124162221-41b3e880-dad9-11eb-8db8-d766a5af7c77.png)  

![3_box](https://user-images.githubusercontent.com/29765855/124162264-48426000-dad9-11eb-8c2b-7af04f387fa3.png)  

![0_box](https://user-images.githubusercontent.com/29765855/124162313-4e384100-dad9-11eb-9872-48edf4b79be8.png)  


