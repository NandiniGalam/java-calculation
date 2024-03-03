# java-calculation
import java.util.*;
class Calculation {
  int z;
  public void addition(int x,int y) {
    System.out.println("the sum of the given  numbers:"+z);
  }
  public void subraction(int x,int y) {
    z=x-y;
    System.out.println("the difference between the given numbers:"+z);
  }
}
class My_Calculation extends Calculation {
  public void multiplication(int x,int y) {
    z=x*y;
    System.out.println("the product of the given numbers:"+z);
  }
  public static void main(String args[]) {
    int a =20,b = 10;
    My_Calculation demo = new My_Calculation();
    demo.addition(a,b);
    demo.subraction(a,b);
    demo.multiplication(a,b);
  }
  
}
