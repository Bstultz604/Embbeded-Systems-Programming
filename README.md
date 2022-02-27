# Embbeded-Thermostat
Project showcasing my work with embedded systems.

# Summarize the project and what problem it was solving.
  This project utilizes a Texas Instuments SimpleLink CC3220S microcontroller LaunchPad to implement a thermostat. The project consisted of three condtions. The first being the use of the imbedded thermostat that would read the tempurature of the room. The second condition was to enable a setable interger value that would be cpmared to the tempurature reading to determine wether an external heater should be tunred on. The third condtion is to have data formated and sent to a file log server. 
    The first conditionwas meet simply by accessing the thermostats pins. In the second condition I used two buttons that will decrement or increment the setable integer value. Finally I formated this data into a string format which I then printed out to a COMM port every second.
    
# What did you do particularly well?
  I implemented a task shecudler effectivly in this project. Utilizing an array data structure to hold objects of each state, which are then iterated over, using a internal object variable to check when the state code should ececute. These features enable the program to run in set time intervals in accourence with a global timer. 
  
# What skills from this project will be particularly transferable to other projects and/or course work?
  The main transferable skill obtained from this project is the design principles used for embedded system. I now understand the memonry and compuational limitations of embeded systems, giving me insights into thier strewngths and weaknesses. I also have a strong understanding of how embedded systems should be designed and tasks seperated to ensure high functioniing products. 
