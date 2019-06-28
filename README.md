# msnsam


Little modification of msnsam. 
The number of decimals for the segsites' positions goes from 4 to 5.

See msnsam.c line 200. 
fprintf(pf,"%6.5lf ",posit[i] ); // the 5 in %6.5lf represents the number of decimal for each position


See : 

Hudson, R. (2002) Generating samples under a Wright-Fisher neutral model of genetic variation. Bioinformatics, 18, 337–338

Ross-Ibarra J, Wright SI, Foxe JP, Kawabe A, DeRose-Wilson L, et al. 2008. Patterns of Polymorphism and Demographic History in Natural Populations of Arabidopsis lyrata . PLoS ONE 3(6): e2411
