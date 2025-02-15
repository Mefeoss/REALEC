# REALEC

Эти программы помогут вам автоматизировать загрузку файлов на сайты [Grammarly](https://www.grammarly.com), [Write & Improve](https://writeandimprove.com) и [Duolingo](https://cefr.duolingo.com) и получить информацию об уровне английского языка. Результаты с названием файла и уровнем английского записываются в csv файлы.

## Инструкция
1. Перед тем, как начать работу, вам необходимо установить браузеры Chrome и Mozilla и скачать, соответственно, [ChromeDriver](https://chromedriver.chromium.org) и [FirefoxDriver](https://github.com/mozilla/geckodriver/releases). По моим наблюдениям, Grammarly работает только в Firefox'e.
2. В [personal_info_grml.py](https://github.com/soimmary/REALEC/blob/main/personal_info_grml.py) в переменные **LOGIN_GRML** и **PASSWORD_GRML** добавьте логин и пароль от вашего акаунта на [Grammarly](https://www.grammarly.com).
3. В [personal_info_wi.py](https://github.com/soimmary/REALEC/blob/main/personal_info_wi.py) в переменные **LOGIN_WI** и **PASSWORD_WI** добавьте логин и пароль от вашего акаунта на [Write & Improve](https://writeandimprove.com).
4. В [write_improve.py](https://github.com/soimmary/REALEC/blob/main/write_improve.py) добавьте значения в переменные **my_wb_path** и **my_essay_path**. Как это сделать, см. ниже:

### my_wb_path:

![**my_wb_path:**](https://github.com/soimmary/REALEC/blob/main/my_wb_path.gif)

### my_essay_path:

![**my_essay_path:**](https://github.com/soimmary/REALEC/blob/main/my_essay_path.gif)

5. В [cefr_prediction.py](https://github.com/soimmary/REALEC/blob/main/cefr_prediction.py) на основе полученных в [duolingo.py](https://github.com/soimmary/REALEC/blob/main/duolingo.py), [grammarly.py](https://github.com/soimmary/REALEC/blob/main/grammarly.py), [write_improve.py](https://github.com/soimmary/REALEC/blob/main/write_improve.py) данных делается общая таблица и предсказывается уровень английского.

## Если возникают ошибки

Варианты решения:
- перезагрузить программу
- увеличить аргумент time.sleep()


**Автор:** 💁🏼‍♀️ Мария Бочарова

**Контакты:** 
- 📨 rozovayatumbochka@gmail.com
- 📠 telegram: https://t.me/soimmary
