# Intelligent Kernel
Implementing machine learning  to the most essential part of the computers (operating system). using machine learning C libraries like darknet. main aim is to analyse the possiblity to  work on diffrent aspects of  kernel and systems programming to make the linux kernel ahead in race wrt their closed source counter-parts.

----------------
# kernel optimization

1.  analysing the process metrics and then tuning the operation of the operating system correspondingly has been the main concern  for the  system admins , thus making a ML engine that will automatically throttle the required performance  by  aiding the scheduler will be the swiss knife for the  system programmers .
  - [X]  getting the dataset and understanding the pain points of the kernel programming <br>
        -  its essential to improve the processes scheduling 
        -  working on the  tradeoff on whether we need to mask off the errors at lower level or over allocate the resources                for error avoidance :-[this paper](https://arxiv.org/abs/1809.05859) gives good overview of that.
 

  - [ ]  getting used to using C  for making machine learning models.
        - Tensorflow api , BOOST and MLpack will be enough for consideration.
  
  - [ ] then try to work on [the next level](https://docs.kali.org/development/recompiling-the-kali-linux-kernel) and optimise         the kali linux
  
  - [ ] working on the much specific prospect rather than broadening it . 
  
# UPDATE :- 
# 1. Initial baby steps (To be completed till 4th Oct) : 
getting the crux from how the linux works : [linux insides](https://legacy.gitbook.com/book/0xax/linux-insides/details). 




well i think the god father of this project will also be to devise on the foorsteps of the  paper given by Deepmind about neural computers:- https://www.nature.com/articles/nature20101 . will be  extremely ambitious but atleast optimising several parts of the operation process ( like  I/O functions , for  memory allocation and checking for malicious  payload etc).
