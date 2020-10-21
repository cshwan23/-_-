# 연산자-_-
산술연산자/나머지연산자/더하기연산자

package org.opentutorials.javatutorials.operator;

public class ArithmeticDemo {

	public static void main(String[] args) {
		
		// 연산자(operator)
		// : 특정한 작업을 사용하기 위한 기호
		// ex.(대입연산자.= 산술연산자.+- 비교연산자 논리연산.조건문)
		
		// 1.산술연산자(Arithmetic)
		// 수학적인 기능(+,-,*,/,%) 
		
		
		//result의 값은 3
		int result = 1 + 2;
		System.out.println(result);
		//int 데이터 타입. result 변수명.
		
		//result의 값은 2
		result = result - 1;
		System.out.println(result);
		
		//result의 값은 4
		result = result * 2;
		System.out.println(result);
		
		//result의 값은 2
		result = result / 2;
		System.out.println(result);
		
		//result의 값은 10
		result = result +8;
		System.out.println(result);
		
		//result의 값은 3
		result = result % 7;
		System.out.println(result);
		
	
		//2.나머지(%) 연산자
		//reamain  
		
		
		
		int a = 3;
		System.out.println(0%a);
		//0 을 a 로 나누면
		//0 을 3 로 나누면
		// 값은 0 나머지도 0
		
		System.out.println(1%a);
		// 1을 3 로 나누면
		// 값은 0 나머지는 1
		
		System.out.println(2%a);
		// 2을 3 로 나누면
		// 값은 0 나머지는 2
		
		System.out.println(3%a);
		// 3을 3 로 나누면
		// 값은 1 나머지는 0
		
		System.out.println(4%a);
		// 4를 3으로 나누면
		// 값은 1 나머지는 1
		
		System.out.println(5%a);
		// 5를 3으로 나누면
		// 값은 1 나머지는 2
		
		// 나머지를 잘 쓰면 순환하는 값을 
		// 만들 수 있다.
		// 요긴하게 사용되는 경우가 있다.
		
		
		
		// 3. 더하기 연산자
		// concat
		// 숫자와 숫자를 더할 때도 사용이되지만,
		// 문자열과 문자열을 결합할 때도 사용된다.
		
		String firstString = "This is";
		
		String secondString = " a concatenated string.";
		
		String thirdString = firstString + secondString;
		
		System.out.println(thirdString);
		
		
		
