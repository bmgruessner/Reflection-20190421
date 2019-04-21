Brian Gruessner
20190421

**Reflection: Plot Protein**

This paper concerns a vis program called Plot Protein, which attempts to visualize mutations to predict their effect on function. This function allows for medically relevant predictions to be made about, for example, mutations in cancer, infectious disease, important genes to human health, and general mechanisms of action in biological systems. This program is relevant to my project, which attempts to do the same. Interestingly, this program uses some of the same vis methods that I have chosen to use, but its approach is very different from mine.
Plot Protein predicts the sensitivity of regions of a protein based on conservation of protein sequence in related species.  More conserved sequences are likely key to the protein function and therefore more sensitive to change than non-conserved regions.  This approach has the advantage of being able to predict the consequences of mutations in most species without prior information on the effects of mutations.  Because this system takes in data across an entire protein, it is more powerful than the BLOSUM score system that my vis incorporates to predict sensitivity, which only examines individual amino acids at a time. However, my vis also incorporates functional output from known mutants, which is the most reliable information to use if it is available. 
Plot Protein makes reasonable decisions for visualizing data.  It also uses a lollipop plot to represent mutations (*Figure 1*), which is highly effective to show regionally crowded, high-dimensional data. It also utilizes a full-view and a zoom window concurrently, which is a clever way to resolve the tradeoff between the two. Visually, its biggest weakness seems to be that it relies on many stacked horizontal spans of data.  While comparisons of parallel data can be highly reliable, distances between some of the representations start to make them difficult to compare.
This visualization portrays mutation data in a way that allows the user to draw conclusions on how mutations will affect function in a reasonable way.  However, the programs does not appear quantify and predict mutants effectively.  This would be a powerful function to include in a vis, and one that I hope to include in my own.
 

![alt text](https://github.com/bmgruessner/Reflection-20190421/blob/master/R20190421F1.png, "Figure 1")
Figure 1: part of output of PlotProtein (continues further downward).


**Source:**
[1]: Turner T (2013). Plot protein: visualization of mutations. *Journal of Clinical Bioinformatics*, 3(14). doi:10.1186/2043-9113-3-14
