import java.util.Scanner;

public class Quest1 {
	public static void main(String[] args) {
		Scanner s=new Scanner(System.in);
		String codeword1=s.nextLine();
		String codeword2=s.nextLine();
	
		System.out.println(codewordCheck(codeword1,codeword2));
	
	}
	public static int codewordCheck(String codeword1,String codeword2) {
		int count=0;
		if(codeword1.length()!=codeword2.length())
			return -1;
		for(int i=0;i<codeword1.length();i++) {
		if(codeword1.charAt(i)!=codeword2.charAt(i)) {
			count++;	
		}
		}
		return count;
 }

}
