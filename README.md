# DST-DFN
# 🚇🚌 Subway passenger flow prediction considering subway-bus transfer:A dynamic spatiotemporal decomposition and gate fusion network

---

## 📦 Environment Setup

Make sure you have the following dependencies installed:

- Python >= 3.9  
- TensorFlow ≥ 2.10
- pandas
- numpy
- scikit-learn
- CUDA ≥ 11.2 (if using GPU)

Install dependencies with:

```bash
pip install -r requirements.txt
```

---

## 📊 Dataset

The dataset contains preprocessed inflow and outflow data from both subway and bus systems. These files are required to run the training and testing scripts.

### Files Description

| File Name               | Description                            |
|------------------------|----------------------------------------|
| `DT_ridership_in.npy`  | Subway inflow data                     |
| `DT_ridership_ou.npy`  | Subway outflow data                    |
| `GJ_DT_flowin.npy`     | Bus inflow data                        |
| `GJ_DT_flowou.npy`     | Bus outflow data                       |
| `DT_ADJ.csv`           | Static adjacency matrix for subway     |

Ensure the data files are placed in the correct paths as expected in the code.  

---


## 🧠 Overall Architecture
This is the framework of the dynamic spatial-temporal decomposition and fusion network (DST-DFN).
![Framework of the dynamic spatial-temporal decomposition and fusion network (DST-DFN).](./Figs/over-stru.jpg)


---

## 📮 Contact

If you have questions, issues, or suggestions, feel free to reach out:

- **Email**: liushan22@seu.edu.cn  

---

## 🧪 Project Status

This project is still **under active development**.  
We are continuously working on:

- Adding support for projects that only use subway data.  
- Providing trained model weights 

Stay tuned for updates!
