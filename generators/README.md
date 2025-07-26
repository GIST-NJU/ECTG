# 🧪 Test Generator Usage

This document describes how to run the **ACTS** and **PICT** generators using the executable files `acts_3.2.jar` and `pict`, respectively.  
For the **ECTG** generator, please refer to the `README.md` file under the `generator_ECTG` subdirectory.

---

## 📁 Setup

1. **ACTS**  
   Place the model file in the same directory as `acts_3.2.jar`.  
   You can refer to the example model in [`models/model_ACTS.txt`](../models/model_ACTS.txt).

2. **PICT**  
   Place the model file in the same directory as the `pict` executable.  
   You can refer to the example model in [`models/model_PICT.txt`](../models/model_PICT.txt).

---

## ▶️ Running ACTS

Use the following command under Linux:

```bash
java -Ddoi=<strength> -Doutput=csv -jar acts_3.2.jar <model>
```

**Parameters**:

* <strength>: Coverage strength (e.g., 2, 3, or 4)
* <model>: Model file name


## ▶️ Running PICT

Use the following command under Linux:

```bash
./pict  <model>  /o:<strength>
```

**Parameters**:

* <strength>: Coverage strength (e.g., 2, 3, or 4)
* <model>: Model file name


