
Домашка 1 по nlp
# эксперимент 1
![image](https://github.com/user-attachments/assets/cbbaf077-38e4-43fc-b51c-ce92e50ba846)
![image](https://github.com/user-attachments/assets/16fa9e73-f1f5-4027-8762-bb16aa9013c4)


по графикам не видно что достигнут предел обучения, поэтому увеличим кол-во эпох и посмотрим


![image](https://github.com/user-attachments/assets/4e665c5b-c69b-46df-9a74-712c345ec825)
![image](https://github.com/user-attachments/assets/503ccab8-d4f8-4109-aacb-a3de82259c4a)


Судя по графикам, как раз около 10 эпохи модель начинает переобучаться. Оптимальное число эпох - примерно 10. 

Поведение модели:
Train Loss постепенно снижается, что говорит о хорошем обучении модели на тренировочных данных.
Validation Loss в начале выглядит относительно стабильным, но ближе к 10-й эпохе начинает колебаться.
После 15-й эпохи наблюдаются резкие скачки вверх, что указывает на переобучение.

Validation ROC-AUC колеблется,а после 10 эпохи происходят резкие спады, что подтверждает ухудшение качества модели.



# эксперимент 2

![image](https://github.com/user-attachments/assets/e565872f-54b9-4a03-9d05-cc3af70d94f3)
![image](https://github.com/user-attachments/assets/3c8f36fe-7f67-4a49-b54a-456ede4f36bf)


Loss снижается быстрее, модель лучше обучается.


# эксперимент 3

![image](https://github.com/user-attachments/assets/c98b7491-0369-4f44-b80c-706be08ac654)
![image](https://github.com/user-attachments/assets/0545fe20-aa59-441f-9369-dd23a973720a)


Модель сходится еще быстрее, чем предудыщие, но метрики хуже
