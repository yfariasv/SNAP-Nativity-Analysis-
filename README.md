# Analysis of SNAP participation between native-born and foreign-born populations in New York and Texas using IPUMS Data

## Table of Contents 
- Introduction
- Justification of the Research 
- Literature Review 
- Notebook 
  - Analysis: SNAP Participation by Nativity
- Conclusion
- Next Steps
- References

---

## Introduction 
Public discussion often claim that immigrants rely heavily on government assistance programs in the United States. However, the extent to which this claim reflects reality remains debated. This project analyzes Supplemental Nutrition Assistance Program (SNAP) participation among native-born and foreign-born individuals in New York and Texas. 
Using census-based microdata obtained from IPUMS, this study examines demographic and socioeconomic factors associated with SNAP usage. By comparing two states with different political climates and immigration histories, the analysis aims to determine whether nativity status significantly influences reliance on SNAP benefits. 
The guiding research question for this project is: 
**How does SNAP participation differ between native-born and foreign-born populations in New York and Texas?**

---

## Justification of the Research 
SNAP is one of the largest anti-poverty programs in the United States, providing food assistance to millions of households each year. Despite its importance, public perceptions often portray immigrants as disproportionately dependent on social assistance programs. Understanding whether these perceptions align with actual data is essential for informing policy discussions and addressing misinformation. 
This research is important becuase it helps clarify how nativity status relates to SNAP participation. By identifying differences or similarities in program usage, the analysis contributes to a more accurate understanding of economic vulnerability among different population groups. 
additionally, comparing states such as New York and Texas allows the research to explore how regional political and social contexts may influence SNAP participation patterns. 

---

## Literature Review 

Debates about the economic impact of immigrants in the United States have persisted for decades and are often used as political talking points to influence public opinion. With the increasing use of social media and artificial intelligence, the spread of misinformation has become more common, frequently portraying immigrants as criminals, heavy users of government assistance, or as having a negative impact on the economy. These narratives often circulate widely despite empirical research suggesting a more complex reality. As a result, it becomes important to examine the available statistical evidence to better understand the actual economic conditions and public assistance usage among immigrant populations.
One study conducted by Iceland (2021) examined the prevalence of economic hardship among immigrants in the United States using data from the 2008 and 2014 panels of the Survey of Income and Program Participation (SIPP). The findings indicate that immigrants are not uniformly worse off than native-born individuals. For example, foreign-born individuals who had become U.S. citizens were less likely than native-born households to report certain bill-paying hardships during the 2010 hardship period (11.9% compared with 14.3%). Although undocumented immigrants reported higher levels of hardship (23.7%), these differences became smaller and often statistically insignificant when controlling for income-to-poverty ratios (Iceland, 2021). When examining the 2013 hardship period using the 2014 SIPP panel, differences between immigrants and native-born individuals were generally less pronounced. In some controlled models, noncitizens were even less likely than native-born individuals to report bill-paying hardships. These findings suggest that economic hardship among immigrants cannot be explained solely by immigration status and that broader socioeconomic factors play an important role.
Similarly, Ku and Bruen (2013) analyzed data from the 2012 Current Population Survey (CPS) to examine whether low-income immigrants used public assistance programs at higher rates than native-born citizens. Their analysis focused on major programs including Medicaid/CHIP, SNAP (food stamps), Temporary Assistance for Needy Families (TANF), and Supplemental Security Income (SSI). The results showed that low-income immigrants, particularly noncitizens, generally used public benefits at lower rates than comparable low-income native-born citizens. For instance, SNAP participation rates were approximately 33% for native-born adults compared to 25% for naturalized citizens (Ku & Bruen, 2013). The study also found that children in immigrant households were less likely to live in households receiving TANF or SSI compared to children in households where all members were citizens. Overall, these findings contradict the claim that immigrants place a disproportionate burden on public assistance programs.
While these earlier studies provide valuable insights, many of their observations occurred during or shortly after the Great Recession, a period when economic instability may have increased public assistance usage across the entire population. More recent research has examined how immigration policy and political context may influence participation in public programs. Butcher, Hu, and Perry (2024) investigated whether the proposed expansion of the Public Charge Rule in 2018, which emphasized SNAP and Medicaid participation as potential factors in immigration status decisions, influenced safety-net program participation among U.S.-born children. Using data from the American Community Survey (ACS) from 2001 to 2022, the authors compared citizen children based on their parents’ citizenship status. Their findings indicate that after the 2018 proposal, participation in SNAP and Medicaid declined more among U.S. born children with noncitizen parents than among children with U.S. born parents, despite no change in program eligibility. Descriptive statistics show SNAP participation of 11% among households with two U.S. born parents compared with 26% among households with two noncitizen parents, while Medicaid participation increased from 23% to 65% across these groups (Butcher et al., 2024). After controlling for demographic and socioeconomic characteristics, the authors interpret the decline in participation as evidence of a “chilling effect,” where concerns about immigration consequences discourage families from accessing benefits for which they are eligible.
Additional research has examined public assistance participation among older immigrant populations. Mudrazija and Ayala (2025) analyzed data from the Health and Retirement Study (1998–2020) to evaluate public benefit participation among older immigrants in the United States. Their findings indicate that older immigrants are generally less likely than native-born individuals to receive benefits such as Social Security Disability Insurance and other cash transfers. An exception appears among Hispanic immigrants, who historically showed slightly higher participation in SNAP benefits prior to 2018. However, the study documents a long-term decline in public benefit participation among immigrants relative to the native-born population, particularly during the late 2010s. These findings further challenge the narrative that immigrants place disproportionate pressure on the welfare system.
Beyond individual socioeconomic characteristics, public policy environments may also influence how immigrants interact with social support programs. Fouka (2024) synthesizes causal evidence showing that immigrant integration is shaped by complex policy environments operating through both material channels, such as access barriers, administrative burdens, and economic opportunities, and symbolic channels, including signals of inclusion or exclusion that influence trust and willingness to engage with institutions. The review concludes that policies lowering immigrants’ costs of adjustment are more consistently effective than policies that attempt to incentivize integration by withholding resources or restricting rights. Importantly, these policy effects vary by context and may produce spillovers or unintended consequences. This framework supports the comparison of New York and Texas in the present study. If New York’s policy climate reduces the perceived risks and administrative barriers associated with interacting with government institutions, immigrants may be more willing to access programs such as SNAP when eligible. Conversely, in a more restrictive policy environment, immigrants may avoid applying for benefits due to fear or uncertainty, potentially lowering observed participation even when economic need is similar.

---

## Notebook 

The notebook includes a step by step documentation of the data preparation, statistical analysis, and interpretation of results. 
-  [SNAP Nativity Analysis Notebook](./FinalProjectSDS510-2.ipynb)

---

## Conclusion 

This analysis examined SNAP participation among native-born and foreign-born individuals in New York and Texas. The findings suggest that while differences exist between the two groups, the gap in SNAP usage was smaller than initially expected. 
In New York, foreign-born individuals showed slightly higher participation rates in SNAP compared to native-born individuals. This result raised questions about whether state-level support systems, immigrant integration, or economic factors may influence program usage patterns. 
Overall, the analysis suggests that nativity alone does not fully explain SNAP participation. Instead, broader socioeconomic factors likely play a significant role in determining eligibility and program usage. 

## Future Steps 

While this exploratory analysis provides initial insights into SNAP participation patterns, additional research could expand on these findings. 
Future work could include: 
- Examining additional states to determine whether patterns are consistent nationwide
- Investigating how length of residence in the United States influences SNAP participation
- Exploring the role of employment, education, and household composition
- Applying machine learning methods to identify predictors of SNAP participation
Expanding the dataset and incorporating additional variables could provide a more comprehensive understanding of how economic conditions influence access to food assistance programs.

___

## References 
- Butcher, K. F., Hu, L., & Perry, R. (2024). The public charge rule and program participation among US citizens. The ANNALS of the American Academy of Political and Social Science, 711(1), 170-198. https://doi.org/10.1177/00027162241293910
- Fouka, V. (2023). State policy and immigrant integration. Annual Review of Political Science, 27. https://doi.org/10.1146/annurev-polisci-051921-102651 
- Iceland, J. (2021). Hardship among immigrants and the native-born in the United States. Demography, 58(2), 655-684. https://doi.org/10.1215/00703370-8958347 
- Ku, L., & Bruen, B. (2013). Poor immigrants use public benefits at a lower rate than poor native-born citizens. Cato Institute Economic Development Bulletin, (17).
Citation for IPUMS USA 
- Steven Ruggles, Sarah Flood, Matthew Sobek, Daniel Backman, Grace Cooper, Julia A. Rivera Drew, Stephanie Richards, Renae Rodgers, Jonathan Schroeder, and Kari C.W. Williams. IPUMS USA: Version 16.0 [dataset]. Minneapolis, MN: IPUMS, 2025. https://doi.org/10.18128/D010.V16.0



