# position-of-odd-and-even
import java.util.*;
public class stringdemo
{
public static void main(String args[])
{
String st;
int i,j;
Scanner sc=new Scanner(System.in);
st=sc.next();
int n=st.length();
for(i=0;i<n;i++)
{
j=i+1;
if(j%2!=0)
{
System.out.print(st.charAt(i));
}
}
System.out.print(" ");
for(i=0;i<n;i++)
{
j=i+1;
if(j%2==0)
{
System.out.print(st.charAt(i));
}
}
}
}
