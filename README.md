//StudentIdentities
import java.util.Scanner;
public class StudentIdentity{
public static void main(String[]args){
    Scanner input=new Scanner(System.in);//scanner object for taking input from user 
    System.out.println("Enter Student name:");
    String studentname=input.nextLine();
    //Taking Student details from user
    System.out.println("Enter Student ID:");
    int studentID=input.nextInt();
    System.out.println("Enter Student Age:");
   int studentAge=input.nextInt(); 
   System.out.println("Enter Student Fee:");
float studentFee=input.nextFloat(); 
System.out.println("Enter Student Grade:");
char studentGrade=input.next().charAt(0);
//Print student details
System.out.println("Student Name="+studentname);

System.out.println("Student ID="+studentID);
System.out.println("Student Age="+studentAge);
System.out.println("Student Fee="+studentFee+"Lakh BDT");
System.out.println("Student Grade="+studentGrade);
input.close();//closing scanner
}

}
