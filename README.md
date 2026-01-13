## GeNeRaTe: Generating Neural Representations from Text for Classification.

### Abstract
Advancements in language modelling over the last decade have significantly improved downstream tasks such as automated text classification. However, deploying such systems requires high computational resources and extensive training data. Human adults can effortlessly perform such tasks with minimal computational overhead and training data which prompts research into leveraging neurocognitive signals such as Electroencephalography (EEG). We compare BERT against EEG features captured during natural reading tasks for the downstream task of text classification. Additionally, we introduce GeNeRTe, a novel state-of-the-art synthetic EEG generative model. Using only a limited amount of data, GeNeRTe learns to produce synthetic EEG features for a sentence through a neural regressor that resolves the relationship between embeddings for a sentence and its natural EEG. From our experiments, we show that GeNeRTe can effectively synthesise EEG features for unseen test sentences with just 236 sentence-EEG training pairs. Furthermore, using synthetic EEG features significantly improves text classification performance and reduces computation time. Our results emphasise the potential of synthetic EEG features, providing a viable path to create a new type of physiological embedding with lower computing requirements and improved model performance in practical applications.

### This repository contains the data for our paper.

- The raw dataset for ZuCo can be found at: https://osf.io/q3zws/
- Our processed training data can be found in the data folder.
- Our model code can be found in the code folder.
- Our results can be found in the results folder.
- Checkpoints for GeNeRTe can be found in the model folder.
