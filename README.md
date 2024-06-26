# goit-algo-hw-07

# Проєкт: Бінарне Дерево Пошуку

Цей проєкт демонструє реалізацію бінарного дерева пошуку (Binary Search Tree, BST) на мові програмування Python. У проєкті представлена реалізація основних операцій з деревом, таких як додавання, видалення, пошук, знаходження мінімального та максимального значення, а також обчислення суми всіх елементів у дереві.

## Опис

Бінарне дерево пошуку (BST), або ще його називають AVL-деревом - це структуроване дерево, де кожен вузол має не більше двох нащадків. Лівий нащадок вузла містить значення, менше або рівне значенню самого вузла, а правий нащадок містить значення, більше або рівне значенню вузла.

## Функціональність

Проєкт реалізує такі методи для роботи з бінарним деревом пошуку:

- `insert(self, new_node)`: Додає новий вузол у дерево.
- `delete(self, key)`: Видаляє вузол із заданим ключем.
- `find_max(self)`: Повертає максимальне значення у дереві.
- `find_min(self)`: Повертає мінімальне значення у дереві.
- `get_sum(self)`: Повертає суму всіх значень у дереві.
- `search(self, key)`: Шукає задане значення у дереві.

## Результати

Приклади роботи програми:

Заповнюємо AVL дерево, приклад:
- Root: 50
  - L--- 37
    - L--- 5
      - R--- 15
        - R--- 21
  - R--- 96
    - L--- 69
      - L--- 59
      - R--- 71
        - R--- 92

Сума всіх значень: 515

Мінімальне значення: 5

Максимальне значення: 96
