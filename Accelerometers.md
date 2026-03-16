## What is accelerometer?
A device which measures the rate of change of velocity in one or more axes.
units of acceelration , m/s2 or g.
They output ax,ay,az i.e acceleration along all 3 axes.
Imagine a phone lying flat on table, it will experience ax=0, ay=0 however az=g since gravity is pushing it downwards.
## Accelerometers help us detect?
1. linear acceleration (change in velocity in straight direction)
2. gravity detection ( helps find orientation, in which direction is the gravity getting applied, for eg if az=g and rest all 0, meaning lying flat. if ax and az!=0, means object at some angle, help calculate its tilt.)
3. motion detection
## They measure proper acceleration- the acceletrtion caused by forces acting on it.
Consider a phone lying on table, the normal force acts on it upwards and the gravity acts on the phone downwards.
### Accelerometers dont measure the gravity itself, but the contact forces acting on it.that is, it measures the non-gravitational forces acting on it.
If it measures 0g meaning it is under freefall(no contact force acting on it)
Gravity vector?
Types of accelerometer -
1. MEMS
2. piezoelectric
3. capacitive

### MEMS Accelerometer
1. proof mass
2. spring
3. capacitors
The proof of mass is attached to the spring.When the accelerometer moves, becoz of inertia then mass tries to remain at its original position resulting in chnage in distance between the capacitor plates and hence the capacitance.
Corresponding analog volateg is calculated which trough adc gets converted to some digital value and hence values like ax,ay,az.
side each chip there are 3 diff sensing structures for each axis.
## Output of the accelerometer
a=(ax,ay,az)
Inside the chip, the data is stored as int values in registers, using scaling converted into m/s2.this data is read using digital comm protocols like spi,i2c etc.
### Uses of accelerometers
1. Drone stabilization
2. rocket launch monitoring
3. launch detection (eg if acc>3g-> launch)
4. Velocity estimation
5. Vibartion monitoring
6. part of inertial navigation system
7. 
