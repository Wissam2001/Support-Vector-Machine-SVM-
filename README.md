# Linear SVM from Scratch: A Mathematical Implementation 📐
This project was developed as a Master's Lab project in Machine Learning, focusing on understanding and implementing the Support Vector Machine (SVM) algorithm from scratch. Instead of relying on scikit-learn's SVM implementation, we manually implemented the linear SVM classifier using gradient-based optimization with hinge loss.

The project demonstrates the complete mathematical foundation of SVMs, including:
- The maximum margin hyperplane concept
- Hinge loss formulation for misclassification
- Gradient descent optimization for weight learning
- Visualization of decision boundaries and support vectors

# Project Objectives 🎯
**Understand SVM theory and master the mathematical formulation of linear SVMs:**
- Hyperplane equation: w·x + b = 0
- Margin maximization: 2/||w||
- Hinge loss: max(0, 1 - y_i(w·x_i + b))
  
**Implement SVM optimization from scratch, build gradient descent with:**
- Regularization term (L2 norm)
- Parameter updates for both weights and bias
- Generate synthetic data - Create linearly separable datasets with make_blobs
- Visualize decision boundaries - Plot separating hyperplane and margins


# Libraries Used 🛠️
- **numpy**	Mathematical operations, matrix manipulations
- **matplotlib**	Data visualization and decision boundary plotting
- **seaborn**	Enhanced plotting aesthetics
- **sklearn.datasets**	Synthetic data generation (only for data creation, not for SVM)

Note: The SVM algorithm itself is implemented entirely from scratch without using sklearn.svm.

# Lesson Learned 💡 
- Maximum margin leads to better generalization than any separating hyperplane
- Hinge loss creates a "safe zone" (margin) where points don't affect the boundary
- Support vectors are the critical points that define the margin
- Regularization (λ) controls the trade-off between margin width and misclassification
- Learning rate selection is critical: too high causes divergence, too low causes slow convergence
- Feature scaling is essential for SVM performance (though our synthetic data was already scaled)

 # License 📝
  This project is for educational purposes as part of a Master's lab assignment.

# Contact ✉️
- **Email:** wissambadia4@gmail.com
- **LinkedIn:** [Badia Ouissam Lakas](linkedin.com/in/badia-ouissam-lakas-a66a28214) 
