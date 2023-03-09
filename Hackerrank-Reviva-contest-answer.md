# Hackerrank Contest answer

## Try Here: [https://www.hackerrank.com/reviva-23-hackerrank-contest](https://www.hackerrank.com/reviva-23-hackerrank-contest)

## Reviva'23- Add the Alternative Digits
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/223967963-fb41e276-56fb-42fe-a0d0-0d9ac7c89d9e.png)

</details>

<details><summary>Answer</summary>

```c++
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */   
    long int n;
    int c=0,d=0;
    cin>>n;
    int size=0;
    while(n>0)
    {
        int a=n%10;
        if(size%2==0)
             c=c+a;
        else
            d=d+a;
        n=n/10;
        size++;
    }
    if(size%2==0){
        cout<<c<<" "<<d;
    }
    else
        cout<<d<<" "<<c;
    return 0;
}
```

</details>

## Reviva'23 - Largest nth Number
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/223969199-bd1339c8-980d-4abf-991a-7eb921848774.png)


</details>

<details><summary>Answer</summary>

```c++
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */   
    int n, k, number[100];
    cin>>k;
    for(int i=0; i<k; i++)
    {
        cin>>number[i];
    }
    cin>>n;
    for(int i=0; i<n; i++)
    {
        for(int j=0; j<k-1-i; j++)
        {
            if(number[j]>number[j+1])
            {
                int a= number[j];
                number[j]=number[j+1];
                number[j+1]=a;
            }
        }
    }
    
    cout<<number[k-n]<<endl;
    return 0;
}
```

</details>


## Reviva'23- Remove [...]
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/223969941-ea275f98-7160-4c38-8054-472b51bbe078.png)

</details>

<details><summary>Answer</summary>

```c++
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main()
{
    char a[100000];
    scanf("%[^\n]",a);
    int f=0;
    for(int i=0; i<strlen(a); i++)
    {
        if(a[i]=='[')
            f=1;
        if(f==0)
            printf("%c",a[i]);
        if(a[i]==']')
            f=0;
    }
}
```

</details>