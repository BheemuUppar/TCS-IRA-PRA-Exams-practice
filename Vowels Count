import java.util.Scanner;
public class Solution {
	public static void main(String[] args) {
		Scanner scn=new Scanner(System.in);
		String s=scn.nextLine();
		int vowels=0; 
		int consonents=0;
		scn.close();
		for(int i=0;i<s.length();i++) {
			if (s.charAt(i)>=65 && s.charAt(i)<=123) {
				if (s.charAt(i)=='a'|| s.charAt(i)=='e'|| s.charAt(i)=='i' || s.charAt(i)=='o' || s.charAt(i)=='u' || s.charAt(i)=='A'|| s.charAt(i)=='E'|| s.charAt(i)=='I' || s.charAt(i)=='O' || s.charAt(i)=='U')  {
					vowels++;
				}
				else {
					consonents++;
				}
			}
		}
		System.out.println("Vowels: "+ vowels);
		System.out.println("Consonants: "+consonents);
	}
}
