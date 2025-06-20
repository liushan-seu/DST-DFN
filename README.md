# DST-DFN
# 🚇🚌 Subway passenger flow prediction considering subway-bus transfer:A dynamic spatiotemporal decomposition and gate fusion network

---

## 📦 Environment Setup

Make sure you have the following dependencies installed:

- Python >= 3.9  
- tensorflow==2.10
- numpy==1.26.4
- joblib==1.5.1
- pandas==2.3.0
- scikit-learn==1.7.0
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
## 📚 Citation

If you find this repository helpful, please consider citing our work.  
The corresponding paper is currently under review and will be released soon.  

Citation information will be updated here once the paper is published.

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
