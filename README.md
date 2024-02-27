#SIF_space_hackathon_2023
The problem statement involves employing a RESNet model to address the LULC Level 2 Classification task. The model architecture encompasses various elements and structures to accomplish this classification objective.
<img width="943" alt="Screenshot 2024-02-27 at 11 10 19 PM" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/82580a12-e781-4e76-a4f5-bc50b27b9507">
<img width="859" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/9d60d3a4-0fd9-41c5-ba87-4fce8f68bcf6">
<img width="858" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/fb47b9ca-29ab-478e-a967-8a92938fc964">
<img width="859" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/c8361e86-9df2-42e5-9367-309c25783dca">
<img width="862" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/97ed191c-4931-4939-a359-d9a83eefcf59">
<img width="855" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/a3d00029-bd66-4287-9f56-4abd17e7307e">
<img width="858" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/336755c5-b945-4b89-893c-ead13889a542">
<img width="857" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/07d54685-86a5-40a8-ae33-9c9d2ce4cdfa">
<img width="854" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/ef3a7258-609d-4d25-aa8e-f78086a8399f">
<img width="853" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/3a9586fa-17cb-4425-a020-66d7071b0f56">
<img width="854" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/8c8b2c62-cd44-48c9-b796-1665aa02a89c">
<img width="1440" alt="" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/8607c9a1-7906-4987-8a73-6c6f0745814e">
<H3>Results On Training</H3>
Following the training of the model on the Sentinel-2 dataset sourced from Kaggle's EuroSAT classification for initial parameter training, which comprises 23,555,082 trainable parameters within the deep neural network, the resulting test outcomes include the ROC curve.
<img width="1402" alt="Screenshot 2024-02-27 at 11 07 38 PM" src="https://github.com/sanvishukla/SIF_space_hackathon_2023/assets/161497545/28a76e69-fa3d-43f6-86d1-e42cafa14027">
Despite encountering challenges with processing the provided .TIF images within the desired timeframe, we successfully trained the model on 27,000 (64,64) size images of labeled land use instances, meticulously following the specified guidelines. Remarkably, this initial training phase yielded an impressive test accuracy of 89.78%. Looking ahead, we anticipate even greater advancements in performance as we continue to train the model with the seasonal dataset provided, fostering optimism for enhanced results in the near future.
