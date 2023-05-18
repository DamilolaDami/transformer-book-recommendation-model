# transformer-book-recommendation-model
This repository contains a recommendation model based on transformer architecture for personalized book recommendations. The model leverages transfer learning and fine-tuning techniques using a pre-trained transformer model to generate highly relevant book recommendations based on book names.

The dataset used for training and evaluation is `goodreads_data.csv`. This CSV file contains book information including book names, genres, descriptions, and average ratings. It serves as the basis for training the recommendation model.


This will install the necessary packages, including pandas, numpy, sentence_transformers, tqdm, and scikit-learn.

## Usage

1. Data Preprocessing:

- Ensure that the `goodreads_data.csv` file is located in the same directory as the Jupyter Notebook (`books_recommendations_model.ipynb`).
- Open the Jupyter Notebook and run the cells to preprocess the data, including cleaning, preprocessing, and encoding book genres and descriptions.

2. Fine-tuning the Model:

- Using the preprocessed data, fine-tune the transformer-based model for recommendation by running the corresponding cells in the Jupyter Notebook.

3. Generating Recommendations:

- After the model is fine-tuned, utilize it to generate personalized book recommendations by running the relevant code cells in the Jupyter Notebook.
- Provide a book ID as input to get recommendations for that particular book.

## Contributing

Contributions to this repository are welcome. If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
