# Fine-tuning a Large Language Model for Text Classification Task

| Model        | Weights   | Trainable token | Trainable layers        | Context length                            | CPU/GPU | Training time | Training acc | Validation acc | Test acc |
|--------------|-----------|-----------------|-------------------------|-------------------------------------------|---------|---------------|--------------|----------------|-----------|
| Phi-3 (3.8 B)| instruct  | last            | head                    | dynamic padding (batch-wise)        | T4 (Colab free)    | 0.63 min      | 99.51%       | 99.32%         | 96.66%    |
