## Setup
* git clone SM4Depth my test fork: https://github.com/schen2000/SM4Depth_t
* Install anaconda if didn't , https://www.anaconda.com/
* Install NVidia driver and cuda toolkit, mine is cuda 12.4
* Follow readme.md "# create conda environment" section to prepare environment
* Download pretrained model : 
     https://drive.google.com/file/d/1ModtPQrsPbyVMDA4lVVEL-D1OlMemK0a/view?usp=sharing
     Put in dir <SM4Depth_t>/../data/models
     ( Inside SM4Depth_t/data/, there is soft link : "../../data/models/")

## Quick-Quick start
* activate sm4depth conda environment.
* run "run.sh"

Put source images are in dir data/test_imgs/
Check/modify index in data/test_imgs/index.txt
 ( Note: the 2 digital number are camera intrinsic fx and fy, 
    To be corrected with real parameters after camera calibration )
The result will be generated in dir test_imgs/output

