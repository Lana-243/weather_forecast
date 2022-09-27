[![forthebadge](http://forthebadge.com/images/badges/made-with-ruby.svg)](http://forthebadge.com)

# Weather Forecast
Текстовое приложение для получения прогноза погоды

## Пример прогноза:

<img width="440" alt="Screenshot 2022-09-27 at 20 27 16" src="https://user-images.githubusercontent.com/84347249/192598913-f7b3dd5b-b9f5-427f-8bee-6b6e1d509767.png">

## Как запустить приложение:

Внести в терминал следующий код:

```
ruby main.rb
```

## Как получить прогноз:

Просто выбери нужный город из списка, внеси в терминал его номер, указанный в строке и нажми Enter.

### Дополнение списка городов

Если хочешь скорректировать список городов, то найди ссылку на него на странице https://meteodays.com/en/content/export

И далее просто внеси дополнительную строку в файле data/city_url.xml внутри тега <cities></cities>

В следующем формате:
```
<city name='Krasnodar' url='https://xml.meteoservice.ru/export/gismeteo/point/199.xml'></city>
```
