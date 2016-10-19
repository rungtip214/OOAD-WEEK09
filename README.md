# OOAD-WEEK09 Homework

#ส่งการบ้านเรื่อง class Diagram 5 ภาพ

รูป1

![](http://www.plantuml.com/plantuml/img/5Sqn2iCm30NGNQSG7WiUkdOeMNg3abrnFuwf8WL7eUJsJVO7RzX2UkoB4hr7JlV4jvmvBM97ufUYH7ThXHzSt4AQRKG1LQop6zXFF242_JY9rDfH9PhRfShCEJ_vQ_vJI0NH0FjSrny0)

@startuml

TV "1" *-- "many" Electronic : contains

tellephone o-- bettery : aggregation

tech --> knowleage

@enduml


รูป2

![](http://www.plantuml.com/plantuml/img/BOqn2e0m40JxUyNMGZehaI3e0om4wwW72SG8Tr6_Rm9sEpF53fgTvFkCj8GS6Vrcz-XKwnYT44qI7XOO54A7ewB2KiN6OFNCiNZl7aRxUsCmi-YLIkXnlKc91av7lVa0)

@startuml
Title <b>class <b>Car

Driver - Car : drives >
Car *- Wheel : have 4 >
Car -- Person : < owns

@enduml


รูป3

![](http://www.plantuml.com/plantuml/img/Kt0eBaaiAYdDpU5ApaaiBbQmgT7LTSrBpyaipk222baf9ENdPsjemlXGQOLgBcrF5oxjvFoyaiIy4gvQBeVKl1IGIG00)

@startuml
class <|--English

class : book()

class English {
+ID
+contant
}
@enduml


รูปที่4

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLYWkJSfAJIvHgEPIKD3EIynD1TAwdYuWNcfUUavcSOQ69eYJcrW2PQMM9Ei1MRLS0000)

@startuml
class subject {
  +name
  -ID
  +english()
  +math()
  +etc.()
}


รูปที่5

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLd0fpSsjLAZcKb1Go4m1ajM9ISKbHOd99RKAsPbvwHgQg6A5fQcfUUY2MOd9sK2nMYw7rBmKaD40)

@startuml
class Dummy {
   id
  {abstract} king()
  {abstract} queen()
  {abstract} jack()
}
@enduml


##Usecase Diagram

```
@startuml

title Use Case Diagram 


(Login)
(Run Process) as (Proc1)
usecase (Undo Process)
usecase (Log Out) as UC4

@enduml
```

<img src = "https://github.com/OOAD-2559/OOAD-WEEK09/blob/master/Homework/usecase1.png">

