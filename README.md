# netology_virtd34
Ответы на вопросы:
1) В использовании физического сервера, аппаратная виртуализация использует физический сервер с помощью гипервизора позволяет создавать виртальные машины изолированные друг от друга с помощью программной имитации ресурсов, при паравиртуализации гостевые ОС (виртуальные машины) используют ресурсы сервера, виртуализация на уровне ОС (контейнеризация) используют функционал ядра ОС, потому более легковестны, и им не требуется использовать аппаратное обеспечение.
2) высоконагруженная база данных, чувствительная к отказу, я бы выбрал физические сервера так как можно собрать отказоустойчивую систему используя все ресурсы имеющегося сервера или серверов
   различные web-приложения, тут скорее всего выбор пал бы на виртуализацию уровня ОС, так как такие ОС легкие и быстро развертываемые, у каждой изолированная среда
   Windows-системы для использования бухгалтерским отделом
   системы, выполняющие высокопроизводительные расчёты на GPU, в последних двух вариантах использовал бы паравиртуализацию, так как это хороший способ предоставить быструю рабочую среду, при этом используя мощность физического сервера.
3) 100 виртуальных машин на базе Linux и Windows, общие задачи, нет особых требований. Преимущественно Windows based-инфраструктура, требуется реализация программных балансировщиков нагрузки, репликации данных и автоматизированного механизма создания резервных копий.
  Ответ: Hyper-V для данной задачи подойдет решение Microsoft, я думаю он больше всего подходит под ВМ Windows так же на нем можно делать снапшоты, и настроить Windows Server Backup
Требуется наиболее производительное бесплатное open source-решение для виртуализации небольшой (20-30 серверов) инфраструктуры на базе Linux и Windows виртуальных машин.
  Ответ: VirtualBox как по мне достаточно быстрый, это open source решение и легкий в освоении и использовании
Необходимо бесплатное, максимально совместимое и производительное решение для виртуализации Windows-инфраструктуры.
  Ответ: Опять же для Windows-инфроструктуры я думаю лучше всего подходит Hyper-V
Необходимо рабочее окружение для тестирования программного продукта на нескольких дистрибутивах Linux.
   Ответ: Docker мало наю про него, но для тестирования программного продукта подойдет решение контейниризации, так как это быстро, не занимает много места
4)
