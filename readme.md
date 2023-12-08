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

Example to how to find the categories:
```
query queryCategories {
  id
  name
  description
}
```
