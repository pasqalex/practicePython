# Python Practice Tasks

Учебные задачи по Python, решённые в рамках самостоятельной подготовки.  
Репозиторий создан для отработки навыков написания чистого и идиоматичного кода, работы с алгоритмами и структурами данных, а также освоения современных возможностей языка.

## Цели репозитория

- Прокачать уверенное владение Python на уровне, достаточном для позиции Junior+/Middle Data Engineer.
- Научиться писать чистый, самодокументируемый и поддерживаемый код (PEP 8, type hints, docstrings).
- Освоить функциональное и объектно-ориентированное программирование в Python.
- Попрактиковаться в реализации классических алгоритмов и структур данных с нуля.
- Изучить продвинутые возможности языка: декораторы, контекстные менеджеры, генераторы.
- Подготовиться к реальным задачам на собеседованиях и в работе с данными.

## Стек

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/Black-000000?style=for-the-badge&logo=black&logoColor=white" />
  <img src="https://img.shields.io/badge/Flake8-EF4323?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/MyPy-2A6D8A?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
</p>

## Навигация по задачам

## Используемые техники

### Структуры данных и алгоритмы

- `list`, `dict`, `set`, `tuple` — выбор подходящей структуры под задачу.
- `collections` (`Counter`, `deque`, `defaultdict`, `OrderedDict`) — расширенные контейнеры.
- `heapq` — работа с кучами для задач на приоритеты.
- Связные списки, стеки, очереди, хеш-таблицы — реализация с нуля.
- Алгоритмы сортировки, поиска, скользящего окна и двух указателей.
- Динамическое программирование для оптимизации сложных задач.

### Функциональное программирование

- `map`, `filter`, `reduce` — обработка коллекций в функциональном стиле.
- `lambda` и `partial` — создание анонимных и частично применённых функций.
- `itertools` — эффективные итераторы для комбинаторики и обхода данных.
- `functools` — кэширование (`lru_cache`), композиция и обёртки.

### ООП и продвинутые возможности

- Классы, наследование, полиморфизм, инкапсуляция.
- `@property`, `@staticmethod`, `@classmethod` — управление доступом и поведением.
- Дескрипторы (`__get__`, `__set__`, `__delete__`) — контроль над атрибутами.
- Декораторы классов и функций с сохранением метаданных (`@wraps`).
- Абстрактные базовые классы (`ABC`, `abstractmethod`).

### Итераторы и генераторы

- `yield` и `yield from` — ленивые вычисления и экономия памяти.
- Пользовательские итераторы (`__iter__`, `__next__`).
- Генераторные выражения и включения (`generator expression`).
- Бесконечные последовательности и конвейерная обработка данных.

### Работа с файлами и данными

- `pathlib` — объектно-ориентированная работа с путями.
- `csv`, `json` — парсинг и сериализация структурированных данных.
- `with` statement и пользовательские контекстные менеджеры (`__enter__`, `__exit__`).
- Работа с бинарными файлами и потоками (`io.BytesIO`, `io.StringIO`).

### Асинхронное программирование

- `asyncio` — написание конкурентного кода.
- `async` / `await` — кооперативная многозадачность.
- `aiohttp` — асинхронные HTTP-запросы.
- `async for` и асинхронные генераторы.

### Тестирование и качество кода

- `pytest` — юнит-тесты, параметризация, фикстуры.
- `unittest.mock` — мокирование зависимостей.
- `black` — автоматическое форматирование.
- `flake8` — статический анализ и линтинг.
- `mypy` — статическая типизация и проверка type hints.

## Примечания

- Задачи взяты из открытых источников (LeetCode, Codewars, Cracking the Coding Interview) и адаптированы под учебные цели.
- Некоторые решения намеренно реализованы несколькими способами (наивный, оптимизированный, однострочник) для сравнения подходов.
- Все задачи разобраны в отдельных файлах с подробным описанием логики, сложности по времени и памяти, а также юнит-тестами.
- Репозиторий будет пополняться по мере прохождения новых тем.
- README находится в процессе доработки.
