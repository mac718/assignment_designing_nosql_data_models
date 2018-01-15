## Intermediate 1

# reservation

```
{
  restaurant_id: int  
  number_of_guests: int
  reservation_time: datetime
  name: string
  phone_number: int //must be 10 digits
}

```

# restaurant

```
{
  id: int
  name: string
  tables: {
    id: int
    capacity: int
    open_time_slots: array of times
  }
}

```
