# NumPy Tutorial

A hands-on NumPy tutorial series covering array creation, operations, advanced analytics, and file I/O. Each phase builds on the previous one, taking you from the basics to real-world business data analysis.

## Phases

### Phase 1 — Array and Basics (`phase-1.ipynb`)
- Creating arrays from Python lists (1D and 2D)
- List vs NumPy array: behavior differences and performance benchmarking
- Creating arrays from scratch (`zeros`, `ones`, `full`, `random`, `arange`)
- Vectors, matrices, and tensors
- Array properties (`shape`, `ndim`, `size`, `dtype`)
- Reshaping: `reshape`, `flatten`, `ravel`, and transpose

### Phase 2 — Array Operations (`phase-2.ipynb`)
- Slicing and indexing (1D, 2D, negative indexing, step)
- Sorting (`np.sort` with axis)
- Filtering with boolean masks
- Fancy indexing vs `np.where()`
- Adding and removing data (`concatenate`, `vstack`, `hstack`, `delete`)
- Array compatibility checks

### Phase 3 — Advanced Operations with Business Examples (`phase-3.ipynb`)
- Real-world Zomato sales analysis dataset
- Aggregation: `sum`, `min`, `max`, `mean` along different axes
- Cumulative sums across years
- Visualizing sales trends with Matplotlib

### Phase 4 — Saving and Loading Arrays (`phase-4.ipynb`)
- Saving arrays to `.npy` files (`np.save`)
- Loading arrays from disk (`np.load`)
- Displaying array data as images with Matplotlib (`imshow`)

## Files

| File | Description |
|------|-------------|
| `phase-1.ipynb` | Array creation and basics |
| `phase-2.ipynb` | Array operations and manipulation |
| `phase-3.ipynb` | Advanced analytics with a business dataset |
| `phase-4.ipynb` | Saving and loading NumPy arrays |
| `array1.npy` | Saved array output from phase 4 |
| `array2.npy` | Saved array output from phase 4 |
| `array3.npy` | Saved array output from phase 4 |

## Requirements

- Python 3.x
- NumPy
- Matplotlib (for phase 3 and 4)

Install dependencies:

```bash
pip install numpy matplotlib
```

## How to Run

Open each notebook in Jupyter or VS Code and run the cells top to bottom:

```bash
jupyter notebook phase-1.ipynb
```
