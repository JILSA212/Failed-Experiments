This repository is created to keep all the failed experiments at one place. 

The aim of the project is to convert natural language to formal language.
The dataset was generated using CharGPT. That includes 50 training statements, 15 validation statements and 15 test statements.
The folders follow a similar stucture where each trial is assigned a number according to its order of experiment.
Most of experiments are performed using OpenNMT except `trail6` which utilized HuggingFace library.
The folders commonly contain `x.txt`, `x_val.txt`, `x_test.txt`, `y.txt`, `y_val.txt`, `y_test.txt`, `trial#.yaml` and a directory named `Results`
The model and vocabulary builder information is stored in the yaml file. 
The results directory includes the vocab files and models.
The results produced by `model_step_10.pt` on `x_test.txt` is stored in `pred_1000.txt`.

Every trials differ slightly from each other and usually the changes can be seen in the data files or yaml file. 
