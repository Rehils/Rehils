import java.util.Scanner;
public class grade{
public static void main(String args[]){
double marks;
Scanner input= new Scanner(System.in);
System.out.println("input marks");
marks=input.nextDouble();
if ((marks>=90)&&(marks<=100)){
System.out.println("Grade=A");
}
else if((marks>=75)&&(marks<90)){
System.out.println("Grade=B");
}
else if((marks>=50)&&(marks<75)){
System.out.println("Grade=C");
}
else{
System.out.println("Grade=F");
}
}
}

