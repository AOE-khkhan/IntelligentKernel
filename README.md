# Intelligent Kernel
Implementing machine learning  to the most essential part of the computers (operating system). using machine learning C libraries like darknet. main aim is to analyse the possiblity to  work on diffrent aspects of  kernel and systems programming to make the linux kernel ahead in race wrt their closed source counter-parts.

----------------
# kernel optimization

1.  analysing the process metrics and then tuning the operation of the operating system correspondingly has been the main concern  for the  system admins , thus making a ML engine that will automatically throttle the required performance  by  aiding the scheduler will be the swiss knife for the  system programmers .
  - [X]  getting the dataset and understanding the pain points of the kernel programming <br>
        -  its essential to improve the processes scheduling 
        -  working on the  tradeoff on whether we need to mask off the errors at lower level or over allocate the resources                for error avoidance :-[this paper](https://arxiv.org/abs/1809.05859) gives good overview of that.
 

  - [X]  getting used to using C  for making machine learning models.
        -  BOOST and MLpack will be enough for consideration.
  
  
  - [ ] working on the much specific prospect  detecting the labels of the maliciosu process. 
  
# UPDATE :- 
getting the crux from how the linux works :[X][linux insides](https://legacy.gitbook.com/book/0xax/linux-insides/details). 
  - checking the tripwire and other file integrity checks and the logs for the OS security.
  - how the BPF and other standard communication works . bredanengg.com . 
  
adding some tensorflow interaction in C  with the process  monitor on the any of the following components of the architecture :

![total modules in the kernel](https://i.pinimg.com/originals/66/3e/e6/663ee695a2613f0b9d83b2a600bcf9b8.png)







# credits 
## thanks to the linux kernel diagram , getting the information about linunx performance tools by bernard gregg and others for showing the extensive possiblities that we can  work upon so as to make the linux host the next genreration 




# final architecture :


[The Initial arch - V1](https://drive.google.com/uc?export=view&id=11uAgqZcNABHPUnLpHXsEzWTCEVcSo5u_)

1. From here , the modules related to user and kernel space interaction , we can create the datasets of diffrent  processes with timestamp , doing the joins on the dataset based on the time and  feeding it to the tensorflow engine which will have another python based console  for writing the models and the tools in higher language  







Now the actual implementation :

Step-1: standardizing the data 
