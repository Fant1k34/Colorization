# Колоризация бинарных изображений с помощью свёрточной нейронной сети
Цель: разработать и обучить модель для преобразования чёрно-белых изображений в цветные (палитра RGB)
![image](https://user-images.githubusercontent.com/45245696/149221866-af579a0f-ad17-4611-a6d3-82255e701ca7.jpg)

# Технологии:
- Python 3
- Pytorch
- PIL
- Numpy
- Matplotlib

# Слои в модели:
- Conv2d (свёртка)
- MaxPooling
- Swish-функция активации
  ![c2a30f0a1d6a9c3f14da54c41a1a9cd4](https://user-images.githubusercontent.com/45245696/149221632-103955a2-9052-46fe-94c6-0f2057685bd4.png)
- BatchNorm (батч-нормализация)

# Результаты:
В репозитории также находится обученная модель с расширением h5
![Без названия](https://user-images.githubusercontent.com/45245696/149221593-cfeeb514-9b06-41ca-a9e1-f5c0df012ad3.png)
