## Synopsis

Robocode is a platform for creating code-driven battlebots.  Your mission is to create an artifically intelligent robot bent on destruction.  After designing your robot to fight against robot enemies, you will then face off against each other in what will certainly be a battle where only one will survive.  

While there are MANY strategies you can employ to confuse or dispose of the competition, you have to decide if brains or brawn will win the day.  

## Where do I sign up!?

Clone this repository to your local machine and import the Eclipse project located in robocode_robot.  In this project you can begin writing your own personal robot intelligence.  The main file you will work in is src/yourinitials/YourRobotName.java.

To get started just refactor->rename the package yourinitials with your initials, then refactor->rename the file YourRobotName.java with whatever you would name the robot.

## Writing your robot

In this file, you will see a framework for running the robot, scanning for other robots, reacting to getting shot, and reacting to hitting walls.  Keep in mind that there are many more framework and function options than what is in the file.

API Here:  
Wiki Here: http://robowiki.net/wiki/Robocode

## How to I run my bot?

Open the eclipse project as mentioned earlier.  Inside of Eclipse right click robocode_robot then click Run As->Run Configurations.  Expand Java Application and select "Run Robot".  Click Run at the bottom right of the window.  

When the Robocode application opens click "Options-> Development Options".  Here you need to add the directory where you cloned/downloaded the repository.

Example for my machine:  /home/curt/terrorbytes/source/repo/robocode/robocode_robot/bin

It is important you point this at robocode/robocode_robot/bin so that the application can see your robot.  You will only have to do this once.  

At this point you can click Finish which brings you back to the main window.  Then click:

Battle->New

In here you should see your initials under packages, and your robot name on the right.  Add your robot, and some sample bots, then click Start Battle!  That's it.  Enjoy the game and good luck :)

## Can I download the official release from Robocode?

Of course!  I only made this Eclipse project with links to make it easier on you.  I took care of the IDE setup so that you can get to programming the robot faster.  There is also an IDE built into the robocode application, but as you probably guessed, Eclipse is MUCH better!

## How do I score points?

Here's a breakdown of all the statistics:

**Total Score* - This is everything else added up, and determines each robot's rank in this battle.
**Survival Score* - Each robot that's still alive scores 50 points every time another robot dies.
**Last Survivor Bonus* - The last robot alive scores 10 additional points for each robot that died before it.
**Bullet Damage* - Robots score 1 point for each point of damage they do to enemies.
**Bullet Damage Bonus* - When a robot kills an enemy, it scores an additional 20% of all the damage it did to that enemy.
**Ram Damage* - Robots score 2 points for each point of damage they cause by ramming enemies.
**Ram Damage Bonus* - When a robot kills an enemy by ramming, it scores an additional 30% of all the damage it did to that enemy.
**1sts, 2nds, 3rds* - These do not actually contribute to score, but are there to show how long the robot survived, i.e. the number of rounds the robot was placed 1st, 2nd, and 3rd.

Reference and more information found at:  http://robowiki.net/wiki/Robocode/Scoring

## Final Notes

Please read around on http://robowiki.net.  There is a wealth of information available including more difficult robots to download for you to compete against.

I also encourage you to play against your friends before the big-day to fine-tune your combat!  This is meant to be fun.  Your robots are located in robocode_robot/bin.  Just copy your initial folder which includes the .class file to your friend's bin folder and start the application.  Don't worry, your friends (ahem...competition) can't see your code in the class file :).

## Links

http://robowiki.net/wiki/Robocode_Download_And_Install
http://robowiki.net/wiki/Category:Tutorials
http://robowiki.net/wiki/Robocode/My_First_Robot
http://robowiki.net/

## Credit

I had no part of development of Robocode, nor did I write any code that differs in this package.  This is only a pre-linked Eclipse project to aid in development.  Credit goes to the brilliant developers who made this fun platform for friendly competition and aiding in learning.