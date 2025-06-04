# Side-Channel Power Analysis Lab
Demonstration of CPA &amp; DPA Attacks against AES

## Features

- Walkthrough of CPA and Monobit DPA attacks on AES-128
- Analysis and visualization of real power traces
- Full attack pipeline: trace loading -> key recovery -> message decryption

## Getting Started

1. Clone this repository.
2. Install requirements:  
   ```
   pip install pycryptodome scared matplotlib
   ```
3. Open and run the notebook: `Lab.ipynb`

## Alternative: View the Notebook Online
- [Run & Interact on Binder](https://mybinder.org/v2/gh/Red91K/Side-Channel-Power-Analysis-Lab/HEAD?urlpath=%2Fdoc%2Ftree%2FLab.ipynb)
- [View on nbviewer](https://nbviewer.org/github/Red91K/Side-Channel-Power-Analysis-Lab/blob/main/Lab.ipynb)  

## References

- [Scared Library Documentation](https://eshard.gitlab.io/scared/guides/dpa_v2_attack.html)
- [Intro to Power-Based Side-Channel Attacks](https://www.allaboutcircuits.com/technical-articles/a-basic-introduction-to-power-based-side-channel-attacks/)
