# Data-Analysis
Отчет по лабораторной работе #1 выполнил(а):
- Кузьминых Данил Альбертович
- РИ-220950
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * |  |
| Задание 2 | * |  |
| Задание 3 | * |  |

## Цель работы
###Установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
###Написать программу Hello World на Python с запуском в Jupiter Notebook.

Код на python:

```py

print("Hello World")

```
Скриншоты работы:
<img alt = "Скриншот с jupiter" src = "https://github.com/Vinters565/Data-Analysis/blob/main/изображение_2023-10-03_132455886.png">
<img alt = "Скриншот с jupiter" src = "https://github.com/Vinters565/Data-Analysis/blob/main/изображение_2023-10-03_132511044.png">

## Задание 2
### Написать программу Hello World на C# с запуском на Unity.

Код на C#:

```C#

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Play : MonoBehaviour
{
    [SerializeField] string text;

    private void Start()
    {
        Debug.Log(text);
    }
}

```

Скриншоты работы:
<img alt = "Скриншот с Visual Studio" src = "">
<img alt = "Скриншот с Unity Engine" src = "https://github.com/Vinters565/Data-Analysis/blob/main/изображение_2023-10-03_132535654.png">

## Задание 3
### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.
