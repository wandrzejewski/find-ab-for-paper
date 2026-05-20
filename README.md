# Reconstructing Projection Function From Selection-Projection Query Result

This repository contains the official code and resources accompanying the paper **"Reconstructing Projection Function From Selection-Projection Query Result"** by Witold Andrzejewski, Paweł Boiński, and Robert Wrembel.

## Citation

If you use this code, methodology, or data in your research or projects, please cite our paper:

> Witold Andrzejewski, Paweł Boiński, and Robert Wrembel. "Reconstructing Projection Function From Selection-Projection Query Result." *[Insert Journal/Conference Name]*, [Year]. [Insert DOI or URL]

### BibTeX
```bibtex
@inproceedings{andrzejewski_reconstructing,
  title={Reconstructing Projection Function From Selection-Projection Query Result},
  author={Andrzejewski, Witold and Boi{\'n}ski, Pawe{\l} and Wrembel, Robert},
  booktitle={[Insert Journal/Conference Name]},
  year={[Year]},
  doi={[Insert DOI]}
}
```

## Setup and Usage

This project uses Python. The core numerical processing and JIT compilation rely on `numpy` and `numba`. Standard library modules (`time`, `contextlib`) are used for performance profiling and execution management, so they do not require separate installation.

### 1. Requirements

Ensure you have Python 3.10+ installed. Install the required external packages using pip:

```bash
pip install numpy numba
```


### 2. Running the Code

To execute the projection function reconstruction script, run the main Python file from your terminal:

```bash
python main.py
```
## License

This project is licensed under the **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** license. 

You are free to share and adapt the material for any purpose, even commercially, under the following terms:
* **Attribution:** You must give appropriate credit (cite the paper above), provide a link to the license, and indicate if changes were made.
* **ShareAlike:** If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

See the [LICENSE](LICENSE) file or visit the [Creative Commons website](https://creativecommons.org/licenses/by-sa/4.0/) for full details.
