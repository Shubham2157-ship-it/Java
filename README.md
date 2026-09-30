import java.util.*;
public class Calculator{
  public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    System.out.println ("number1");
    double num1=sc.nextDouble();
    System.out.println ("number2");
    double num2=sc.nextDouble();
    System.out.println("operation +,-,*,/,%");
    char operation=sc.next().charAt(0);
    double result =0;
    switch(operation){
    case '+':result=num1+num2;
    break;
    case '-':result=num1-num2;
    break;
    case'*':result=num1*num2;
    break;
    case'/':result=num1/num2;
    break;
    case'%':result=num1%num2;
    return;
    }
    System.out.println("answer="+result);
    }
    }
