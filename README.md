# Анализ данных в разработке игр
Отчет по лабораторной работе #1 выполнил(а):
- Лошаков Данил Евгеньевич
- РИ220930
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Написать программу Hello World на Python с запуском в Jupiter Notebook.
- Задание 2.
- Написать программу Hello World на C# с запуском на Unity.
- Задание 3.
- Оформить отчет в виде документации на github (markdown-разметка).
- Выводы.
- ✨Magic ✨

## Цель работы
- Установить и ознакомиться с программным обеспечением. 

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.
-  ![image](https://github.com/smakkkkk/DA-in-GameDev-lab1/assets/129764703/884a8608-c1d5-4f51-b94a-d28259c0085a)
-  ![image](https://github.com/smakkkkk/DA-in-GameDev-lab1/assets/129764703/6fdcfe05-66fc-4f9a-9a68-97e38c80c0bb)
-  ![image](https://github.com/smakkkkk/DA-in-GameDev-lab1/assets/129764703/7e87e80c-eefd-4591-a361-eb7aa6ca72a5)


## Задание 2
### Написать программу Hello World на C# с запуском на Unity.
- ![image](https://github.com/smakkkkk/DA-in-GameDev-lab1/assets/129764703/0213636a-2c9e-41d4-beb7-7a4f486b0272)
- ![image](https://github.com/smakkkkk/DA-in-GameDev-lab1/assets/129764703/cb802e67-45ac-4756-895a-6d245b98187a)
- ![image](https://github.com/smakkkkk/DA-in-GameDev-lab1/assets/129764703/49c6b87c-abd7-4761-b7d8-dad38913da01)
- ![image](https://github.com/smakkkkk/DA-in-GameDev-lab1/assets/129764703/ba4246a4-59e6-4c24-9eec-0e8cb02b9e14)
- ![image](https://github.com/smakkkkk/DA-in-GameDev-lab1/assets/129764703/8408d894-bc00-4067-b9ac-cdf4b587df6d)

 







## Задание 3
### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.

- Перечисленные в этом туториале действия могут быть выполнены запуском на исполнение скрипт-файла, доступного [в репозитории](https://github.com/Den1sovDm1triy/hfss-scripting/blob/main/ScreatingSphereInAEDT.py).
- Для запуска скрипт-файла откройте Ansys Electronics Desktop. Перейдите во вкладку [Automation] - [Run Script] - [Выберите файл с именем ScreatingSphereInAEDT.py из репозитория].

```py

import ScriptEnv
ScriptEnv.Initialize("Ansoft.ElectronicsDesktop")
oDesktop.RestoreWindow()
oProject = oDesktop.NewProject()
oProject.Rename("C:/Users/denisov.dv/Documents/Ansoft/SphereDIffraction.aedt", True)
oProject.InsertDesign("HFSS", "HFSSDesign1", "HFSS Terminal Network", "")
oDesign = oProject.SetActiveDesign("HFSSDesign1")
oEditor = oDesign.SetActiveEditor("3D Modeler")
oEditor.CreateSphere(
	[
		"NAME:SphereParameters",
		"XCenter:="		, "0mm",
		"YCenter:="		, "0mm",
		"ZCenter:="		, "0mm",
		"Radius:="		, "1.0770329614269mm"
	], 
)

```

## Выводы

Абзац умных слов о том, что было сделано и что было узнано.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
