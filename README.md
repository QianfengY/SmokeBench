#  <center> 🔥 SmokeBench: A Real-World Dataset for Surveillance Image Desmoking in Early-Stage Fire Scenes  [ACM MM 2025 Datasets Track]

<!-- 

> [[Paper]()]

-->

> Wenzhuo Jin* <sup>1</sup>, [Qianfeng Yang](https://ncfjd.github.io/)* <sup>2</sup>,Xianhao Wu* <sup>3</sup>, [Hongming Chen](https://scholar.google.com/citations?user=2DBuqfkAAAAJ&hl=zh-CN&oi=sra) <sup>4</sup>,  [Pengpeng Li](https://scholar.google.com/citations?user=Y-VG6gMAAAAJ&hl=zh-CN&oi=sra) <sup>5</sup>, [Xiang Chen](https://cschenxiang.github.io/) <sup>5</sup>
>
> Beijing Jiaotong University<sup>1</sup>, Dalian Polytechnic University<sup>2</sup>, Nanjing University of Aeronautics and Astronautics<sup>3</sup>,  Dalian Martime University<sup>4</sup>, Nanjing University of Science and Technology<sup>5</sup>


 **👉️ Welcome to visit our website (专注底层视觉领域的信息服务平台) for low-level vision:[https://lowlevelcv.com/](https://lowlevelcv.com/)**

---

## ⛳️ To do

* ✔ Release the dataset
* ✔ Release the visual results
---

## :hammer: Dataset pipeline
![image](https://github.com/ncfjd/SmokeBench/blob/main/pipeline_diagram.png)

---

## 🔎 Illustration of the WeatherBench
![image](https://github.com/ncfjd/SmokeBench/blob/main/sample.png)

---

### ⬇️ Dataset Download
| Download Link | Description |
|---------|------|
| [Google Drive](https://drive.google.com/file/d/1NfusIRKwB9el2TpD2xYMOB1fIxPf8PW8/view?usp=drive_link) / [Baidu Netdisk]( https://pan.baidu.com/s/15mE9RGq8PgkD5WVlidSvfw) (refs)  | Tran: 9,875 pairs.    Test: 100 pairs. |

---


## 📘 Quantitative Results
![image](https://github.com/guanqiyuan/WeatherBench/blob/main/figs/Quantitative_Results.jpg)

---

## 📷️ Visual Results

We provide evaluation code ([Python Code](https://github.com/guanqiyuan/WeatherBench/blob/main/evaluation.py)) to assess PSNR, SSIM, and LPIPS results. You need to set the parameters `--generated_images_path`, `--target_path`, and `--Score_save_path`.

> If WeatherBench is helpful for you, please help star the GitHub Repo. Thanks!
>
> 
| Method | Download Link |
|---------|------|
| DehazeFormer | [Google Drive](https://drive.google.com/file/d/1RuhlakyTOoMmryIQHQ2Nxn8unwyiqaA_/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1cV1-D58AMEfMdfHD67WHqg) (deha) |
| DCMPNet | [Google Drive](https://drive.google.com/file/d/1mrwOc9dHz_bzgUhuPfTNiHzJCOOdbzEr/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1lBzuuNBbcOF6YZzV-15c5w) (dcmp) |
| DRSformer | [Google Drive](https://drive.google.com/file/d/1_KKcxZu3o7xopwcSRdDMySDwhNJxVhlF/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1l1D7z310hSm-tshdat0__g) (drsf) |
| NeRD-Rain | [Google Drive](https://drive.google.com/file/d/1dDMHOyX3M_Wej81Xe8oBZX7ZZpD_Nnqf/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1TEISi-iru9pDp_UpJ-K5Kg) (nerd) |
| SnowFormer | [Google Drive](https://drive.google.com/file/d/1j6ldRL0dZgpOLTdC4cDOSpNj_JkMx-nj/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1XJXN0sky6Xe6WEOuni0n2g) (snof) |
| MPRNet | [Google Drive](https://drive.google.com/file/d/1GRUXUNtDYYcpy4GSdZ1bqUibZ2HMe3PV/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1UOyDO-k4h5VyYC24nkCPEQ) (mprn) |
| Restormer | [Google Drive](https://drive.google.com/file/d/1suoKuCahKECsA_u0rApJZrOtdGBMqJ6O/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1qOT1r0pr2JWdV5ptsoFgdw) (rest) |
| AirNet | [Google Drive](https://drive.google.com/file/d/1Gu5Zzp61DLfOJzO2ZF1odqQkBVbDra42/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1YouRqNem3K-XtFBMkJnaOA) (airn) |
| TransWeather | [Google Drive](https://drive.google.com/file/d/189BGlLQQWNzqf8aRunvIC_kPh5ZqGIkM/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/19HEzydiYen7XK6cipCbI4A) (tran) |
| PromptIR | [Google Drive](https://drive.google.com/file/d/1TtJlK2Bf_ZtlTzavSnyQa2E706xSf0zf/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1AxKpHAcM2UIE52Iad4CoSw) (prom) |
| WGWS-Net | [Google Drive](https://drive.google.com/file/d/1IwrbeEJ92PXwefkh3swj_9Cg3OD9vhR1/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1fzkq2fTaYeitC02zlV6yZw) (wgws) |
| DiffUIR | [Google Drive](https://drive.google.com/file/d/1RsjgN5zfHZtdJ5E9jkXAcNOQgdRb292I/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1UCngiy_WBLKNtOXWPupGqg) (diff) |
| MWFormer | [Google Drive](https://drive.google.com/file/d/1Bac20_ffU9W54S36KlNDo0_pbfMpzzTQ/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1YoEKMUMnCOQhsn0HGUZLJg) (mwfo) |
| Histoformer | [Google Drive](https://drive.google.com/file/d/1zSu1kEbOy9XpLOKiB59k8RZsys91UYp6/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1bPEbpyxbJ3hh_J2o6Bkr2Q) (hist) |
| AdaIR | [Google Drive](https://drive.google.com/file/d/19wbuZDCWAR1RhtzsS7DsBFdqvYEczMhY/view?usp=drive_link) / [Baidu Netdisk](https://pan.baidu.com/s/1jWxwv36Gxz-EjJ-gbT3U5g) (adai) |

---

## ❣ Citation
`Coming soon.`

---

## 📧 Contact
If you have any questions, please feel free to contact chenxiang@njust.edu.cn or csqianfengyang@163.com.
