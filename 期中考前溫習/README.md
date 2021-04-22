
#
```
public class Main {

	public static void main(String[] args) {
		int total1, x=17, y=28;
		double total2, i=3.8, j=22.7, k=15.1;
		total1 = _____(1)_____;  => add(x,y);
		total2 = _____(2)_____;  => add(i,j,y);
		System.out.printf("%d%n",total1);
		System.out.printf("%f%n",total2);
	}
	
	static int add(int a, int b) {
		return a + b; // 傳回兩個整數相加的結果
	}
	
	static double add(double a, double b, double c) {
		return a + b + c; // 傳回三個倍精確度相加的結果
	}
  
}
```
```
上述程式中填寫結果如下(選出錯誤的)  => ???
[A]total1 = add(x, y);   <====(1)
   total2 = add(x, y, k); <=====(2)
   會正確執行
[B]total1 = add(x, y);   <====(1)
   total2 = add(i, j, k); <=====(2)
   會正確執行
[C]total1 = add(i, j);   <====(1)
   total2 = add(i, j, k); <=====(2)
   會正確執行
[D]以上都會正確執行
```
