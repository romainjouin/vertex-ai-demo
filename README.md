This repo gives you hints and demos to jumpstart on vertex ai.

[cloud_orbit_demo_1_apis.ipynb](https://github.com/romainjouin/vertex-ai-demo/blob/main/cloud_orbit_demo_1_APIs.ipynb)   
**explain the basic vertex ai apis**
- vision.image
- sentiment_analysis
- entities recognition (nlp)
- google translate

[cloud_orbit_demo_2_automl_endpoint_fetch.ipynb](https://github.com/romainjouin/vertex-ai-demo/blob/main/cloud_orbit_demo_2_automl_endpoint_fetch.ipynb)  
**explain the usage of automl.**
- fetching answer from a deployed endpoint

[cloud_orbit_demo_3_vertex_pipeline.ipynb](https://github.com/romainjouin/vertex-ai-demo/blob/main/cloud_orbit_demo_3_vertex_pipeline.ipynb)  
**explain vertex ai pipelines**
- creating components
- creating a pipeline with the components
- compiling the pipeline
- run a pipeline job
- use a yaml file to do programatic pipelines
- creating a pipeline for machine learning
-  creating a tabular dataset based on big query
-  creating an auto-ml model
- callling the previous component to know if the model's performance is good enough
- using a conditional test from "dsl" library to decide or not to deploy
- creating an endpoint to serve the model
- visualizing the pipeline in vertex's user interface :  


[cloud_orbit_demo_4_gpu_vs_cpu.ipynb](https://github.com/romainjouin/vertex-ai-demo/blob/main/cloud_orbit_demo_4_gpu_Vs_cpu.ipynb)  
**explore gpu calculus and endpoint deploiement**
- testing cpu vs gpu calculus on vertex ai 
- seeing that gpu is slower on small dataset, but faster in big ones
- creating a pipeline for data preparation
- create a pipeline model 
- create a pipeline api endpoint with the created model 
- testing the created endpoint

[video_transcription_demo_github.ipynb](https://github.com/romainjouin/vertex-ai-demo/blob/main/video_transcription_demo_github.ipynb)  
**explain how to do an automatic summary of a video, with timestamped parts.**
Example of result [here](https://storage.googleapis.com/jr-non-uniform/Conseil%20municipal%20du%20mardi%207%20novembre%202023.html#)
- import and upload a video in a bucket
- use vidéo transcription for speech to text
- use genai and prompt-engineering with text-bison@002 to do a chapitrage
- output as html
