---
title: sampling
type: doc
---

# sampling

#### `weighted_sampling(numbers, k=1, with_replacement=False, **kwargs)`

Return k numbers from a weighted-sampling over the supplied numbers

**Returns:** List, np.ndarray or a single number (depending on the input)

- **`numbers`** `List or np.ndarray`

   numbers to sample
- **`k`** `int` `default = 1`

   How many numbers to sample. Choosing `k=None` will yield a single number
- **`with_replacement`** `Boolean` `default = False`

   Allow replacement or not

#### `boltzmann_sampling(numbers, k=1, with_replacement=False)`

Return k numbers from a boltzmann-sampling over the supplied numbers

**Returns:** List, np.ndarray or a single number (depending on the input)

- **`numbers`** `List or np.ndarray`

   numbers to sample
- **`k`** `int` `default = 1`

   How many numbers to sample. Choosing `k=None` will yield a single number
- **`with_replacement`** `Boolean` `default = False`

   Allow replacement or not