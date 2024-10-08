---
layout: default
title: Markdown
---

# Добро пожаловать на страницу Markdown

[О Markdown](#about)

[Представление и возможности разметки с помощью Markdown](#syntax)

## <a name="about"></a> О Markdown

Markdown - облегченный язык разметки, с расширением md, который может быть использован в качестве страниц сайтов.


## <a name="syntax"></a> Представление и возможности разметки с помощью Markdown

Текст может быть **жирным**, _наклонным_, ~~перечеркнутым~~ или `выделенным`.


# Заголовок 1

Это обычный параграф после заголовка.

## Заголовок 2

> Это цитата после заголовка
>
> Когда что-то достаточно важное, вы это делаете, даже если шансы не в вашу пользу

### Заголовок 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Заголовок 4

*   Это неупорядоченный список, следующий за заголовком.
*   Это неупорядоченный список, следующий за заголовком.
*   Это неупорядоченный список, следующий за заголовком.

##### Заголовок 5

1.  Это упорядоченный список, следующий за заголовком.
2.  Это упорядоченный список, следующий за заголовком.
3.  Это упорядоченный список, следующий за заголовком.

###### Заголовок 6

| номер фрукта |    название       | цена      |
|:-------------|:-----------------:|----------:|
| 1            | апельсин          | 100       |
| 2            | киви              | 150       |
| 3            | яблоко            | 120       |
| 4            | грейпфрут         | 70        |

### Горизонтальный разделитель после абзаца.

* * *

### Неупорядоченный список:

*   Элемент foo
*   Элемент bar
*   Элемент baz
*   Элемент zip

### Неупорядоченный список:

1.  Пункт 1
1.  Пункт 2
1.  Пункт 3
1.  Пункт 4

### And a nested list:

- пункт уровня 1 
  - пункт уровня 2
  - пункт уровня 2
    - пункт уровня 3
    - пункт уровня 3
- пункт уровня 1
  - пункт уровня 2
  - пункт уровня 2
  - пункт уровня 2
- пункт уровня 1
  - пункт уровня 2
  - пункт уровня 2
- пункт уровня 1

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)


### Списки определений можно использовать с синтаксисом HTML.

<dl>
<dt>Название</dt>
<dd>Годзила</dd>
<dt>Год рождения</dt>
<dd>1952</dd>
<dt>Место рождения</dt>
<dd>Япония</dd>
<dt>Цвет</dt>
<dd>Зеленый</dd>
</dl>

```
Длинные однострочные блоки кода не должны переноситься. Они должны прокручиваться по горизонтали, если они слишком длинные. Эта строка должна быть достаточно длинной, чтобы продемонстрировать это.
```

```
Последний элемент.
```

[Назад](./)
