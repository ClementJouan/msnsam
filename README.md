# msnsam


Little modification of msnsam. 
The number of decimals for the segsites' positions goes from 4 to 5.

See msnsam.c line 200. 
fprintf(pf,"%6.5lf ",posit[i] ); // the 5 in %6.5lf represents the number of decimal for each position
