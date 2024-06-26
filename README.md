# Дорожная карта сисадмина

Данная карта базируется на [DevOps Roadmap](https://roadmap.sh/devops). Почему она ведь там какой-то devops? Все просто. Системный администратор сейчас очень широкое определение с бесконечным списком навыком и требований. Для начала будем считать, что DevOps это название системного администратора. Позже тут будет дано более ясное определение, что это вообще такое.

## Начинаем начинать

Тут описаны основные этапы начального обучения на сисадмина с необходимыми ссылками на метриала для обучения и моими комментариями.
Основная цель данного материала это не придумать еще один велосипед, а найти пройти весь путь с минимумом затрат. Понадобиться только компьютер, много времени и жалание пройти этот трудный путь.

Главное начать! Как говорят японцы:
> 千里の道も一歩から  "Даже путь в тысячу ри начинается с одного шага."

## Верутализация

Об этом пункте написано достаточно хорошо в [этой](https://habr.com/ru/articles/657677/) статье.

Для новичка тут нужно знать следующие. Вертуализация помогает создавать изолированное окружение с помощью программного обеспечения.

То есть установив на домашний компьютер vmware или virtualbox можно разворачивать любый операционные системы!

Гайд как установить себе на компьютер [vmware](https://www.youtube.com/watch?v=mmZg04SQawI).

На самом деле vmware workstation это самый мизер о вертуализации.

!Тут указать про гипервизоры

## Linux

В 95% процентах случаях прод всегда будет поднять на разных вариантах linux. Почему так? Если открыть гугл и задать вопрос на эту то вылезет огромное количество статей на эту тему. Отмечу тут пожалуй самые важные факторы! Операционные системы на базе LInux бесплатны, открыты и надежны!

В этой главе придется сталкнуться с самым сложным для новичков этапе - командная строка!

### Основные команды для жизни

Бесплатный [вводный](https://ru.hexlet.io/courses/cli-basics) курс от хекслет по командной строке

Также очень полезным будет полистать вот [эту](https://www.piter.com/product/komandnaya-stroka-linux-polnoe-rukovodstvo) книгу. Найти можно бесплатно в pdf. В ней собраны основная информация о командной строке и почему она такая.

### Git

Бесплатный [вводный](https://ru.hexlet.io/courses/intro_to_git) курс от хекслет по гиту

### Vim

Большой и сложный редактор, который легко понять вот с [этим](https://www.youtube.com/watch?v=jkxLIFVGfd4&list=PL8hRAtHSjAgZv7WFVDvQzzU-WoL-7jZGJ) курсом

## Базы данных

База данных — это упорядоченный набор структурированной информации или данных, которые обычно хранятся в электронном виде в компьютерной системе.

Обычно вся информация хранится в них или ссылки на то где взять жто информацию

Базы данных деляться на несколько типов на реалицонные и нереалиционные. [Подробнее](https://aws.amazon.com/ru/compare/the-difference-between-relational-and-non-relational-databases/) об этом.

### Реалицонные базы данных

Я же предлагаю начать с классических раелиционных баз данных на примере [postgressql](https://www.postgrespro.ru/education/courses). Использоваться они будут всегда и везде по удобной простой причине. Они надежны, как танк!

Полезный [тренажер](https://stepik.org/course/63054/syllabus) по sql

На сайте postgressql.ru ребята бесплатно подготовили основные курс про их продукт и что важно бесплатно!

Начать можно прям с [DEV1](https://postgrespro.ru/education/courses/DEV1)

## Сети

Неплохой [курс](https://stepik.org/course/83555/promo?search=3721008768) для получения базовых знаний по сетям.

## Языки программирования

Зачем этот страшный зверь ведь я же админ, а не разработчик?
