
# DoDUO - Annotating Columns with Pre-trained Language Models

In this phase of our assignment, we focused not only to explore but also to improve 
the DoDUO model variants of our selected paper (https://github.com/megagonlabs/doduo).

**This repository consists mainly of 6 below notebooks**:
* ***DoDUO_Finetune_MSP_Inference.ipynb***
  An implementation of finetuning the pretrained DoDUO (given) 
  with Masked Column Prediction (MCP), along with its inference
  
* ***T5_single_column_annotation.ipynb***
  An implementation of single column annotation, same approach as mentioned in the paper,
  where the main architecture is based on the T5 model.

* ***T5_single_colpair_columns_relationship.ipynb***
  An implementation of single column relationship, same approach as mentioned in the paper,
  where the main architecture is based on the T5 model.

* ***T5_single_column_MTL.ipynb***
  An implementation of single column relationship & single column annotation, 
  where we introduce a single unified T5 model training for both tasks though 
  Multi Task Learning.

* ***T5_tablewise_annotation.ipynb***
  An implementation of multi-column (tablewise) annotation, same approach as mentioned in the paper,
  where the main architecture is based on the T5 model.

* ***T5_tablewise_relationship.ipynb***
  An implementation of multi-column (tablewise) relationship, same approach as mentioned in the paper,
  where the main architecture is based on the T5 model.

***Important Notes***
An overall graph with all the F1 validation score of the T5 model variants

***Important Notes***
- In all the respective notebooks, the official DoDUo repository is cloned and integrated
  via the "git clone" command.
- The requirements.txt file is generated from the Coolab-notebook envrironment of the notebooks.
- **All the python scripts (\*.py) are generated and downloaded from the respective notebooks.**
- All the notebooks are executable, therefore it is easy to reproduce the results with no limitations at all.
