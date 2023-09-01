# Minimization_of_power_consumption-LabVIEW
In this project, the main objective of this report is to minimize the Extra Power consumed by two Sample Classes and Labs than the required by making use of  day sequences and setting the time table for each day using LabVIEW Software with G-coding. Any developments/modifications are welcome

Here in this project
First the Sample Classes and laboratories are considered and the lights and fans in each class and Labs are 
indicated by Boolean indicators. According to the Day Sequence and Time table the lights and fans are turned ON and power is Calculated every day with respect to time. This Calculated Power output is given to “Write to Measurement File” in order to store the calculated power values in the Excel Sheet. The Power Output is connected to the Alarm Indicators so that if the obtained power exceeds the limit then an ALERT message is displayed using String Indicator and alarm is Enabled. Thus, by setting the Time table and Switching on the lights and fans automatically can only in the required class rooms reduce the power consumption to some extent. By making use of Alarm Indicators we can ensure to limit the Over consumption of Power.

-> Follow the block diagram for the code overview

Below are the Algorithms provided for each model to help design the G-code easily

-> OVER POWER USAGE INDICATORS AND ALERTS

-> Calculating the power of the classes and labs

-> Power Calculations

-> CASE STRUCTURE FOR DAY SEQUENCE

-> TIME SYNCHRONIZATION

Note: This code is considered by taking the examples of 2 standard classrooms and 2 Labs and the day schedule. This code is found to be Effective with the G-code.
