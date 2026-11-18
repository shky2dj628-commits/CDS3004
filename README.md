# CDS3004
Agent-assisted data mining group project for CDS3004

## Reproducibility
To reproduce our results:
1. Ensure `random_state=42` is used in `train_test_split`.
2. Run the Jupyter Notebook from top to bottom.
3. The model will output the exact Confusion Matrix: `[[67, 13], [29, 10]]`.

## AI Agent Trajectory
*   Agent was used to suggest variable types.
*   Human intervention: Manually overrode the Agent's classification of `studytime` from Nominal to Ordinal.
