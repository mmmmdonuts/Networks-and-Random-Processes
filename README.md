# Networks-and-Random-Processes

Notebooks will be uploaded for each support class.

For Latex, I recommend you to use Overleaf (particularly useful for RSG as can have multiple people working on the same document at the same time - plus you can chat to each other on there): [https://www.overleaf.com/](https://www.overleaf.com/)

For GitHub help, check out https://www.gitkraken.com/

**Steps to download GitKraken:**
- Download the .deb file
- open terminal and go into your downloads (cd Downloads)
- `sudo dpkg -i name.deb`
- log in with you github

**Useful links for the assignments:**
- Log Normal Distribution: [https://en.wikipedia.org/wiki/Log-normal_distribution](https://en.wikipedia.org/wiki/Log-normal_distribution)
- Log Normal Scipy Documentstion: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.lognorm.html
- KDE plot visualisation: https://mathisonian.github.io/kde/
- Fokker-Planck Equation: book Stochastic Processes in physics and chemistry - N.G. Van Kampen
- Ornstein-Uhlenbeck process: [https://en.wikipedia.org/wiki/Ornstein%E2%80%93Uhlenbeck_process#Fokker%E2%80%93Planck_equation_representation](https://en.wikipedia.org/wiki/Ornstein%E2%80%93Uhlenbeck_process#Fokker%E2%80%93Planck_equation_representation)
- Colour options in matplotlib [https://xkcd.com/color/rgb/](https://xkcd.com/color/rgb/)

# Detail of each notebook:

`Support Class 1.ipynb`
- basic linear algebra in python
- simple random walk animation 
- function SRW, a simple random walk with arguements p (probability steping up), tmax (when to terminate the walk) and N (number of replications)
- empirical distribution calculated at a fixed time (hist plot over possible states at time n)
- simulation with periodic boundary conditions (modulus L (L =10))
- simulation with closed boundary conditions (reflects at 10 and 0)

`Support Class 2.ipynb`
- Geometric random walk
- ergodic average 
- empirical tail (1 - CDF)
- Wright-fisher model ( heatmaps)
- time to reach steady state
- Gershgorin disk theorem 

`Support Class 3.ipynb`
- general plotting techniques in matplotlib [http://matplotlib.org/1.5.3/api/pyplot_api.html#matplotlib.pyplot.plot]( http://matplotlib.org/1.5.3/api/pyplot_api.html#matplotlib.pyplot.plot)

`Support Class 4.ipynb`
- Kingman's Coalescent 
- CTMC (waiting times, exponentially distributed)

`Support Class 5.ipynb`
- Orenstein-Uhlenbeck Process 
- simulated by finite difference approximation (taking the Weiner incremenet by sampling from normal distributioon with zero mean and dt vaiance)
- simulated using `sdeint` (python stochastic differential equations, numerical integration)

`Support Class 6.ipynb`
- Moran model (similar to wright-fisher but continuous time)
- CTMC with waiting times
- introduction to networks and using the `networkx` package in python
- degree distribution, clustering, transitivity, distance, largest component 

`Support Class 7.ipynb`
- Erods-Renyi random graphs 
- compare degree distribution to binomial distribution
- expected size of largest component for multiple realisations 
- expected local clustering coefficient for multiple realisations 
- Wigner semi-circle law 

`Support Class 8.ipynb`
- compare degree distribution to poisson distribution 
- Barabsai-albert model 
- empirical tail distribution 
- expected degree of nearest neighbour given node has degree k
