# DAC 2024 Design Contest

For full contest details, please see the [2024 DAC System Design Contest](https://pku-sec-lab.github.io/dac-sdc-2024/info/) page.

## Usage
The get started, users have to run the following command on the gpu board:
(you should first come to the directory under which you want to do this work, e.g. ~/workspace/)

```shell
git clone https://github.com/AstroCIEL/gpu_starter_2024.git
```

After the above step is completed successfully, you will see a folder `gpu_starter_2024` under your work
directory.  Open the `sample_team/dac_sdc.ipynb` notebook for directions on where to begin.

Note that in `common` directory exist dac_sdc.py and score_miou.py. score_miou.py gives the standard to score your inference results. Also pay attention to dac_sdc.py and modify it when necessary. It is suggested that `common` directory is as the same level as the directory which contains `.ipynb` file.

## Folder Structure

1. sample_team: This folder contains a `.ipynb` jupyter notebook. You should create a new folder for your team as the level as sample_team, where you will keep all of your files and a `.ipynb` file must exist as the main program to submit and evaluate.

2. images: All the test images are stored in this folder.

3. labels: All the test labels(.json files) are stored in this folder. 

4. result: The results contain the output xml produced when execution is complete, and contains the runtime, energy usage, and predicted location of each object in each image.


