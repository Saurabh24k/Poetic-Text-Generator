# Poetic Text Generator

The Poetic Text Generator is a deep learning project designed to mimic the style of Shakespeare's writings. Using TensorFlow and Keras, this project utilizes a character-level LSTM network to generate poetic text based on the extensive corpus of Shakespeare's works.

## Getting Started

### Prerequisites

- Python 3.6+
- TensorFlow 2.x
- NumPy

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/Saurabh24k/Poetic-Text-Generator.git
cd Poetic-Text-Generator
```

Install the necessary Python packages:

```bash
pip install -r requirements.txt
```

### Usage

Run the main script to start generating text:

```bash
python main.py
```

### How It Works
The project trains an LSTM model on a dataset comprised of Shakespeare's works. By analyzing the patterns in character sequences, the model learns to predict the next character in a sequence, thereby generating text one character at a time.

### Contributing
Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

1. Fork the project.
2. Create your feature branch:
   
   ```bash
   git checkout -b feature/AmazingFeature
   ```
   
3. Commit your changes
   
   ```bash
   git commit -m 'Add some AmazingFeature'.
   ```
   
4. Push to the branch
   
   ```bash
   git push origin feature/AmazingFeature.
   ```
   
5. Open a pull request.
