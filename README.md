# Improvised-HGS-Algorithm
> Nature-inspired computing is a technique that is inspired by processes, observed from nature. These algorithms are subject to computational intelligence. The purpose of developing such algorithms is to optimize engineering problems. As the world moves towards industrialization, engineering problems are becoming more complex and difficult to optimize. This is because of increasing dimensions, variables, time complexity, space complexity, etc. To cope up with such a situation, nature-inspired algorithms are designed to optimize numerical benchmark functions, multi-objective functions and solve NP-hard problems for a large number of variables, dimensions, etc. Nature-inspired algorithms are a set of novel problem-solving methodologies and approaches and have been attracting considerable attention for their good performance. Several real-world optimization problems have been studied by several nature-inspired algorithms. 

## Problem Statement
> In this project, we aim to develop an enhanced version of a nature-inspired algorithm, Hunger Games Search algorithm, to compensate for its drawbacks. K-means algorithm will be used to test its efficacy.

## Hunger Games Search Algorithm
> Hunger games search (HGS) was proposed in 2021, and it is a performance-based swarm optimization method, which has a strong performance compared to many optimizers and DE variants in studied benchmark problems. HGS simulates the logic of collaborative interactions based on individual hunger.  In each iteration, the algorithm searches around the optimal location, in the same manner, that animals forage, where the weights, or hunger values, mimic the impact of hunger on an animal’s individual activity. 

## Improvised Algorithm design
>* Aiming at the shortcomings of the hunger search, such as low precision, low optimization dimension, and mainly slow convergence speed, two improved versions of HGS have been developed. One version is based on Cauchy flight, and the other version is based on Levy flight.
>* A Lévy flight is a random walk in which the step-lengths have a Lévy distribution, a probability distribution that is heavy-tailed. The term "Lévy flight" originates from the fact that the distribution of step sizes is a Levy distribution. For the case where the distribution of step sizes is a Cauchy distribution, it is called Cauchy flight. 

## Testing the improvised algorithm
> * Qualitative analysis of the algorithm was carried out using four indicators, including search history, the trajectory of the first dimension, average fitness, and convergence curve. 
> * The proposed Hunger Games Search (HGS) versions were validated on a comprehensive collection of 30 benchmark functions and IEEE CEC2014 functions. 
> * The Wilcoxon sign rank test was utilized to assess the statistical significance between the two modified versions of HGS and other well-known metaheuristic algorithms. 
> * The experimental results show that the version of HGS improvised using Levy flight has an efficient searching ability compared with other algorithms, and it can quickly find and develop the target solution space. Overall, LevyHGS is very good at balancing exploration and exploitation. 
> * To confirm the improved performance of the modified versions, each algorithm was then tested with k-means clustering to see which version performed better. From the experimental results, LevyHGS can satisfy the optimization effect.

## Conclusion
> In this project, we followed the most straightforward rules for developing HGS to make it easier to expand and integrate with existing artificial intelligence methods. There are many windows for the future directions of this new efficient HGS algorithm. First, researchers can investigate the effectiveness of this open-source HGS code for solving real-world problems in parameter optimization for machine learning models, binary feature selection, and image segmentation. Another window is how to enhance the performance of the basic version proposed in this research. Lastly, the proposed Hunger Games Search is a single-objective approach in the currently released version, and the next task can be to develop the binary, multi-objective and many-objective variants of the developed Hunger Games Search to deal with more variety of multi-objective, binary, and many-objective problems.
