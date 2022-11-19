
Class Heartattern
{
Public static void main(String[] args)
{
 Final int size=4;
For(int n=0;n<=4*size;n++)
{
double pos1 = math.sqrt(math.pow(m.size,2)+math.pow(n-size,2));
double pos2 =math.sqrt(math.pow(n-size,2)+math.pow(n-3*size,2));

If(pos1<size+0.5||pos2<size+0.5)
{
System.out.print('*');
}
else
{
System.out.print('   ');
}
}
System.out.print(System.lineSeparator());
}
For(int m=1;m<=2*size;m++)
{
for(int n=0;n<m;n++)
{
System.out.print('  ');
}
for(int n=0;n<4*size+1-2*m;n++)
{
System.out.print("*");
}
System.out.print(System.lineSeparator());
}
}
}
