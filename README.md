# Data-driven-feedback-control
This repository contains the attempt for proof for the convergence of data driven feedback control algorithm with the strong convexity assumtption made on 
the discretized gradient. 

The algorithm was first proposed in the Archibald etal (https://link.springer.com/article/10.1007/s10915-020-01358-y)

One can observe that the diffusion process/estimated control gets closer to the true process/control as the size of the particle cloud gets larger. 
The first and the second image detail the controls obtained from running the algorithm with 16 and 512 particles.
![dim1_control_S16](https://user-images.githubusercontent.com/107137651/173209432-90db48b3-d0a5-40e1-9fb1-c8e625a6ae53.png)
![dim1_control_S512](https://user-images.githubusercontent.com/107137651/173209387-4d436ce0-c787-496e-a424-6157a84e5d97.png)

The following two images detail the X obtained from running the algorithm with 16 and 512 particles.
![dim1_X_S2](https://user-images.githubusercontent.com/107137651/173209390-3736a382-5e3c-401e-be4c-b12bd6c3975c.png)
![dim1_X_S512](https://user-images.githubusercontent.com/107137651/173209392-e7eec22d-450e-4037-8022-8796e1f61fbe.png)
