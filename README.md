# PSDMF Code
Matlab code for algorithms for positive semidefinite matrix factorization (PSDMF) based on singular value projection (SVP) and alternating block gradient (ABG) is available via https://dana.lahat.org.il/psdmf.html.
	
The above link contains the following files:
1. run_demo_psdmf.m (main file, start here)
2. psdmf.m (where the actual algorithms are implemented)
3. script_psdmf_functions.m (used by run_demo_psdmf.m to run the algorithms you choose in run_demo_psdmf.m)
4. script_draw_plots.m (figures for output of run_demo_psdmf.m)
5. psdmf_init.m (generate pseudorandom factors according to the PSDMF model)
6. psdmfgen.m
7. ReadMe.txt

If you use this code, please cite:
1. D. Lahat, Y. Lang, V. Y. F. Tan and C. Févotte, "Positive Semidefinite Matrix Factorization: A Connection With Phase Retrieval and Affine Rank Minimization," in IEEE Transactions on Signal Processing, vol. 69, pp. 3059-3074, 2021, doi: 10.1109/TSP.2021.3071293
2. Please note that the algorithms in psdfm.m are based on phase retrieval and affine rank minimization methods that had been published in other papers. Please cite also the relevant works(s) on which these functions are based. This information appears within the .m files.

Please contact the authors immediately if you have any questions or concerns. 
