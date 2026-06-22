# Skin Cancer Detection Binary Images Mini Dataset for Kids

A small, kid-friendly skin lesion image dataset designed for teaching machine learning, computer vision, and medical image classification concepts to children and beginners.

This dataset helps students understand how AI can learn patterns from images and classify skin lesions into two categories: cancerous and non-cancerous.

## 📁 Dataset Structure

```text
skin-cancer-detection-binary-images-mini-dataset-for-kids/
├── training/
│   ├── cancer/       # 33 training images
│   └── non_cancer/   # 33 training images
└── testing/
    ├── cancer/       # 5 testing images
    └── non_cancer/   # 5 testing images
```

### Classes

- `cancer`
- `non_cancer`

## 🎯 Purpose

This dataset is perfect for:

- Teaching machine learning to kids
- Introduction to medical image classification
- Computer vision learning activities
- Binary image classification projects
- Understanding patterns and predictions
- AI education and STEM programs
- Demonstrating healthcare applications of AI

## 📊 Details

| Attribute | Value |
|-----------|---------|
| Classes | 2 (cancer, non_cancer) |
| Training images per class | 33 |
| Total training images | 66 |
| Testing images per class | 5 |
| Total testing images | 10 |
| Total images | 76 |
| Dataset size | Mini/small |
| Source | Extracted from a larger skin disease classification dataset |

## 🧠 Learning Objective

Using this dataset, students can:

1. Train a simple image classification model
2. Learn how AI identifies visual patterns
3. Understand binary classification problems
4. Explore real-world healthcare applications of AI
5. Test model performance using unseen images
6. Learn the importance of training and testing datasets

## 🚀 Quick Start

```python
from pathlib import Path

dataset_dir = Path("skin-cancer-detection-binary-images-mini-dataset-for-kids")

for split in ["training", "testing"]:
    split_dir = dataset_dir / split
    print(f"\n{split.upper()}")

    for class_dir in split_dir.iterdir():
        if class_dir.is_dir():
            print(
                f"{class_dir.name}: "
                f"{len(list(class_dir.glob('*')))} images"
            )
```

## 🧪 Suggested Classroom Activity

1. Train an image classification model using the images in the `training` folder.
2. Use the images in the `testing` folder to evaluate the model.
3. Compare predictions with the actual labels.
4. Discuss how the model learned patterns from the images.

Questions for students:

- What visual differences might exist between the two classes?
- Why is this called a binary classification problem?
- Why do we keep separate training and testing datasets?
- How might additional images improve model performance?

## ⚠️ Educational Disclaimer

This dataset is intended **only for educational and learning purposes**.

- The dataset is designed to teach machine learning and computer vision concepts.
- It should **not** be used for medical diagnosis, treatment decisions, or healthcare advice.
- Real medical AI systems require significantly larger datasets, expert validation, and rigorous testing.

## ⚠️ Notes

- Images were extracted and prepared from a larger publicly available skin disease classification dataset
- Intended for educational purposes and beginner AI/ML projects
- Suitable for demonstrating binary image classification concepts
- Small size enables quick experimentation on local machines
- Appropriate for classroom demonstrations and guided learning activities

## 📝 License

Public dataset for educational use.

## 🙏 Acknowledgments

The images in this mini dataset were extracted from a larger publicly available skin disease classification dataset available on Kaggle. Credit belongs to the original dataset creators and contributors.

## 🔍 Keywords

Machine Learning for Kids, AI for Kids, Computer Vision Dataset, Medical Image Classification, Skin Cancer Detection, Skin Lesion Classification, Binary Classification Dataset, Healthcare AI, Educational Dataset, Beginner Machine Learning Dataset, Computer Vision for Beginners, Image Classification, Pattern Recognition, Prediction Models, Supervised Learning, STEM Education, Classroom AI Activities, Mini Dataset, Small Dataset, Medical AI Education

## 🏷️ Topics

#MachineLearning #ArtificialIntelligence #ComputerVision
#SkinCancerDetection #MedicalAI
#HealthcareAI #ImageClassification
#BinaryClassification #MachineLearningForKids
#AIForKids #EducationalDataset
#ComputerVisionDataset #STEMEducation
#PatternRecognition #SupervisedLearning
#DataScienceEducation #MiniDataset
#MedicalImageClassification

## 👨‍💻 Author

Prepared and curated by **Khairullah Hamsafar** for educational and classroom learning purposes.

Focused on making Machine Learning, Artificial Intelligence, Computer Vision, Data Science, and Generative AI accessible to children, students, educators, and beginners.
