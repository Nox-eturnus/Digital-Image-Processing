# Digital Image Processing Lab

Course work and experiments for the Digital Image Processing course.

## Files

| File | Description |
| :--- | :--- |
| `rgb2grey.py` | Extracts RGB channels and converts an image to greyscale, outputs a 2×2 grid. |
| `bit_plane_slicing.py` | Converts an image to greyscale, extracts all 8 bit planes (Bit 0 to Bit 7), and outputs a 3×3 comparison grid. |
| `housie_tickets.py` | Generates and renders valid Housie/Tambola tickets as a PNG. |
| `GUI/app.py` | Interactive desktop toolkit for running DIP operations on images. |
| `GUI/operations/` | Drop-in modules for the GUI (RGB & Channels, Bit Plane Slicing, etc.). |

## Running the GUI

```bash
pip install numpy pillow ttkbootstrap
python GUI/app.py
```
