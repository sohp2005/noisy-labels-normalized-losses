
## Author

**Name:** Soham Ulhas Pujari  
**ID:** 2024A7PS0490G

---

###  Impoving accuracy of models for a dataset with noisy labels

This project focused on **robust learning under noisy labels**. The goal was to test how different loss functions handle increasing levels of label noise:

- Introduced **symmetric noise** to the CIFAR-10 dataset.
- Implemented and compared:
  - `Cross-Entropy (CE)`
  - `Normalized Cross-Entropy (NCE)`
  - `Active-Passive Loss (APL = NCE + RCE)`
- Plotted accuracy vs. noise rate to highlight differences in **robustness**.
- Evaluated performance as noise levels increased.
