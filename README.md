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
getting the crux from how the linux works : [linux insides](https://legacy.gitbook.com/book/0xax/linux-insides/details). 
  - checking the tripwire and other file integrity checks and the logs for the OS security.






adding some tensorflow interaction in C  with the process  monitor to feed the dataset and then 
