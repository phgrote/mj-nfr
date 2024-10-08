# MJ-NFR: Neural Field Representations for State Estimation of Multi-Joint Objects

## Abstract
Learning to operate complex tools and heavy machines with complex kinematic structures, 
such as cranes and excavators, requires the robotic agent to reason about the underlying joint states. 
Traditional approaches rely on the assumption that the joint states, can be measured. 
But many machines are not equipped with the required sensors, and it would be costly to retrofit them. 
In this paper, we propose MJ-NFR a framework for inferring Multi-Joint Neural Field Representations 
from (multiple) RGB-observations. The framework is capable of generating different outputs such as RGB-images, 
depth images and pixelwise classifications from a given internal representation. MJ-NFR computes such
representations by iteratively updating randomly initialized latent codes until the loss between 
the real observations and generated outputs has been minimized. 
We show that with this method it is possible to obtain highly accurate joint state estimations even 
for out of distribution input data. Furthermore, we demonstrate that it is possible to 
track the motion of multiple joints only from images in real time using a few gradient descent steps.
## Video <a name="Video"></a>
