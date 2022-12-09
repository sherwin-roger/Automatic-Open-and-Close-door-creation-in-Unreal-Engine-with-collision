# Automatic-Open-and-Close-door-creation-in-Unreal-Engine-with-collision


# Aim
To implement Automatic-Open-and-Close-door-creation-in-Unreal-Engine-with-collision 

# Procedure
Begin by creating a New > Games > Blank > Blueprint project with Starter Content enabled named TimelineDoorActor.

Click the Add/Import button to create a new Blueprint Actor class named BP_DoorActor.

Double-click the BP_Door Actor from the Content Browser to open it in the Blueprint Editor and open the Class Defaults.

Next, from the Components tab click the Add Component button and select Static Mesh to add a new Static Mesh Component.

Right-click your static mesh component and select Rename to rename it to DoorFrame.

Next, from the Components tab click the Add Component button and select Static Mesh to add a new Static Mesh Component. (Repeating step 3)

Right-click your static mesh component and select Rename to rename it to Door.

Click Add Component, select Box Collision from the dropdown menu, and rename it to Box.

Next, open the Event Graph, right-clickthe graph, and choose Add Timeline from the Blueprint Context Menu. Name your Timeline DoorTimelineComponent.

Begin by double-clicking the DoorTimelineComponent in the Event Graph to open the Timeline Editor.

Click Add Float Curve to add a new curve to the track and name the curve DoorRotation

Shift select both your keys, right-click, and from the Key Interpolation dropdown menu select Auto interpolation.

Save your float track.

# Output
![image](https://user-images.githubusercontent.com/75235128/206687192-68c89079-6292-4a4c-9e72-b7aa958e7335.png)

# Result
Thus Automatic-Open-and-Close-door-creation-in-Unreal-Engine-with-collision is implemented
