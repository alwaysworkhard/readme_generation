# Experimentation on Provable Meta-Learning of Linear Representations for Contextual Bandits
This repository is divided into two main directories: Synthetic and Real-World, to make it easier to evaluate our algorithm on both synthetic and real-world datasets (Movielens and LastFM). 
## Synthetic Data Experiments
In the Synthetic directory, enter the Comparison_Benchmarks folder. Here, you can use the Compare.ipynb to run algorithms with different parameters (d, T) and generate results. Run the plot1.ipynb to see the plot of individual parameter combinations. To perform comparative analysis across multiple parameter sets, run Compare.ipynb with different parameters. Save the results in folders named: d = 100, d = 150, d = 200. Then, use plot2.ipynb to generate bar charts showing the results from these parameters. The Meta-Test folder in the Synthetic directory is for evaluating our performance in transfer learning scenarios. To obtain the plot, run Meta-Test_Compare.ipynb, then plot.ipynb. 
## Real-World Data Experiments
The Real-World directory has two subdirectories: LastFM and Movielens. Each folder is set up to run experiments with the corresponding dataset. To obtain the plots, use the same procedure as in the Synthetic directory. TO evaluate transfer learning performance using the LastFM dataset, save the results in folder named: N_1 = 300, N_1 = 400, N_1 = 500. Then, use the plot.ipynb to visualize the plot. 
