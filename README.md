# Feedback-Generation
In this repository, you will find databases used in work titled "Harnessing Graph Neural Networks to Craft Fragrances Based on Consumer Feedback". Below you will find a description of the included files:

**Train GGNN**:
This folder contains three files. To train the GGNN a large database containing several fragrant molecules was split into three sets: one for training, one for testing, and one for validation. The files include the SMILES representation of the molecules used.

**Transfer Learning**:
This folder contains several subfolders, one for each fragrance note used in the Transfer Learning process. Similarly to "Train GGNN", each fragrance note contains three files relative to the three sets used by the model.

**Autoencoder Embeddings**:
This database contains the compressed form of the boolean matrix that relates perfumes to their fragrance notes. It results from the execution of the Autoencoder on the boolean matrix.

**Parfumo**:
This database contains all the information extracted from the Parfumo forum. It includes 27,443 perfumes, with basic information (name, brand, year, and target gender), fragrance notes, and numerical evaluations for scent and other aspects of the perfumes.

**Vapor Pressure KMeans**:
This database contains substances and information on their vapor pressure and boiling points. It was used to define vapor pressure boundaries for the three fragrance note levels (top, middle, and base)

**Vocabulary Mapping**:
Database containing the vocabulary that describes fragrance notes used in the training of the GGNN model (Scrapped from the Good Scents Company) and the equivalent words used in the Parfumo forum.
# Feedback-Generation
