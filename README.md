# Market-Basket-Analysis-on-Medications

#### PROPOSAL OF QUESTION
Which medications are frequently prescribed together? 
DEFINED GOAL
The primary goal is to identify patterns of medication co-prescription to optimize treatment regimens and improve patient outcomes. 

#### EXPLANATION OF MARKET BASKET
Market Basket Analysis (MBA) is a data analysis technique to understand the relationship between items in a dataset. When applied to the medicine prescription data, MBA helps identify patterns in which medications are frequently prescribed together. 
MBA works by first having data where each row represents a transaction, and each column represents a specific medication. The values are typically True if the medication was prescribed and False if it was not. Then, MBA identifies combinations of medications that frequently appear together. From these medications, MBA generates rules that describe the likelihood of one medication being prescribed, given that another medication has been prescribed. 
The expected outcomes are identifying the commonly co-prescribed medications and optimizing inventory management. Select medications with a high lift value to identify common co-prescribed medications. Moreover, pharmacies can use this analysis to manage their inventory better to ensure they stock enough of the medications prescribed together.  
#### MARKET BASKET ASSUMPTION
MBA assumes that each transaction is independent of other transactions. This means that the presence or absence of items in one transaction does not affect the presence or absence of items in another transaction. If the assumption of independence is disregarded, the association rules generated might not accurately reflect true prescribing patterns and could lead to biased conclusions.  
#### SIGNIFICANCE OF SUPPORT, LIFT, AND CONFIDENCE SUMMARY
Support measures how frequently an itemset appears in the dataset. The analysis for top support highlights that carvedilol and abilify are prescribed together in approximately 5.97% of all transactions in the dataset. The high support value indicates that the combination of these two medications is relatively common in the dataset. 
Confidence measures the likelihood that a consequent item is prescribed when the antecedent item is prescribed. High confidence means that when a patient is prescribed one medication, there is a high probability that they will also be prescribed another specific medication. The analysis for top confidence indicates that 45.65% of the time, when metformin is prescribed, abilify is also prescribed. This high confidence value suggests a strong likelihood that patients on metformin are also being prescribed abilify. 
Lift measures the strength of an association between two medications beyond their individual occurrence rates. A lift greater than 1 indicates a positive association. The lift value of 2.29 for the top lift itemset means that the prescription of lisinopril is twice as likely when carvedilol is prescribed compared to the prescription of lisinopril independently. This high lift value indicates a strong positive association that is not by chance alone. 
#### PRACTICAL SIGNIFICANCE OF FINDINGS
The findings from the analysis provide valuable insights that can help optimize inventory management, identify potential drug interactions, and cost management and efficiency. 
Knowing which medications are most frequently prescribed together allows pharmacies to optimize their inventory. Medications with high support values should be stocked in higher quantities to meet patient demand. Moreover, lift values greater than 1 highlight strong associations between medications that are prescribed together more frequently than by chance. This can alert healthcare providers to potential drug interactions. Finally, by understanding the most common medication combinations, healthcare providers can reduce waste by ordering the right quantities of these drugs and avoiding overstocking less frequently prescribed medications. 

#### COURSE OF ACTION
Integrate medication management for high-support itemsets. Since carvedilol and abilify are prescribed together in approximately 5.97% of transactions, healthcare providers should ensure coordinated care for patients receiving these medications. This involves monitoring for potential interactions and providing comprehensive patient education on the effects and proper use of these medications. 
Enhance patient monitoring for high-confidence associations. A confidence value of 45.65% indicates that nearly half of the patients on metformin are also prescribed abilify. Providers should be aware of the reasons behind this co-prescription and manage any possible side effects.
The strong association of 2.29 between carvedilol and lisinopril suggests that pharmacies should ensure both medications are available together. Pharmacies can utilize stock management and inventory optimization with high-lift associations. This can help in reducing wait times for prescriptions and improving patient satisfaction. 

