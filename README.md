package exam1;
import java.util.Scanner;
public class Main {
    static void print(String txt){
        System.out.print(txt);
    }
    public static void main(String[] args) {
        double n1,n2,n3;
        Scanner in = new Scanner(System.in);
        print("Enter your first grade grades : ");
        n1 = in.nextDouble();
        print("Enter your second grade grades : ");
        n2 = in.nextDouble();
        print("Enter your third grade grades : ");
        n3 = in.nextDouble();
        if(n1<50||n2<50||n3<50){
            print("fail");
        }else{
            print("passed \nTotal : "+(n1+n2+n3)+"\nAv : "+(n1+n2+n3)/3);
        }
    }
