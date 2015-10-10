****what is mutable and immutable object?****
immutable object:
    in java  Immutable simply means un modifiable or unchangeable.once an object is created its data or state cannot be change but a new string object is created.If an object is known as to be immutable the object reference can be shared.following are an example of immutable object.

Example:

class immutable object{

     
public static void main (string args[])
 {


  string s="kiran";



  s.concat("Tufail");


 System.out.println(s);

  }

}

output:
         kiran

 Mutable object:

        Mutable object can be modified or can be changed after its creation.
        The example of mutable object is given below.

Example:

class mutable object{

public static void main(string args[])

          {
           
            string s="Kiran";


           s=s.concat("Tufail");


          System.out.println(s);

           }

     }

output:
   kiran Tufail
       
Q:what is string in java ?

   string is an immutable object that cannot be change once it is created.
if there is needs to make a modification to string string buffer is used.
there are various function use in string.

* To lower():

           IT CONVERT THE STRING IN TO LOWER CASE.

* TO UPPER():

IT CONVERT THE STRING INTO UPPER CASE.

* CONCAT():

      IT CONCATE TWO STRING.MEANS COMBINING TWO STRINGS.

* LENGTH():

     it count the total length of string.

* char at():

      it can be use to search a character.

* sub str():

       return a string that is sub string of the string.

* TRIM():

       Returns a copy of the string with leading and trailing white space omitted.


    
    
            
       
 