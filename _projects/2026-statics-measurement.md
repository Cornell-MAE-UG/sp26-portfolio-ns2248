---
layout: project
title: Statics Nutcracker Project Part 1
description: Nutcracker Project
technologies: Chrome, Canvas
image: /assets/images/IMG_8019.jpeg
image2: /assets/images/IMG_8044.jpeg
---


## Find
A design for a nutcracker mechanism

## Assume (from external sources):
- Average nut size is 15 mm
- Macadamia nut load is 222 Kg or 488.4 Lbs
- Average grip strength is 90 Lbs

## Given
Given:
- Structure of the mechanism
- Instructions for the problem

![Nutcracker Information](/sp26-portfolio-ns2248/assets/images/IMG_8019.jpeg)

## Approach
Show the grip strength forces among the two handles of the nutcracker mechanism and display the maximum macadamia load at the points where nut and mechanism contact one another. Use equilibrium equations, such as the moment about the point of contact between the nut and the nutcracker, to solve for the length at which the grip forces should be applied to break the nut.

![Nutcracker Diagram](/sp26-portfolio-ns2248/assets/images/IMG_8044.jpeg)

## Discussion
This nutcracker takes the forces from a users grips and amplifies that force to break the nut. If the nut load and average grip strength are as assumed, it is calculated that the nut cracker would have to be around 27 cm long to generate a force large enough to crack the nut. It is important to note, as the length of the nutcracker handles increase, so does the distance between the points at which the grip strength forces are applied. Thus, a longer handle may be unusable if human hands cannot fit around it to generate a breaking force.

## Websites used:
https://www.progressiveautomations.com/collections/linear-actuators

https://doi.org/10.1007/s10071-007-0131-2

https://www.racmn.com/blog/get-a-grip-your-health-is-in-your-hands-really





---
title: Statics Nutcracker Project Part 2
description: Nutcracker Project
technologies: Chrome, Canvas
image: /assets/images/IMG_8019.jpeg
image2: /assets/images/IMG_8044.jpeg
---

## Find
a) Find the location of maximum elastic deflection in the nutcracker handles
b) Find a beam design such that the vertical deflection is less than 2% of the handle length
c) Draw the new nutcracker design


## Given
Given:
- Quantities from part 1
- A is a pivot
- Force from hand is 488.4 Lbs, approximately 400N
- Force from nut is 90 Lbs, approximately 2170N

![Nutcracker Information](/sp26-portfolio-ns2248/assets/images/IMG_8019.jpeg)

## Approach
Draw a Free Body Diagram of one of the handles and use equilibrium to determine the reaction force at pivot A. Then use the diagram to create a moment equation, M(x), for the system. Use this equation to determine the location of maximum deflection. Next, determine the length of allowed vertical deflection and use equations to find an inequality for E and I relating to the maximum deflection. Plug in values for E and I until the inequality is true, and use the corresponding cross-section and material to check that the deflection is allowed. Finally, draw the new nutcracker.

![Nutcracker Diagram](/sp26-portfolio-ns2248/assets/images/IMG_8044.jpeg)

## Discussion
The hollow aluminum cylindrical handle works, because the calculated vertical deflection of 2.69 mm is less than the allowed deflection of 5.4 mm. Thus, the design would minimize the deflection to at most 2% of the 27cm handle.
