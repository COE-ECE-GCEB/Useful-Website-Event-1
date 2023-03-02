# Club of Elite / Hackerrank Contest / Solution-Explanation
**Requirements:** Any one programming language (here for shake of simplicity `c/c++` is considered through out the solution)

Introduction to Hackerrank: [Youtube video](https://youtu.be/f6D61fNreKo?list=PLhP5RsB7fhE2394h0wg-H8-PGttb1Ao7n&t=42)

Hackerrank Problem Link: [Link](https://www.hackerrank.com/domains/algorithms) (in this link the first 10 problems are taken for the contest)

## Problem Title
- [Solve Me First](#solve-me-first)
- [Simple Array Sum](#simple-array-sum)
- [Compare the Triplets](#compare-the-triplets)
- [A Very Big Sum](#a-very-big-sum)
- [Diagonal Difference](#diaonal-difference)
- [Plus Minus](#plus-minus)
- [Stair Case](#staircase)
- [Min Max](#min-max)
- [Birthday Cake Candles](#birthday-cake-candles)
- [Time Conversion](#time-conversion)

**General Answer format**

They given the blocks of code(some times the given code may not be editable(they are shown with the blue line in the left side of the code)). They ask you to complete the function(here solveMeFirst function) to get the desired output.
![image](https://user-images.githubusercontent.com/57592824/222167973-84a6163a-946d-4e89-8d6e-6c33ddd3582c.png)

### Solve Me First
**Requirement:** return value in function, operators, variable, datatypes
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/222163930-283a7805-3aee-4bda-8bff-b96dc6e78931.png)

</details>

<details><summary>Explanation</summary>

![image](https://user-images.githubusercontent.com/57592824/222171012-9425199c-6489-4ab5-aee5-dccbeff73584.png)
</details>

youtube explanation: [Link](https://youtu.be/f6D61fNreKo?list=PLhP5RsB7fhE2394h0wg-H8-PGttb1Ao7n&t=141)

### Simple array sum
**Requirement:** array, function, datatypes, variable, operators
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/222336006-9c4e0d61-8ecf-4b3f-9464-7b4120619d79.png)

</details>

<details><summary>Explanation</summary>

![image](https://user-images.githubusercontent.com/57592824/222335885-020d78f5-a6fe-4804-8f63-2ac64c3d86cc.png)

</details>

youtube explanation: [Link](https://www.youtube.com/watch?v=BvLVaDfkGAw&list=PLhP5RsB7fhE2394h0wg-H8-PGttb1Ao7n&index=2)

### Compare the triplets
**Requirement:** array, function, datatypes, variable, operators, if-else
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/222336759-166dbb14-8be0-4cd1-bdaa-25f2a9f3989f.png)
![image](https://user-images.githubusercontent.com/57592824/222336793-963de0d0-87a1-4d22-b52c-c5117bb6f5b7.png)


</details>

<details><summary>Code:(C++)</summary>

```c++
#include <iostream>

using namespace std;

int main()
{
    
    int a[3],b[3];
    int a_s=0, b_s=0;
    for(int i=0; i<=2; i++)
        cin>>a[i];
    for(int i=0; i<=2; i++)
        cin>>b[i];
    for(int i=0; i<=2; i++)
    {
        if (a[i]<b[i])
            b_s++;
        if (a[i]>b[i])
            a_s++;
    }
    cout<<a_s<<" "<<b_s;
    return 0;
    
}
```

</details>

youtube explanation: [Link](https://www.youtube.com/watch?v=jZZQjGNxOb0&list=PLhP5RsB7fhE2394h0wg-H8-PGttb1Ao7n&index=3)

### A Very Big Sum
requirement: array, function, datatypes, variable, operators, long datatype
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/222191687-7c35fdc5-1d3b-46f2-9c89-ab6b83a3e0aa.png)

</details>

<details><summary>Explanation</summary>

![image](https://user-images.githubusercontent.com/57592824/222335526-a3f15ae7-3379-49ac-a35c-4ff933373a34.png)

</details>

youtube explanation: [Link](https://youtu.be/APFCMe96KSw)

### Diaonal Difference
**Requirement:** array, function, datatypes, variable, operators, 2d array, if else, for loop
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/222337648-7816f8a9-119f-4746-a343-65d3d877aa96.png)
![image](https://user-images.githubusercontent.com/57592824/222337688-a1514ccf-be47-46a3-b8d5-8dc1428bc02f.png)



</details>

<details><summary>Code: (C++)</summary>

```c++
#include<iostream>
#include<stdlib.h>
using namespace std;
int main(){
    int n, arr[100][100];
    int l_d_s=0,r_d_s=0;
    cin>>n;
    for(int i=0; i<n; i++){
        for(int j=0;j<n;j++){
            cin>>arr[i][j];
            if(i==j){
                l_d_s=l_d_s+arr[i][j];
            }
            if(j==n-1-i){
                r_d_s=r_d_s+arr[i][j];
            }
        }
    }
    cout<<abs(l_d_s-r_d_s);
}
```

![image](https://user-images.githubusercontent.com/57592824/222335885-020d78f5-a6fe-4804-8f63-2ac64c3d86cc.png)

</details>

youtube explanation: [Link](https://youtu.be/APFCMe96KSw?t=310)

### Plus-Minus
**Requirement:** array, function, datatypes, variable, operators, long datatype, setprecision in c++, vector in c++, type casting, if else, for loop
<details><summary>Question</summary>


![image](https://user-images.githubusercontent.com/57592824/222338308-fb4ddc96-27c5-4c00-8f44-bb69694bc7ae.png)
![image](https://user-images.githubusercontent.com/57592824/222338302-e7a0c094-ee7c-4eba-ac4f-ae8c1a549317.png)




</details>

<details><summary>Code: (C++)</summary>

```c++
// only the function is given here
void plusMinus(vector<int>  v1) {
int P=0,N=0,Z=0;
for (int i=0; i<v1.size(); i++)
{
    if(v1.at(i)>0)
        P++;
    else if(v1.at(i)<0)
        N++;
    else
        Z++;
}
    cout<<setprecision(6)<<float(P)/v1.size()<<endl;
    cout<<setprecision(6)<<float(N)/v1.size()<<endl;
    cout<<setprecision(6)<<float(Z)/v1.size()<<endl;
}
```


</details>

youtube explanation: [Link](https://www.youtube.com/watch?v=EMy7gpJ6us4)

### Staircase
**Requirement:** array, function, datatypes, variable, operators, for loop, nested for loop
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/222339427-798e229d-15ba-4eb6-a9f6-9150e582a7cd.png)


</details>

<details><summary>Code: (C++)</summary>

```c++
//only the function is given
void staircase(int n) {
    for(int i=0; i<n; i++)
    {
        for(int j=0; j<n-i-1; j++)
        {
            cout<<" ";
        }
        for(int k=0; k<i+1; k++)
        {
            cout<<"#";
        }
        cout<<"\n";
    }
}

```


</details>

youtube explanation: [Link](https://www.youtube.com/watch?v=YqRkgbGq9CU&list=PLhP5RsB7fhE2394h0wg-H8-PGttb1Ao7n&index=5)

### Min-Max
**Requirement:** array, function, datatypes, variable, operators, long datatype, sorting, long, for, vector in c++
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/222339768-5faaf4a2-fbc2-43ca-84f3-b3606cbe3c54.png)


</details>

<details><summary>Code: (C++)</summary>

```c++
//only the function is given
void miniMaxSum(vector<int> arr) {
    sort(arr.begin(),arr.end());
    long long int min_sum=0, max_max=0;
    for(int i=0; i< 5; i++)
    {
        if(i<4)
           min_sum=min_sum+arr[i];
        if(i>=1)
            max_max=max_max+arr[i];
        
    }
    cout<<min_sum<<" "<<max_max;    
}

```


</details>

youtube explanation: [Link](https://www.youtube.com/watch?v=U6LDKYwJKTA&list=PLhP5RsB7fhE2394h0wg-H8-PGttb1Ao7n&index=6)

### Birthday cake candles
**Requirement:** array, function, datatypes, variable, operators, long datatype, for, if, macros(INT_MIN, which is the most minimum value intergen can have)
<details><summary>Question</summary>
![image](https://user-images.githubusercontent.com/57592824/222340643-980609fe-a995-4cda-9358-199c4967a79e.png)


</details>

<details><summary>Code: (C++)</summary>

```c++
//only the function is given
int birthdayCakeCandles(vector<int> candles) {
    int max=INT_MIN;
    int count=0;
    for(int i=0; i<candles.size(); i++)
    {
        if(candles[i]>max)
        {
            max=candles[i];
            count=0;
        }
        if(max==candles[i])
        {
            count++;
        }
    }
    return count;
}

```


</details>

youtube explanation: [Link](https://www.youtube.com/watch?v=6Ig6rhNVMLU&list=PLhP5RsB7fhE2394h0wg-H8-PGttb1Ao7n&index=7)

### Time Conversion
**Requirement:** array, function, datatypes, variable, operators, long datatype, Strings, String function, long, for
<details><summary>Question</summary>

![image](https://user-images.githubusercontent.com/57592824/222341393-d220b4e9-3432-4f6a-b00d-d04b4872a616.png)


</details>

<details><summary>Code: (C++)</summary>

```c++
//only the function is given

string timeConversion(string s) {
int s1=int(s[0])-48;
    int s2=int(s[1])-48;
    int hh=(s1*10)+s2;
    char noon = s[8];
    s=s.erase(8,2);
    if( noon == 'P'){
        if (hh!=12)
            hh=hh+12;
    }
    if(hh==12 && noon=='A'){
        hh=00;
    }
    s[0]=(hh/10)+48;
    s[1]=(hh%10)+48;
    for(int i=0; i<8; i++)
    {
        cout<<s[i];
    }
    return s;
}


```


</details>

youtube explanation: [Link](https://www.youtube.com/watch?v=sYZ7j5OSwxY)