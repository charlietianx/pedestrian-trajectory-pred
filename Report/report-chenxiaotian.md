#Phase1
##introduction
Pedestrian Trajectories Prediction with InfoGAN: based on history trajectories to predict the future trajectories of the pedestrians.
Motivation: trajectories prediction has been widely applied in many modern industries. From service robots to automatic driving, trajectories prediction plays a quite important role.
Previous works: by social LSTM[1], social GAN[2]
Contribution: Analysis the factors that affected the trajectories, possible factors: agent's destination, the social group the agent is in(eg. the agent is a couple), the social scene and the social interation
Work flow: 
1.Questions or problems definition; phase 1
2.Acquire training and testing data; phase 2
3.Wrangle, prepare, cleanse the data. phase 2
4.Analyze, identify patterns, and explore the data. phase 2/3
5.Model, predict and solve the problem. phase 3
6.Evaluate, visualize, report, and present the problem solving steps and final solution. phase 4

##PROBLEM STATEMENT
Pedestrian Trajectories Prediction: By training models based on trajectories' data, use the models to make prediction
Deep Learning: InfoGan, a generator and a discriminator. Generator generates x as input to discriminator, and discriminator output 
a result telling if x is true or false. Our goal is to maximize the loss of discriminator and minimize the loss of generator.
Our questions: How many factors of variations can be obtained from the data?





[1] Alexandre Alahi, Kratarth Goel, Vignesh Ramanathan, Alexandre Robicquet, Li Fei-Fei, Silvio Savarese; Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016, pp. 961-971
[2] Agrim Gupta, Justin Johnson, Li Fei-Fei, Silvio Savarese, Alexandre Alahi; Social GAN: Socially Acceptable Trajectories with Generative Adversarial Networks, 2018