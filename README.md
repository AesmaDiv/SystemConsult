![SystemConsult](https://user-images.githubusercontent.com/34000496/133040494-df4565fd-bab8-42ed-a454-91ee44876626.jpg)
# Тестовое задание для СистемКонсалт

## Задание:
Разработать консольное приложение на C# .Net по описанию.<br>
Реализовывать долгосрочное хранение информации о встречах необязательно, достаточно хранить встречи в памяти.<br>
Для приложения написать план тестирования.

## Исходные данные:
Необходимо разработать приложение для управления личными встречами.<br>
* Встреча – событие, которое планируется заранее, для которой всегда известно время начала и примерное время окончания. 
* Данные о встречах могут быть добавлены, изменены и удалены. Встречи всегда планируются только на будущее время. При этом встречи не должны пересекаться друг с другом.<br>
 * Также для встречи может быть настроено время, за которое нужно уведомить пользователя о предстоящей встрече. Время напоминания также может быть изменено после создания встречи. При наступлении времени напоминания приложение информирует пользователя о предстоящей встрече и времени ее начала.<br>
* Пользователь может посмотреть расписание своих встреч на любой день, в том числе и прошедший.<br>
* Помимо просмотра он может с помощью приложения экспортировать расписание встреч за выбранный день в текстовый файл.<br>

## Реализация:
* .NET 5.0 Framework
* Terminal.Gui

### Структура проекта:
- **Program:** _основной класс программы_
- **IValidator:** _интерфейс валидатора_
- **MeetingValidator:** _класс валидатора встреч_
- **Meeting:** _класс встречи_
- **Scheduler:** _класс ежедневника_
- **GUI:** класс _консольного интерфейса_
