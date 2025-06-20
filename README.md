# Post-OCR Text Correction for Bulgarian historical documents
A repository for post-OCR text correction for Bulgarian historical documents written in the Drinov or Ivanchev orthographies. Code for the paper: https://link.springer.com/article/10.1007/s00799-025-00415-x

## Description
In this work, we focus on Bulgarian, and we create the first benchmark dataset for evaluating the OCR text correction for historical Bulgarian documents written in the first standardized Bulgarian orthography: the Drinov orthography from the 19th century. We further develop a method for automatically generating synthetic data in this orthography, as well as in the subsequent Ivanchev orthography, by leveraging vast amounts of contemporary literature Bulgarian texts. We then use state-of-the-art LLMs and encoder-decoder framework which we augment with diagonal attention loss and copy and coverage mechanisms to improve the post-OCR text correction. The proposed method reduces the errors introduced during the recognition. It improves the quality of the documents by 25%, which is an increase of 16% compared to the state-of-the-art on the ICDAR 2019 Bulgarian dataset.

## Citation
Beshirov, A., Dobreva, M., Dimitrov, D., Hardalov, M., Koychev, I., & Nakov, P. (2025). Post-OCR Text Correction for Bulgarian historical documents. International Journal on Digital Libraries. https://doi.org/10.1007/s00799-025-00415-x
