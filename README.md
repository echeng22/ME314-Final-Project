##### Project was completed for ME314: Theory of Machines - Dynamics.

The purpose of this project was to simulate the dynamics of a swinging whip hitting a falling block using the material taught in the course. This included describing the dynamics of the system using the Euler-Lagrange equations, how impacts can affect the system, and how rotational inertia can change due to impacts.

The equation below describes the Lagrangian (L), where T represents the kinetic energy of the system and V represents the potential energy of the system.

$$
\begin{align*}
L = T - V
\end{align*}
$$

We use the Euler-Lagrange equations to solve for the equations of motion of the system, described below.

$$
\begin{align*}
\frac{d}{dt}(\frac{\partial L}{\partial \dot{q}}) - \frac{\partial L}{\partial q} = 0
\end{align*}
$$

Finally, in order to describe the impact that occurs between, we must first solve for when the geometries of the block and the tip of the whip overlap. Using this time of impact, we can find the position and velocities of the whip and block at that time, and solve for the change in velocities after impact using the impact equations described below.

$$
\begin{align*}
\frac{\partial L}{\partial \dot{q}}|^{\tau +}_{\tau - } = \lambda \frac{\partial \phi}{\partial q}
\end{align*}
$$

$$
\begin{align*}
[\frac{\partial L}{\partial \dot{q}}\cdot\dot{q} - L(q,\dot{q})]^{\tau +}_{\tau - } = 0
\end{align*}
$$


Plugging in the velocities after impact into the equations of motion of the system will then describe how the system will continue to behave after impact.

The video image links below shows the simulation of this system slowed down so impact and changes in the system are seen. All video and coding done for this project was done in Mathematica. Source code and write up can be found at this [link]{:target="_blank"}.
<div style="text-align:center">
    <a href="http://www.youtube.com/watch?v=Bayp_y6na8A" target="_blank">
        <img src="http://img.youtube.com/vi/Bayp_y6na8A/0.jpg" alt="Full View of Project" align="middle"/>
    </a>
</div>
<div style="text-align:center">
    <a href="http://www.youtube.com/watch?v=BokumHZa_Mo" target="_blank">
    <img src="http://img.youtube.com/vi/BokumHZa_Mo/0.jpg" alt="Closer View of Project"/>
    </a>
</div>

