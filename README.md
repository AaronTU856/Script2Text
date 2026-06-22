# Script2Text

An image-processing project exploring a practical preprocessing pipeline for handwritten-text recognition. The work focuses on preparing scanned handwriting for downstream OCR through colour conversion, contrast transformation, denoising, binarisation and segmentation experiments.

## Technical Focus

- Python
- OpenCV and image-processing workflows
- Jupyter notebooks for reproducible exploration
- TIFF and PNG image handling
- Image denoising, thresholding, histogram analysis and segmentation

## Repository Structure

```text
src/            Small Python experiments and sanity checks
notebooks/      Exploratory image-processing workflows
data/samples/   Sample handwritten inputs
Images/         Supporting project images
```

## Run Locally

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Open the notebooks in `notebooks/` to follow the preprocessing experiments. The sample data is included for learning and demonstration purposes only.

## Portfolio Context

This is a supporting technical portfolio project rather than a production OCR product. It is useful evidence of image-processing fundamentals and experimental workflow, but should be pinned only after the notebooks have clear narrative outputs and before/after visual results.
