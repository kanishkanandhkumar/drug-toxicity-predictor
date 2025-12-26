
```
Drug Toxicity Predictor

This project predicts if a molecule is toxic using its SMILES string.

How to use:
from src.predict import predict

result = predict("CC(=O)OC1=CC=CC=C1C(=O)O")  # Aspirin
print(f"Prediction: {result['prediction']}")

Files needed:
- models/bbbp_toxicity_model.pth  (The trained model)
- src/predict.py                  (Code to make predictions)
- data/BBBP.csv                   (The data used for training)

Install:
pip install torch numpy pandas scikit-learn
```


```python
with open('README.txt', 'w') as f:
    f.write('''Drug Toxicity Predictor

This project predicts if a molecule is toxic using its SMILES string.

How to use:
from src.predict import predict

result = predict("CC(=O)OC1=CC=CC=C1C(=O)O")  # Aspirin
print(f"Prediction: {result['prediction']}")

Files needed:
- models/bbbp_toxicity_model.pth  (The trained model)
- src/predict.py                  (Code to make predictions)
- data/BBBP.csv                   (The data used for training)

Install:
pip install torch numpy pandas scikit-learn''')
```
