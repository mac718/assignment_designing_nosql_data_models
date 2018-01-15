## Advanced 1

# products

```
{
  id: int
  code: string
  name: string
  price: int
  department_id: int
  stock: int
}

```

#department

```
{
  id: int
  name: string
  products: array of priduct ids
}
```

# transactions

```
{
  id: int
  amount: float
  date: date
  product_id: array of product ids
}

```

# customer

```
{
  id: int
  f_name: string
  l_name: string
  email: string
  password: string
  address: {
    street_1: string
    street_1: string
    city: string
    state_id: int
    zip_code: int
  }
  phone_number: int
}

```