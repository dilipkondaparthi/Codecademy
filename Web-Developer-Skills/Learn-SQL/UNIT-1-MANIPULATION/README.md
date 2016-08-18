

##1.Introduction

  > *SELECT * FROM celebs;*
  
##2. Relational Databases

  > *SELECT * FROM celebs;* 
  
##3. Statements

  > *CREATE TABLE celebs (id INTEGER, name TEXT, age INTEGER);*
  
##4. Create

  > *INSERT INTO celebs(id,name,age) VALUES(1,'Justin Beiber',21);*
  
  > *SELECT * FROM celebs;*

##5. Insert
 
  > *INSERT INTO celebs(id, name, age) VALUES(2, 'Beyonce', 33);*
  
  > *INSERT INTO celebs(id, name, age) VALUES(3, 'Jeremy Lin', 26);*
   
  > *INSERT INTO celebs(id, name, age) VALUES(4, 'Taylor Swift', 26);*

  > *SELECT name FROM celebs;*
  
##6. Select

  > *UPDATE celebs SET age=22 WHERE id=1;*

  > *SELECT * FROM celebs;*
  
##7. Update

  > *ALTER TABLE celebs ADD COLUMN twitter_handle TEXT;*

  > *SELECT * FROM celebs;*

##8. Alter

  > *UPDATE celebs SET twitter_handle = '@taylorswift13'  WHERE id = 4;*
  
  > *DELETE FROM celebs WHERE twitter_handle IS NULL;*
 
  > *SELECT * FROM celebs;*
  
##9. Delete

  > *DELETE FROM celebs WHERE twitter_handle IS NULL;*
  
##10. Generalizations
  
  > *Congratulations! You've learned six commands commonly used to manage data stored in a relational database.*
