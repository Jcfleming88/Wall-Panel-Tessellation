# Wall-Panel-Tessellation
Automated tessellation of panels along a wall surface

---

![Random Panels](https://user-images.githubusercontent.com/64108488/93528824-d8d8f680-f932-11ea-9605-a5141aa0585e.png)

---

# Description
Created to test various Revit and Dynamo skills, the script tessellates wall panels along a face and sets 
peramters for the panel. In this case I created a custom panel to be spread across the wall which the 
script then alters the width of the panel to create raised sections.

The script currently does seperate patterns:

1 - Random - Heights of each panel are set at a random height to create a random pattern of raised areas. 
The panels are standardise to minimise the number of different panels used.

2 - Vertical Gradient - A simple setting to create a gradient from top to bottom along the wall face.

---

# To - Do

- Add further patterns to the script. There is currently a mechanism in Dynamo to change which pattern is 
used so that further variations can be added in the same script. Additional patterns:-

>- Curve based - Setting parameters based on the proximity to a line or curve.

>- Varying panel sizes - Adding various different panels to create a crazy paving effect.
