# Auto-Rigger
A repository of code for a work in progress of an auto rigger for Maya

It is currently split up into 5 parts, which are :
    Set Locators
    Rig Skeleton
    Rig IK-FK Skeleton
    Make Controls
    Set Controls
    
Set Locators will make a goup of locators, which need to be sized to the character model. Please note that proper protocol is still needed here, such as making sure that the locators for the arms and legs line up in the same axis.

Rig Skeleton will turn all of the locators into a skeleton and joints. These can now be rotated to the proper locations, or sized to desire.

Rig IK-FK Skeleton turns the joints into the proper hierarchy, with the skeleton having both an IK form, as well as an FK form.

Make Controls will make controls. These can be resized as desired, and made to fit the model.

Set Controls will then set the controls and the skeleton, making it so that the skeleton is fully usable.

At this point, the only thing that should be left is skinning. Please note that this autorigger is for research purposes only, and as such, there are bugs that have not been fixed. I am also a college student at the current time, so fixing code for something that only I use has not been a priority. If any bugs are encountered, feel free to note them and inform me.
