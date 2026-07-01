
### 1. Fundamental Arithmetic & Transformations

- **Matrix Multiplication (Dot Product):** Understanding how rows combine with columns. Essential for change of basis, coordinate transformations, and state space transitions.
    
- **Matrix Transpose ($A^T$):** Flipping a matrix over its diagonal. Crucial for symmetric matrices, tensor analysis, and optimization algorithms.
    
- **Matrix Inversion ($A^{-1}$):** Solving the system $Ax = b$ as $x = A^{-1}b$. Crucial for understanding system reachability and solving static equilibrium equations.
    

### 2. System Characteristics & Solvability

- **Determinant ($\det(A)$ or $|A|$):** Measures the scaling factor of the transformation. A zero determinant indicates a singular matrix (no unique inverse), which physically signifies mechanism lockup, structural collapse, or unresolvable systems.
    
- **Rank and Nullity:** * **Rank:** The number of linearly independent rows or columns (indicates the true dimensionality of the system).
    
    - **Null Space (Kernel):** The set of all vectors that map to zero ($Ax = 0$), representing internal degrees of freedom or unconstrained movements.
        

### 3. Spectral Decomposition & Modal Analysis

- **Eigenvalues and Eigenvectors ($Ax = \lambda x$):** * **Eigenvectors:** Directions that do not change orientation under a linear transformation.
    
    - **Eigenvalues:** The scaling factor along those directions.
        
    - _Engineering Use:_ Essential for vibration analysis (natural frequencies), structural stability (buckling modes), and Principal Component Analysis (PCA).
        
- **Matrix Diagonalization ($A = PDP^{-1}$):** Decoupling coupled systems of differential equations into independent equations that can be solved individually.
    

### 4. Advanced Matrix Factorizations (Decompositions)

- **LU Decomposition ($A = LU$):** Factoring a matrix into Lower and Upper triangular matrices. Used numerically by solvers to efficiently compute solutions to $Ax = b$ and find determinants.
    
- **QR Decomposition ($A = QR$):** Factoring a matrix into an orthogonal matrix ($Q$) and an upper triangular matrix ($R$). Used for stable least-squares solutions and finding eigenvalues.
    
- **Singular Value Decomposition (SVD) ($A = U \Sigma V^T$):** The generalization of eigendecomposition to non-square matrices. Critical for data compression, noise reduction, and dimensionality reduction.