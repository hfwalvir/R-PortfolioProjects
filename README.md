# R-PortfolioProjects

**PROJECT 1:**
## Social Network Analysis in R

This project demonstrates the power and versatility of social network analysis using R. It showcases various techniques for creating, visualizing, and analyzing network structures, leveraging the `igraph` package and other tools in R's ecosystem.

### Key Features:
1. **Network Creation**: Illustrates how to create network graphs from both manual edge lists and data frames.
2. **Visualization**: Demonstrates multiple ways to plot networks, including:
   - Basic plots with customized colors and sizes
   - Layouts like Fruchterman-Reingold and Kamada-Kawai
   - Visualizations that reflect network metrics (e.g., node degree)
     
3. **Network Metrics**: Calculates and utilizes various network measures such as:
   - Degree (in, out, and total)
   - Diameter
   - Edge density
   - Reciprocity
   - Closeness and betweenness centrality
    
4. **Advanced Analyses**: 
   - Hub and authority scores
   - Community detection using edge betweenness
     
5. **Data Import**: Shows how to import network data from CSV files for analysis.
   
7. **Statistical Visualization**: Includes histogram generation for node degree distribution.


This project serves as both a tutorial and a reference for conducting social network analysis in R. It's suitable for beginners looking to understand the basics of network analysis, as well as for more advanced users seeking code examples for specific network metrics or visualization techniques.The code demonstrates the entire workflow from data import to complex analysis and visualization, making it a comprehensive resource for anyone interested in exploring social networks using R.
**PROJECT 2:
##Convertible Bond Pricing and Analysis in R**

This project implements a comprehensive analysis and pricing model for convertible bonds using R. It demonstrates the application of financial theory, particularly the Black-Scholes model, to price complex financial instruments.
**Key Features :**
**Convertible Bond Pricing:** Implements a function to calculate the price of a convertible bond using the Black-Scholes model, considering both the bond and option components.
**Yield Curve Visualization:** Plots the yield curve and highlights the position of the convertible bond, providing a visual representation of its yield in relation to the market.
**Price-Stock Relationship Analysis:** Examines how the convertible bond's value changes with fluctuations in the underlying stock price.
**Component Analysis:** Breaks down the convertible bond's value into its constituent parts (straight bond value, conversion value, and option value).
**Sensitivity Analysis:** Includes functions to calculate key metrics such as duration and convexity, allowing for sensitivity analysis of the bond price to changes in yield.
**Techniques Used**
Black-Scholes Model adaptation for convertible bonds
Data visualization using ggplot2
Financial calculations including present value, yield, duration, and convexity
Integration of multiple R packages for comprehensive financial analysis
Potential Applications
**This project can be useful for:**
Financial analysts pricing convertible bonds
Portfolio managers assessing the risk and potential of convertible bond investments
Students and researchers studying complex financial instruments
**Future Enhancements**
Incorporation of more complex convertible bond features (e.g., call and put options)
Integration with real-time market data
Expansion to include other types of hybrid securities
