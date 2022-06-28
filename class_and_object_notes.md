Classes notes

In the classes image, I chose to represent the on/off state of both the computer and monitor by using a boolean, as it can use True for on, and False for off.

The variavble operating_system is represented by a String as it is just the name of the operating system being used, e.g. Windows, MacOS, or Linux.

The variable dimensions_of_case is the last variable I chose to use for the Computer class, and it is represented by a list of integers, with the intention of the int at index 0 holding the x value, the int at index 1 holding the y value, and the int at index 2 holding the z value.  I also could've used a dictionary instead, which could be as follows:

dimensions_of_case = {
    "x_value" = 1,
    "y_value" = 2,
    "z_value" = 3
}

The first function of Computer, turn_on, takes power as an argument, and does not have any outputs.

The second function, change_framerate, takes no arguments, and it returns the updated framerate of the monitor.  I decided to run this through the computer, as the framerate is usually changed through it, rather than the monitor.

In the Monitor class, it has two variables, power which holds a boolean, and framerate which holds an integer.

It also has a turn_on function, similar to the one in the Computer class, as it can be turned on seperately from the computer.

The two classes are linked together, as the Computer class is able to change the framerate of the Monitor Class in this scenario.

Object Notes

For the objects, I decided to use my computer and monitor, as an example of the Computer and Monitor classes respectively.

Both my computer and monitor's power are set to on, so both 'power' variables are set to True.

My computer runs on macOS, so 'operating_system' is set to "macOS".

For dimensions_of_case, i entered in three random integers to show how it would look like when stored in a list.

The framerate of the monitor is also set to 144.