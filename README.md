Finding Length of string without using length() method
In this article we’re going to make a Java program to find length of String without using length() method . In this program first we will take the String input from user . After that we will convert String to character array by using toCharArray() . After that we will use for-each loop to count the length  of the String

length of string without using strlen
Algorithm:
In this program first we will take String input from user and store in the variable called s with the help of next()
After that we will take a for-each loop and in the paremeter of for-each loop we will convert the String to character array using toCharArray() 
After that for every variable we will take a variable named as count and increment this every time
Calculating Length of the string without using strlen()
Code in Java
Run
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		int length=0;
		
                String s = "prepinsta";
                for (char c1 : s.toCharArray()) 
			length++;
		System.out.println("Length of String is : "+length);
		
	}

}
Output
Enter a String prepinsta
Length of String is : 9
Note
The time complexity of this code is O(n) and if you are using the build in function like strlen or length the time complexity will still be same O(n)
