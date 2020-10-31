  Planning
----------
### Definition of the problem 
My client is Mr. Pierre Lacoste, the Deputy Head of UWC ISAK Japan - he is supervising the team that locks up the buildings inside the school, the team's responsibility is to 
check-in the buildings, that no one is in there after curfew, make sure the lights are off and windows closed inorder to safe energy and be sustainable,  and finally to lock them up. and through out the proccess, 
the team has faced problems regarding the lights - as sometimes lights might be forrgoten on and not turned off, which creates a loss of energy and money.

### Solution proposed
Based on the information giving by Mr. Lacoste regarding the problem, I have decided to create a notification system that helps my client to follow the statu 
of the lights in the buildings of the school - Mr. Lacoste and I have agreed on placing the prototype System in the Gym because it is the place that will cause more loss of energy 
if forgotten on more than any other rooms, and that is due to its huge space and the lights needed to keep it on. 
I am going to use Rasberry Pi to build this notification system. It provides the ability to connect the light sensor needed to determine the statu of the light, also it is a whole computer that can connect to a wifi network and make the process of sending the notification emails. Also I will be using Flask to create a User Interface where the addministrator can check the statu of the lights live, as it will provide me with the tools and the libraries that will help the user navigate 
throgh the web-app effectively. 

### Feasibility Study

**TELOS** is a method in project management used to define five areas of feasibility that determine whether
a project should run or not. 

In this **Internal Assessment**, I will be Developing a notification system for Mr. Lacoste to serve the purpose of avoiding energy loss in UWC ISAK Japan.  

The notification system successfully passes the TELOS feasibility:

The system is **technically feasible.** I will be using a Rasberry Pi to make the system happen, both the hardware and software part - Rasberry Pi will allow me to plug sensors and connect to wifi in order to notify the team responsible for the locking up. 

The system is **economically feasible.** The developing tools are availiable and not needed to be paid - also the user would be able to use it without paying
since internet is avaliable by the school. 

The system is **legally feasible.** There are no regulations against any of the technical or logistical parts of the System. 

The system is **operationally feasible.** This system will not cause any conflicts with any other operations - it can be placed anywhere and does not require any software connections to be ran (except the first set-up). 

The system is **well scheduled**. It will take about two months to be developed. Time is needed to research about Rasberry Pi (Hardware & Software) and also to learn how to create a suatbale databse - There needs to be meetings with the client. As it is an Internal Assessment by IB, We will be following a schedule provided by the Teacher of Computer Science. 

### Success Criteria

| No. | Success Criteria                                                                             |
|:---:|----------------------------------------------------------------------------------------------|
| 1   | The system is accecieble throgh a web-application.                                           |
| 2   | The user can check the statu of the lights anytime during the day.                           |
| 3   | The user should be able to check if the lights in the designated room are on.                |
| 4   | When lights are forgotten on (After 9:45 PM) - System should notify the team by E-mail.      |
| 5   | System should be provided with a proper Documentation should be provided with the system.    |
| 6   | User is able to check the history of the hours the the lights has been on for.               |
| 7   | UI should be interactive for the user, which means animation of buildings will be provided.  | 
| 8   | Web-App should be secure, which means that only the team members and the administrator are able to acess the system.|

