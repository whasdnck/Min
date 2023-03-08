# Min

## Min 코드
package sungil21102algo;

import java.util.Scanner;

class Min {

	public static void main(String[] args) {
		
		
		Scanner stdIn = new Scanner(System.in);
		
		System.out.println("한 개의 정수를 입력하세요.");
		int a = stdIn.nextInt();
		System.out.println("또 다른 정수를 입력하세요.");
		int b = stdIn.nextInt();
		System.out.println("마지막 정수를 입력하세요.");
		int c = stdIn.nextInt();
		
		int min = a;
		if(b < min) min = b;
		if(c < min) min = c;
		
		System.out.println("셋 중 가장 최소 값은 " + min +  "입니다.");
	}
}
