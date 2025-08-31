# Mixture of Contexts (MoC)

**Definition:** A novel, learnable sparse attention mechanism designed for efficient long video generation. It treats long-context attention as a retrieval problem, intelligently routing queries to a small subset of relevant historical data ("chunks") rather than attending to the entire context.

Category: [[Technologies]]

Alias: MoC

Source: [[Bibliography - Project Chimeras Fire Sources v1.2|ByteDance/Stanford Paper (2025)]]

### Key Innovations:

- **Learnable Sparse Attention Routing:** Employs a non-parametric but learnable router to select informative history chunks for attention calculation.
    
- **Massive Efficiency Gains:** Achieves approximately **7x fewer FLOPs** and **85% attention pruning** in minute-long video generation tasks.
    
- **Architectural Shift:** Solves the quadratic scaling problem of dense attention with an algorithmic solution, reducing the reliance on massive hardware for long-context tasks.