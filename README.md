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
    
