# Data Mining and Machine Learning Group Coursework

## Group Members

1. Wasin hongmanee - @WasinHongmanee - H00510924
2. Aedh Alshehri - @Ayad3alshehri - H00464712
3. Astrid Barau - @AstridENSTA - H00508589
4. Khaja Ihteshamddin. - @Khaja718 - H00493331
5. Junaid Ishfaq - @junaid-4001 - H00490039

## Initial Project Proposal


### [MSc Students Only] Research objectives

> What are the questions you are trying to answer? What are the goals of your project? What are your hypotheses?

Which country grows the highest quality coffee beans? Can we distinguish the quality of coffee beans visually?


### Source of Datasets

1. [Tabular Dataset](https://github.com/jldbc/coffee-quality-database/blob/master/data/arabica_ratings_raw.csv) | License: MIT License
   
| quality_score | Aroma | Flavor | Aftertaste | Acidity | Body | Balance | Uniformity | Clean Cup | Sweetness | Cupper Points |
|---------------|-------|--------|------------|---------|------|---------|------------|-----------|-----------|----------------|
| 90.58         | 8.67  | 8.83   | 8.67       | 8.75    | 8.50 | 8.42    | 10.00      | 10.00     | 10.00     | 8.75           |
| 89.92         | 8.75  | 8.67   | 8.50       | 8.58    | 8.42 | 8.42    | 10.00      | 10.00     | 10.00     | 8.58           |

   
3. [Image Dataset](https://data.mendeley.com/datasets/52877z55vr/1) | License: CC BY 4.0

<img width="470" height="247" alt="image" src="https://github.com/user-attachments/assets/94d41ed5-2bd0-42ac-b879-1eea3cd7456e" />


### Milestones

1. Week 1-5 Research Coffee beans datasets and find out how to divide up tasks.
2. Week 6-8 Work on individual tasks, collaberate if needed.
3. Week 9 Combine notebooks and findings. Work out remaining requirements with the group.
4. Week 10 Finish the project and get feedback from faculty. 


## Installing the project

There is a requirements.txt file in the repo

Download and install Jupyter notebooks
```
pip install notebook
```
Download or clone the notebook folder from this Github repo '/notebooks'

Run 'Combined Notebook.ipynb' along with the depencies listed below:

```
pip install pandas numpy scipy matplotlib torch seaborn scikit-learn
```
Note: To use the ImageDataset.ipynb file, it neeeds to be placed in the same folder as the Image Dataset

## Data Preparation Pipeline

The data is prepared and cleaned within the 2nd cell of the 'Combined Notebook' notebook. The dataset is loaded into the notebook as a pandas dataframe. There is a line of code which gets the current directory of the notebook.
```
current_dir = os.getcwd()
coffee_df = pd.read_csv(f'{current_dir}/arabica_ratings_raw.csv')
```
The data is in arabica_ratings_raw.csv inside the same folder. 

Warning: The arabica_ratings_raw.csv must be in the same directory as the notebook.


## Coursework Requirements

### R2. Data Analysis and Exploration
Data Analysis and Exploration for the tabular dataset is in the PredictCoffeeOrigin.ipynb notebook under the folder "notebooks". We also have it in the Combined Notebook.ipynb with the other parts of the tabular dataset.
For the picture dataset, Data Analysis and Exploration is in ImageDataset_finish.ipynb in the notebooks folder. The corresponding sections in the file are "Taking Info on the Dataset" and "Exploratory Data Analysis (EDA)".

### R3.	Baseline Training and Evaluation Experiments
Baseline training and evaluation is in the notebook Aedh_Baseline.ipynb under the folder "notebooks" for the tabular dataset. We also have it in the Combined Notebook.ipynb with the other parts of the tabular dataset.
Baseline training and evaluation for the picture dataset is in the notebooks folder in ImageDataset_finish.ipynb and in the scripts folder in ImageDataset.ipynb. In both cases, they are the sections under "R3: Machine Learning ALgorithms".

### R4. Neural Networks
Neural Networks is in the Clustering_and_Regression.ipynb notebook under the folder "notebooks". We also have it in the Combined Notebook.ipynb with the other parts of the tabular dataset.
As in the other cases, the Neural Networks are in the notebooks folder in ImageDataset_finish.ipynb and in the scripts folder in ImageDataset.ipynb for the picture dataset. The programs are located in the "R4: Neural Networks" and "Neural Networks Evaluation" sections of the code.

## Documentation

Weekly updates are kept in the `documentation/` directory.
