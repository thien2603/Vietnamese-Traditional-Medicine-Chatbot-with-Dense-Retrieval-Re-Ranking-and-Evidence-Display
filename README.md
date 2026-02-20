# README

Google Colab link: https://colab.research.google.com/drive/1Ey1kVE_p9bnC5qpwYqMqJOTJSoESJ7Sx?usp=sharing

## How to run
1. Open the Colab link.
2. Import data files.
3. Run all cells: Runtime → Run all (or use the play buttons).
4. Try to make other query input for different result.

## Import data files into the runtime
- Upload from your local machine (drag the files):
- Or mount Google Drive:
```python
from google.colab import drive
drive.mount('/content/drive')
```
- After uploading, paths are typically under `/content/` or `/content/drive/My Drive/`.