# CGR and Multifractal Analysis of DNA Sequences

This repository contains Python notebooks and data for analyzing DNA sequences using Chaos Game Representation (CGR), time series transformations, Multifractal Detrended Fluctuation Analysis (MF-DFA), and Complexity-Entropy measures.

## Repository Structure


---

## Analysis Workflow

1. **Chaos Game Representation (CGR)**  
   Use `CGR.ipynb` to convert a DNA sequence into a CGR plot, which visualizes the distribution of k-mers in the sequence.  
   Input: DNA sequence file  
   Output: CGR image and k-mer distribution file  

2. **Time Series Transformation**  
   The `timeseries.ipynb` notebook converts the DNA sequence into a numerical time series based on base-pair mapping (e.g., A → 2, C → -2, G → 1, T → -1).  
   Input: DNA sequence file  
   Output: Time series file  

3. **Multifractal Detrended Fluctuation Analysis (MF-DFA)**  
   Apply `MFDFA.ipynb` to the generated time series to compute multifractal parameters, including the Hurst exponent, singularity spectrum, and scaling exponents.  
   Input: Time series file  
   Output: Hurst exponent plot, singularity spectrum, scaling exponent plot, and associated CSV files  

4. **Complexity-Entropy Analysis**  
   Run `complexity_entropy.ipynb` to compute the permutation entropy and statistical complexity of the time series.  
   Input: Time series file  
   Output: Permutation entropy and complexity metrics  

---

## Dependencies

Ensure the following Python libraries are installed before running the notebooks:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `ordpy`
- `MFDFA`
- `scipy`


