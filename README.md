# Aryan Hood

Final-year B.Tech · Pune, India · **Efficient, Physics-Informed & Calibrated ML for Edge Perception and Physical Systems**

My work studies how physical inductive biases, nested width/precision compression, and distribution-free conformal calibration behave when models move out of i.i.d. splits into kilobyte-scale edge deployments and non-stationary physical regimes. Every project below pairs leak-free multi-seed or SHA-256 shared-environment evaluation with documented negative results and automated test/CI gates.

---

## Selected Research & Systems

| Project | Core Problem & Method | Verified Quantitative Outcomes | Artifacts & Links |
|---|---|---|---|
| **[BearingBench (`shm-bearing-dataset`)](https://github.com/aryanhood/shm-bearing-dataset)** | Envelope-first Computed Order Tracking + single-training `MatryoshkaOrderCNN` (`d ∈ {8..128}`) + static QDQ INT8 ONNX + Online ACI conformal control over 100 real `.mat` recordings (CWRU & uOttawa, 5 seeds). | `96.02% ± 0.52%` unseen-speed Order-CNN (`+7.61 pp`, 95% CI `[+6.61, +8.58] pp`, McNemar `p < 1e-10` vs. Time CNN); `35.77 KB` INT8 at `92.93%` (`0.12 ms` CPU); Online ACI `+22.88 pp` coverage recovery (`50.16% -> 73.04%`) under unseen CWRU spall diameters. | **[Technical Report (PDF)](https://github.com/aryanhood/shm-bearing-dataset/blob/main/paper/technical_report.pdf)** · **[LaTeX](https://github.com/aryanhood/shm-bearing-dataset/blob/main/paper/technical_report.tex)** |
| **[Hawk-Eye Lite (`hawkeye-lite`)](https://github.com/aryanhood/hawkeye-lite)** | Vectorized 12-configuration court homography, consensus multi-view DLT 3D triangulation, multi-plane KNN outlier rejection, sub-frame RK4 physics, and oblique skid-footprint line calling. | 300-case 2D-pixel-only benchmark (`sigma = 1.0 px`, `6%` `±80 px` clutter): `31.27 mm` 4-Cam / `52.64 mm` 2-Cam median bounce error vs. `2708.21 mm` 1-Cam parallax; `+6.61 pp` tight-call gain from skid ellipse; `92.65%` Python branch coverage. | **[Benchmark Report](https://github.com/aryanhood/hawkeye-lite/blob/main/docs/benchmark.md)** · **[Web Studio](https://github.com/aryanhood/hawkeye-lite/tree/main/web)** |
| **[Thermal Sentinel (`thermal-sentinel`)](https://github.com/aryanhood/thermal-sentinel)** | Paired discrete-event benchmark on SHA-256 shared environments comparing Fixed patrol vs. Greedy EWMA, Risk-Adaptive EWMA, Page CUSUM, and a 3-state Bayesian HMM sequential detector across 700 scenarios & a 12-regime sensitivity sweep. | 3-State Bayesian HMM achieves `16.0 s` median confirmation (`17.01 s` faster than fixed) at `0.09` false alarms/hr vs. `6.57`/hr EWMA (`100%` SLA compliance); `48` tests (`97.56%` Python branch coverage). | **[Benchmark Report](https://github.com/aryanhood/thermal-sentinel/blob/main/docs/benchmark.md)** · **[Pareto Plot](https://github.com/aryanhood/thermal-sentinel/blob/main/assets/pareto_sensitivity.png)** |
| **[Self-Balancing Control (`self_balance_robot` · `eyantra-kb_3323`)](https://github.com/aryanhood/self_balance_robot)** | Continuous Algebraic Riccati (CARE) LQR vs. filtered PID disturbance rejection, symbolic Jacobian linearization, complementary IMU filtering, and stability invariant testing. | `-32.0%` squared control effort and `-37.0%` squared angle error vs. PID under `0.1 rad` impulse disturbance; controllable-subspace Hurwitz & CoppeliaSim (`eYRC KB #3323`) control modules. | **[LQR Validation](https://github.com/aryanhood/self_balance_robot)** · **[eYRC KB #3323](https://github.com/aryanhood/eyantra-kb_3323)** |

---

## Technical Stack

- **ML, Edge Deployment & Uncertainty:** Python, PyTorch, ONNX / ONNX Runtime (static QDQ INT8), Scikit-Learn, NumPy, SciPy, Hypothesis property testing
- **Vision, Control & Web:** OpenCV, Multi-View DLT & Homography Geometry, Control / SymPy, C/C++, TypeScript, React 19

---

## Links

- **GitHub:** [github.com/aryanhood](https://github.com/aryanhood)
- **LinkedIn:** [linkedin.com/in/aryanhood](https://www.linkedin.com/in/aryanhood/)
