# DS-340W

Prerequisites
---
The MIMIC-III subset data can be accessed through this link: https://drive.google.com/drive/folders/1dmBQLetdRL5UMzqEX3b7SxK5wmaUlLuH?usp=sharing

**A psu email is required to download this data. Please do not share this data elsewhere as it technically requires certain IRB trainings and research agreements to access.**

Prior to running the python notebook, please download the data to your local computer. Replace any references to OneDrive within the code with your personal path to the data / saved model.

Because this is using an older version of python, I recommend creating a virtual environment as follows:
1. Install Miniconda.
2. Run ```conda create -n "mimic3" python=3.7.13```.
3. Run ```conda init [SHELL_NAME]```. You might also need to do ```source ~/.bashrc``` or ```source ~/.zshrc``` (depends on the shell version).
4. Change the conda environment to mimic3 by running conda activate mimic3.

If running the python notebook in VSCode (or any other coding IDE) there should be an option to select the mimic3 environment as the kernel once it is created. 

If there are any questions in regards to running the code, please contact cby5187@psu.edu.
