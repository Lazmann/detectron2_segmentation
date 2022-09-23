# detectron2_segmentation
Output exceeds the size limit. Open the full output data in a text editor
Looking in indexes: https://pypi.org/simple, https://us-python.pkg.dev/colab-wheels/public/simple/
Looking in links: https://download.pytorch.org/whl/cu101/torch_stable.html
Collecting torch==1.5
  Downloading https://download.pytorch.org/whl/cu101/torch-1.5.0%2Bcu101-cp37-cp37m-linux_x86_64.whl (703.8 MB)
     |████████████████████████████████| 703.8 MB 22 kB/s 
Collecting torchvision==0.6
  Downloading https://download.pytorch.org/whl/cu101/torchvision-0.6.0%2Bcu101-cp37-cp37m-linux_x86_64.whl (6.6 MB)
     |████████████████████████████████| 6.6 MB 37.9 MB/s 
Requirement already satisfied: numpy in /usr/local/lib/python3.7/dist-packages (from torch==1.5) (1.21.6)
Requirement already satisfied: future in /usr/local/lib/python3.7/dist-packages (from torch==1.5) (0.16.0)
Requirement already satisfied: pillow>=4.1.1 in /usr/local/lib/python3.7/dist-packages (from torchvision==0.6) (7.1.2)
Installing collected packages: torch, torchvision
  Attempting uninstall: torch
    Found existing installation: torch 1.12.1+cu113
    Uninstalling torch-1.12.1+cu113:
      Successfully uninstalled torch-1.12.1+cu113
  Attempting uninstall: torchvision
    Found existing installation: torchvision 0.13.1+cu113
    Uninstalling torchvision-0.13.1+cu113:
      Successfully uninstalled torchvision-0.13.1+cu113
ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
torchtext 0.13.1 requires torch==1.12.1, but you have torch 1.5.0+cu101 which is incompatible.
torchaudio 0.12.1+cu113 requires torch==1.12.1, but you have torch 1.5.0+cu101 which is incompatible.
fastai 2.7.9 requires torch<1.14,>=1.7, but you have torch 1.5.0+cu101 which is incompatible.
fastai 2.7.9 requires torchvision>=0.8.2, but you have torchvision 0.6.0+cu101 which is incompatible.
...
Copyright (C) 2017 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

Output exceeds the size limit. Open the full output data in a text editor
Looking in indexes: https://pypi.org/simple, https://us-python.pkg.dev/colab-wheels/public/simple/
Looking in links: https://dl.fbaipublicfiles.com/detectron2/wheels/cu101/torch1.5/index.html
Collecting detectron2==0.1.3
  Downloading https://dl.fbaipublicfiles.com/detectron2/wheels/cu101/torch1.5/detectron2-0.1.3%2Bcu101-cp37-cp37m-linux_x86_64.whl (6.2 MB)
     |████████████████████████████████| 6.2 MB 524 kB/s 
Collecting yacs>=0.1.6
  Downloading yacs-0.1.8-py3-none-any.whl (14 kB)
Collecting fvcore>=0.1.1
  Downloading fvcore-0.1.5.post20220512.tar.gz (50 kB)
     |████████████████████████████████| 50 kB 7.6 MB/s 
Requirement already satisfied: cloudpickle in /usr/local/lib/python3.7/dist-packages (from detectron2==0.1.3) (1.5.0)
Requirement already satisfied: tqdm>4.29.0 in /usr/local/lib/python3.7/dist-packages (from detectron2==0.1.3) (4.64.1)
Requirement already satisfied: Pillow in /usr/local/lib/python3.7/dist-packages (from detectron2==0.1.3) (7.1.2)
Requirement already satisfied: matplotlib in /usr/local/lib/python3.7/dist-packages (from detectron2==0.1.3) (3.2.2)
Requirement already satisfied: pydot in /usr/local/lib/python3.7/dist-packages (from detectron2==0.1.3) (1.3.0)
Requirement already satisfied: tensorboard in /usr/local/lib/python3.7/dist-packages (from detectron2==0.1.3) (2.8.0)
Requirement already satisfied: future in /usr/local/lib/python3.7/dist-packages (from detectron2==0.1.3) (0.16.0)
Requirement already satisfied: termcolor>=1.1 in /usr/local/lib/python3.7/dist-packages (from detectron2==0.1.3) (1.1.0)
Requirement already satisfied: tabulate in /usr/local/lib/python3.7/dist-packages (from detectron2==0.1.3) (0.8.10)
Collecting mock
  Downloading mock-4.0.3-py3-none-any.whl (28 kB)
Requirement already satisfied: numpy in /usr/local/lib/python3.7/dist-packages (from fvcore>=0.1.1->detectron2==0.1.3) (1.21.6)
Requirement already satisfied: pyyaml>=5.1 in /usr/local/lib/python3.7/dist-packages (from fvcore>=0.1.1->detectron2==0.1.3) (5.1)
Collecting iopath>=0.1.7
  Downloading iopath-0.1.10.tar.gz (42 kB)
...
  Stored in directory: /root/.cache/pip/wheels/aa/cc/ed/ca4e88beef656b01c84b9185196513ef2faf74a5a379b043a7
Successfully built fvcore iopath
Installing collected packages: portalocker, yacs, iopath, mock, fvcore, detectron2
Successfully installed detectron2-0.1.3+cu101 fvcore-0.1.5.post20220512 iopath-0.1.10 mock-4.0.3 portalocker-2.5.1 yacs-0.1.8
Output exceeds the size limit. Open the full output data in a text editor
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   892  100   892    0     0    437      0  0:00:02  0:00:02 --:--:--   437
100 75.3M  100 75.3M    0     0  27.1M      0  0:00:02  0:00:02 --:--:--  103M
Archive:  roboflow.zip
 extracting: README.dataset.txt      
 extracting: README.roboflow.txt     
   creating: test/
 extracting: test/20697_jpeg.rf.9929fd7364c385934d7780e1b7abcdec.jpg  
 extracting: test/20832_jpeg.rf.cb81da210ab86f6b70f4fd67f09420dc.jpg  
 extracting: test/20836_jpeg.rf.134cb65a41e22c9c828665a0f08a2227.jpg  
 extracting: test/20877_jpeg.rf.bc4305ca62a4e4370aac45689746b872.jpg  
 extracting: test/20888_jpeg.rf.175e015810f6cf61dc76dbf6d11b7978.jpg  
 extracting: test/20914_jpeg.rf.8da3962bd5ee07356ee1807e716dfe4b.jpg  
 extracting: test/20915_jpeg.rf.bd80568f0a5e2c1d9e13ad45a8aed221.jpg  
 extracting: test/20921_jpeg.rf.7fc3b9416fbec77dc4d824bbd134494f.jpg  
 extracting: test/20941_jpeg.rf.fdd602242df5d706b79f90de744d27ae.jpg  
 extracting: test/20946_jpeg.rf.1a527a896e4fe6cd519ad25a58b19790.jpg  
 extracting: test/21043_jpeg.rf.87520cf8c3b156982b90ebc0987a2821.jpg  
 extracting: test/21089_jpeg.rf.3e22e5e9771152425d4243076c4f06a6.jpg  
 extracting: test/21102_jpeg.rf.acbd7f9a423dd06c530e5f4ad6dfa225.jpg  
 extracting: test/21127_jpeg.rf.1dd57352ad5e39dc9b61dd04d8cb1c35.jpg  
 extracting: test/21175_jpeg.rf.4eea81c55f3ec85186bef72056d7c0f4.jpg  
 extracting: test/21199_jpeg.rf.3a5edfaed7db50e75bdf0d1e907d9575.jpg  
 extracting: test/21201_jpeg.rf.bf6ad605f56a431bb7928072abab3b92.jpg  
...
 extracting: valid/metrokent_Panoramic_000218_3_jpg.rf.e85ff7b94d56bedb630c63abd5210979.jpg  
 extracting: valid/metrokent_Panoramic_000228_0_jpg.rf.86048a54f0516196a862f51c424e09e1.jpg  
 extracting: valid/metrokent_Panoramic_000233_0_jpg.rf.1feedd5d42cec67644511eb5e436a36e.jpg  
 extracting: valid/metrokent_Panoramic_000233_2_jpg.rf.3bad13773902c4c0837c2c14589e22fc.jpg  
WARNING [09/23 12:07:41 d2.data.datasets.coco]: 
Category ids in annotations are not in [1, #categories]! We'll apply a mapping for you.

[09/23 12:07:41 d2.data.datasets.coco]: Loaded 333 images in COCO format from /content/train/_annotations.coco.json


