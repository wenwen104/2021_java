
```
import java.util.Scanner;
public class NestIf4 {
  public static void main(String[] args) {
		Scanner scn = new Scanner(System.in);
		int num1, num2, num3, max;
		System.out.print("Please input 4 numbers:");
		num1 = scn.nextInt();
		num2 = scn.nextInt();
		num3 = scn.nextInt();
		if (num1 > num2) {        
			if (num1 > num3)
				if (num1 > num4)
				    max = num1;
				else
					max =num4;
			else
			    if (num3 > num4)
				    max = num3;
				else
					max =num4;
		} else {
        待完成 期中考必考
        
        
        
        
        
        
        
        
        
		}
		System.out.println("程计琌:" + max);
		scn.close();
	}
}

```

