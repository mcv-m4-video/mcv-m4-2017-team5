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


## [WEEK 3](Week%2003/)
- [Task 1, 2, 3: Hole filling, area filtering and morphological operators](Week%2003/week3_task123.m)
 Performs the tasks 1, 2 and 3 of this week. There is a parameter named task which let choose the task to execute
- [Task 4: Shadow removal](Week%2003/week3_task4.m)
 It performs the shadow removal algorithm based on (Xu, Landabaso, Pardàs, Shadow removal with blob-based morphological reconstruction for error correction, ICASSP 2005)
- [Task 5: Final evaluation](Week%2003/week3_task5.m)

 For each sequence after the processing done in the previous tasks, this task plots the Precision-Recall curves for a range of alpha values, and computes the AUC.

## Contributors

 * Idoia Ruiz ([idoiaruiz](https://github.com/idoiaruiz))
 * Roque Rodriguez ([RoqueRouteiral](https://github.com/RoqueRouteiral))
 * Lidia Talavera ([LidiaTalavera](https://github.com/LidiaTalavera))
 * Onofre Martorell ([OnofreMartorell](https://github.com/OnofreMartorell))
