# MSE_Spring_2026

Course Description:
	Over the last few years, we have moved from talking about machine learning in the abstract to watching it step into the lab and the factory. Startups such as Lila Scientific and Periodic Labs, along with Google, Amazon, Meta, Microsoft and others, are building platforms where algorithms do not just analyze data - they propose experiments, control instruments, and help decide what to do next. However, once ML enters the real world, the questions change. It is no longer enough to train a good model; we must understand how real objects become mathematical abstractions, what structure we impose on them, how we reason about uncertainty, and how we turn all of this into actionable decisions about the next experiment, the next sample, or the next device to build.
	
The conceptual foundation for this course goes back to Eugene Wigner’s famous essay “The Unreasonable Effectiveness of Mathematics in the Natural Sciences.” Mathematics has long given us a way to translate messy reality into equations we can analyze, simulate, and use to guide discovery. This course extends that tradition into the age of ML and automated labs. The real name of this course could be “The Art of Automated Decision Making.”
	
We begin with the scientific Python ecosystem and the classical mathematical tools: linear and nonlinear equations, ordinary and partial differential equations, and basic regression and functional fitting. From there, we move to methods emerging at the interface between data and physics, including Physics-Informed Neural Networks (PINNS), NeuralODEs, and Neural Operators. We follow with Bayesian methods for data analysis and prediction, focusing on how to combine mathematical rigor with prior knowledge and domain beliefs in a transparent and traceable way. We then introduce causal analysis, one of the fastest-growing areas in modern machine learning, and contrast causal reasoning with purely correlative models. In the final part of the course, we focus on probabilistic decision-making under uncertainty - the keystone of automated and autonomous experimentation in chemistry, materials science, and physics. 
	
By the end, you will have hands-on experience in modeling chemical and physical processes, learning physics from observational data, and designing workflows that can drive an autonomous lab of the future. The instructor, Sergei V. Kalinin, has over 15 years of experience applying ML to imaging and materials science at Oak Ridge National Laboratory and spent a year in Amazon’s special projects group, bringing a practical perspective on how these methods operate in real-world settings.

The tentative course outline is:

1. Mathematical Methods in Physical Science
•	Mathematics as the backbone of physical sciences
•	Modeling, data analysis, and hypothesis making
•	Mathematics vs. machine learning and automated decision making
2. Introduction to Python and the SciPy Ecosystem
•	Basic principles of Python and scientific notebooks
•	Cloud and GitHub for reproducible science
•	Numerical and symbolic methods in science (NumPy, SciPy, SymPy, etc.)
3. Classical Numerical Methods with Python
•	Linear systems and basic linear algebra
•	Ordinary differential equations (ODEs)
•	Partial differential equations (PDEs)
4. Regression Methods
•	Linear regression and its variants (robust, multivariate, regularized)
•	Functional fits with Python
•	Symbolic regression
5. Mathematical Representation of the Real World
•	Choosing variables and state spaces (design, control, observation)
•	Scaling, nondimensionalization, and constraints
•	Feature engineering vs. learned representations
•	Similarity, kernels, and distances
•	Representing structured objects (images, spectra, graphs, etc.)
6. Differentiable Modeling and Physics-Informed Neural Networks
•	Automatic differentiation and differentiable programming
•	Neural ODEs and neural PDE surrogates
•	Physics-informed neural networks (PINNs) for forward and inverse problems
•	Hybrid physics–ML models (blending differential equations and neural nets)
7. Bayesian Data Analysis
•	Bayesian and frequentist viewpoints
•	Priors, likelihoods, and posteriors
•	Bayesian inference and uncertainty quantification
8. Causal Methods
•	Principles of causal analysis and graphical models
•	Causal inference (interventions, counterfactuals)
•	Causal discovery
9. Gaussian Processes, Bayesian Optimization, and Active Learning
•	Classical Gaussian processes
•	GP-based Bayesian optimization and acquisition functions
•	Deep kernel learning and scalable GP surrogates
10. Gaussian Processes Meet Physics
•	Structured GPs and physics-informed priors
•	Multifidelity, multitask, and multiobjective methods
•	From active learning to automated experiments
11. Decision Loops, Model-Based Control, and State Estimation
•	Dynamic programming and Bellman equations
•	Stochastic optimization and model-based methods
•	State-space models and Kalman filters (and extensions at a conceptual level)
•	Integration between multiple decision loops and open decision making
12. Use of LLMs for Decision-Making Workflows
•	Deep surrogate models in scientific workflows
•	LLM integration via rewards, priors, and tool use
•	LLMs as planners and orchestrators in automated labs

