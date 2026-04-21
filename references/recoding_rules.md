# Recoding Rules

## 1. SadOrHopeless_Recoded (For Inference)
To calculate the sample proportion and perform the 1-Prop Z-test, the original `SadOrHopeless` variable was recoded into a standard dummy/binary format.
* **Original Value `1` (Yes)** -> **Recoded Value `1.0`**
* **Original Value `2` (No)** -> **Recoded Value `0.0`**
* Missing values (NaN) were dropped before conducting the inference test.

## 2. Sex_Label (For Advanced EDA)
For clear visual interpretation in the Exploratory Data Analysis, the numeric sex variable was mapped to string labels:
* **`1`** -> **`Female`**
* **`2`** -> **`Male`**

## 3. CDC_Category (For Advanced EDA)
To investigate the non-linear relationship (J-Curve Effect) between body image and depression, `BMIPCT` was categorized into four distinct groups based on CDC standard thresholds:
* `BMIPCT < 5` -> `1. Underweight (<5)`
* `5 <= BMIPCT < 85` -> `2. Healthy Weight (5-84)`
* `85 <= BMIPCT < 95` -> `3. Overweight (85-94)`
* `BMIPCT >= 95` -> `4. Obese (>=95)`
