# Conventional-Neural-network

Author: Hengameh Mirhajianmoghadam

If the pytorch is not install in jupyter notebook,

1. Create a new environment in Anaconda Pwershell Prompt
    conda create --name new-env

2. Activate the environment 
    conda activate --name

3. Based on the Pytorch website choose the specific command for installing the Pytorch in the computer
    conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch

4. Install jupyter notebook inside the activated environment
    conda install jupyter

5. Then run the jupyter notebook
    jupyter notebook

Based on these steps, if importing torch in the jupyter notebook, it should work without any error.

Requirement:
jupytur notebook 6.4.5
conda 4.10.3
cudatoolkit=11.3
