# MSE1065_Brohath_1004517383
Fall 2022 - MSE 1065 - AI in Materials Design 

<b> Dataset Selection </b>
<p>
The dataset is from the paper "Nonaqueous rechargeable aluminium batteries." The dataset can be found in the supplementary material. Here is the 
<a href = "https://doi.org/10.1016/j.joule.2021.12.003"> DOI <a>
for the paper.
</p>

<b> Dataset CSV </b>
<p>
<a href = "https://github.com/BrohathA/MSE1065_Brohath_1004517383/blob/main/Primary%20Dataset.csv"> File <a>
</p>

<b> Featurisation Plan </b>
<p>
..* Cathode - composition of elements, type of structure (nano, composite, pure) (one-hot encoding), type of material (sulphide, oxide, graphitic etc.) (one-hot encoding)
..* Electrolyte - ionic conductvity, SMILES 
..* Mechanism - CV Oxidation and Reduction Peaks, 16 possible (one-hot encoding) 
</p>

  <b> Learning Task </b>
  ..* Basic: Try to classify the materials based on Capacity, Energy and Power Density 
  ..* Couple of ways to go about it: either predict capacity using features or predict mechanism using features 
  </p>
 
