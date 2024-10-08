# ITMO_FP

Сосновцев Григорий 335046 P34102 

## Лабораторная работа 0: Выбор языка и средств разработки

- **Язык программирования:** Coq (Gallina)
- **IDE:** VSCode + VsCoq
- **Тестирование и линтеры:** встроены в среду

### Обоснование выбора

Выбор языка Coq и среды разработки VSCode с расширением VsCoq обусловлен несколькими факторами. Coq является мощным инструментом для формальной верификации программ и доказательства теорем, что делает его идеальным для задач, связанных с формализацией и проверкой сложных алгоритмов и систем. Язык Gallina, используемый в Coq, позволяет выразить математические утверждения и доказательства в строгой и формальной манере, что обеспечивает высокую степень уверенности в корректности программ.

Использование VSCode с VsCoq предоставляет удобную и интегрированную среду разработки, которая облегчает написание и проверку доказательств. Встроенные инструменты тестирования и линтинга помогают поддерживать качество кода и быстро выявлять ошибки. Это особенно важно при работе с формальными доказательствами, где даже небольшие ошибки могут привести к неверным выводам.

Кроме того, Coq имеет обширное сообщество и множество доступных ресурсов, таких как "Software Foundations" и "Coq in a Hurry", которые могут значительно ускорить процесс обучения и разработки. Эти материалы предоставляют как теоретическую базу, так и практические примеры, что делает их ценными для изучения и использования Coq в проектной работе.

### Идеи по проектной части

В качестве предметной области для проекта хотелось бы взять либо распределенные системы, либо concurrency. Например, для первого возможно построение модели некоторого распределенного алгоритма и формальное доказательство гарантий, им предоставляемых. Для второго было бы интересно попробовать формализовать что-то из области моделей памяти. В любом случае, модели памяти / модели согласованности — достаточно смежные области, и подобные задачи хорошо подходят для выбранного языка.

### Материалы

- [Software Foundations](https://softwarefoundations.cis.upenn.edu/) - книга для изучения
- [Coq in a Hurry](https://cel.hal.science/inria-00001173) - книга для изучения
- [CSC Семантика ЯП](https://youtube.com/playlist?list=PLlb7e2G7aSpTA0aT2M1CvIWof3Osslo7Z&feature=shared) - видео использовавшееся для подготовки эссе
- [Why every programming student should learn Coq](https://rubber-duck-typing.com/posts/2018-03-11-why-every-programming-student-should-learn-coq.html) - материал для подготовки эссе