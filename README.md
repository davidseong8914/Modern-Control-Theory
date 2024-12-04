# Modern Control Theory | Modern Control For Robotics
### CMU 24677 - Project Demos

In this class, we were tasked with developing our own controllers to enable a Tesla to complete a path in a [Webot](https://cyberbotics.com/) simulation environment. I develoepd 5 different controls (PID, FSF, LQR, ...) for the Tesla to complete the path as fast as possible while meeting the accuracy requirements. Through the projects, I was able to deepen my understanding of different control systems and their applications in autonomous vehicles.

## Unoptimized Simulation
Simulation of an unoptimized run to compare against runs with custom controllers.

[Watch the unoptimized simulation on YouTube](https://www.youtube.com/watch?v=LSsvH2R49dw)


## P1 : PID Control
> Requirements: 
>> Runtime: < 400s <br>
>> Maximum Distance from Path:10m <br>
>> Maximum Avg Distance from Path: 5m

[Watch the PID control simulation on YouTube](https://www.youtube.com/watch?v=98Yn8yShmd8)


![Alt Text](p1/PID_1.png)
![Alt Text](p1/PID-400-10-5.png)

## P2 : Full State Feedback Control
> Requirements:
>> Runtime: < 350s <br>
>> Maximum Distance from Path: 9m <br>
>> Maximum Avg Distance from Path: 4.5m

[Watch the FSF control simulation on YouTube](https://www.youtube.com/watch?v=o_HNBtnbN30)

![Alt Text](p2/fsf.png)
![Alt Text](p2/FSF-350%209%201.45.png)


## P3 : LQR
> Requirements:
>> Runtime: < 250s <br>
>> Maximum Distance from Path: 7.0m 
>> Maximum Avg Distance from Path: 3.5m

[Watch the LQR control simulation on YouTube](https://www.youtube.com/watch?v=O3-dlC_X07o)

![Alt Text](p3/lqr.png)
![Alt Text](p3/lqr_2.png)

## P5 : MRAC (Model Reference Adaptive Controller)
> Developed a MRAC, LQR control for a drone that recovers from 65% thrust loss in one of the motors

[Watch the MRAC drone control simulation on YouTube](https://www.youtube.com/watch?v=KfT4UupcHBs)

![Alt Text](p5/lqr.65.png)