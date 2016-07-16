#Version Control System flow
##Основные принципы
###Ядро модели разработки
репозиторий содержит две главные ветки, существующие всё время:
- [master](branch-master.md)
- [developer](branch-developer.md)

Помимо главных ветвей [master](branch-mater.md) и [developer](branch-developer.md), модель разработки содержит некоторое количество типов вспомогательных ветвей, которые используются для распараллеливания разработки между членами команды, для упрощения внедрения нового функционала (features), для подготовки релизов и для быстрого исправления проблем в __production__ версии 
В отличие от главный ветвей, эти ветви всегда имеют ограниченный срок жизни. Каждая из них в конечном итоге рано или поздно удаляется.

##Источники
* https://habrahabr.ru/post/106912/