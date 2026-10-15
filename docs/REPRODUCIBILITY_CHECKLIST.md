# Computational Reproducibility Checklist for Machine Learning Papers

A checklist to ensure research artifacts satisfy ACM/IEEE artifact evaluation criteria:

### 1. Codebase & Environment
- [ ] Pinned dependency file provided (`environment.yml`, `requirements.txt`, or `Dockerfile`).
- [ ] Python, CUDA, and cuDNN versions explicitly stated.
- [ ] Single-command entry point available (e.g. `bash run_experiments.sh` or `python main.py --config config.yaml`).

### 2. Random Seeds & Determinism
- [ ] Random seeds fixed for NumPy, PyTorch, and random packages (`torch.manual_seed(42)`).
- [ ] Deterministic CuDNN flags set where applicable (`torch.backends.cudnn.deterministic = True`).
- [ ] Number of cross-validation folds and dataset splits clearly documented.

### 3. Hardware & Compute Metrics
- [ ] Compute hardware specified (e.g., NVIDIA A100 80GB, Intel Xeon).
- [ ] Total wall-clock training time reported.
- [ ] Peak GPU memory consumption and inference latency metrics documented.

### 4. Open Science & Data Availability
- [ ] Pre-trained weights hosted on Zenodo or Hugging Face Hub with permanent DOIs.
- [ ] Data preprocessing scripts included to convert raw datasets into model-ready tensors.
