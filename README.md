# Основы Javascript
## Урок 10. Семинар. Объекты в JavaScript

### Задание 1:

Дан объект numbers. Необходимо вывести в консоль все значения,
которые больше или равны 3.

```
const numbers = {
    keyin1: 1,
    keyin2: 2,
    keyin3: 3,
    keyin4: 4,
    keyin5: 5,
    keyin6: 6,
    keyin7: 7,
};
```

### Задание 2:

Из объекта post, который задан в константе, выведите значения с
комментариями в консоль.

```
const post = {
        author: "John", // вывести этот текст
        postId: 23,
        comments: [
            {
                userId: 10,
                userName: "Alex",
                text: "lorem ipsum",
                rating: {
                    likes: 10,
                    dislikes: 2, // вывести это число
                },
            },
            {
                userId: 5, // вывести это число
                userName: "Jane",
                text: "lorem ipsum 2", // вывести этот текст
                rating: {
                    likes: 3,
                    dislikes: 1,
                },
            },
        ],
};
```

### Задание 3:

Дан массив products. Уменьшите цену каждого продукта на 15% с
использованием метода forEach.

```
const products = [
    {
        id: 3,
        price: 200,
    },
    {
        id: 4,
        price: 900,
    },
    {
        id: 1,
        price: 1000,
    },
];
```

### Задание 4

Описание задачи:

1. Выведите в консоль массив продуктов, у которых есть хотя бы одна
фотография, используя метод filter.
2. Отсортируйте массив products по цене в порядке возрастания и выведите
отсортированный массив в консоль.

```
const products = [
    {
        id: 3,
        price: 127,
        photos: ["1.jpg", "2.jpg"],
    },
    {
        id: 5,
        price: 499,
        photos: [],
    },
    {
        id: 10,
        price: 26,
        photos: ["3.jpg"],
    },
    {
        id: 8,
        price: 78,
    },
];
```
