# sum-of-last-digits-of-two-numbers
import java.util.Scanner;
public class Main{
public static void main(String[] args){
Scanner myvar=new Scanner(System.in);
Scanner myvar2=new Scanner(System.in);
int n1=myvar.nextInt();
int n2=myvar2.nextInt();
int sum=0;
sum=sum+(n1%10)+(n2%10);
System.out.println(sum);
}
}


