# Заголовок 1
## Заголовок 2
### Списки 
#### Маркированный 
- пункт 1
- пункт 2
- пункт 3

#### Нумерованный 
1. первый
2. второй
3. третий

## Ссылки
[GitHub](https://github.com)
[doykitochkacom](https://twitch.tv/koryamc)
[Yandex](https://ya.ru)

## Текст
Обычный текст. Без разрыва строки.
Несмотря на Enter все равно без разрыва сроки.

Но с двумя Enter (переносом строки перенос будет)<br>Или же вообще использовать br

*Курсив* **жирный** ***жирный курсив***

## Код
Код в строке `sudo rm -rf /`
Код в блоке кода


```python
def merge_dicts(dict1, dict2):
    result_dict = dict.copy(dict1)
    for k, v in dict2.items():
        if k in result_dict:
            if isinstance(result_dict[k], list):
                result_dict[k].append(v)
            else:
               result_dict[k] = [result_dict[k], v]
        else:
            result_dict[k] = v
    return result_dict
```
## Разделитель 

---

## Картинки 

Картинка по `URL`

![лого гитхаба](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/1280px-Octicons-mark-github.svg.png)

Локальная картинка 
![Капибара](./files/vetki.png)

## Таблица

| Title 1 | Title 2|
| ----- | -----|
|Текст 1 | Текст 2|
