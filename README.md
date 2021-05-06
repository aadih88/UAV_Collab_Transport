# Multi-UAV Collaborative Transportation of Payloads with Obstacle Avoidance
The repository contains figures and an animation of a pair of UAVs transporting a rigid elongated payload as they maneuver through obstacles in the environment.<br>
**Simulation details:**<br>
Number of obstacles, <img src="https://render.githubusercontent.com/render/math?math=M = 3"><br>
Initial position of UAV 1, <img src="https://render.githubusercontent.com/render/math?math=\mathbf{p}_1 = [0,4]^T\ \text{m}"><br>
Initial position of UAV 2, <img src="https://render.githubusercontent.com/render/math?math=\mathbf{p}_2 = [0,2]^T\ \text{m}"><br>
Initial distance between UAVs, <img src="https://render.githubusercontent.com/render/math?math=l = 2\ \text{m}"><br>
Position of target (T), <img src="https://render.githubusercontent.com/render/math?math=\mathbf{p}_T = [7,0]^T\ \text{m}"><br>
Radius of standoff circle about target for UAV 1, <img src="https://render.githubusercontent.com/render/math?math=R_1 = 1\ \text{m}"><br>
Radius of standoff circle about target for UAV 2, <img src="https://render.githubusercontent.com/render/math?math=R_2 = 3\ \text{m}"><br>
Control gain for standoff circle tracking, <img src="https://render.githubusercontent.com/render/math?math=K_T = 0.8"><br>
Gain for CBF obstacle avoidance constraint, <img src="https://render.githubusercontent.com/render/math?math=\gamma = 5"><br>
Control input bound, <img src="https://render.githubusercontent.com/render/math?math=u_{\text{max}} = 0.5\ \text{m/s}"><br>
Angular rate bound about UAV 2, <img src="https://render.githubusercontent.com/render/math?math=\omega_{\text{max}} = 0.2\ \text{rad/s}"><br>
<br>
Payload mass <img src="https://render.githubusercontent.com/render/math?math=m = 1\ \text{kg}"><br>
Payload moment of inertia <img src="https://render.githubusercontent.com/render/math?math=J = 0.33\ \text{kg-m}^2"><br>
Mass of UAVs <img src="https://render.githubusercontent.com/render/math?math=m_1,m_2 = 1\ \text{kg}"><br>
Gain for velocity-based control <img src="https://render.githubusercontent.com/render/math?math=K= 2"><br>
<br>
Obstacle circular buffer region positions and radii:<br>
1) <img src="https://render.githubusercontent.com/render/math?math=\mathcal{O}_{1}: \mathbf{p}_{o_1} = [2,1]^T\ \text{m}, R_{o_1} = 0.9\ \text{m}"><br>
2) <img src="https://render.githubusercontent.com/render/math?math=\mathcal{O}_{2}: \mathbf{p}_{o_2} = [2,3]^T\ \text{m}, R_{o_2} = 0.5\ \text{m}"><br>
3) <img src="https://render.githubusercontent.com/render/math?math=\mathcal{O}_{3}: \mathbf{p}_{o_3} = [3.5,2.5]^T\ \text{m}, R_{o_3} = 0.7\ \text{m}"><br>
