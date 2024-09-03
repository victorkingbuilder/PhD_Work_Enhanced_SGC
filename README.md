# Final Project Work
We reviewed and ran simulations on the Simplified Graph Convolution (SGC) model as proposed in the referenced paper. This involved developing the model and simulating results using synthetic datasets, including the Karate Club and Email Enron datasets. We recorded time and memory utilization, as well as CPU and GPU utilization. However, we identified limitations, particularly in terms of influence spread, when considering the temporal nature of graphs and their heterogeneity.

We explored the possibility of stress-testing the model by using higher dimensionality for K_MAX, which represents the number of steps and epochs. We conducted this test on the synthetic dataset, Karate Club, and Email Enron, expanding the matrices to 80x80. During this process, we recorded time and memory utilization, as well as CPU and GPU utilization, and identified the model’s point of convergence.

We expanded the study by considering the temporal dynamics and heterogeneity of graphs. To do this, we utilized the Flux machine learning framework, which abstracts much of the complexity of graph networks. We extended the SGC models by introducing time and location factors to account for dynamic and heterogeneous characteristics.

We selected the Julia programming language for our implementation due to its capability in abstracting graph neural networks effectively.

We heavily utilized the 'FluxML' and 'GeometricFlux.jl' libraries for our implementation, leveraging their strengths in machine learning and graph network processing.

We optimized our implementation by using the MLDatasets library in Julia to define the characteristics of our datasets. The graph datasets used included Cora, PubMed, and CiteSeer, while miscellaneous datasets like Iris were also considered. Additionally, we utilized text datasets for language models and vision datasets such as MNIST, CIFAR-10, and CIFAR-100.

We provided a theoretical foundation for the dynamic nature of graphs, incorporating time and heterogeneity by factoring in location-based characteristics.

We conducted a detailed review of a paper that elaborates on the dynamic nature of graphs, particularly in relation to temporal factors.

We applied the newly derived model to synthetic datasets, the Karate Club dataset, and the MNET dataset, where we observed significant improvements in execution time, processor utilization, and overall model performance.

We further developed mathematical formulations to address the heterogeneous nature of graphs using location data.

We examined existing research that extensively addresses geospatial characteristics in solving real-world problems.

Finally, we tackled the challenges of heterogeneity using synthetic data, the Karate dataset, and additional datasets from the MLDatasets library.
