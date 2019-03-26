# Summit Notebooks

*Summit: Scaling Deep Learning Interpretability by Visualizing Activation and Attribution Summarizations*

Summit is a an interactive system that summarizes and visualizes what features a deep learning model has learned and how those features interact to make predictions.
This repository contains the python notebooks used to generate the data used in the [Summit visualization][summit].

For the Summit visualization, go to [https://github.com/fredhohman/summit][summit].

### Main notebooks:

* [`activation-matrices.ipynb`](activation-matrices.ipynb): generate activation matrices
* [`activation-matrices-to-json.ipynb`](activation-matrices-to-json.ipynb): combine activation matrices per class into json format
* [`dag.ipynb`](dag.ipynb): making class attribution graphs from all influence matrices


### Experimental notebooks:

* [`top-channels-used-per-layer.ipynb`](top-channels-used-per-layer.ipynb): analysis for determining which channels were used the most by all classes for all layers

***

## Live Demo

For a live demo, visit: 


## Installation

Download or clone this repository:

```bash
git clone https://github.com/fredhohman/summit-notebooks.git
```


## Usage

To run Summit Nooteboks, run a Jupyter server:

```bash
jupyter lab
```


## License

MIT License. See [`LICENSE.md`](LICENSE.md).


## Contact

For questions or support [open an issue][issues] or contact [Fred Hohman][fred].

[summit]: https://github.com/fredhohman/summit
[fred]: http://www.fredhohman.com
[issues]: https://github.com/fredhohman/summit-notebooks/issues
