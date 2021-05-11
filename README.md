## Тест по адресу [demo api](http://localhost:9000/api)
`
query {
  listings {
    id
    title
    price
    address
  }
}


 mutation {
   deleteListing(id: "001") {
     id
     title
     price
     address
   }
 }

`
