---
title: "`set.has()`"
description: "Метод проверяет наличие значения в коллекции Set"
authors:
  - nlopin
tags:
  - doka
---

## Кратко

Метод `has` проверяет, содержится ли значение в коллекции [`Set`](/js/set). Если значение есть в коллекции, метод вернёт `true`, в противном случае — `false`.

## Пример

```js
const watchList = new Set(['Сияние', 'Интерстеллар', 'Казино'])

console.log(watchList.has('Казино'))
// true

console.log(watchList.has('Чёрная пантера'))
// false
```

## Как пишется

Метод принимает один аргумент — значение, которое нужно проверить.

Возвращает булево значение:

- `true` если коллекция содержит искомое значение;
- `false` если значения в коллекции нет.
