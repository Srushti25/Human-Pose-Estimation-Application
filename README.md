# Human-Pose-Estimation-Application
Here we have barely scratched the surface of pose estimation’s techniques and use.
We have made use of opencv, tensorflow module and basic posenet module.

We have implemeneted 2D SPPE which accepts RGB image as input with approach of Bottom up

Single-person pose estimation (SPPE) is the easier, with the guarantee of only one person present in the frame. 
Models working on RGB-only input have a huge advantage over others in terms of the mobility of the input source.
2D Pose Estimation is predicting the location of body joints in the image (in terms of pixel values). 

Every pose estimation algorithm agrees upon a body model beforehand. It allows the algorithm to formalize the problem of human pose estimation into that of estimating the body model parameters. Most algorithms use a simple N-joint rigid kinematic skeleton model (N is typically between 13 to 30, we have taken 19) as the final output.

Bottom up approaches involve first detecting the parts or joints for one or more humans in the image, and then assembling the parts together and associating them with a particular human. In simpler terms, the algorithm first predicts all body parts/joints present in the image. This is typically followed by the formulation of a graph, based on the body model, which connects joints belonging to the same human. Integer linear programming (ILP) or bipartite matching are two common methods of creating this graph.

There are 3 application we have implemented
1. Pose detection
2. Eye filter
3. Kids game

OBJECTIVES

● To identify, locate and track the key points of Human Pose Skeleton

● To use and apply the results of PoseNet with real life applications.

CONCEPTS REQUIRED

● Basic Tensorflow

● Python Programming
  
