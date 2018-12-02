# guvi
import java.util.Scanner;
public class digits{
public static void main(sting[]args){
Scanner S=new Scanner(System.in);
int count=0;
int n=S.nextInt();
while(n!=0){
n=n/10;
count++;
}
System.out.print(count);
}
}
