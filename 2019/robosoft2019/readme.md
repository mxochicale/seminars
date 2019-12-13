# Robot Software



## Wed 13 Nov 2019

### Davide Brugali
Managing software variability for dynamic reconfiguration of robot control systems
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Brugali.pdf

Robotic Variabilty 

* Hardware and Software: Different arquitectures according to hardware and 
software
* Task: Logistics, Social interaction, housekeeping
* Environment: Mostly static, hihgly dynamic, indoor or outdoor
* Capabilities: Motion control (onmidirection, differential drive),
trajectory following, trajectory planning, etc.

Challenges:
* Software requirements
* Functional requirements
* Modelling and analysis of NF-Requirements for reconfigurable systems


Variability Modeling of Service Robotis: Experiences and Challenges
Sergio Garcia et al.

Model-based development of QoS-aware Reconfigurable Autonomous 
roobtic Systems
Brugali et al 2018 in ICRC

Q&A:
* It was not clear which regulations are followed for Software in 
Robotics in Europe


### Gusz Eiben
Evolving Robot Software and Hardware 
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Gusz.pdf


Reality gap: Computer simulation vs to reality

Can real robots evolve?
Can real robots reproduce?
Can real robots have children?



Introduction to Evolutionary Robotics

The trigangle of life: evolcving robots in real time and real space
Eiben Bredeche, etc. in ECAL 2018


https://evosphere.eu
1. Production center
2. Trainign ccenter
3. Arean (the world)
4. Recycling
VIDEO: https://youtu.be/BfcVSb-Q8ns


Brodbeck Hauser, Ida
Morphological evolution of physcical robots
through model-free pehnotye develipment
Plos one 2015



Real-Wor;d Evolutions of Roboti Morphologies
Jelisavcic, De Carlo, Hupkes,
in Artificial Live 2017


2nd order software/hardware engineering


The ARE Robot Fabricator: How to (Re)produce Robotics 
that can Evolve in the Real World
Hale et al ALIFE 2019


Improvements-extensions
* Body
* Brain
* Evolution
* Environment


Evolving embodied intelligence from materials to machines
Howard et al. Nature Machine Intelligence 2019


From Evolutionary Computation to the Evolution of Things
Eiben and Smith in Nature 2015



What is more important the body of the brain?

publications: 
https://www.cs.vu.nl/~gusz/index.php/my-publications/





### Christian Schlegel
Composition, Separation of Roles and Model-Driven Approaches 
as Enabler of a Robotis Software Ecosystem 
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Schlegel.pdf


Towares and EU Digital indutrials Platform for Robotics

* Change on solution
* Change in requirements


Service Robots Ulm
SmartMDSD

EU Projects
* RobMoSys
* SeRoNEt


RobMoSys
Ecosystem Tiers:


Groot

SmartTCL 
youtu.be/RHwd6THGz


Middleware Late Binding/Middleware Agnostic Modeling
Standards


OpenSource Software project


Code verification on the

Q&A
* Bottom up composition operators
* Generating trust



### Sebastian Brunner
The RAFCON Task Control Framework    
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Brunner.pptx



How to enable robotic experts program autonomous robots?

Hierarchical, PArallel Finite State Machiens with data flows
IROS 2016


Mapping timeline of the part of the robots
Identify Robustness Bottlenecks



Model Checking Implementation
* uses the HPFD as transition systems


Aplications Scenario: 
* The Arches Project



### Arnaud Gotlieb
Testing Robotic Systems: A New Battlefield!   
Slides:  https://www.cs.york.ac.uk/robostar/robosoft/slides/Gotlieb.pdf


* Constrain programming
	* Constration propagation
	* VAriable labelling
	* Domain filtering


nvalue(N,V)
Pachet Roy 1999 Beldiceanu 01

gcc(F,N,V)
global cardinality constration


SWMOD: Deployment of Test Case Execution Scheduling at ABB Robotics
Based with VisaulStudio, python, 

Collet et al
Stress Testing of Single Arm Robitcs 
Through Constraion based generation of continuos trajectories
April 2019

Ahuja et al.
DeepRegresion : Regresion TEsting of Deep Learning 
Sysitem Using Reduced TRaining Dataset


Spieker and Gatieb
Adaptive MEthamorphic: Testing with Contextual Robotis 



### Kersting Eder
Gaining Confidence in the Correctness of Robotic and Autonomous Systems   
Trustworthy Systems Laboratory  
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Kerstin.pdf  



Verification and validation and correcness

User Requirements > 
Optimiser >  
Contorller (SW/HW)

What can go wrong in robot navigation software?
SPARK: a verifiable subset of ADA


WAIT HAMMER NO!

https://github.com/riveras/simulink


* Simulink control 
1. Idea
2. Control system desing in simulkin
3. Implentation level


Verifying Stability


De
Systematic and Realisting Testing in Simulation of Control Code for Robotics
in Colaborative Human-Robot Interaction.


github.com/robosafe/techbench


What about agency?
Can we shallow a robot?


Q&A


### Alan FT Winfield
Ethical Standards in Robotics and AI
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Winfield.pdf

Ethical governance is essential to building trust
in robotics and AI systems.

Transparence
* Process standars for trasnparency
* Technical standars for transparency
* Technologies for transparency


Reponsive innovation
Responsive Robotics
* design
* manufacuter
* operation
* repaing
* recycling


ROBOTIPS (5 years project)
Responside Robotics for the Digital Economy
robotips.co.uk
* Ethical black box

Winfield and Jiroka in TAROS 2017
The case fo an etichal black box 


Winfield
Ethical standars in Robotics and AI
Nature electronics


S: The quality of discussions is


### Michael Fisher  
Verifiable Autonomy and Respnisbile Robotics   
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Fisher.pdf



With an autonomus system we can examine its internal 
programming 
* What is thinking?
* What choices it has, and
* Why it decides to take particular ones




ISOBSI standar on Modularity

IEEE P70001



Varieties of Verification
* Proof
* Traditonal Model-Chekding
* Testing
* Synthesis
* Dynamics Fault Monitoring
* Program Model-Chedking



Toward Reo;ab;e Autonmous Robotics Assistance Through Formal Verification

Alves et al.
Generating Cerfification Evidence for embedding into an Autonmous 
Vehicle Agent
FMAS 2019




## Day 2: Thursday, 14th November


### Félix Ingrand
Verification of Autonomous Robots, a Roboticist Bottom Up Approach
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Ingrand.pdf

https://redmine.laas.fr/projects/minnie


### Ana Cavalcanti
RoboStar technology - a roboticist’s toolbox for combined proof and sound simulation
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Cavalcanti.pdf


https://www.cs.york.ac.uk/robostar/robosim/robosim-reference.pdf
https://www.cs.york.ac.uk/circus/publications/techreports/reports/robochart-reference.pdf


### Rob Skilton 
A software framework for interoperable, plug-and-play distributed robotic systems of systems  
https://www.cs.york.ac.uk/robostar/robosoft/slides/Skilton.pdf


### Rob Hierons
Systematic automated testing of Robotic Systems based on Formal Models  
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Hierons.pdf


### Patrizio Pelliccione
Making robots usable in everyday life
Slides https://www.cs.york.ac.uk/robostar/robosoft/slides/Pelliccione.pptx


### Jim Woodcock  
Modelling uncertainty in RoboChart using probability  
https://www.cs.york.ac.uk/robostar/robosoft/slides/Woodcock.pdf


### Zeyn Saigol
Extending automotive certification processes to handle autonomous vehicles  
Slides: https://www.cs.york.ac.uk/robostar/robosoft/slides/Saigol.pdf

















## References
https://www.cs.york.ac.uk/robostar/robosoft/programme/
