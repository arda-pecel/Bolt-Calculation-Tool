# Bolt-Calculation-Tool

 Bolt Friction Calculator Technical Documentation

  1. Single Calculation Mode
        --------------------------
        Calculates adjusted pretension force (F_adj) and coefficient of friction (μ) 
        using initial (M1) and final torque (M2).

        Formulas:
        - Axial displacement: ΔL = (A * P) / 360
        - Pretension force: F = (ΔL * S * E) / L
        - Adjusted pretension: F_adj = F * (1 + M1/M2)
        - Coefficient of friction: T = 0.5 * ds * F * tan (tan^-1 (P / (π * ds) + tan^-1 (μ / cos(30))) + 0.25 * (Dp + dp) * F * μ
        which solves numerically

        2. Group Test Mode
        ------------------
        - Enter group names and samples for each group
        - Common torque values (M1 and M2) used for all samples
        - Results displayed with statistical analysis


        ![image](https://github.com/user-attachments/assets/0f44cbaa-4a50-4caf-acdc-1caa748eba57)

        ![image](https://github.com/user-attachments/assets/4e63c50b-c500-4722-8467-f57b0f0c0a54)


    
