## Graph WaveNet Baseline Model Results

This folder contains the trained baseline model and test results. The implementation is attributed to work from the following paper: [Graph WaveNet for Deep Spatial-Temporal Graph Modeling, IJCAI 2019] (https://arxiv.org/abs/1906.00121) with citation:

"@article{wu2019graph,
  title={Graph wavenet for deep spatial-temporal graph modeling},
  author={Wu, Zonghan and Pan, Shirui and Long, Guodong and Jiang, Jing and Zhang, Chengqi},
  journal={arXiv preprint arXiv:1906.00121},
  year={2019}
}"

### Files
- `best_model.pth`: PyTorch checkpoint of the trained model
- `test.csv`: Test set predictions and ground truth
- `metrics.csv`: Evaluation metrics on the test set
- `args.pkl`: Pickled Python object storing the full set of training arguments
  (model architecture, optimisation hyperparameters, data settings, random seed)
  used to produce `best_model.pth`

### Environment
- Python:  3.9
- PyTorch: 1.10.2
- Device: MPS (Apple Silicon)
- Conda environment exported in `environment.yml`
