import java.util.Scanner;
public class UserInput {
   public static void main(String[] args){
       
     Scanner myObj = new Scanner(System.in);
       
        String name = myObj.nextLine();
        System.out.println("Enter name:" + name);
        
        int age = myObj.nextInt();
        System.out.println("Enter age:" + age);
        
        double salary = myObj.nextDouble();
        System.out.println("Enter salary:" + salary);
        
       char grade = myObj.next().charAt(2);
       System.out.println("Enter grade:" + grade);
       
       boolean k = myObj.nextBoolean();
       System.out.println("Enter Experience:" + k);
