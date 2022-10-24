# simbio-<name>

## Installation

```
pip install simbio-<name>
```

## Usage

```python
from simbio.models.<name> import <model>
from simbio.simulator import Simulator

t = range(100)
Simulator(<model>).run(t).plot()
```
