# Room: an SQLite object mapping library

Handling an SQLite database in Android implies challenges like: 
- a lot of boilerplate code
- database operations on the main thread
- queries checked at runtime and especially 
- unmaintainable code

At Google I/O 2017, the Android team launched Room, an SQLite object mapper, that provides a set of components and features that will solve all these challenges and will help us, the developers, to have a better experience when using a database in our app. 

This code includes examples about:
- how to use the main components from Room (@Entity, @Dao, @Database)
- how to handle the relations between the entities
- how to use the (observable) queries
- not run database operations on the main thread
- migration support

Check these 4 tutorials:
- Introduction: https://medium.com/@magdamiu/android-room-persistence-library-97ad0d25668e 
- Components: https://medium.com/@magdamiu/android-room-components-5a7458b99191
- Relations: https://medium.com/@magdamiu/android-room-persistence-library-relations-75bbe02e8522
- Queries and Migration: https://medium.com/@magdamiu/android-room-persistence-library-queries-and-migration-support-a9f21d2dc9d8 
