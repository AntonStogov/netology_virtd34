# netology_virtd34
Ответы на вопросы:
1) Опишите основные преимущества применения на практике IaaC-паттернов.
   - С IaC возрастает скорость и уменьшение затрат, направление на прозрачность помогает другим командам всего предприятия работать быстрее и эффективнее, что в свою очередь освобождает ресурсы для выполнения других более важных задач.
   - Масштабируемость и стандартизация, с помощью IaC командам не нужно прибегать к ручной настройке - они обеспечивают корректность, описывая с помощью кода трубемое состояние сред. IaC стандартизирует сетап инфраструктуры, что во многом снижает вероятность ошибок.
   - Так же стандарты безопасности можно легко и последовательно применять в разных компаниях , так как за вычислительные, сетевые и службы хранения отвечает код они развертываются одинаково.
   - Восстановление в аварийных ситуациях, IaC - эффективный способ отслеживания вашей инфрастурктуры и повторного развертывания последнего работоспособного состояния после сбоя
   Какой из принципов IaaC является основополагающим?
   Ответ: Основологающий принцип IaC идемпотентность - свойство операции или объекта при котором повторное выполнение дает результат идентичный предыдущему и всем последующим выполнениям
3) Чем Ansible выгодно отличается от других систем управление конфигурациями?
   - Быстро осваивается, достаточно поверхностного понимания синтаксиса YAML и Jinja
   - Нет необходимости устанавливать специальное ПО на хосты, нужен только SSH и python
   - Доступная подбробная документация
   - Позволяет реализовать принцип идемпотентности в управлении состояними хостов
     Какой, на ваш взгляд, метод работы систем конфигурации более надёжный — push или pull?
     Ответ: Push дешевле, так как не требует установки дополнительных серверов, простой в архитектуре, конфигурации хранятся локально в том виде котором удобно администратору, подходит для тестирования DSC, при развертывании серверов очень просто вписывается в философию IaC.
     
image1.png
image2.png
