/*
Author:Chuankai Xu
Date:2021-10-17

*/
I use these code to do a evaluation and analysis on four optimization algorithms for three toy problems and NN training
#UCI Divorcehttps://archive.ics.uci.edu/ml/datasets/Divorce+Predictors+data+set

Four optimization algorithm was conducted on the datasets,which is Simulation Annealing,MIMIC,genetic algorithm,random hill climbing.
Some of them were based on molrose, while some are not compatible with scikit-learn out-of-the-box. 
So I use my designed code on three toy problems that could change the parameters and size of problems.
============================================================================

All of my source code could be got in my github Repository:

https://github.com/trankxu/MLAssignment2

======================================================\

Requirements:
certifi=2021.5.30
charset-normalizer=2.0.6
colorama=0.4.4
cycler=0.10.0
graphviz=0.17
idna=3.2
joblib=1.0.1
kiwisolver=1.3.2
matplotlib=3.4.3
numpy=1.21.2
pandas=1.3.3
Pillow=8.3.2
pip=21.0.1
pyparsing=2.4.7
python-dateutil=2.8.2
pytz=2021.1
scikit-learn=0.24.2
scipy=1.7.1
setuptools=52.0.0.post20210125
six=1.16.0
sklearn=0.0
svm =0.1.0
threadpoolctl=2.2.0
torch=1.9.1
torchvision=0.10.1
typing-extensions=3.10.0.2
urllib3=1.26.7
wheel=0.37.0
wincertstore =0.2
xlrd =2.0.1
xlwt= 1.3.0
xmltodict=0.12.0
===================================================================
Toy Problems

       Simulation Annealing

	Run  python ./code/SA.py


      MIMIC

               Run python ./code/MIMIC.py


      Genetic Algorithm

	Run python ./code/GA.py


      Random Hill Climbing

	Run python ./code/RHC.py


Neural Network Optimization

	Simulation Annealing


		Run  python ./code/NN-SA.py


      	MIMIC

               		Run python ./code/NN-MIMIC.py


     	Genetic Algorithm


		Run python ./code/NN-GA.py


      	Random Hill Climbing

		Run python ./code/NN-RHC.py

