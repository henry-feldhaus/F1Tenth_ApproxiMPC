# F1Tenth ApproxiMPC

This repository is the project handoff bundle for the F1TENTH LSTM-vs-MPC comparison work.

It is organized as a small umbrella repo made of submodules:

- `ApproxiMPC/` - original MPC data collection and analysis reference code.
- `lstm_racer/` - ROS 2 LSTM controller package.
- `mpc_racer/` - ROS 2 MPC controller package.
- `controller_benchmark/` - shared benchmark logger and summary tooling.
- `f1tenth_gym_ros/` - F1TENTH gym ROS simulation environment.

Each submodule owns its own setup details. This top-level repo is meant to keep the pieces together in one clean deliverable.
