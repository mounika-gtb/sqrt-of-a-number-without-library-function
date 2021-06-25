# sqrt-of-a-number-without-library-function
public class sqrt_without_function
{
public class void main(Strings[] args)
Scanner sc = new scanner(System.in);
System.out.println("enter number");
int n = sc.nextInt();//16
float sqrt,t=0;
sqrt = n/2;//16/2 = 8
if (n==1)
System.out.println("Square root of "+n" is "+n);
else
{
while(sqrt !=t)//8!=0,5!=8,4.1!=5,4.0!=4.1,4.0==4.0
{
t = sqrt;//t=8,t=5,t=4.1,t=4.0,
sqrt = (n/t + t)/2;///sqrt=(16/8+8)/2=5;sqrt=4.1;sqrt=4.0;sqrt=4.0

}
System.out.println("square root of "+n" is "+sqrt);//4.0
}
}
