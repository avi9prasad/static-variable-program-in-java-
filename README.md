# static-variable-program-in-java-
class Student8{  
   int rollno;  
   String name;  
   static String college ="TIB";  
     
   Student8(int r,String n){  
   rollno = r;  
   name = n;  
   }  
 void display (){System.out.println(rollno+" "+name+" "+college);}  
  
 public static void main(String args[]){  
 Student8 s1 = new Student8(111,"Abhinav");  
 Student8 s2 = new Student8(222,"Dipendu");  
   
 s1.display();  
 s2.display();  
 }  
}  
