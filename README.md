# APS360 - Speech Emotion Recognition Project

## Progress Tracking

| Task                            | Description                                                                         | Team Member       | Internal Deadline | Completed?  |
|---------------------------------|-------------------------------------------------------------------------------------|-------------------|-------------------|-------------|
| Data preprocessing              | Retrieve and label audio clip datasets                                              | Paul, Saad        | Feb 18            | Y           |
| Audio Feature Expansion         | Use librosa library to extract features                                             | Paul, Saad        | Feb 22            | Y           |
| Baseline Model                  | Develop random forest model and perform end-to-end testing                          | Muhammad, Saad    | Feb 25            | Y           |
| Initial NN Model                | Build Neural Network Model using NLS + feedforward ANN                              | Muhammad, Mahmoud | Feb 27            | Y           |
| Progress Report                 | Work on progress report                                                             | ALL               | Mar 02            | In Progress |
| LSTM Model                      | Modify initial NN to include LSTM layers                                            | Muhammad, Mahmoud | Mar 07            |             |
| Tune Hyperparameters (learning) | Investigate and analyze effect of learning rate, batch size, dropout rate           | Paul, Saad        | Mar 14            |             |
| Tune Hyperparameters (LSTM)     | Investigate different LSTM layers and Uni vs Bidirectional                          | Muhammad, Mahmoud | Mar 20            |             |
| Finalize Model                  | Based on all gathered findings, finalize the model before proceeding with test data | ALL               | Mar 30            |             |
| Project Presentation            | Prepare slides and demo                                                             | ALL               | April 06          |             |
| Final Deliverable               | Prepare final report and summarize findings                                         | ALL               | April 13          |             |

## Result Tracking

|            | Test Accuracy |
|------------|---------------|
| Baseline   | 53.53%        |
| Initial NN | 64.11%        |

### Useful resources
NSL with keras: <a href="https://www.tensorflow.org/neural_structured_learning">tensorflow NSL </a> <br>
NSL tutorial: <a href="https://analyticsindiamag.com/tensorflows-neural-structured-learning-makes-deep-learning-super-easy/"> tutorial </a> <br>
Cuda with tensorflow: <a href="https://colab.research.google.com/notebooks/gpu.ipynb"> tf cuda </a> <br>
