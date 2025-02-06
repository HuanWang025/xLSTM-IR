# Cognitive-inspired xLSTM for Multi-agent Information Retrieval

## 📌 Introduction

In the era of big data and complex information retrieval tasks, multi-agent systems play a crucial role in handling large-scale, complex queries across various domains. Traditional approaches, such as BERT, RoBERTa, and Transformer models, have been widely used in information retrieval. However, these methods often suffer from computational inefficiencies and limited coordination between agents when dealing with long-term dependencies and collaborative tasks.

To address these challenges, we propose **Cognitive-inspired xLSTM**, a novel model designed specifically for **multi-agent information retrieval**. The model introduces **advanced memory mechanisms, shared memory structures, and dynamic gating functions**, enabling **efficient long-term dependency management and enhanced agent collaboration**.

## 🚀 Key Features

- **Advanced Memory Mechanisms**: Efficient long-term dependency management.
- **Shared Memory Structures**: Facilitates collaboration between multiple agents.
- **Dynamic Gating Functions**: Adaptive processing of information for optimized retrieval.
- **Improved Efficiency**: Faster training and inference compared to existing methods.
- **State-of-the-Art Performance**: Outperforms leading models on key metrics.

## 📊 Experimental Results

Our model was evaluated on four benchmark datasets:

- **HotpotQA**
- **APPS**
- **MBPP**
- **FEVER**

### 📈 Performance Comparison

xLSTM significantly outperforms **six state-of-the-art** methods in terms of:

- **Training Time**
- **Inference Time**
- **Accuracy**
- **Recall**
- **F1 Score**

## 🛠 Installation

To set up the project, follow these steps:

```bash
# Clone the repository
git clone https://github.com/your-repo/xLSTM-Information-Retrieval.git
cd xLSTM-Information-Retrieval

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'

# Install dependencies
pip install -r requirements.txt
