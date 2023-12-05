[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12060741&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[PUT-YOUR-REPOSITORY-HERE]/main)

# 27410 - Group assignment - Group 14 - [Optimising L-aspartate production in _E. coli_]

Our repository is [group-assingment-group-14](https://github.com/27410/group-assingment-group-14)


## Project summary (<300 words)

The aim of this project was to explore the optimisation of L-aspartate production in _E. coli_ using computational methods. To achieve this we first assessed the quality of two different GSM models using Memote. Using the highest quality model we then explored different strategies for optimising L-aspartate production, including testing different gene knockouts, overexpression targets, mimicking the insertion of a more active AspC, changing the substrate and finally, trying different cofactors. We have found that maltose, maltohexaose and maltotriose are the best substrates for optimising L-asp production. We also found that increasing the flux to EX_asp_L_e leads to less L-asp production, due to the negative effect this exerts on biomass. Changing the bounds of the ASPTA reaction did not lead to any significant changes in L-asp production. Finally, we found that the best strategy for optimising L-asp production is to change the substrate, since none of the genetic modifications rendered viable results due to L-aspartate's relationship with biomass. Exchanging glucose for maltohexose increased the yield of L-asp from 0.3 to 1.25 g/L. 


## Project overview
The report for this project is presented in the file [Report.ipynb](https://github.com/27410/group-assingment-group-14/blob/main/Report.ipynb) The code used to complete it can be found on github and appears in the following order:

[0. Memote](https://github.com/27410/group-assingment-group-14/blob/main/0.%20Memote.ipynb)

[1. Objective function](https://github.com/27410/group-assingment-group-14/blob/main/1_Objective_function.ipynb)

[2. Theoretical yield](https://github.com/27410/group-assingment-group-14/blob/main/2_Theoretical_yield.ipynb)

[3. E. coli gene KOs](https://github.com/27410/group-assingment-group-14/blob/main/3_E.%20coli_gene_Kos.ipynb)

[4. Overexpression targets](https://github.com/27410/group-assingment-group-14/blob/main/4_Overexpression_targets.ipynb)

[5. Insertion of a more active AspC](https://github.com/27410/group-assingment-group-14/blob/main/5_AspC_higher_Kcat.ipynb)

[6. PPPA glucose](https://github.com/27410/group-assingment-group-14/blob/main/6_PPPA.ipynb)

[7. Cofactor swapping](https://github.com/27410/group-assingment-group-14/blob/main/7_Cofactor_swapping.ipynb)

[8. DFBA](https://github.com/27410/group-assingment-group-14/blob/main/8_DFBA.ipynb)

[9. PPA maltose](https://github.com/27410/group-assingment-group-14/blob/main/10_PPPA_maltose.ipynb)

[10. PPA maltohexaose](https://github.com/27410/group-assingment-group-14/blob/main/11_PPPA_maltotrexaose.ipynb)

[11. PPA maltotriose](https://github.com/27410/group-assingment-group-14/blob/main/12_PPPA_maltotriose.ipynb)




