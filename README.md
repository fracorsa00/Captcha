# DW-GAN
A GAN based framework for CAPTCHA breaking in the dark web. Especially for the CAPTCHA with curve and dot noisces. 

## Requirement
This code is implemented in Python and PyTorch. All of the required libraries could be installed by pip or conda. 
## Usage
### Data
Due to the shortage of the storage space, data is not uploaded in this repository. Please find the [Kaggle Page](https://www.kaggle.com/njznjz/captcha-collected-from-darknet-websites) for the data. 
### Training
GAN model is trained and uploaded. An example of making dataset for training CNN model is under the folder [Example_and_Record](https://github.com/johnnyzn/DW-GAN/blob/main/Example_and_Record/notebook_example/case_synthetizer-4.ipynb)
<!-- ## Citation
If you use this code for your research, please cite our papers.
```
@inproceedings{zhang2020generative,
  title={A generative adversarial learning framework for breaking text-based CAPTCHA in the dark web},
  author={Zhang, Ning and Ebrahimi, Mohammadreza and Li, Weifeng and Chen, Hsinchun},
  booktitle={2020 IEEE International conference on intelligence and security informatics (ISI)},
  pages={1--6},
  year={2020},
  organization={IEEE}
}
``` -->
## Acknowledgments
For [CNN model training](https://github.com/dee1024/pytorch-captcha-recognition), Dee Qiu's code is used for reference. The [CNN Synthesizer](https://github.com/lepture/captcha) is used from an open-source CAPTCHA library. Based on that implementation, we change the code to satisfy our need for experiments. 

## Presentation
Made by Francesco Corsaro, Emil Galeazzi, Stefano Ronchi. (https://www.canva.com/design/DAFsj2ViUb0/h4MVflA5zOzaCpe6VDbhQA/edit?utm_content=DAFsj2ViUb0&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
