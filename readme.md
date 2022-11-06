Prints look like this?

<img src="./Images/cube_example.png" alt="Example Cube" style="zoom:20%;" />

This tool aims to help diagnose the source of the issue. I'll leave the theory till the bottom and begin with a walkthrough.
# Step By Step
1) Please download this tower by Mihai Designs:
https://mihaidesigns.com/pages/inconsistent-extrusion-test

2) Slicer settings: Above all else, this needs to be printed in vase mode. Or spiralise outer contour, with no infil, and 1 wall. 
Wide layer lines and tall layer heights are still recommended as per the original instructions, 0.3 LH and 0.5 LW work well.

3) Once printed, you should be able to see some woodgrain, as per Mihai's example photos. We are interested in the length of the repeat of this grain effect. The easiest place to measure, would be tip to tip of the grains, as pictured.

<img src="./Images/measure_example.png" alt="Measure this" style="zoom:80%;" />

4) Enter the peak to peak measurment, into the document here: https://docs.google.com/spreadsheets/d/1vnIXAw5A0ayoq_EFUgS8qki22nJuo8gVn8SWhKNcVW4/edit?usp=sharing
under the "pattern wave length" field, along with your chosen layer height and line width.

5) The value created in red, should be a close match to one of the values in the table below for an extruder running BMG guts.
Given the comparison, with any luck, you now know which gear, or interaction, is causing your inconsistency. A close mechanical inspection, and adjustment, should be able to rectify this.

Currently only BMG gears are directly supported, but please contact me, Weaslus on the voron design or annex engineering discords, if you have other extruders and want help interpreting your results.

# Theory
Words, what are they...
section in progress.

# Thanks
Obviously, the biggest thank you to Mihai Design for pioneering this test print. It has been the inspiration for this tool since the day i first saw it.
I also like to give a shoutout to Foof on the voron discord for creating the initial spreadsheet, and Mazor for just generally being a legend and patient with my and my Github struggles.
