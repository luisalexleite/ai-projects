# Covid-19 Checker

Aplication of Neural Network knowledge to detect Covid-19 and Simply Pneumonia, by lungs x-ray images.

## Features:

- Detect condition via lungs X-Ray images
- Detect afected areas

## Neural Network Model

<p align='center'>
  <img alt="Model" src="https://github.com/luisalexleite/ai-projects/blob/main/covid-19-checker/model.png">
</p>

## Results

### Conditions

| Test Nº | Loss | Accuracy%|
|---------|------|----------|
|1|0.0942|96.74|
|2|0.1156|94.24|
|3|0.1141|95.48|
|4|0.1143|95.32|
|5|0.1134|95.88|

Average Loss: 0.1103

Average Accuracy%: 95.53

### Afected Areas

#### Covid-19

![Heatmap Covid-19](https://github.com/luisalexleite/ai-projects/blob/main/covid-19-checker/img/results_example/COVID/000002-29.jpg)

#### Pneumonia

![Heatmap Pneumonia](https://github.com/luisalexleite/ai-projects/blob/main/covid-19-checker/img/results_example/PNEUMONIA/person82_bacteria_402.jpeg)

## Execution Instrutions

### Google Colaboratory

- Zip the [img](https://github.com/luisalexleite/ai-projects/tree/main/covid-19-checker/img) folder and move it to the [Drive](https://drive.google.com/drive/) where your file is located.

- Uncomment the first lines of the [notebook](https://github.com/luisalexleite/ai-projects/blob/main/covid-19-checker/covid-19-checker.ipynb) file.

- Activate GPU rendering ("Edit" -> "Notebook Options") on Google Colaboratory if your want that code runs faster.

### Local Jupyter Notebook Server

- Install the requirements (Commented as "External Python Libraries" on Notebook file)

- Activate GPU rendering (For Ubuntu 20.04 you can consult this [link](https://towardsdatascience.com/installing-tensorflow-gpu-in-ubuntu-20-04-4ee3ca4cb75d)) if want that the code runs faster.
