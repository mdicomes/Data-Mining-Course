Data Mining Coursework

A collection of homework assignments completed for a Data Mining course at the University of New Mexico, demonstrating foundational and intermediate data science techniques applied to large, high-dimensional datasets.

Assignment Descriptions

Euclidean Distance & Wavelet Transform -
Computes pairwise Euclidean distance matrices on a large, high-dimensional dataset (16,000 rows × 128 features) using multiple approaches including block-based computation for memory efficiency. Applies a Haar wavelet transform to reduce dimensionality to the first four coefficients and evaluates the impact on distance calculation speed and accuracy.
Key skills: Distance matrix computation, z-normalization, wavelet-based dimensionality reduction, computational efficiency

Perceptron with 5-Fold Cross-Validation -
Implements a perceptron classifier from scratch — without machine learning libraries — on a high-dimensional binary classification dataset. Uses 5-fold cross-validation to evaluate model performance and reports accuracy and convergence behavior across folds.
Key skills: Manual perceptron implementation, weight updates, learning rate tuning, cross-validation, model evaluation

Cluster Analysis using PAM (Partition Around Medoids) -
Implements the PAM clustering algorithm (BUILD and SWAP phases) on a high-dimensional dataset. Uses PyTorch with GPU acceleration to compute pairwise Euclidean distance matrices efficiently at scale, significantly reducing computation time compared to CPU-based approaches.
Key skills: Medoid-based clustering, GPU-accelerated computation with PyTorch, large-scale distance matrix computation, cluster evaluation

Outlier Detection with Pruning -
Identifies the most outlying object in a large, high-dimensional dataset (16,000 rows × 128 features) using a nearest-neighbor distance approach. Benchmarks four configurations — no pruning, pruning step 1 only, pruning step 2 only, and both pruning steps — to evaluate the computational efficiency gains of each strategy.
Key skills: Outlier detection, pruning strategies, computational benchmarking, z-normalization, reference-based distance optimization

Technologies Used

Python 3,
NumPy — numerical computation and matrix operations,
Pandas — data loading, cleaning, and manipulation,
PyTorch — GPU-accelerated distance computation (HW3),
Jupyter Notebooks — development and documentation environment


Course
Data Mining — University of New Mexico

Notes -
All implementations are built from scratch where specified by the assignment, without relying on high-level machine learning library abstractions. This was intentional to demonstrate understanding of the underlying algorithms.
