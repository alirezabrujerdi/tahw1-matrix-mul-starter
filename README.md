# TA HW 1 - Matrix Multiplication - 50 Points

[![Grader Status](https://kntu-grader.herokuapp.com/minimal?repo=tahw1-matrix-mul-starter&id=9725073)](https://kntu-grader.herokuapp.com/minimal?repo=tahw1-matrix-mul-starter&id=9725073)




# Assignment discription

<div dir="rtl" align="right">
تابعی مطابق با امضای تعریف شده زیر تعریف کنید تا عملیات ضرب ماتریسی به وسیله آرایه دو بعدی را پیاده سازی کند.


</div>



```java
package ir.ac.kntu;

public class MatrixSolution{

    public static int[][] multiply(int[][] matA,int[][] matB){
        //return null when multiplication is not possible

    }

    public static void main(String[] args){
        int[][] d = {{1, 2, 3, 5},{4, 5, 6, 8}};
        int[][] c = {{1, 2, 3},{4, 5, 6},{9, 1, 3},{9, 1, 3}};
        int[][] multiply = multiply(d, c);
        System.out.println("multiply = " + Arrays.deepToString(multiply));
    }

}
```

# ورودی
نیازی به دریافت ورودی نیست. امضای متد تعریف شده را تغییر ندهید در صورت نیاز متد های خودتان را اضافه کنید.
# خروجی
نیازی به چاپ خروجی نیست.
