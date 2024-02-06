## Evolution strategy algorithm:

1. **Initialization (t=0)**:
   - Set \( t = 0 \).

2. **Initialize Population**:
   - Initialize the population \( P_t \) with \( \mu \) random individuals from \( \mathbb{R}^n \).

3. **Iterative Evolution**:
   - While the stopping condition is not met, do:
     1. **Offspring Generation**:
        - Determine individuals from \( P_t \) with equal probability to obtain \( \lambda \) offspring.
     2. **Mutation**:
        - Perform mutations on offspring.
     3. **Fitness Evaluation**:
        - Calculate the fitness-function of the offspring.
     4. **Selection**:
        - Select the best individuals and descendants based on the fitness-function values, and create \( P_{t+1} \).
     5. **Update Generation Count**:
        - \( t = t + 1 \).
