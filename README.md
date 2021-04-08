# Ranking Loss used for Deep Image Retrieval


### Pytorch source code
**(Included in /src)**
1. Install dependencies: pip install -r requirements.txt
2. Directory structure
* /data: Download the data from google drive link provided. You can choose to download the data from VGG website but, we have already created the negative ground truth files using structural similarity and have included in google drive. Otherwise the script will automatically start to create the negative examples which might take about 2 hrs. So using google drive to download data is recommended.
* /weights: store model weights here (pre-trained weights can be downloaded from google drive) 
* /src: contains the source code (Included in submission)
* /fts_pca: contains the pca features generated using trained networks for both datasets. (Can be downloaded from google drive)
* /results: You can store the results here (You need to create this manually)
3. Run the main function in main.py with required arguments. The codebase is clearly documented with clear details on how to execute the functions. It also includes an example. You need to interface only with this function to run the training.
4. To create the pca embeddings using your own model, use create_db.py. The function is clearly documented with an examples as well.
5. To run inference on query image files, use inference_on_single_image.py. The function is clearly documented.

