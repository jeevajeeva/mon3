# mon3
import java.io.*;
import java.util.*;
public class Main
{
public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        String s=sc.next();
        char[] ch1=s.toCharArray();
        int j=s.length();
        for(int i=0;i<j;i++)
        {
            if(ch1[i]!=ch1[j-1])
            {
                System.out.print(ch1[i]+" "+ch1[(j-1)-i]+" "); 
            }
        }
        
    }
}
