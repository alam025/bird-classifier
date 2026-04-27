```markdown
<!-- Capsule Render Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=150&section=header&text=Image%20Classifier%20App&fontSize=50&fontColor=FFFFFF" />
</div>

<!-- Typing SVG -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=0xF7B2A1&size=30&lines=Fine-tuned+ResNet-50+achieving+91%25+Top-5+accuracy;Built+with+Python+%7C+PyTorch+%7C+Gradio+%7C+AWS+S3" />
</div>

<!-- Badges -->
<div align="center">
  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=ffffff)
  ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2A?style=flat&logo=pytorch&logoColor=ffffff)
  ![Gradio](https://img.shields.io/badge/Gradio-00B140?style=flat&logo=gradio&logoColor=ffffff)
  ![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat&logo=amazonaws&logoColor=ffffff)
</div>

<!-- Mermaid Diagram -->
```mermaid
graph TD;
    A[User] -->|Uploads Image| B[Gradio Interface]
    B --> C[Model Prediction]
    C --> D[ResNet-50]
    D -->|Returns Result| B
    B -->|Displays Result| A
```

<!-- Performance Metrics Table -->
| Metric              | Value                       |
|---------------------|-----------------------------|
| Model               | ResNet-50                   |
| Top-5 Accuracy      | 91%                         |
| Dataset             | CUB-200                    |
| Deployment Platform  | HuggingFace Spaces          |

<!-- Quick Start -->
## Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/alam025/bird-classifier.git
   ```
2. Install the dependencies:
   ```bash
   cd bird-classifier
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

<!-- Tech Stack -->
## Tech Stack
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gradio/gradio-original.svg" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" width="40" height="40" />
</div>

<!-- Capsule Render Footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=150&section=footer&text=Thank%20You%20for%20Visiting!&fontSize=30&fontColor=FFFFFF" />
</div>
```