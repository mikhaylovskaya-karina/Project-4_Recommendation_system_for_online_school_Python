# Project-4: Recommendation system for online school Python

Онлайн школе требуется решение бизнес-проблемы - увеличение среднего чека. Решено предлагать слушателям курсы, которые могут быть им интересны, для чего требуется создание рекомендательной системы - таблицы, в которой каждому курсу будут соответствовать по две рекомендации.

## Цель: создать основу рекомендательной системы

Решено предлагать студентам курсы, которые чаще покупают вместе с другими курсами. Таким образом, предложенные курсы вероятнее будут соответствовать интересующей студентов предметной области. Для курсов, которые не покупали вместе с другими курсами, решено предлагать рекомендации из числа популярных курсов.

Представленный Python и SQL код отражает этапы анализа продаж курсов и создания основы рекомендательной системы.

*Использованные библиотеки Python: pandas, numpy, psycopg2, collections, itertools, plotly*

**Основные этапы:**
- импорт данных из БД с помощью SQL и библиотеки Psycopg2, анализ продаж курсов школы, создание комбинаций из пары курсов для таблицы с рекомендациями инструментами Pandas;
- создание визуализаций инструментами Plotly;
- выводы и рекомендации.
