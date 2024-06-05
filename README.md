# string-concatenation
public class Concatenation
{
public static void main(String args[])
{
String stringOne = "Hello";
String stringTwo = "Edureka!";
//By using + operator
String finalString = stringOne + " " + stringOne;
System.out.println(finalString)
//by using StringBuilder
StringBuilder sb = new StringBuilder(14);
sb.append(stringOne).append(" ").append(stringTwo);
System.out.println(sb.toString())
//by using StringBuffer
StringBuffer sBuffer = new StringBuffer(15);
sBuffer.append(stringOne).append(" ").append(stringTwo);
System.out.println(sBuffer.toString());
}
}
