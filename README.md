## Задание 1 (пакет com.dmrval.task1)

### Постановка задачи

Реализуйте метод `findDuplicates`, который должен возвращать список значений, которые повторяются `numberOfDuplicates`
раз.

К примеру:

```java
findDuplicates(asList(-1,1,3,2,2,2,5,6,-1,3,6),2);
```

должен возвращать «-1, 3 и 6», поскольку эти значения повторяются «numberOfDuplicates = 2» раз, но не «2», которое
повторяется 3 раза.

```java
findDuplicates(asList(-1,-1,2,2,null,null),2);
```

_Пустые значения не учитываются:_

должен вернуть `-1 и 2`.

_Метод не должен возвращать значение  `null` (если передается null, возвращайте пустой список)._

## Задание 2 (пакет com.dmrval.task2)

### Постановка задачи

Необходимо реализовать метод `integerSum` (в классе `ListOperation`), который должен возвращать сумму целых значений из
списка строк.

К примеру:

```java
integerSum(Arrays.asList("1 больше чем -1","сегодня 1 апреля 2021 года"));
```

должен вернуть

```java
2022
```

## Задание 3 (пакет com.dmrval.task3)

### Постановка задачи

Необходимо реализовать метод `getThreeMaximum` (в классе `FindTheMaximumElements`), который должен возвращать 3
максимальных значения BigDecimal из списка строк.

К примеру:

```java
getThreeMaximum(Arrays.asList("2","15","654","11","94","-200","89","-1","0"));
```

должен вернуть

```java
Arrays.asList("89","94","654")
```
_Метод не должен возвращать значение  `null` (если передается null, возвращайте пустой список)._
_Пустые значения не учитываются._

## Задание 4 (пакет com.dmrval.task4)

### Постановка задачи

Необходимо реализовать метод `findFromCollection` (в классе `EvenAndOddFinder`) принимающий `List<Set<String>> input`, 
который должен возвращать `Map<CharacterType, Set<String>>` - `Map` с распределенными сетами, состоящих из четных и не четных символов строк.

Где:

`CharacterType` это перечисление из двух элементов, четное(`EVEN`) и не четное(`ODD`)

К примеру:

```java
Set<String> set1 = инициализация ...;

Set<String> set2 = инициализация ...;

findFromCollection(Arrays.asList(set1, set2));
```

должен вернуть

```java
{ODD=[сет из строк с не четным количеством символов], EVEN=[сет из строк с четным количеством символов]}
```
_Метод не должен возвращать значение  `null`. Если передается `null`, возвращайте:_
```java
{ODD=[], EVEN=[]}
```
_Метод может принимать `null` вместо `Set<String>` внутри списка._
_Метод может принимать `null` и `""` элементы._




