****what is mutable and immutable object?****
immutable object:
    in java  Immutable simply means un modifiable or unchangeable.once an object is created its data or state cannot be change but a new string object is created.If an object is known as to be immutable the object reference can be shared.following are an example of immutable object.

Example:

class immutable object{
     
public static void main (string args[])
 {
string s="kiran";

s.concate("Tufail");

System.out.println(s);

  }

}

output:
         kiran
 Mutable object:

        Mutable object can be modified or can be changed after its creation.The example of mutable object is given below.

Example:

class mutable object{
public static void main(string args[])
          {
            string s="Kiran";
           s=s.concate("Tufail");
          System.out.println(s);
           }
     }

output:
kiran Tufail
       
            
       
 
