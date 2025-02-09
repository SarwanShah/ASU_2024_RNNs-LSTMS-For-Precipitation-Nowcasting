# Understanding RNNs and LSTMs for Precipitation Nowcasting

## 📌 Project Overview  
This project was completed as a part of **EEE-560 Mathematical Foundations of Machine Learning** at **Arizona State University** during Spring 2024. This project explores the theoretical foundation, architecture, and applications of **Recurrent Neural Networks (RNNs)** and **Long Short-Term Memory (LSTM)** networks, with a specific focus on their use in **precipitation nowcasting**. The study emphasizes the mathematical modeling, training methodologies, and challenges of these neural network architectures.

**REPORT: [Final Paper](./SSHAH219-EEE560-Final-Paper.pdf)**

## 🛠 Project Features  
- **Neural Network Fundamentals**: Review of basic neural networks, including feed-forward architectures.
- **RNN and LSTM Modeling**: Analysis of temporal relationships in sequential data through RNNs and their architectural variant, LSTMs.
- **Challenges in Training**: Exploration of issues like vanishing and exploding gradients and methods to mitigate them.
- **Applications in Meteorology**: Use of LSTMs and ConvLSTMs for short-term precipitation predictions.
- **Advanced Architectures**: Overview of extensions such as **ConvLSTM** and **TrajGRU** for improved spatial and temporal modeling.

## 🏗 Implementation Details  

### ➤ **Neural Network Architecture**  
- **Single and Multi-Layer Networks**: Explains how multi-layer architectures capture complex patterns in data through non-linear activation functions.
- **Training via Backpropagation**: Describes how neural networks are trained using **gradient descent** and backpropagation.

### ➤ **RNNs**  
- **Temporal Layering**: Captures sequential dependencies by maintaining shared weights across time steps.
- **Backpropagation Through Time (BPTT)**: Modifies standard backpropagation to handle temporal sequences.

### ➤ **LSTMs**  
- **Cell States**: Introduces stable long-term memory storage to address gradient issues.
- **Gate Mechanisms**: Explains how input, forget, and output gates regulate hidden states and memory.

### ➤ **Applications in Precipitation Nowcasting**  
- **Short-Term Weather Forecasting**: Highlights the use of LSTMs for predicting precipitation within a 0 to 6-hour window.
- **ConvLSTM**: Enhances LSTM by adding spatial awareness through convolutional operations.
- **TrajGRU**: Introduces location-variant connections to improve modeling of motion patterns like rotation and scaling.

## 📚 Key Insights  
- Neural networks require **non-linear activation functions** to model complex patterns.
- RNNs and LSTMs excel at handling short-term sequential data but face challenges with long-term sequences.
- Advanced architectures like **ConvLSTM** and **TrajGRU** enhance both spatial and temporal modeling capabilities, making them well-suited for precipitation nowcasting.


This project contributes to the understanding of advanced neural network architectures and their application in real-world scenarios, particularly in meteorology.
