# CONTEST1
**Bài 1. Tính toán giá trị của biểu thức**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int x;
    scanf("%d\n",&x);
    printf("%lld\n",(long long)pow(x,3) + 3ll*x*x + x + 1);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 2. Tính toán giá trị biểu thức 2**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b,c;
    scanf("%d %d %d \n ",&a,&b,&c);
    printf("%lld\n",1ll*a*(b+c)+1ll*b*(a+c));

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 3. Đổi nhiệt độ**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int c;
    scanf("%d\n",&c);
    printf("%.2f", (float)c * 9/5 +32);
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 4. Chu vi và diện tích hình tròn**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    double const PI=3.14;
    int r;
    scanf("%d",&r);
    printf("%.4lf %.4lf",2*PI*r,PI*r*r);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 5. Khoảng cách Euclid.**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int x1,y1,x2,y2;
    scanf("%d %d %d %d",&x1,&y1,&x2,&y2);
    printf("%.2lf",sqrt(pow(x2-x1,2)+pow(y2-y1,2)));

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 6. Luyện tập viết câu điều kiện**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n; 
    scanf("%d", &n);
    //1
    if(n % 2 == 0){
        printf("YES");
    }
    else{
        printf ("NO");
    }
    //2
    if((n % 3 == 0) && (n % 5 == 0)){
        printf("\n""YES");
    }
    else{
        printf("\n""NO");
    }
    //3
    if((n % 3 == 0) && (n % 7 != 0)){
        printf("\n""YES");
    }
    else{
        printf("\n""NO");
    }
    //4
    if((n % 3 == 0) || (n % 7 == 0)){
        printf("\n""YES");
    }
    else{
        printf("\n""NO");
    }
    //5
    if((n > 30) && (n < 50)){
        printf("\n""YES");
    }
    else{
        printf("\n""NO");
    }
    //6
    if((n >= 30) && (n % 2 == 0 || n % 3 == 0 || n % 5 == 0)){
        printf("\n""YES");
    }
    else{
        printf("\n""NO");
    }
    //7 10 = 99
    int r = n % 10; // chu so cuoi cung
    if((n >= 10) && (n <= 99) && (r == 2 || r == 3 || r == 5 || r == 7)){
        printf("\n""YES");
    }
    else{
        printf("\n""NO");
    }
    //8
    if((n <= 100) && (n % 23 == 0)){
        printf("\n""YES");
    }
    else{
        printf("\n""NO");
    }
    //9
    if((n < 10) || (n > 20)){
        printf("\n""YES");
    }
    else{
        printf("\n""NO");
    }
    //10
    if(r % 3 == 0){
        printf("\n""YES");
    }
    else{
        printf("\n""NO");
    }
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 7. Số lớn nhất và nhỏ nhất**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b;
    scanf("%d %d",&a,&b);
    printf("%d\n",a / b * b);
    printf("%d\n",(a + b - 1) / b * b);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 8. Tổng, hiệu, tích, thương**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b;
    scanf("%d %d",&a,&b);
    printf("%lld\n",(long long)a+b);
    printf("%lld\n",(long long)a-b);
    printf("%lld\n",(long long)a*b);
    if (b==0)
        printf("INVALID");
    else printf("%.4f\n",(float)a/b);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 9.Kiểm tra năm nhuận**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n;
    scanf("%d",&n);
    if (n%400==0 || (n%4==0 && n%100!=0))
        printf("YES");
    else printf("NO");

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 10. Tam giác hợp lệ**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b,c;
    scanf("%d %d %d",&a,&b,&c);
    if (a>0 && b>0 && c>0 && a+b>c&&a+c>b&&b+c>a)
       printf("YES");
    else  printf("NO");
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
![image](https://user-images.githubusercontent.com/127211886/235078959-86eaf677-f603-42a7-88c2-a7d27ff2a8a9.png)
**Bài 11. Kiểm tra tam giác**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b,c;
    scanf("%d %d %d",&a,&b,&c);
    if (a>0 && b>0 && c>0 && a+b>c&&a+c>b&&b+c>a)
        if(a==b && b==c)
           printf("1\n");
       else if(a==b || b==c || a==c)
                printf("2\n");
            else if((a*a+b*b)==c*c || a*a+c*c==b*b|| c*c+b*b==a*a)
                     printf("3\n");
                 else printf("4\n");
    else  printf("INVALID");

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 12. Số ngày của tháng**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int t,n;
    scanf("%d %d",&t,&n);
    if (t>0 && n>0 && t<=12)
        if (t==1 || t==3||t==5||t==7||t==8||t==10||t==12)
            printf("31\n");
        else if (t==4 || t==6||t==9||t==11)
                 printf("30\n");
             else if (n%400==0||(n%100!=0&& n%4==0))
                      printf("29");
                  else printf("28");
    else printf("INVALID");

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 13. Đổi ngày sang năm, tuần, ngày**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n;
    scanf("%d",&n);
    printf("%d ",n/365);
    printf("%d ",(n%365)/7);
    printf("%d ",(n%365)%7);
        

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 14. Xếp loại học sinh**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    float a,b,c,d;
    scanf("%f %f %f %f",&a,&b,&c,&d);
    float tb=(a+b+2*c+3*d)/7;
    if (tb>=8)
        printf("GIOI");
    else if (tb>=6.5)
             printf("KHA");
         else if (tb>=5)
                 printf ("TRUNG BINH");
              else printf("YEU");

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 15. Mua nước**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long a,b, n;
    scanf("%lld %lld %lld ",&n,&a,&b);
    if (n%2==0)
        if (n*a<n/2*b)
            printf("%lld",n*a);
        else printf("%lld",n*b/2);
     else if (n*a<n/2*b+a)
            printf("%lld",n*a);
          else printf("%lld",n/2*b+a);
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 16. Kí tự kế tiếp**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    char c;
    scanf("%c",&c);
    int n=(int)c;
    if ((char)n=='z'||(char)n=='Z')
        printf("a");
    else if (n<97)
             printf("%c",(char)n+32+1);
         else
             printf ("%c",(char)n+1);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
** Bài 17. Kiểm tra chữ cái**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    char c;
    scanf ("%c",&c);
    int n=(int)c;
    if (n>=48 && n<=57)
        printf("DIGIT");
    else if (n>=65 && n<=90)
             printf("UPPER");
         else if (n>=97 && n<=122)
                 printf("LOWER");
               else printf("SPECIAL");
    
    
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 18. Chuyển đổi in hoa in thường**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    char c;
    scanf("%c",&c);
    int n=(int)c;
    if (n>=65&& n<=90)
        printf("%c",(char)n+32);
    else if (n>=97&& n<=122)
           printf("%c",(char)n-32);
         else printf("%c",(char)n);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 19. Domino**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int m,n;
    scanf("%d %d",&m,&n);
    if (m%2==0)
        printf("%lld",(long long)m/2*n);
    else printf("%lld",(long long)m/2*n+n/2);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 20. Lát đá quảng trường**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,m,a;
    scanf("%d %d %d",&n,&m,&a);
    printf("%lld",(long long)ceil((double)m/a)*1ll*(long long)ceil((double)n/a));

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
![image](https://user-images.githubusercontent.com/127211886/235081228-3a01246f-f483-4fbf-be04-554c4e3ead16.png)
** Bài 21. Frog**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b,k;
    scanf("%d %d %d",&a,&b,&k);
    if (k%2==0)
        printf("%lld",(long long)k/2*a-(long long)k/2*b);
        else printf("%lld",(long long)(k/2+1)*a-(long long)k/2*b);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 22. Đồng xu**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long n,s;
    scanf("%lld %lld ",&n,&s);
    if (s%n==0)
        printf("%lld",s/n);
    else
      printf("%lld",s/n+1);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 23. Doremon leo cầu thang**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,m;
    int x;
    scanf("%d %d",&n,&m);
    if (n%2==0)
        x=n/2;
    else x=n/2+1;
    int c= (x+ m - 1)/m*m;
    if (c<=n)
    printf("%lld",c);
    else printf("%d",-1);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 24. Đường đi ngắn nhất**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int d1,d2,d3;
    scanf("%d %d %d",&d1,&d2,&d3);
    printf("%lld",(long long)fmin(2ll*d1+2ll*d2,fmin(d1+d2+d3,fmin(2ll*d1+2ll*d3,2ll*d2+2ll*d3))));

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 25. Đổi tiền**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n;
    scanf("%d",&n);
    printf("%d",n/100+(n%100)/20+(n%100%20)/10+(n%100%20%10)/5+(n%100%20%10%5));
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 26. Số lớn nhất nhỏ nhất trong 4 số**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long a,b,c,d;
    scanf("%lld %lld %lld %lld ",&a,&b,&c,&d);
    long long max=a;
    if (b>max) max=b;
    if (c>max) max=c;
    if (d>max) max=d;
    long long min=a;
    if (b<min) min=b;
    if (c<min) min=c;
    if (d<min) min=d;
    printf("%lld %lld",max,min);
    

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 27. Làm tròn số**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    double x;
    scanf("%lf",&x);
    //printf("%lld",(long long)round(x));
    long long x1=(long long)x;
    double c=x-x1;
    if (c>=0.5)
        printf("%lld",x1+1);
    else printf("%lld",x1);
    
    

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 28. Cấp số cộng**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,u1,d;
    scanf("%d %d %d",&n,&u1,&d);
    printf("%lld",(long long)1ll*n*u1+1ll*(n*(n-1))/2*d*1ll);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 29. Cấp số nhân**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b,c,d;
    scanf("%d %d %d %d",&a,&b,&c,&d);
    int x;
    if(b%a==0)
       x=b/a;
    else printf("NO");
    if(b==a*x)
        if(c==b*x)
            if(d==c*x)
                printf("YES");
    else printf("NO");
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 30. Tổ hợp chập 2**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n;
    scanf("%d",&n);
    printf("%lld",1ll*n*(n-1)/2);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
![image](https://user-images.githubusercontent.com/127211886/235086127-4ddc112b-7ad3-474d-a209-758f82d0afa1.png)

