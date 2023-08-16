# node-db

https://www.mongodb.com/docs/manual/crud/

<h2>Вставка документов в коллекцию</h2>

```
db.books.insertMany([
{
  title: "Шерлок холмс",
  description: "приключения знаменитого сыщика",
  authors: "Артур Конан Дойл"
},
{
  title: "Путешествие в Икстлан",
  description: "общение с индейским магом",
  authors: "Карлос Кастанеда"
}])
```

<h2>Поиск полей документов коллекции books по полю title</h2>

```
db.books.find(
{
  title: "Шерлок холмс"
})
```

<h2>редактирования полей: description и authors коллекции books по _id записи</h2>

```
db.books.updateOne(
{
  {_id: 1},
  {$set {
    description: "приключения знаменитого сыщика и доктора",
    authors: "А. Конан Дойл"}}
})
```
