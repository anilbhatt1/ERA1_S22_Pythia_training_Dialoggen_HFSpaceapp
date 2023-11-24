### Inferencing with Pythia Models

- Github Ref : https://github.com/Lightning-AI/lit-gpt
- All the required files and CLI command to do inferencing is taken from above github repo
- Huggingface Space app : 
https://huggingface.co/spaces/neuralorbs/DialogGen
- Notebooks:
    - ERA1_s22_sagemaker_training_v0.ipynb 
        - This notebook deals with training Pythia-160M-Deduped on custom data to get a loss of 2.5
        - This weights will be later used in HF space app for inferencing
    - ERA1_s22_sagemaker_inference_v1.ipynb
        - This notebook deals with inferencing using CLI commands as mentioned in https://github.com/Lightning-AI/lit-gpt
    - ERA1_s22_sagemaker_inference_gradio_v2.ipynb
        - This notebook deals with inferencing in gradio which was later used in building HF space app
- Weights folder : https://drive.google.com/drive/folders/1BuHtPPs_qkQeokto-1T0YT0ii9yYZmxE?usp=sharing OR ~/AI/ERAV1/s22_sagemaker/WEIGHTS/checkpoints/EleutherAI