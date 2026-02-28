# QUEST-PCC  
A Reference Dataset for Content-Aware V-PCC Streaming and Compression

QUEST-PCC is an open-source reference dataset for objective quality-driven evaluation of heterogeneous dynamic point clouds encoded using **MPEG Video-based Point Cloud Compression (V-PCC)**.

Unlike existing human-centric volumetric datasets, QUEST-PCC spans six diverse object categories — Vehicle, People, Architecture, Artifact, Animal, and Furniture — enabling systematic analysis of **content-dependent rate–distortion behavior** in volumetric compression and immersive streaming systems.

The dataset provides:

- Compressed V-PCC bitstreams (r1–r5 rate levels)  
- Reconstructed dynamic PLY point clouds  
- Standardized per-frame MPEG PCC quality metrics (MSE P2P, PSNR P2P, RGB PSNR)  
- Reproducible encoding configuration using MPEG TMC2  

QUEST-PCC is designed to support research in volumetric adaptive streaming, content-aware encoding, bitrate ladder construction, and cross-layer optimization for 6DoF media systems.

---

## 📦 Dataset Release

The full dataset (bitstreams, reconstructed sequences, and evaluation metrics) is now publicly available.

🔗 **Download here:**  
[Google Drive – QUEST-PCC Dataset](https://drive.google.com/drive/folders/1HKYqNgmdU2KyiLmnzftzfPB_whFBvkx_)

If you use QUEST-PCC in your research, please cite our paper. 

For questions or issues, please open a GitHub issue.


## ACM Reference Format

```text
Sidhu, J. S., Bentaleb, A., Hamza, A. and Gudumasu S. 2026.
QUEST-PCC: A Reference Dataset for Content-Aware V-PCC Streaming and Compression.
In Proceedings of the 17th ACM Multimedia Systems Conference 2026 (MMSys '26),
April 4-8, 2026, Hong Kong, Hong Kong. ACM, New York, NY, USA, 6 pages.
https://doi.org/10.1145/3793853.3799809
```

### BibTeX

```bibtex
@inproceedings{sidhu2026quest,
  author    = {Sidhu, Jashanjot Singh and Bentaleb, Abdelhak and Hamza, Ahmed and Gudumasu, Srinivas},
  title     = {QUEST-PCC: A Reference Dataset for Content-Aware V-PCC Streaming and Compression},
  booktitle = {Proceedings of the 17th ACM Multimedia Systems Conference 2026 (MMSys '26)},
  year      = {2026},
  month     = apr,
  address   = {Hong Kong, Hong Kong},
  publisher = {ACM},
  doi       = {10.1145/3793853.3799809}
}
```
