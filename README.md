# getting-three-inputs
sample program
import java.util.Scanner;
class threeinp
{
public static void main(String []args)
{

Scanner s=new Scanner(System.in);
System.out.println("Enter Three Inputs");
System.out.println("enter the value a:");
int a=s.nextInt();

System.out.println("enter the value b:");
int b=s.nextInt();

System.out.println("enter the value c:");
int c=s.nextInt();


if((a>b)&&(a>c))
{
System.out.println("a is grater");
}
else if((b>c)&&(b>a))
{
System.out.println("b is grater");
}
else if((c>b)&&(c>a))
{
System.out.println("c is grater");
}
else 
{
	System.out.println("false");
}
}
}
