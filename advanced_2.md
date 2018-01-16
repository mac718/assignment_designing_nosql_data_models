# Advanced 2

## user

```
{
  id: int,
  user_name: string,
  email: string,
  fname: string,
  lname: string,
  password: string,
  friends: array of user ids,
  profile:{
    about: text,
    gender: string,
    bday: date,
    occupation: string,
    location:{
      city: string,
      state_id: int
    }
  }
  friends: array of user ids
  interactions: array of user ids
  activites: array of ids and timesstamps, i.e. [[activity, timestamp]]
}

```

## activity

```
{
  id: int
  code: string
}

```

## state

```
{
  id: int
  abbrev: string
}

```



