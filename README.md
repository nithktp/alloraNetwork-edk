# The AlloraEvaluator is part of the [Allora Network](https://allora.network) Evaluator Development Kit (EDK). It provides a modular framework to assess machine learning model performance using decentralized, configurable evaluation criteria.-.

---


## 📦 Installation 
```bash 
git clone https://github.com/nithktp/alloraNetwork-edk.git
 cd allora-edk-evaluator
pip install -r requirements.txt
 ```
 ## 🔧 Configuration 
 The config dictionary includes:
 
```bash
nano evaluator.py
```
 
```bash
config = {
  'evaluator_id': 'allora-edk-evaluator',
  'model_endpoints': [
    'http://model1.example.com/predict',
    'http://model2.example.com/predict'
  ],
  'evaluation_criteria': {
    'weights': {
      'accuracy': 0.5,
      'confidence': 0.3,
      'latency': 0.2
    }
  },
  'server_port': 5000
}



```
---
## 🧪 Example Usage Run the evaluator with a sample inference:

```
 python evaluator.py 
```
###  Output:

<img width="1258" height="1009" alt="image" src="https://github.com/user-attachments/assets/a29abb17-f30e-45c7-8e18-7b9532ba7d1f" />
