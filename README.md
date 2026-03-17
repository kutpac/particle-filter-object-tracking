#  Multi-Algorithm Particle Filter Object Tracking

Benchmarking metaheuristic optimization algorithms integrated with 
Particle Filters for real-time object tracking across multiple video scenarios.

##  Algorithms Compared
| Algorithm | Full Name |
|---|---|
| PF | Standard Particle Filter (baseline) |
| PSO-PF | Particle Swarm Optimization + PF |
| FA-PF | Firefly Algorithm + PF |
| SMO-PF | Slime Mould Optimizer + PF |
| MGWO-PF | Modified Grey Wolf Optimizer + PF |
| SMC-PF | Sequential Monte Carlo + PF |

##  Test Videos
- `car_30fps.mp4` — vehicle tracking at 30fps
- `seagull_25fps.mp4` — fast/irregular motion tracking
- `parachute_25fps.mp4` — slow large-object tracking

## Tech Stack
Python · NumPy · OpenCV · Matplotlib
