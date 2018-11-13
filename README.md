# Inheritance-Java


package main;
class Base
{
public void Print()
{
System.out.println("Base");
}
}
class Derived extends Base{
public void Print()
{
System.out.println("Derived");
}
}
class Main4{
Public static void DoPrint(Base o)
{
o.print();
}
public static void main(String[] args)
{
Base x=new Base();
Base y=new Derived();
Derived z=new Derived();
DoPrint(x);
DoPrint(y);
DoPrint(z);
}
