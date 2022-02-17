# LIGN167_hate_speech_classification
Investigate domain-specific pre-training on improving the performance of hate speech classification task.

## Use GPU Cluster (UCSD DataHub)
- Step1: Go to [DataHub Website](https://datahub.ucsd.edu/hub/spawn)
- Step2: Select the env with GPU ( Python 3, nbgrader (1 GPU, 8 CPU, 16G RAM) )
- Step3: Click "Launch Environment"
- Step4: On the top right corner, click "New". In drop-down menu, click "Terminal"
  - This should spawn a bash terminal
- Step5: Clone project repo in the new terminal, by running: 

  ```git clone https://github.com/kylewang1999/LIGN167_hate_speech_classification.git``

  **NOTE**: GitHub now requires personal access token for ssh authentication. See [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) for how to create the token.
- Step6: (Only after the first clone) Download dataset by running: 
  
  ```cd ~/LIGN167_hate_speech_classification/ && bash get_data.sh```

- Step7: Switich to the desired branch by running: 
  
  ```git checkout <branch_name>```
