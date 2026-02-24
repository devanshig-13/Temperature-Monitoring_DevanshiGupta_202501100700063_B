"Problem Statement"



The objective of this program is to 
simulate a temperature monitoring system that continuously checks 
temperature values and compares them with user-defined minimum and 
maximum limits.

The program generates random temperature readings at regular intervals 
and alerts the user if the temperature goes beyond the acceptable range.

This helps in understanding basic concepts of:


User input handling


Conditional statements


Loops


Random number generation


Time delay in Python





"Approach"



The program first imports the random and time modules.



random is used to generate random temperature values.


time is used to create a delay between readings.


The user is prompted to enter:


Minimum acceptable temperature (min_temp)


Maximum acceptable temperature (max_temp)


A loop runs 10 times to simulate continuous temperature monitoring.


In each iteration:


A random temperature between 0 and 100 is generated using random.randint(0, 100).


The temperature is printed on the screen.


The program checks:


If temperature > max_temp → Display "Temperature is too high"


If temperature < min_temp → Display "Temperature is too low"


Otherwise → Display "Temperature is within acceptable limit"



A delay of 2 seconds (time.sleep(2)) is added after each reading to simulate real-time monitoring.





"Sample Output"



Enter minimum temperature: 25
Enter maximum temperature: 60
Temperature: 49
Temperature is within acceptable limit
Temperature: 67
Alert: Temperature is too high
Temperature: 16
Alert: Temperature is too low
Temperature: 79
Alert: Temperature is too high
Temperature: 87
Alert: Temperature is too high
Temperature: 38
Temperature is within acceptable limit
Temperature: 1
Alert: Temperature is too low
Temperature: 61
Alert: Temperature is too high
Temperature: 23
Alert: Temperature is too low
Temperature: 90
Alert: Temperature is too high
