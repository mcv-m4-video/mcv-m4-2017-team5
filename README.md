# mcv-m4-2017-team5

## [WEEK 2](Week%2002/)

This week work performs foreground detection for the sequences that are placed at the /Database/Week02/ directory (highway, fall and traffic)


- [Task 1: Gaussian distribution](Week%2002/week2_task1_Gray.m)

 Input parameters: Sequence used (either highway, fall or traffic)

 It computes foreground detection on the selected sequence using Gaussian modelling for several values of alpha. The evaluation is performed computing performance metrics as well as  Precision-Recall and ROC curves.


- [Task 2: Adaptative modelling](Week%2002/week2_task2_Gray.m)

 Input parameters: aplha, rho and the sequence used (either highway, fall or traffic)

 It computes foreground detection on the selected sequence using adaptative modelling.
 Then, grid search is performed to find the optimum values for rho and aplha. It computes the precision, recall and F-measure for a set of values for rho and alpha (the values between min_alpha, min_rho and max_alpha,max_rho)
 The evaluation is finally performed using the optimum values.
 A video is also generated to compare these results with the task 1 ones.


- [Task 3: Comparison](Week%2002/week2_task32.m)

 Input parameters: Sequence used (either highway, fall or traffic)

 It compares results from previous single gaussian methods with the foreground segmentation results of applying a GMM model.


- Task 4: Color extension using [HSV](Week%2002/week2_task4_HSV.m) and [RGB](Week%2002/week2_task4_RGB.m)

 Input parameters: Sequence used (either highway, fall or traffic)

 This task does the same as task 1 but using color sequences (on HSV and RGB colour spaces) instead of using gray scale ones.

## Contributors

 * Idoia Ruiz ([idoiaruiz](https://github.com/idoiaruiz))
 * Roque Rodriguez ([RoqueRouteiral](https://github.com/RoqueRouteiral))
 * Lidia Talavera ([LidiaTalavera](https://github.com/LidiaTalavera))
 * Onofre Martorell ([OnofreMartorell](https://github.com/OnofreMartorell))
