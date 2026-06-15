# From Single-Step to Iterative Vulnerabilities: A Comparative Evaluation of FGSM and PGD in Deep Vision Architectures

## Author
* **Prerona De** - June 2026

## Abstract
Adversarial machine learning has emerged as a critical field addressing the vulnerabilities of AI systems to maliciously crafted inputs. This paper bridges foundational and advanced adversarial attack methods by comparing the Fast Gradient Sign Method (FGSM) and Projected Gradient Descent (PGD) in deep vision architectures. 

Our results demonstrate that while FGSM provides a quick and computationally inexpensive attack, PGD's iterative approach significantly outperforms FGSM in reducing model accuracy. Furthermore, we observe catastrophic overfitting when training solely against FGSM, resulting in models highly vulnerable to PGD attacks.

## Empirical Evaluation Metrics
The evaluated ResNet-18 model architecture was trained on the CIFAR-10 dataset and tested under standard cross-entropy loss against both attack configurations ($\epsilon=8/255$):

| Attack Type | Target Accuracy |
| :--- | :--- |
| **No Attack (Clean)** | 92.3% |
| **FGSM (Single-Step)** | 55.7% |
| **PGD (10 Iterations)** | 32.4% |

## PDF Document
The complete written formal research report detailing the methodologies, mathematical frameworks, and literature background can be found inside this repository as a PDF:
👉 **[View Full Paper PDF](./ModelStressTest.pdf)**
