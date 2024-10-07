# Rural land use based on Andy Ford's forest management in equilibrium
The rural land use structure was originally developed and documented by Hovmand et al (2015) as part of the molecules library used to teach the Winter Institute in India with Foundation for Ecological Security and based on Ford's forest management in equilibrium structure (1999, p. 57). 

<img width="536" alt="image" src="https://github.com/user-attachments/assets/e0f63af0-3932-4cf0-80cc-c9dba469084a">

Figure 1. Rural land use

<img width="536" alt="image" src="https://github.com/user-attachments/assets/7f1ae76a-9f46-4e87-90d6-66e55c08a40d">

Figure 2. Baserun

## Equations 


1. Cash Crops= INTEG (Converting Land from Fallow to Cash Crops + Converting Land from Food Crops to Cash Crops-Converting Land from Cash to Food Crops-Fallowing Land from Cash Crops, Initial Cash Crop Land)

Units: Ha

2. Cash Fallowing FR = 0.1

Units: Dmnl/Year

3. Cash to Food FR = 0.1 

Units: Dmnl/Year

4. Converting Land from Cash to Food Crops = Cash Crops*Cash to Food FR

Units:  Ha/Year
   
6. Converting Land from Fallow to Cash Crops=Fallow * Fallow to Cash FR

Units:  Ha/Year

7. Converting Land from Food Crops to Cash Crops = Food Crops * Food Crops to Cash Crops FR

Units: Ha/Year

8. Fallow = INTEG (Fallowing Land from Cash Crops + Fallowing Land from Food Crops-Converting Land from Fallow to Cash Crops - Converting Land from Fallow to Food Crops, Initial Fallow Land)

Units: Ha

9. Fallow to Cash FR = 0.1

Units: Dmnl/Year

10. Fallow to Food FR = 0.15

Units: Dmnl/Year

11. Fallowing Land from Cash Crops = Cash Crops * Cash Fallowing 

Units: Ha/Year

13. Fallowing Land from Food Crops=Food Crops*Food to Fallow FR

Units:  Ha/Ye

15. Food Crops= INTEG (Converting Land from Cash to Food Crops + Converting Land from Fallow to Food Crops - Converting Land from Food Crops to Cash Crops-Fallowing Land from Food Crops, Initial Food Crop Land)

Units: Ha

16. Food Crops to Cash Crops

Units: Dmnl/Year

17. Food to Fallow FR = 0.2 

Units: Dmnl/Year

18. Initial Cash Crop Land = 3 

Units: Ha

19. Initial Food Crop Land = 5 

Units: Ha

20. Initial Fallow Land = 1 

Units: Ha

## Simulation parameters

1. INITIAL TIME = 0 

Units: Year

2. FINAL TIME = 10 

Units: Year

3. TIME STEP = 1

Units: Year

6. SAVEPER = TIME STEP 

Units: Year

# References

Ford, A. (1999). *Modeling the environment: an introduction to system dynamics models of environmental systems. Washington, DC: Island Press.

Hovmand, Peter S., Kuhlberg, J. Brown, A., & Belsky, J. (2015). *Social System Design Lab Molecules Library Version 2.0.* Brown School Social System Design Lab, Washington University in St. Louis.



