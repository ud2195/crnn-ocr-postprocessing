# CRNN OCR Post-processing

This project implements post-processing logic for a CRNN-based OCR model. The main tasks include:

1. Removing duplicate character predictions from timestep-level outputs.
2. Computing a confidence score for the predicted text.
3. Generating approximate character-level regions/masks from model predictions.

The detailed thought process, implementation decisions, and assumptions for each task are documented directly under the corresponding task cells in the notebook.