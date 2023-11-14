This repo contains configuration information and some example trajectories of environments.

AtropineEnv
-----------

The files are mainly ODE-model configurations. If you don't want to change the ODEs of the AtropineEnv, you should not change them.

initial state configuration of the atropine environment. The z0.txt has a dimensionality of 30, and the x0.txt has a dimensionality of 1694. z0.txt represents the states that are monitorable by sensors (flow rates, etc.) x0.txt are mostly intermediate states that are not directly visible or very costly to make visible. U.mat and model.npy are used by the Atropine model (the ODEs).