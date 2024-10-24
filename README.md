# BERT-Based Plagiarism Detection Tool

## Overview

This repository contains a BERT-based plagiarism detection tool designed to identify similarities between a given document and a set of reference documents. By leveraging Natural Language Processing (NLP) techniques, this tool accurately computes the percentage of matching content, making it an invaluable resource for academic integrity and content originality assessment.

## Features

- **High Accuracy:** Utilizes the BERT model to understand context and semantics, providing reliable plagiarism detection.
- **Easy-to-Use Interface:** Simply input a document and a set of reference documents to obtain similarity results.
- **Detailed Reports:** Generates a comprehensive report indicating the percentage of matching content for each reference document.
- **Flexible Input:** Supports various text formats, making it adaptable for different use cases.

## Installation

To run the plagiarism detection tool, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmdmohamedd/bert-plagiarism-detection.git
   ```

2. Navigate to the project directory:
   ```bash
   cd bert-plagiarism-detection
   ```

3. Create a virtual environment (optional but recommended):
   ```bash
   conda create --name plagiarism_detection python=3.8
   conda activate plagiarism_detection
   ```

## Usage

1. Open the `bert_plagiarism_detection.ipynb` Jupyter Notebook.
2. Load the necessary libraries and input your documents:
   ```python
   example_text = "This is a sample document used for testing plagiarism detection."
   
   data = {
       'doc_id': [1, 2, 3],
       'text': [
           "This is a sample document used for testing plagiarism detection.",
           "This is a test document designed to evaluate plagiarism detection.",
           "She opened the book and immediately got lost in the story's magical world."
       ]
   }
   ```
3. Run the cells to preprocess the text, compute similarities, and generate the plagiarism report.

## Example Output

The output will show the percentage of content matching between the input document and each of the reference documents:

```
Plagiarism Results:
Source Document 1: 100.00% of content matches.
Source Document 2: 100.00% of content matches.
Source Document 3: 0.00% of content matches.
```

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.
