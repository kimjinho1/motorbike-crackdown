# License plate detection

**You can download model.weights file from [this link](https://drive.google.com/file/d/1vXjIoRWY0aIpYfhj3TnPUGdmJoHnWaOc/).**  

**model.weights file should be in the weigths folder.**  

## How to use
--img_dir: input image directory, default="img/"  
--img_name: input file name  
--output_dir: output image directory, default="output/"  
  
EX)   
If you want to detect license plate in "img/1.png" and save output file in "output/"  
```
python License_plate_detection.py --img_dir=img/ --img_name=1.png --output_dir=output/
```

Or if your directory name is set to default, just use --img_name  
```
python License_plate_detection.py --img_name=1.png
```

