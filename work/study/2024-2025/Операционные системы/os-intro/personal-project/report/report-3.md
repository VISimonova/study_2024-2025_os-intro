﻿Внешний курс. Блок 3: Криптография 

на практике

Основы информационной безопасности

Симонова Виктория Игоревна

Содержание

1  [Цель работы ](#_page4_x68.00_y151.04) 5 2  [Выполнение блока 3: Криптография на практике  ](#_page5_x68.00_y151.04)6 

1. [Введение в криптографию ](#_page5_x68.00_y274.04).  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 6
1. [Цифровая подпись  .  ](#_page7_x68.00_y576.04).  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 8
1. [Электронные платежи ](#_page10_x68.00_y307.04)................................................................................................ 11
1. [Блокчейн ](#_page11_x68.00_y585.04).......................................................................................................................... 12

3  [Выводы ](#_page14_x68.00_y151.04) 15 

Список иллюстраций

3

1. [Вопрос 4.1.1](#_page5_x68.00_y541.04)
1. [Вопрос 4.1.2](#_page6_x68.00_y247.04)
1. [Вопрос 4.1.3](#_page6_x68.00_y502.04)
1. [Вопрос 4.1.4](#_page7_x68.00_y258.04)
1. [Вопрос 4.1.5](#_page7_x68.00_y518.04)
1. [Вопрос 4.2.1](#_page8_x68.00_y229.04)
1. [Вопрос 4.2.2](#_page8_x68.00_y592.04)
1. [Вопрос 4.2.3](#_page9_x68.00_y248.04)
1. [Вопрос 4.2.4](#_page9_x68.00_y519.04)
1. [Вопрос 4.2.5](#_page10_x68.00_y248.04)
1. [Вопрос 4.3.1](#_page10_x68.00_y558.04)
1. [Вопрос 4.3.2](#_page11_x68.00_y248.04)
1. [Вопрос 4.3.3](#_page11_x68.00_y529.04)
1. [Вопрос 4.4.1](#_page12_x68.00_y318.04)
1. [Вопрос 4.4.2](#_page12_x68.00_y618.04)
1. [Вопрос 4.4.3](#_page13_x68.00_y258.04)
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 6
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 7
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 7
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 8
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 8
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 9
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 9
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 10
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 10
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 11
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 11
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 12
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 12
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 13
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 13
- .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 14



Список таблиц 

<a name="_page4_x68.00_y151.04"></a>1  Цель работы 

Пройти третий блок курса “Основы кибербезопасности”

<a name="_page5_x68.00_y151.04"></a>2  Выполнение блока 3: Криптография 

на практике

1. Введение<a name="_page5_x68.00_y274.04"></a> в криптографию

Для ответа на вопрос используется определение ассмиетричного шифрования с двумя ключами (рис. [2.1).](#_page5_x68.00_y541.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.001.jpeg)

<a name="_page5_x68.00_y541.04"></a>Рис. 2.1: Вопрос 4.1.1

Отмечены основные условия для криптографической хэш-функции (рис. 2.[2).](#_page6_x68.00_y247.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.002.jpeg)

<a name="_page6_x68.00_y247.04"></a>Рис. 2.2: Вопрос 4.1.2 Отмечены алгоритмы цифровой подписи (рис. 2[.3).](#_page6_x68.00_y502.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.003.jpeg)

<a name="_page6_x68.00_y502.04"></a>Рис. 2.3: Вопрос 4.1.3

В информационной безопасности аутентификация сообщения или аутентифи- кация источника данных-это свойство, которое гарантирует, что сообщение не было  изменено во  время передачи (целостность  данных) и  что принимающая сторона может проверить источник сообщения (рис. 2.[4)](#_page7_x68.00_y258.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.004.jpeg)

<a name="_page7_x68.00_y258.04"></a>Рис. 2.4: Вопрос 4.1.4 Определение обмена ключами Диффи-Хэллмана. (рис. 2.[5).](#_page7_x68.00_y518.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.005.jpeg)

<a name="_page7_x68.00_y518.04"></a>Рис. 2.5: Вопрос 4.1.5

2. Цифровая<a name="_page7_x68.00_y576.04"></a> подпись 

По определению цифровой подписи протокол ЭЦП относится к протоколам с публичным ключом (рис. [2.6).](#_page8_x68.00_y229.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.006.jpeg)

<a name="_page8_x68.00_y229.04"></a>Рис. 2.6: Вопрос 4.2.1

лгоритм верификации электронной подписи состоит в следующем. На первом этапе получатель сообщения строит собственный вариант хэш-функции подпи- санного документа. На втором этапе происходит расшифровка хэш-функции, со- держащейся в сообщении с помощью открытого ключа отправителя. На третьем этапе производится сравнение двух хэш- функций. Их совпадение гарантирует одновременно подлинность содержимого документа и его авторства (рис. 2.7[).](#_page8_x68.00_y592.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.007.jpeg)

<a name="_page8_x68.00_y592.04"></a>Рис. 2.7: Вопрос 4.2.2

Электронная подпись обеспечивает все указанное, кроме конфиденциальности (рис.[ 2.8).](#_page9_x68.00_y248.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.008.jpeg)

<a name="_page9_x68.00_y248.04"></a>Рис. 2.8: Вопрос 4.2.3

Для отправки налоговой отчетности в ФНС используется усиленная квалифи- цированная электронная подпись (рис. 2[.9).](#_page9_x68.00_y519.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.009.jpeg)

<a name="_page9_x68.00_y519.04"></a>Рис. 2.9: Вопрос 4.2.4 Верный ответ укзаан на изображении (рис. 2[.10).](#_page10_x68.00_y248.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.010.jpeg)

<a name="_page10_x68.00_y248.04"></a>Рис. 2.10: Вопрос 4.2.5

3. Электронные<a name="_page10_x68.00_y307.04"></a> платежи 

Известные платежные системы - Visa, MasterCard, МИР (рис. 2.[11).](#_page10_x68.00_y558.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.011.jpeg)

<a name="_page10_x68.00_y558.04"></a>Рис. 2.11: Вопрос 4.3.1 Верный ответ на изображении (рис. [2.12).](#_page11_x68.00_y248.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.012.jpeg)

<a name="_page11_x68.00_y248.04"></a>Рис. 2.12: Вопрос 4.3.2

При онлайн платежах используется многофакторная аутентификация (рис. [2.13).](#_page11_x68.00_y529.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.013.jpeg)

<a name="_page11_x68.00_y529.04"></a>Рис. 2.13: Вопрос 4.3.3

4. Блокчейн

<a name="_page11_x68.00_y585.04"></a>Proof-of-Work, или PoW, (доказательство выполнения работы) — это алгоритм достижения консенсуса в блокчейне; он используется для подтверждения тран- закций и создания новых блоков. С помощью PoW майнеры конкурируют друг с другом за завершение транзакций в сети и за вознаграждение. Пользователи

сети отправляют друг другу цифровые токены, после чего все транзакции соби- раются в блоки и записываются в распределенный реестр, то есть в блокчейн. (рис. [2.14).](#_page12_x68.00_y318.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.014.jpeg)

<a name="_page12_x68.00_y318.04"></a>Рис. 2.14: Вопрос 4.4.1

Консенсус блокчейна  — это процедура, в ходе которой участники сети дости- гают согласия о текущем состоянии данных в сети. Благодаря этому алгоритмы консенсуса устанавливают надежность и доверие к самоу сети. (рис. 2.[15).](#_page12_x68.00_y618.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.015.jpeg)

<a name="_page12_x68.00_y618.04"></a>Рис. 2.15: Вопрос 4.4.2

Ответ - цифровая подпись (рис. [2.16).](#_page13_x68.00_y258.04)

![](Aspose.Words.42164e7c-a6c6-4367-b034-3ebeda71de7e.016.jpeg)

<a name="_page13_x68.00_y258.04"></a>Рис. 2.16: Вопрос 4.4.3

<a name="_page14_x68.00_y151.04"></a>3  Выводы 

Я прошла третий блок
15
