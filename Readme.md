# JSON Server
> This is the ` Fake JSON ` server tutorial notes 

- GET :
    - Getting the data \
    ` http://localhost:3000/products ` \
    ` http://localhost:3000/reviews `

- FILTER : 
    - filtering the data \
    ` http://localhost:3000/products?category=electronics `

    - filtering the data with nested items \
    ` http://localhost:3000/products?category=electronics&discount.type=shipping `


- SORT :
    - sorting the data (ascending) & (descending) \
    ` http://localhost:3000/products?_sort=price ` \
    ` http://localhost:3000/products?_sort=price&_order=desc `

    - sorting the data (let say 3 different items have same price) \
    ` http://localhost:3000/products?_sort=price,category&_order=desc,asc `


- PAGINATION :
- 
