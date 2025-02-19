---
title:  "SUTD What The Hack Hackathon 2018"
categories: Projects
---

<a href="https://devpost.com/software/circuit-defense"> SUTD What The Hack Hackathon 2018 Entry </a>

![](/_assets/images/SUTD_WTH/TeamWinSUTD.jpg)
*Winning Best VR Hack*

On the final year of my Diploma studies, our lecturer recommended us to join a hackathon. He felt that it would be a good experience for us, teaching us how to manage our time well and plan our projects effectively, having only one day to finish the project. Two teams from my class signed up for the hackathon. Of the two teams, my team had the least experience participating in hackathons. 

The hackathon's objective was to come up with a VR/AR application and create a demo to pitch to the judges. These had to fulfill one or more categories that SUTD had chosen and annouced to us prior to the hackathon. 

![](/_assets/images/SUTD_WTH/SUTD_WTH_Categories.jpg)
*The categories in the hackathon*

We chose to create a educational VR application that would incorporate the properties of electrical circuits (mainly parallel vs in series) and gamify it into a tower defence game. Players would be asked to build up their defence by combining towers, wires and an energy source. They had to make complete circuits with the pieces in order to power the towers. The strength of the towers is affected by the configuration of the circuit. Not only that, enemies could break the pieces that the player placed down, meaning redundancy was part of their concern as well. This would impart the different properties of circuits in parallel and in series to players.

I took charge in creating the code architecture of the project, determining the framework in which my team members would follow in order to implement their respective features. I utilized C# interfaces and a composition-based approach, which played well with Unity's component based approach. This allowed for everyone to implement their own components, keeping them abstracted from each other via interfaces. Upon finishing their individual components, integration was fast as the interfaces meant the main game structure was already built around the abstraction, needing minimal effort to slot in the team's implementations. This sped up integration at the end of the day long development cycle whilst keeping integration problems to a minimum. 

The project succeeded in its overarching goal of framing circuits in a fun interactive manner. The node-based wire logic, which would have adapted to user placement was the main challenge of the project. We managed to come up with workarounds and fixes in order to have a working product to demo, which allowed for us to communicate our goals for the project successfully. 

One of the aspects of the project that I am proud of was our time management. With the code architecture in place and a well thought out timeline and plan for the implementation, we managed to complete most of the project goals within the short 24 hour time limit we had. When we hit a road block with the node-based wire logic, we came up with work arounds that allowed us to show off the project successfully. For our first hackathon, this is one aspect I am extremely proud of.

### Video Demo
<iframe width="800" height="450" src="https://www.youtube.com/embed/mP89Dt8lZjQ?si=UG2hyAMhilFTeL3X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
