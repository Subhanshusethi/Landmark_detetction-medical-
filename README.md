# README

## Training Instructions

To start training from scratch, set the `LOAD_MODEL` value to `False` and run all cells in the notebook.

## Testing and Validation

For testing and validation:
- Specify the path to the model weights for hypotheses 1 (hyp1) and 2 (hyp2) from the model_weights folder.
- Set `LOAD_MODEL` to `1` for Hypothesis 1.
- Set `LOAD_MODEL` to `2` for Hypothesis 2.

This will iterate through the dataset. Results will be saved in the "saved images" folder after each epoch, which is continuously updated.
