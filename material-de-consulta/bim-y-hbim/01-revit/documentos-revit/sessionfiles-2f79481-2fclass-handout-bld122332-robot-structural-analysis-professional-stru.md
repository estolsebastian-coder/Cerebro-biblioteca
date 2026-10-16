---
type: libro
title: "sessionFiles%2F79481%2FClass_Handout_BLD122332_Robot_Structural_Analysis_Professional_Structural_Analysisfrom_Design_to_Calculation_Safet_Iska_1"
author: "Patricia Lundberg"
categoria: "BIM Y HBIM"
paginas: 15
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/DOCUMENTOS REVIT/sessionFiles%2F79481%2FClass_Handout_BLD122332_Robot_Structural_Analysis_Professional_Structural_Analysisfrom_Design_to_Calculation_Safet_Iska_1.pdf"
convertido: 2026-10-16
---

# sessionFiles%2F79481%2FClass_Handout_BLD122332_Robot_Structural_Analysis_Professional_Structural_Analysisfrom_Design_to_Calculation_Safet_Iska_1

> Texto extraído de `BIM Y HBIM\01. Revit\DOCUMENTOS REVIT\sessionFiles%2F79481%2FClass_Handout_BLD122332_Robot_Structural_Analysis_Professional_Structural_Analysisfrom_Design_to_Calculation_Safet_Iska_1.pdf` (15 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

[BLD122332]
Robot Structural Analysis – From design to
calculation

Safet Iska

Learning Objectives
• Gain a better understanding of how Robot Structural Analysis Professional can be
used and all its benefits
• Learn how Robot Structural Analysis Professional is integrated to the users primary
modeling tool Revit
• Learn how to plan a model and understand what to think of before exporting to
Robot Structural Analysis Professional, and what outcomes can be expected with a
bad model
• Get an overview of the steel design and reinforcement design tool in Robot
Structural Analysis Professional

Description

Usually our ultimate wish in a project is to eliminate the phase where the user has to remodel
the structure in our FEM-software to execute the load take down calculation, this is quite timeconsuming. The link between Revit and RSA is getting used more and more with the time but
often our first projects doesn’t appear to be that time saving because of the lack of knowledge
users usually have in the first test. Learn what type of issues might appear, how to eliminate it
and which benefits you as a user can have by using these software’s correctly.

Robot Structural Analysis Professional (RSA) is a well-used Structural calculation software or
even sometimes called FEM-software provided by Autodesk. RSA offers advanced calculation
methods for different type of structural material such as concrete, steel and timber. It also allows
us to design our structure considering e.g. Eurocode, ASCE etc.

Page 1

<!-- p. 2 -->

Speaker(s)

Safet Iska, a proud Civil engineer & pioneer who is striving to solve customer questions and
help them improve the way of working mainly within Autodesk´s BIM-products. A technical
sales manager acting within the AEC area in the Nordic market at Symetri AB. Safet Iska is
specialized in FEM-software’s primary working with Autodesk solution Robot Structural analysis.
Influencing the customer to adapt a new perspective of the word FEM and a more connected
BIM-workflow with Revit and Advance Steel.

Email: safet.iska@symetri.com

Page 2

<!-- p. 3 -->

Graphical overview of the design process submitted with RSA and Revit

It is critical for a user to understand which process could be used when we are striving to use
the integration between Autodesk softwares, in this case particular Revit – Robot.

Which barriers do we tear down with this integration?

For a Structural engineer, it is of importance to eliminate specific obstacles when working in a
project. For instance, to specify information twice, remodel the structure for a certain analyze
and submit changes after they are made which is occurs quite often in projects.

Below you can find a work-process which could be implemented after understanding this
process and which time-consuming moments can be eliminated by using Autodesk solutions.

Design Analysis Optimization Detailing Documentation Fabrication

Page 3

<!-- p. 4 -->

\1. Keywords

Analytical line – Each structural object in Revit will provide us with a analytical line. A line
placed in the center of the 3D geometry. This is the data that our FEM-software focus on.

Two-way communication – Possibility to transfer specific data from one environment to
another and later update it back with different data to the same source.

Load take-down calculation – Calculation of the forces acting from the top of the structure to
the ground.

Claddings – A object which acts as a surface and doesn’t contain any weight, its purpose is to
provide us with more accurate load transfer.

Maps – Solution to present static results by color, forces such as moment, shear and normal
forces.

Optimization – Enhance the objects performance so the loads applied on it is not causing too
great strain and overcome the bearing capacity of the object.

Page 4

<!-- p. 5 -->

\2. The link between Robot Structural analysis and Revit

We will start by visualizing the export/update button for starter in both Revit and RSA.

RSA

Take these following steps: Add-Ins > Integration > Autodesk Revit Structure

Revit

Similar steps will be needed in Revit as well: Analyze > Robot Structural Analysis link >

Once we have done the transfer from Revit to Robot the model will be completely dependent on how well
we have prepared the analytical model. It is very important to have the lines connected so we can get an
accurate load transfer from one object to another, that’s how we can finalize the total behavior of the
structures deformation, critical points etc.

Page 5

<!-- p. 6 -->

\3. Preparing the model in Revit

Revit will also assist us in the analytical part by defining constraints for the analytical lines. If we for
instance have applied an offset in the analytical model settings, Revit will automatically connect 2
nodes if they are located within the defined distance.

Additional function which have great impact on this workflow is Steel design from a third-party
product called Naviate Structure. Previous experience has revealed that when we have several
engineers working towards a central file in the same project there might appear accidental
change. Should we move one object and others will follow, the exact height on similar objects is
also something which benefits us in the calculation phase.

This solution helped us secure that there weren’t any accidental changes on the steel frames.
By analyzing our current status of steel frames/objects we could easily follow if that model still
was identical later on in the modelling phase.

Page 6

<!-- p. 7 -->

A project sample of Steel design function is described below.

Page 7

<!-- p. 8 -->

\4. Design-phase in Robot Structural Analysis

When we finally have completed our Revit model and done a quick check that no surprising
changes appear then we can export our model to Robot. Take to account that when the export
is finalized it might be a good step to check so all our profiles do have the right physical data.
Such as profile geometry, steel quality and releases so we can adjust missing part and receive
a good calculation performance.

Easy step to filter this data can be done with bar selection tool as in the following picture below.

When we later have completed the model check we can start the calculation part of the static forces. I will
highly recommend that we start by doing a quick calculation with just a dead load to assure that we do not
get warnings that will be critical for the results. If that step is ok then we can proceed with the correct
load-cases and combination.

To include combinations and a lot of load-cases in the calculation will lead to a longer calculation time
which will be very time consuming if we bump into some problems we must correct.

In this particular case, we used claddings on rooftops instead of doing a manual calculation of the linear
loads on each beam. With claddings, we can easily apply surface loads on it and robot will automatically
calculate the linear load for us in each beam. We can also define how the load-transfer should behave,
which objects should take up load and which shouldn’t.

Page 8

<!-- p. 9 -->

The next step will allow us to examine the results such as moments, normal-/shearforces and reaction
forces which will define the loads the piles will carry.

Page 9

<!-- p. 10 -->

\5. Concrete design – Reinforcement

Concrete objects were further detailed in Robot, as our customer wished for fabric area reinforcement on
the slabs we took that into consideration when we executed the calculation for reinforcement.

With Slab required reinforcement we could see which requirements was needed to fulfill the demands,
this is presented by maps.

After we received the required reinforcement we could easily go further to Provided Reinforcement and
define which fabric area we wished for and apply it to the plate.

The configurations for the slab will be defined in Calculation options and Reinforcement pattern.

Page 10

<!-- p. 11 -->

After performing these steps, we now could get an estimated value of how many Fabric reinforcement net
(K257) we needed to get an accepted solution. The reinforcement was manually placed in the Revit.

For the foundation beams we used similar method as with the frames where we change the slabs to
claddings and could receive the linear loads which is distributed to the beams. In that way, we could
perform a reinforcement calculation, unfortunately this part was done manually after we received the right
linear loads.

Page 11

<!-- p. 12 -->

\6. Steel design - Optimization

The optimization phase of the steel objects was managed under steel design. First step is to apply right
parametric behavior of each system, such as columns, beams and trusses. If the calculation shall be
accurate we must apply defined member type on the objects.

To be able to have more control of the objects we decided to divide the objects into groups for the
optimization. We had specific groups for columns, one for trusses and another one for the beams. The
optimization is a process which is performed in several iterations to finalize a complete utilization of the
objects.

Page 12

<!-- p. 13 -->

After creating our groups, we could then define how Robot should optimize the objects, by a type of
section, weight etc.

At last we could finally press calculations button to get an overview of the verification.
All the objects that had an utilization of more than 100 % were increased in section and those with low
utilization was decreased, because of esthetic part was a thing we wanted to maintain we instead used
the same type section for the certain frame, we didn’t want to have different size of the section on the
same frame.

Page 13

<!-- p. 14 -->

\7. Back to Revit from Robot

In this case because of the large number of objects and changes with sections and movements we
decided to perform this step in several updates so we don’t get too big changes on the model which will
be too hard to control.

Observe when we update back the objects which has been exported to Robot from the start it is very
important that we do it by opening Revit and select which objects should be updated and then update.

If we press send model from Robot to Revit then we will force the new Robot model into the opened Revit
file and there will appear two models. This step is something we only use when we have added new
objects in Robot which doesn’t include in the Revit model.

Export steps when we have added objects in Robot that needs to be transferred to Revit.

Page 14

<!-- p. 15 -->

\8. Conclusion

By implementing this integrated workflow between Revit and Robot Structural analysis Autodesk´s
solution offers the engineers a complete and unique opportunity. The workflow allows us to eliminate
several time-consuming and unnecessary phases between the modelling and calculation span. Steps
we can eliminate which can be confirmed after this project scenario is following (see below).

✓ Remodel the structure.

✓ To manually calculate distribution of loads to each frame.

✓ Generate a lot of manual combinations and find out which one is the right combination for the

specific case.

✓ After optimization submit changes back to the modelling tool.

It happens that the engineers often must manually calculate the load take down for the structure. This

happens to be done by using simple 2D drawings as reference where we must measure distances

between the bearing objects. If the project is a multi-story building then this must be done for each

floor and it takes more time then we really need to put down. A great benefit with 3D FEM-software’s is

that the engineers get a full overview of the structures behavior and in early steps finds out the

weaknesses of the structure. Now that the 3D model can be exported to a FEM environment, that

gives us a great leap forward and leaves the engineer to dump the 2D drawings and plan views from

the designer and can directly focus on the loads calculation process.

\9. References

Document

http://bimandbeam.typepad.com/files/linking-autodesk-revit-and-robot-structural-analysis-professional.pdf

Get going with Robot Structural analysis – Symetri AB

Video

https://www.youtube.com/watch?v=bhEaucg3EBs

https://www.youtube.com/watch?v=ksLjZd62DoY&index=10&list=PLY-

ggSrSwbZqow_60fiqJwS69mg1nQMzk

Page 15
