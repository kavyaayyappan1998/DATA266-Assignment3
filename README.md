Main File:
main.ipynb

SET UP:
Install dependencies:

pip install torch numpy pandas matplotlib langchain langchain-ollama requests

For prompt experiments:
ollama pull llama 3.2:3b
ollama serve

Then run the notebook from top to bottom.

RESULTS:
The trained attention models produced:

Model                               Accuracy
Unmasked Attention                  97.8%
Causal Masked Attention             100%

The causal attention heatmap shows a clear lower-triangular pattern, confirming that tokens do not attend to future positions.
