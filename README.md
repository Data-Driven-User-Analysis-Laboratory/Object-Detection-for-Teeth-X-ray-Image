# Object-Detection-for-Teeth-X-ray-Image

** Contributor   
JongHwan Park : bomebug15@ds.seoultech.ac.kr

* Horizontal Object Detection result image
![image](https://user-images.githubusercontent.com/73214448/104155534-c6775100-542a-11eb-9a69-cd6681f0b1e1.png)

* Rotated Object Detection result image
![image](https://user-images.githubusercontent.com/73214448/104155509-bb242580-542a-11eb-88f1-159c3ad93b02.png)


#### Using only 50 teeth image, we can check process of training normally

#### There's two main files. Choose what use *[Horizontal/Rotated] model you want

# Using Package

```
$ >pip install torch==1.7.1+cu101 torchvision==0.8.2+cu101 torchaudio==0.7.2 -f https://download.pytorch.org/whl/torch_stable.html
$ >pip install -U torch torchvision
$ >pip install git+https://github.com/facebookresearch/fvcore.git
$ >pip install fvcore
$ >pip install pillow==7.2.0
$ >python -m pip install 'git+https://github.com/facebookresearch/detectron2.git'
```
