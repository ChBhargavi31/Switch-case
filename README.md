Package Switchcase;
Public class Switchcase{
Public static void main(String[]args){
int choice;
System.out.println("Pick one:1.Hi\t2 .Hey\t3. Hello\t");
Scanner S=new Scanner(System.in);
choice=S.nextInt();
Switch(choice)
{
case 1:System.out.println("you said Hi");
break;
case 2:System.out.println("you said Hey");
break;
case 3:System.out.println("you said Hello");
break;
default:System.out.println("Invalid choice");
break;
}
}
}
