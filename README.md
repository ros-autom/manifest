# -------WORK IN PROGRESS-------

###### Get familiar with ROS

Follow the notes descripted at the pdf file in notes/ROS Manual directory

###### ROS-autom team sources 

This section requires the knowledge of ROS basics.

+ Grab our sources:

1)Run 

    mkdir -p ~/catkin_ws/src
    
To create your workspace folder.
**This is also descripted in the notes file which we will use later**

2)Initialize our manifest:

    repo init -u git://github.com/ros-autom/manifest.git -b master
      
3)Download the source code:

    repo sync 
      
If,for any reason, you cant download our sources use :
  
    repo sync --force-sync
    
to make git process brutally download the sources.
You can also use
   
    repo sync -j1

if your internet connection is bad

+ Run our scripts ( Advanced )

the 'repo sync' command will grab the proprietary scripts to run all **our** executables.

+ Run our Android implementation

1)Build Android APP 

Detailed information about android app is located [here](https://github.com/ros-autom/RobotCA/blob/kinetic/README.md)

Run from your workspace:

     cd android_package
     ./android.sh
    


