# remove_copy_if

**Ограничение времени:** 1 секунда  
**Ограничение памяти:** 64Mb  
**Ввод:** стандартный ввод или `input.txt`  
**Вывод:** стандартный вывод или `output.txt`  

Вам надо написать свою реализацию стандартного алгоритма `remove_copy_if`. Заголовок функции должен быть таким:

```cpp
namespace mystd {
template <typename It, typename Out, typename Pred>
Out remove_copy_if(It first, It last, Out out, Pred f);
}
```

Функция должна копировать из подпоследовательности `[first; last)` в последовательность, начинающуюся с `out`, те элементы, которые не удовлетворяют предикату `f`. Функция возвращает итератор, указывающий за последний скопированный элемент.

Протестируйте вашу функцию для предиката "число является чётным" на контейнере `list`.

## Формат ввода
На входе дана последовательность целых чисел.

## Формат вывода
Выведите числа, скопированные вашей функцией `remove_copy_if`.

### Пример 
| **Ввод** | **Вывод** |
| -------- | --------- |
| 1 2 3    | 1 3       |
