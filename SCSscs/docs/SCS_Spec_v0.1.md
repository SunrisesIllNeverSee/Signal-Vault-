# Signal Compression System (SCS) — Spec v0.1

## Status
Spec-first, public-safe draft.  
Implements **definitions & schema**, not proprietary weights.

## Metrics

### 1. Signal-to-Noise Ratio (SNR)
Ratio of actionable semantic units to total units.  
Extraction via heuristic cues (weights withheld).

### 2. Prompt Complexity
Composite of:  
- Intent breadth  
- Constraint count  
- Dependency depth  

### 3. Session Depth
Longest coherent reasoning chain, normalized by tokens out.

### 4. Cross-Thread References
Count of successful integrations of external context.

### 5. SigDrift Points
Discrete breaks in alignment (topic jumps without bridge).

### 6. Ghost Tokens (Proxy)
Approximation of overhead tokens from tokenizer/system load.

## Roadmap
- v0.2: add inter-rater calibration  
- v0.3: add benchmark datasets  
- v1.0: API interface
