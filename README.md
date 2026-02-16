## Dataset

Due to size limitations, the dataset is hosted on Google Drive:

https://drive.google.com/drive/folders/1JBqn311D6y2JdDx9LVXixIlePPcp77lj?usp=sharing

The dataset consists of the following files:

- **`llm_repsim-20260216T052136Z-1-001.zip`**  
  Contains extracted layer-wise representations from large language models used for representation similarity analysis.

- **`embeddings-20260216T052057Z-1-001.zip`**  
  Contains sentence embeddings of generated outputs (tweets), used to compute output-level similarity.

- **`all_pair_sim-20260216T052156Z-1-001.zip`**  
  Contains precomputed pairwise similarity matrices between models and conditions.

After downloading, unzip the files and place them under the following directory structure:

```text
data/
├── llm_repsim/
├── embeddings/
└── all_pair_sim/
