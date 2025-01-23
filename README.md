# TrustAuto Self-Driving Car

Science Fair

 




Project Title: Programming the Smart Car to Avoid Obstacles Using Ultrasonic Sensors





Required Wall Poster:





Project Type: Artificial Intelligence
Project Name: TrustAuto
Number of members: 2 (Neem Rashid - Al-Jawhara Salim)
Purpose of the TrustAuto Car:





The TrustAuto car focuses on:




Precise Obstacle Avoidance:




Equipped with advanced ultrasonic sensors that detect obstacles with high accuracy, helping to effectively avoid them.
Autonomous Driving:




Relies on an autonomous driving system that allows safe vehicle control without human intervention.
Artificial Intelligence:



Utilizes AI techniques to analyze surrounding data and make quick decisions that enhance safety.
In summary, TrustAuto aims to provide safe and intelligent driving by precisely avoiding obstacles, relying on autonomous driving, and using smart technologies.



Programming Language Used: Python





Attached is the method for programming the smart car using Python and ultrasonic sensors to detect and avoid obstacles.




![alt text](https://cdn-ck-me.classera.com/33994/images/1736991450_image.png)
 
 
 
 while inCurrentTask():
   
    go(100, 100, 0.01)
    
    if get_ultrasound()[2] < 100:
       
        go(-40, 100, 0.7)
        
        go(50, 50, 0.6)
        
        go(100, -40, 0.7)  


