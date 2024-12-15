# UltraGSAttack


The datasets contain a series of gesture data perceived by sound waves for adversarial targeted attack on acoustic-based gesture recognition systems.


## 📚Content

- **Gesture type:** digits ('0' - '9', 10 kinds).

- **Number of signals:** 3,950.

- **Collecting device:** Samsung Galaxy Tab S2.

- Some specific details include orientation, environment, posture and distance. If further clarification is needed, please feel free to contact the authors. Alternatively, you can visit [https://github.com/ISAC-GROUP/ISAC-Gesture](https://github.com/ISAC-GROUP/ISAC-Gesture) and read our published paper *PreGesNet: Few-Shot Acoustic Gesture Recognition Based on Task-Adaptive Pretrained Networks* for more detailed information.

## ⚙️File Structure

```bash
- /
  ├── /extracted_wav_lab
  │   ├── /0
  │   │   ├── p1-sss-0-1-lab-none-24.wav
  │   │   ├── p8-sss-0-1-lab-none-2.wav
  │   │   └── ...
  │   ├── /1
  │   │   ├── ...
  │   ├── /2
  │   │   └── ...
  │   └── ...
  ├── /extracted_wav_out
      ├── /0
      │   ├── p3-sss-0-1-out-none-30.wav
      │   ├── p4-sss-0-1-out-none-23.wav
      │   └── ...
      ├── /1
      │   ├── ...
      │   └── ...
      └── ...

```


## ✔️Usage

1. **Download**: Clone or download the dataset locally. **Due to the number of files, we have also placed the datasets on Google Drive.**

```bash
git clone https://github.com/ISAC-GROUP/UltraGSAttack.git
```

```bash
https://drive.google.com/drive/folders/1qkWu9JBX8QUZPGHs6srjWEEbrEF69GQa?usp=sharing
```

2. **Data format:** Datasets are stored as wav files in their respective category folders.

```bash
 p1    -     sss    -     0    -    1    -    lab    -    none    -    24     .wav
 │            │           │         │          │            │           │      │              
user       device    orientation distance  environment   posture      count  format
     
```


## 😀Contact information

**If you have any questions or feedback, please feel free to contact us:**

- Author: [Yongpan Zou(邹永攀), Yunshu Wang(王云舒), Yanbo He(何彦博)]
- E-mail: [yongpan@szu.edu.cn; wangyunshu2018@email.szu.edu.cn; yanboheszu@gmail.com]
- Address: College of Computer Science and Software Engineering, Shenzhen University, 3688 Nanhai Ave, Shenzhen, Guangdong, China, 518060.

Thank you for using our dataset!

---
