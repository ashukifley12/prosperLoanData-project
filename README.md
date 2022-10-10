# prosperLoanData-project
The 113937 loan items in the Prosper loan dataset each have 81 properties, such as the loan amount, borrower rate (or interest rate), current loan status, borrower income, and many more.
There are two major groups:

1, Information about the borrower: The borrower's fundamental characteristics, such as annual income, employment status, interest rate, and loan status.

2, Information on loan performance: metrics assessing the risk of the loans, including Prosper score and bank card usage, etc. To produce analyses and visualizations that are engaging and reliable, a few things needed to be fixed.

Summary of Results

This study's goal is to identify the following variables that effect loan amount and borrower rate:

During my research, I discovered a somewhat strong negative link between interest rate and loan size. Additionally, there are some significant and negative connections between the interest rate and the categorical/ordinal variables chosen. As an illustration, persons without jobs have more stringent credit requirements (higher rates) than those who have.The second factor is that homeowners or borrowers with collateral have cheaper rates than those without collateral (house).

The third factor is that lenders often charge lower interest rates to customers who make more money each month. So it's also a reliable indicator. Similar evidence suggests that the borrower's rate is highly influenced by the borrower's Prosper rating and score. We can infer that the rate is lower the higher the score. In other words, borrowers with AA prosper ratings should anticipate an APR that will probably fall between 2-15%, while those with poor ratings (HR) can anticipate interest rates as high as 40%!

I also expanded my research into loans and interest rates in comparison to the most explanatory factors.

The multivariate analysis here revealed that banks apply more stringent credit requirements to customers who are in default (past due, charged-off payments) (higher interest rates). These individuals also have lower credit scores than those with high status.

Another thing to note is that different rates are used depending on maturities. In other words, regardless of the prosper rating, rates for 5-year loans are typically higher than rates for loans with other maturities (with the exception of the E rating, which has rates the same for 3- and 5-year loans, and the HR rating). It goes without saying that a longer duration increases the likelihood that the operation will result in a rate increase. Of course, as is frequently stated, those with good ratings pay the lowest prices. It's interesting to note that just 3 years of loans are found in this dataset for HR ratings.

Parallel to this, defaulted and charged-off loans often have a higher borrower APR compared to completed or ongoing loans for all Prosper Ratings except "A" and "AA" (good records).
Last but not least, a collateral and a higher income assist in obtaining a larger loan amount. It is obvious that owning a property is a crucial factor in obtaining a greater loan amount.

Key Takeaways for the Presentation

I narrow my attention for the presentation to only a few factors that affect interest rates and loans. By visualizing the distribution of the loan status and loan amount variables, I began by introducing them.

After that, to further explore the connection between my interest-related variables (interest rate and loan), I utilized violin plots, box plots, and line graphs.
