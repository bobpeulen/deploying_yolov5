# deploying yolov5
Deploying a pre-built Yolov5(s) model using Oracle Data Science. The notebook is part of larger project, but the deployed Yolov5 model can be invoked from any application.

Files included:
- Small video of the end result. Storing an image in the 'input_bucket', infering the deployed Yolov5 model, and getting the output image in the 'output_bucket'
- Notebook: yolov5_apex.ipynb.
This notebook works through all the steps needed to build and deploy a Yolov5 model within an Oracle Data Science projects.

The steps are:
1. Creating and publishing a custom conda environment
2. Building the model artifacts, including the Yolov5 directories and additional packages, score.py, runtime.yaml
3. Storing the model artifacts in the Model Catalog
4. Deploying the model using Model Deployment
5. Testing the HTTP endpoint
