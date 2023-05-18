# transformer-book-recommendation-model
This repository contains a recommendation model based on transformer architecture for personalized book recommendations. The model leverages transfer learning and fine-tuning techniques using a pre-trained transformer model to generate highly relevant book recommendations based on book names.
## Usage

1. Preprocess the data:

- Prepare a CSV file containing book names and relevant labels.
- Update the `data.csv` file with the appropriate data.

2. Fine-tune the model:

- Run the `train_model.py` script to fine-tune the transformer model on the provided data.

3. Generate recommendations:

- Update the `generate_recommendations.py` script with the path to the fine-tuned model.
- Run the `generate_recommendations.py` script and provide a book name as input to get personalized recommendations.

## Contributing

Contributions to this repository are welcome. If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
