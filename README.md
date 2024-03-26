# FASC-Net
Fork of FASC-NET https://github.com/jack8zhou/FASC_Net

A Fast and Lightweight Detection Network for Multi-Scale SAR Ship Detection under Complex Backgrounds. The code will be made public after the paper is published.

## Input data
Needs annotations in YOLO txt format

## Changes to the original code
### train.py
line 200 

| Old value | New value |
| --- | --- |
| MLC < NC | MLC <= NC |

### utils/loss.py

line 209: error float

| Old value | New value |
| --- | --- |
| gain(3) | int(gain(3)) |




