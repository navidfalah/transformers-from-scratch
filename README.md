# 🐍 Transformer Architecture Implementation

## 📝 Description
This Python script demonstrates the implementation of a **Transformer architecture** from scratch, including **self-attention**, **multi-head attention**, and **feed-forward layers**. It also visualizes attention mechanisms using the `bertviz` library. The script includes a custom Transformer encoder layer and a sequence classification model.

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/navidfalah/transformer-architecture.git
   cd transformer-architecture
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Install additional libraries:
   ```bash
   pip install bertviz torch transformers
   ```

## 🚀 Usage
1. Run the script:
   ```bash
   python transformer_architecture.py
   ```
2. The script will:
   - Visualize attention mechanisms using `bertviz`.
   - Implement and demonstrate self-attention, multi-head attention, and feed-forward layers.
   - Build a custom Transformer encoder layer and sequence classification model.

## 📂 File Structure
```
transformer-architecture/
├── transformer_architecture.py  # Main script
├── README.md                    # This file
├── requirements.txt             # Dependencies
└── data/                        # (Optional) Data folder for local inputs
```

## 🧩 Key Features
- **Attention Visualization**:
  - Use `bertviz` to visualize attention heads in BERT.
- **Self-Attention**:
  - Implement scaled dot-product attention.
- **Multi-Head Attention**:
  - Combine multiple attention heads for richer representations.
- **Feed-Forward Layer**:
  - Apply a two-layer feed-forward network with GELU activation.
- **Transformer Encoder**:
  - Build a custom Transformer encoder layer with skip connections and layer normalization.
- **Sequence Classification**:
  - Implement a Transformer-based sequence classification model.

## 📊 Example Outputs
1. **Attention Visualization**:
   - Visualize attention heads for the input: "time flies like an arrow".
2. **Self-Attention Output**:
   - Shape: `(batch_size, sequence_length, hidden_size)`.
3. **Multi-Head Attention Output**:
   - Shape: `(batch_size, sequence_length, hidden_size)`.
4. **Feed-Forward Output**:
   - Shape: `(batch_size, sequence_length, hidden_size)`.
5. **Sequence Classification Output**:
   - Shape: `(batch_size, num_labels)`.

## 🤖 Models Used
- **BERT**: For attention visualization.
- **Custom Transformer**: For implementing self-attention, multi-head attention, and feed-forward layers.

## 📈 Performance Metrics
- **Attention Visualization**: Visualize attention weights.
- **Output Shapes**: Verify the shapes of intermediate outputs.

## 🛠️ Dependencies
- Python 3.x
- Libraries:
  - `torch`, `transformers`
  - `bertviz`, `numpy`

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 👤 Author
- **Name**: Navid Falah
- **GitHub**: [navidfalah](https://github.com/navidfalah)
- **Email**: navid.falah7@gmail.com
