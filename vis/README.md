

**Part 1 Due 4/25**. 
 istruzioni https://forms.gle/evfTrUi4SNpMsqBx8 - scegliete  plot e migliorateli sulla base delle regole di Tufte e delle considerazioni fatte in classe | DEADLINE Martedi 4/25
 
 
**Part 2 Due 4/30** Take a plot you made in the past (for a class of research or even for this class) and make it _better_ following the best practices discussed in class. Post your “before” and “after” in a README.md mark down on GitHub in HW6 folder along with a description of what was improved and why

![image](https://github.com/fedhere/MLPNS_FBianco/blob/main/vis/139481925-9b25650c-94ec-491f-973b-645ae9110ee7.png)


![image](https://github.com/fedhere/MLPNS_FBianco/blob/main/vis/139481812-3c4ad4f3-efde-4c1c-844f-6c2edd843ede.png)

This plot suffers from density scaling: the dynamic range of densities of points in different regions of the plot is so significant that it is impossible to perceive simultaneously how dense the dense regions are and how far the data points extend into the parameter space in the original version.

I used transparency to increase the visibility of datapoints where the density of detapoints is not critically high and used contours to represent the point density where the density is so high that the transparency alone would not enable to differences in this region of the plot as well as still see the points that are more isolated. 

Now features in the data, like the bridge of points at log-luminosity ~ 28 and log-effective temperature 3.6-3.8 which was hidden before.

I also modified the x tick labels by changing the axis notation and plotting the log of the points in their natural space, as opposed to the points in log space. This increases the readability of the values of Temperature by enabling the display of more values and on the luminosity by reducing the complexity of the tick labels


