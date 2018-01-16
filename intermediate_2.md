# Intermediate 2

## student

```
{
  id: int
  fname: string
  lname: string
  email: string
  classes: array of class ids
}

```

## class

```
{
  id: int
  title: string
  students: array of student ids
}

```

## semester

```
{
  id: int
  year: int
  period: string  //fall, spring, summer, winter, etc.
}

```

## exam

```
{
  id: int
  student_id: int
  class_id: int
  grade: int or string
  date: date
}

```