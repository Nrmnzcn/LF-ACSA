# LF-ACSA: Levy Flight–Augmented Artificial Circulatory System Algorithm  

### Definition

LF-ACSA is an improved metaheuristic optimization algorithm inspired by the **human circulatory system** and enhanced by **Levy flight dynamics** to improve global exploration and prevent local stagnation.  

The algorithm was used to:
- Optimize **PID controller parameters (Kp, Ki, Kd)** for **DC motor speed control**,  
- Compare performance against **seven benchmark algorithms** (ACSA, DE, EFO, GA, PSO, SCA, SMA),  
- Evaluate robustness under **load disturbance**, **parameter variation**, and **frequency response** analyses.

This repository contains the **Python source codes**, **flowchart**, and **pseudocode** presented in the paper *“Levy Flight–Augmented Artificial Circulatory System Algorithm (LF-ACSA)”*.  



### Key Features  

- 🧠 **Bio-Inspired Framework:** Mimics neural–hormonal regulation of the human circulatory system.  
- 🌀 **Levy Flight Integration:** Heavy-tailed step lengths for enhanced global search.  
- 🔧 **PID Controller Optimization:** Minimizes the *Integral Time Absolute Error (ITAE)* criterion.  
- 📊 **Benchmark Validation:** Tested on 23 classical functions and 12 CEC2022 problems.  
- 🧩 **Robustness:** Verified under multiple DC motor uncertainty scenarios.  
- 📈 **Superior Performance:** Achieved lowest ITAE (0.000414) and zero overshoot under nominal conditions.  



### Publication

You can find the full details of the algorithm in my publication:

- **Title**: Levy Flight–Augmented Artificial Circulatory System Algorithm for optimal PID tuning in DC motor control
- **Authors**: Nermin Özcan, Handan Gürsoy Demir
- **Journal**: AEÜ – International Journal of Electronics and Communications (Elsevier, SCI-Expanded, Q2)
- **DOI/Link**: [10.1016/j.aeue.2025.156101](https://doi.org/10.1016/j.aeue.2025.156101)



### Citation Request

If you use this algorithm in your research, please cite the following paper:

```bibtex
@Article{Ozcan2026LFACSA,
  title     = {Levy Flight–Augmented Artificial Circulatory System Algorithm for optimal PID tuning in DC motor control},
  author    = {Nermin Özcan and Handan Gürsoy-Demir},
  journal   = {AEÜ - International Journal of Electronics and Communications},
  volume    = {204},
  pages     = {156101},
  year      = {2026},
  publisher = {Elsevier},
  doi       = {10.1016/j.aeue.2025.156101}
}

```
