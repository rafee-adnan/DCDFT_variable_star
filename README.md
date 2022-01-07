# DCDFT_variable_star
We used DCDFT to determine the period of the variable star. DCDFT corresponds to a curve-fitting approach using a sinusoid-plus-constant model. we can see from the data that the spacing between observations is roughly a multiple of one sidereal day.

As the Nyquist frequency is roughly 0.5 perD, we considered the range of frequency to be from 0 to 0.5 for the first observation.

We have used a test derived by G. R. Quast to calculate the confidence of the result. From the confidence level curve, we can see that there's a prominent peak near 0.35 perD which has more than a 95% confidence rate.

If we draw another plot from 0.5 to 1, we can see there's another prominent peak around 0.65 perD. We can see that one peak is the alias of the other. From further study, we know this phenomenon is called aliasing and we will get other folds going beyond 1 perD.


![Screenshot from 2022-01-08 00-37-57](https://user-images.githubusercontent.com/76589056/148593050-92dd1709-1aa3-4c85-9eee-f95658845236.png)
## colab runtime 
https://drive.google.com/file/d/1t0e6JyNvT_1SzA4AxOYOOdgFaRcFFLRI/view?usp=sharing
