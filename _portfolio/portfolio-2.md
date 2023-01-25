---
title: "Bouncing Robots: Mobile Robots with Structured Boundary Interactions"
excerpt: "My Ph.D. work focused on exact, nondeterminism-aware motion planning algorithms
for simple mobile robots that can reorient at environment boundaries with
knowledge of the boundary geometry. <br/><img src='/images/bounce_images.gif' width='500'>"
collection: portfolio
---

My Ph.D. work included a deep dive into discrete dynamics, control, and motion planning 
for *bouncing robots*: mobile robots that have structured
interactions with boundaries of their environment. Examples include robot
vacuums that bump into walls to guarantee coverage of an entire room;
[micro-organisms](https://www.youtube.com/watch?v=wGNGCOhFHeE) and
micro-robots; or a fixed-wing drone making straight passes over a forest and
only turning when it reaches the edge.

My approach involves computing discrete representations of the geometry and dynamics of 
robot trajectories in a given environment. By establishing equivalence classes over the
environment and control spaces, we allow for nondeterminism and uncertainty
at the planning stage and still compute plans that have analytical guarantees on
their stability and long-term dynamical behavior. This allows us to use the intrinsic, messy dynamics of the robot to
engineer robust high-level behaviors such as navigating or patrolling a space,
and even object manipulation.
