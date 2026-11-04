# CS163-Radio-Interferometry-Project

## Data

Data is stored in the shared Google Drive folder, not in this repo. Run the notebooks in Colab with Drive mounted, and keep these folders under `MyDrive/CS 163/`:

| Folder | Contents | Used by |
|---|---|---|
| `cs163_data/` | Original `.uvfits` and `.calfits` files | `Aman_Viz`, `Data_Generation_Aman` |
| `cs163_tensors/` | Original dataset as tensors (`X`, `Y`, `M`, `S`) | `Aman_Viz`, `Data_Generation_Aman` |
| `cs163_calibrated/` | `X_calibrated.npy` | `Aman_Viz`, `Data_Generation_Aman` |
| `cs163_random_data/` | Random-sky `.uvfits` and `.calfits` files | `Aman_Viz`, `Data_Generation_Aman` |
| `Albert Dataset Tensors/` | Random-sky dataset as tensors (`X`, `Y`, `M`, `S`) | `Data_Generation_Aman` |

If a shared folder doesn't appear in `MyDrive/CS 163/`, add a shortcut to it there.

`generate_data_for_cs163.ipynb` writes to a local path, so update that path before running it. It also needs the `calico` package.

Don't commit data files or model checkpoints. Put final figures in `figures/`.
