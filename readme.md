# Used Car Price Prediction Tool 
 
| What to do: 	        | Deadline: 	| 
|---	                |---	        |
| Proof of Concept 	    | End of March  |
| Poster 	            | 28th March    |
| Dissertation Report 	| 25th April    |
| Degree Show 	        | 2nd May   	|

 ## Honours Plan
 <b> Stage 1. </b>
- [x] Obtained a dataset
- [x] Explored the dataset
- [X] Pre-Processed the dataset 
- [X] Research and Implement Triplet-Based DML's from Keras Libriary 
- [X] Implement both kNN models

 <b> Stage 2. </b>
- [ ] Select more datasets
- [ ] Explore datasets and see if possible to combine multiple 
- [ ] Apply a RF algorithm to the dataset/s 
- [ ] Use Compare results of the DMLs vs RF vs kNN
- [ ] Fine tune algorithms and\or insights into the AI reasoning for prices

 <b> Stage 3. </b>
- [ ] Build a streamlit based car price prediction tool
- [ ] Build car detail input system so users can predict the price of their own car 

## Potential DML Alternative if necissary 
PiTorch as a potential DML Libriary

## Meeting Notes from 05/02/2024
Anker and positive will be a matching pair, with a randomly selected negative that should be completely different

After the DML process end up with 3 arrays containing the indexes of the similar cars

For the DML's to work we need to cluster on a given category. The only one that makes sense is by creating a price range column. 
The range to be used could be found by looking at the distribution of prices of all cars in the dataset
Find the min and max prices too

### So for next week: 
- [ ] Decide on a price point, and implement range
- [ ] Finish Preprocessing
- [ ] Then implement Keras DML -> 'Image similarity estimation using a Siamese Network with a triplet loss'
- [ ] Visualise Clusters
### If there is time: 
- [ ] Create a baseline accuracy with kNN just on the non-clustered dataset

### For the explainable AI
Most Basic:
- [ ] Could list the similar cars in the cluster

- [ ] Counter Facual Expanations 

