# Pentagon

import java.util.*;
public class Pentagon
{
    public int calcPentagonalNumber(int i)
    {
        return i*(3*i-1)/2;
    }
}

 
public class testPentagon
{
   public static void main(String [] args)
   {
       Pentagon myPentagon = new Pentagon();
       
       int x = 1;
       
       while(x <= 100)
       {
           for (int i=1; i <= 10; i++)
           {
               int value = myPentagon.calcPentagonalNumber(x);
               System.out.print(value+ "  ");
               x++;
           }
       System.out.println();
       }
   }
}
