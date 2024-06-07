# InformationVisualization: Concept Drift

## Information

This is a sample script on how to represent the concept drift with Parallel Histograms through Time (PHT), a representation based on Parallel Coordinates.

## Usage

Install the required packages, then proceed with the unzipping of the datasets:

```bash
pip install -r requirements.txt
cd data/
for i in *.zip ; do unzip $i ; done
cd ..
jupyter notebook concept-drift-visualization.ipynb
```
