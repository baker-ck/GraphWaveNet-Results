## Graph WaveNet Baseline Model Results

This folder contains the trained baseline model and test results.

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
