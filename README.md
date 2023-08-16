# node-db

https://www.mongodb.com/docs/manual/crud/

<h2>Вставка документов в коллекцию</h2>

```
db.books.insertOne({
  title: "Шерлок холмс",
  description: "приключения знаменитого сыщика",
  authors: "Артур Конан Дойл"
})
db.books.insertOne({
  title: "Шерлок холмс",
  description: "приключения знаменитого сыщика",
  authors: "Артур Конан Дойл"
})
```

<h2>Поиск полей документов коллекции books по полю title</h2>
