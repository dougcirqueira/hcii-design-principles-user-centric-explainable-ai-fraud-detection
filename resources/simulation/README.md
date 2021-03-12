# The simulation script is available as a Python Jupyter Notebook.
Instructions

1. You can open the Notebook within a Colab environment
2. Upload the files "xaiMethod.py" and the dataset "HCII_21_DATASET_USER_CENTRIC_XAI_FRAUD" to your environment
3. Go to the Section "Read Data". On line 20, define the boolean value for the variable "random_option". If "False", you will obtain the
results for the Simulated User Confidence score (SUC) according to the relevance of features provided by explanation methods. If "True",
you will obtain the results for SUC based on a random deletion of features.
4. Check if the value 50 is given in the range on line 28 "rand_seed_list = list(range(0,50))"
5. Run all the cells up to Section "Read Data"
6. Run cell in Section "Run Simulation"
7. When the simulation ends, you will obtain a file at your environment naming "confidences_all_XAI.csv"
8. The results reported on the paper are the averages for SUC scores obtained by each explanation method

If you have any issues, please do not hesitate to contact me at: douglas.darochacirqueira2(at)mail.dcu.ie
