# example-package-sergey
Packaging tutorial.

# Example Package sergey

`example-package-YOUR-USERNAME` is a simple Python library that contains a single function for rescaling arrays.

## Installation

Download the source code and use the package manager [pip](https://pip.pypa.io/en/stable/) to install `package`:

```bash
pip install .
```

## Usage

```python
import numpy as np
from example_package_sergey.rescale import rescale

# rescales over 0 to 1
rescale(np.linspace(0, 100, 5))
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
