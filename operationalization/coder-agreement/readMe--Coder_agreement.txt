# Directory: Coder-agreement
You may want to calculate agreement between 2 or more coders (inter-coder agreement) or between the earlier and later work of a single coder (intra-coder agreement). You can use, for example, measurements that do not take "agreement by chance" into consideration, such as percentage agreement, or you can use measurements that do, such as Cohen's Kappa.

This tool helps you calculate both types of agreement:
http://dfreelon.org/utils/recalfront/recal2

This tool is for Cohen's Kappa only:
https://idostatistics.com/cohen-kappa-free-calculator



# Coder agreement testing example

This is an example of coder agreement testing with Cohen's Kappa and percentage agreement available in the SQAFFOLD supplementary materials OSF directory.

The purpose of this example is to show you some considerations in calculating inter- or intra-coder agreement (also known as inter- or intra-rater reliability).

Let's assume we have two codes (Code A and (Code B) and two coders (Coder 1 and Coder 2). The coders could be the same person at e.g., when they begin final coding and half-way through the process.

Let's also assume we want to check the agreement between the two coders, so that we see how aligned their understanding of the two codes are, and check whether they are applying them in the same way. For intra-coder agreement, this would also make sense, as it would give us a good sense of how consistently the single coder is applying the codes over the course of coding the entire dataset.

In this example (available at: https://osf.io/6qa7x), we took 10 lines of data and had both coders apply the two codes to each line. A 1 indicates if the code is present, a 0 if it is not.

There was one disagreement between the two coders in the 10 lines. But as you can see, the base rate of the occurrence of the two codes within the 10 lines are different. While Code A had a 60%-40% ratio of the code being present vs. absent, Code B had a 90%-10% ratio. (The csv used to compute agreement with the tool ReCal is available here: https://osf.io/hrmp9.)

If you now check the results of the inter-coder agreement testing (ICA_demo.PNG available at: https://osf.io/69zue), you can see how vastly different the Kappa results are, despite the percentage agreement being the same. This is because the latter does not take agreement by chance into consideration, while the former computation does.

Thus, when compiling the test set with which you compute Kappa, consider the base rate of the codes' occurrence (among other things).