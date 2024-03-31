# О графике

Этот график я использую на своём текущем месте работы, он показывает анонимную статистику по играм на игровой платформе. В данном репозитории данные генерируются случайным образом и не отображают данные самого продукта.    
Данные, которые предоставляет этот график в обычном режиме:
- Количество ставок в день на протяжении некоторого отрезка времени
- Сумма всех ставок в день на протяжении некоторого отрезка времени
- Прибыль от всех ставок в день (разница значений проигранных ставок и выигранных)

Также у этого графика есть дополнительные режим, добавляющий средние значения (за всё время) для указанных выше метрик.
Помимио этого, можно посмотреть эту же статистику по каждой отдельно взятой игре.

> [!IMPORTANT]
> По техническим причинам, GitHub не способен передать функционал этого графика и отобразить его в файле `plot_test.ipynb`. В связи с этим, я прикрепляю ниже видео, где показаны возможности графика.



https://github.com/PavelUmanskiy/InteractivePlots/assets/114307635/e4ad2fc8-5094-471b-bea3-c9d4470adc12



# Requirements to run this code:
  1. Install Python version 3.11 (if not installed yet): [download](https://www.python.org/downloads/release/python-3116/)
  2. Add Python to the Environment variables (at the top of the `Path` variable)
  3. Clone this repo
  4. In the repo directory, run:
       1. `python -m venv <your_environment_name>`
       2. `.\<your_environment_name>\Scripts\activate`
       3. `pip install -r requirements.txt`
  5. Run this jupyter notebook
