# Transfer-Learning-With-MOBINET 

This project demonstrates transfer learning using MobileNetV2 for custom image classification tasks.

## Setup

1. Install dependencies: `pip install tensorflow keras numpy matplotlib`
2. Organize dataset into train/validation/test directories.

## Training

- Load MobileNetV2 pre-trained model.
- Add custom top layers for specific task.
- Compile model with appropriate settings.
- Train model on training dataset.
- Evaluate model on validation dataset.

## Fine-tuning

- Fine-tune model by unfreezing base layers.
- Compile model with lower learning rate.
- Continue training on same dataset.

## Results

- Visualize training and validation metrics.
- Evaluate model on test dataset.

## Usage

Modify code for your dataset and requirements.

## Contributing

Contributions welcome! Open issues or submit pull requests.

## License

This project is licensed under the MIT License.
