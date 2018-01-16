# Basic

## user

```
{
  id: int  
  username: string  //at least 3 characters
  password: string  //at least 8 characters
  email: string  //must contain '@' and '.' and neither can be the first or last character
  profile: {
    birthday: date  
    gender: string  
    phone_number: int  //must be 10 digits long
    location{
      city: string  //must be > 1 character
      state_id: int
      country_id: int
      about: text
    }
  }
  hide_birthday: boolean
  hide_location: boolean
  hide_gender: boolean
  hide_phone_number: boolean
}



```

## state

```
{
  id: int
  name: string
}

```

## Country

```
{
  id: int
  name: string
}

```