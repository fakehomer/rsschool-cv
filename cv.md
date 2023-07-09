# Aliaksandr Dubiaha  
## Contact Information  
phone: +375333181229  
email: williampokhlyobkin@gmail.com  
discord: fakehomer  
telegram: @k_tulin   
## About Me  
I am student of the Faculty of Electronic Information Systems of BrSTU. I have already completed the 3rd course in the specialty of automated information processing systems. Currently I work as a system administrator in a small company. I want to acquire new knowledge, so I signed up for the JS / FE Pre-School 2023Q2 course.  
## My Skills  
I have basic knowledge of Java and C++ programming language. IDEs I use: VS Code, IntelliJ IDEA, Visual Studio. I have some experience with git and GitHub.
## Code example:  
[Task](https://acmp.ru/asp/do/index.asp?main=task&id_course=3&id_section=23&id_topic=321&id_problem=2084)  
My solution:  
```java
import java.util.Scanner;
 
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int A, B, VA, VB;
        A = scanner.nextInt();
        B = scanner.nextInt();
        VA = 50 * A;
        VB = 70 * B;
        int min, max;
        min = Math.max(VA - 50, VB - 70);
        max = Math.min(VA, VB);
        if (Math.abs(VA - VB) > 60) System.out.print(-1);
        else {
            for (int i = 1; 60 * i < max + 60; i++) {
                if (60 * i > min && 60 * i < max + 60) System.out.print(i + " ");
            }
        }
    }
}
```  
## Courses  
* RS Schools Course «JS/FE Pre-School 2023Q2» (in progress)  
## Languges  
* English - Pre-Intermediate  
* Russian - Native  
* Belarusian - Native  