# pycounts_mds_yibin

Calculate word counts ina a text file!

## Test Pypi Link

https://test.pypi.org/project/pycounts_mds_yibin/

## Installation

```bash
$ pip install -i https://test.pypi.org/simple/ pycounts_mds_yibin
```

## Usage

`pycounts_mds_yibin` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_mds_yibin.pycounts import count_words
from pycounts_mds_yibin.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_mds_yibin` was created by Yibin Long. It is licensed under the terms of the MIT license.

## Credits

`pycounts` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
