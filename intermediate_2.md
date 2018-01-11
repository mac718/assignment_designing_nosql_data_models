## Intermediate 2

# Student

{
  id: int
  first_name: string
  last_name: string
  email: string
  classes: array of class ids
}

# Class

{
  id: int
  title: string
  students: array of student ids
}

#semester

{
  id: int
  year: int
  period: string  //fall, spring, summer, winter, etc.
}

#exam

{
  id: int
  student_id: int
  class_id: int
  grade: int or string
  date: date
}