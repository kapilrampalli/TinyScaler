# TinyScaler

A small CPU image scaling library with SIMD support on x86_64 and Arm (Neon).

## Requirements

- cmake >= 3.1

## Install

> pip install .

## Usage

```python
import numpy as np
import tinyscaler

img = np.random.rand(8, 8, 4).astype(np.float32)

print(tinyscaler.scale(img, (64, 64)))
```

## License

MIT License, see [LICENSE.md](./LICENSE.md)



