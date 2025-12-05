# AI4Mars

## Rover Image Classification -- Evaluating Terrain Risk with Ai

This GitHub repository contains a Jupyter notebook that processes the AI4Mars dataset, which includes navigation camera images from the Curiosity, Opportunity, and Perseverance rovers. The notebook performs terrain classification to assess the traversability risk of each view, supporting autonomous rover navigation by providing an overall assessment of terrain safety. A lower risk score indicates a safer path for the rover to move in that direction. The dataset uses crowdsourced, labeled images from citizen scientists, and in this project, it is trained using a custom-built CNN model and a transfer learning approach with EfficientNet-B0 for improved performance and generalization.

## Documentation

[Research Report](./ai4mars-risk-classification-report.pdf)

## Results

-   82.6% accuracy achieved with EfficientB0 transfer learning and fine tuning
-   87.6% model size reduction vs baseline DeepLabv3 used by JPL
