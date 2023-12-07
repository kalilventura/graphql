To insert a new Category:
```
mutation createCategory {
  createCategory(input: {
    name: "IT course", 
    description: "Technology course"}) {
    id
    name
    description
  }
}
```
