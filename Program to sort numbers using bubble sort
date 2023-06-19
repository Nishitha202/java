package Bubble;

import java.util.Scanner;

public class Bubblesort {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Scanner userInput=new Scanner(System.in);
int temp,i,num,j;
System.out.println("enter the numbers to sort");
  num=userInput.nextInt();
 int a[]=new int[num];
 System.out.println("enter"+num+"integers:");
 for( i=0;i<num;i++) {//for loop to take array input 
	 a[i]=userInput.nextInt();
 }
for(i=0;i<(num-1);i++) {
	
	for( j=0;j<num-i-1;j++) {
		if(a[j]>a[j+1]) {
			temp=a[j];
			a[j]=a[j+1];
			a[j+1]=temp;
			
		}
	}
}
System.out.println("The sorted list of integers are:");
for(i=0;i<num;i++) {
	System.out.println(a[i]);// prints the  sorted array 
}
	
	}

}
