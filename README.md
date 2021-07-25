# House-Price-Prediction
This repository includes train, test and dataset descrpition and py-notebook files. This project is a regression
task which predicts the price of houses. 

Support Vector Machines(SVM) is an ubequitous, versatile and powerful supervised ML algorithm applicable in linear/non-linear classification, regression, and sometimes in outlier detection. Linear-SVM classifier, type of SVM for linearly separable data, functions by finding the $n$-dimensional "maximum margin hyperplane", where $n$ is the attributes in dataset. The objective function for hard-margin linear SVM with dataset $D=\{\mathbf{x}_i, y_i\}$ for $i=1, 2, \cdots, m$ is shown in Eqn(1) solved using quadratic programming, where $\mathbf{w}$ and $b$ are coefficients of linear classifier.

$$
\begin{align}
\min_{\mathbf{w},b}& \hspace{2 mm} J(\mathbf{w}, b) =  \frac{1}{2}||\mathbf{w}||^2 = \frac{1}{2}\mathbf{w}^T\mathbf{w} \tag{1} \\
\text{Subject to}:&  \hspace{2 mm} y_i(\mathbf{w}^T\mathbf{x}_i+b)\geq 1 
\end{align}
$$
