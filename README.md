# Method-overloading-
class PrintLine
{
static void printline()
{
for (int i=0; i<40; i++)
System.out.print('='); System.out.println();
}
static void printline(int n)
{
for (int i=0; i<n; i++) System.out.print('='); System.out.println();
}
static void printline(char ch, int n)
{
for (int i=0; i<n; i++) System.out.print(ch); System.out.println();
}
}
public class polyDemo
{
public static void main(String[] s)
{
PrintLine.printline(); PrintLine.printline(30); PrintLine.printline('+', 20);
}
}
