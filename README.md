# SRCNN for Gaussian Blur

Restore blurred image by removing gaussian blur filter on image using SRCNN.

SRCNN is CNN for Super Resolution problem.

Originate from [SRCNN-Tensorflow](https://github.com/tegg89/SRCNN-Tensorflow)

## Prerequisites

Check out [requirements.txt](./requirements.txt)

- Tensorflow
- Scipy
- h5py
- matplotlib

### Install requirements

```bash
python3 -m venv .env
source ./env/bin/activate
pip3 install -r requirements.txt
```

## Results

### Example 1

Original

![dog-1-o](./img/kong1-gray.png)

Gaussian-blurred image

![dog-1-g](./img/kong1-gray-gaussian.png)

Restored image

![dog-1-r](./img/kong1.png)

### Example 2

Original

![c-o](./img/chicken-gray.png)

Gaussian-blurred image

![c-o](./img/chicken-gray-gaussian.png)

Original

![c-o](./img/chicken.png)
