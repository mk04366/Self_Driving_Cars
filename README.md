# EE 452 - Computer Vision
# Final Project: Behavioral Cloning for Autonomous Cars
# Group Members:
- _Muhammad Ammar Khan_
- _Khwaja Ghulam Alamdar_
- _Aiman Junaid_
-------

## Publication Link
Availaible on [ScitePress](https://www.scitepress.org/Link.aspx?doi=10.5220/0010839900003124)

## Background

After extensive research for the available resources and addressing each of our interests in the field of computer vision, we have decided to work on the topic of ‘Behavioral Cloning for Self-Driving or Autonomous Cars’. 
_1.1Motivation_
The modern aspect of this topic along with its ability of capturing our interest ignited the motive for us to work and research on this field. As an undergraduate, it was necessary for us to get a good baseline for our research which was possible through well-cited research papers written by reputable researchers with good experience as well and fortunately, we were able to find such resources which are very much relevant to our subject.
_1.2 Significance of the project_
Autonomous driving technology is an active research area in the domain of cars and is the most probable future of them as well since many cars are being developed with such capabilities in the first world countries (as the expenses on its implementation are still not optimized). This makes it important for us to learn the techniques that involve in its implementation. This project will definitely help us in understanding the crux of this technology and eventually, we will be able to implement this on various other robotic structures which are to be designed to mimic human/animal behavior.
_1.3 Description of the Project_
Behavioral cloning helps us teach a robot/machine to learn a certain behavior, study, and actions of a person. In this project, we will be teaching a robotic car to drive while avoiding the obstacles and improvising on certain decision making which are needed due to the uncertain conditions of a road. A driver throughout a journey, has to keep making newer decisions by analyzing his viewpoint from all directions, and then acting on the actuators of the car accordingly. In our project, we will constraint ourselves to one viewpoint (which will be front) and try to drive our car on that basis, autonomously making the decisions based on the images it captures.


## Implementation

We are keeping both simulation and practical implementations on the table for now. Simulators such as Carla and Udacity Self Driving Car simulators may be used for training our architectures for self-driving cars. The same platforms could also be used for testing.

Alternatively, we might implement our architectures on a physical (miniature) car. This could be done using the Raspberry Pi development boards. However, the feasibility of such an endeavor needs to be assed.

## Characteristic Feature

Since our project features to do fast processing on images which are captured in real time, this task requires a powerful machine which are usually held on industrial scale and products. Our could be vastly applied on the field of self-driving cars which are being made nowadays by a lot of companies working in this particular domain.
Autonomy of any sort in the history has proven to show efficient results and since this project heads towards building smart cars, industries could integrate GPS routing to the whole mechanism and allow it to perform way more efficiently than a normal person could as the car would take the route with the least traffic and ensure that none of the road gets 
overcrowded and hence, we will see less on-road time for the public, which means that less petroleum would be used and lesser accidents overall. The world, which is gradually increasing in its pace, definitely requires such global intervention and therefore, every car industry wants to develop in this field of research.
Our project will help the self-driving cars in taking pictures simultaneously while driving and then, processing the essential objects out of it and classifying them so it makes sense for the car and it can act on it accordingly. Since machine learning involves a lot of experience and a fast and efficient computer is good in it, each car can be made to utilize its experience gained throughout its life and learn from it to perform better each time it is being taken out to drive and therefore, along with comfort, the users would be experiencing a safer drive as well. 

Henceforth, many companies are interested in this particular field as it would be a bigger part of the future not only in the fields of cars, but in several other domains (e.g., security, smart homes, etc.) as well.

## Application

The reduction of traffic accidents by eliminating human error, increasing road capacity and traffic flow by reducing distance between cars and utilising traffic management information, relieving car occupants from driving and navigation activities and allowing them to engage in other activities or rest are the main drivers for autonomous driving.



## Libraries Used
- Keras
- Tensorflow
- CV2
- Socketio
- Flask
- Scikit
- Pillow
- MatplotLib


## References for Dataset Used

- Economic  Effects  of  Automated  Vehicles  -  Lewis  M.  Clements,Kara M. Kockelman, 2017”, SAGE Journals, 2021.[Online].Available:https://journals.sagepub.com/doi/abs/10.3141/2606-14.   [Accessed:   31-May- 2021].
- N.A.Greenblatt,”Self-drivingcarsandthelaw,”inIEEE    Spectrum,    vol.    53,    no.    2,    pp.    46-51,    Feb.    2016,    doi:10.1109/MSPEC.2016.7419800.
- E. Coelingh, J. Nilsson and J. Buffum, ”Driving tests for self-drivingcars,”  in  IEEE  Spectrum,  vol.  55,  no.  3,  pp.  40-45,  March  2018,  doi:10.1109/MSPEC.2018.8302386.
- M.  Bojarski  et  al.,  ”End  to  End  Learning  for  Self-Driving  Cars”,arXiv.org,  2021.  [Online].  Available:  https://arxiv.org/abs/1604.07316.[Accessed: 30- May- 2021].
- Chirag Sharma, ”Self Driving Car using Deep Learning Technique”,International Journal of Engineering Research and, vol. 9, no. 06, 2020.Available: 10.17577/ijertv9is060247.
- . Miao, M. Gowayyed and F. Metze, ”EESEN: End-to-end speechrecognition using deep RNN models and WFST-based decoding,” 2015IEEE  Workshop  on  Automatic  Speech  Recognition  and  Understanding(ASRU), 2015, pp. 167-174, doi: 10.1109/ASRU.2015.7404790
- S.   Du,   H.   Guo   and   A.   Simpson.   Self-driving   car   steeringangle   prediction   based   on   image   recognition,   2019.   available   at:arXivpreprintarXiv:1912.05440
- Y.   Bengio,   P.   Simard,   and   P.   Frasconi,   “Learning   long-termdependencies with gradient descent is difficult,” Neural Networks, IEEETransactions on, vol. 5, no. 2, pp. 157–166, 1994.
- S.  Hochreiter  and  J.  Schmidhuber,  “Long  short-   ̈  term  memory,”Ne
-  H.   Eraqi,   M.   Mohamed   and   J.   Honer,   ”End-to-End   DeepLearning   for   Steering   Autonomous   Vehicles   Considering   TemporalDependencies,”   31st   Conference   on   Neural   Information   ProcessingSystems (NIPS), vol 32, pp. 1-8, 2017
-  Z.  Gu,  Z.  Li,  X.  Di  and  R  Shi,  ”An  LSTM-Based  AutonomousDriving Model Using a Waymo Open Dataset,” Appl. Sci., vol. 10, no.2046, 2020. https://doi.org/10.3390/app10062046
-  TimeDistributedlayer,Keras.io.Ac-cessedon:May20,2021.[website].Available:https://keras.io/api/layers/recurrentlayers/timedistributed
-  R.  Valiente,  M.  Zaman,  S.  Ozer  and  Y.  P.  Fallah,  ”ControllingSteering   Angle   for   Cooperative   Self-driving   Vehiclzing   CNN   andLSTM-based    Deep    Networks,”    2019    IEEE    Intelligent    VehiclesSymposium (IV), 2019, pp. 2423-2428, doi: 10.1109/IVS.2019.8814260.
-  Uˇriˇc ́aˇr, M., Kˇr ́ıˇzek, P., Hurych, D., Sobh, I., Yogamani, S.,  Denny,P. (2019). Yes, we gan: Applying adversarial techniques for autonomousdriving. Electronic Imaging, 2019(15), 48-1.
