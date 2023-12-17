### sheet 1

- A

```c++
#include <iostream>
using namespace std;

int main(){
    string name;
    cout << "enter your name : ";
    cin>>name;
    cout << endl << "Hello, "<<name;
    return 0;
}
```

- B

```c++
#include <iostream>
using namespace std ;

int main(){
    int x;  double n;
    char a ; float i;
    
    cout << " enter integer number, double, char, float : ";
    cin>>x>>n>>a>>i;
    cout << x << endl; 
    cout << n << endl;
    cout << a << endl;
    cout << i << endl;
    return 0;
}
```

- C

```c++
#include <iostream>
using namespace std ;

int main(){
 int x , y;
    cout<< " enter two number ";
    cout << x <<" + "<<y <<" = " << x+y << endl;
    cout << x <<" * "<<y <<" = " << x*y << endl;
    cout << x <<" - "<<y <<" = " << x-y << endl;
    
    return 0;
}
```

- D

```c++
#include <iostream>
using namespace std ;

int main(){
 int a , b ,c ,d ,x;
    cout<<"enter four number : ";
    cin>>a>>b>>c>>d;
    x=(a*b)-(c*d);
    cout<<endl<<"defirant = "<<x;
    
    
    return 0;
}
```

- E

```c++
#include <iostream>
#include<iomanip>

using namespace std ;

int main(){
    
    cout << fixed << setprecision(9);

    double pi=3.141592653 , area ,  r ;
    cout<<"enter redus for calc area : ";
    cin>>r;
    area = pi*(r*r);
    cout<<area;
    
    return 0;
}
```

- F

```c++
#include <iostream>

using namespace std ;

int main(){
    int n , m ; 
    cout<<"enter two number : ";
    cin>>n>>m;
    int digtN= n % 10;
    int digtM= m % 10;
    cout<<digtN <<" + "<<digtM<<" = "<<digtn+digtM <<endl;
    return 0;
}
```

- G

  ```c++
  #include <iostream>
  
  using namespace std ;
  
  int main(){
      int n , sum=0;
   	cout<< "enter number for summation : ";
      cin >>n;
      for(int i=1 ; i<=n ; i++){
          sum += i ;
      }
      cout<< "the summion for number is "<<
      
      return 0;
  }
  ```

  - H

  ```c++
  #include <iostream>
  #include <cmath>
  using namespace std;
  int main() {
      double a, b;
  	cout << "enter number a : ";
      cin >>a;
      cout <<endl<< "enter number b : ";
      cin >>b;
      
  
      double floorResult = floor(a / b);
      double ceilResult = ceil(a / b);
      double roundResult = round(a / b);
  
      cout << "Floor of A/B: " << floorResult << endl;
      cout << "Ceil of A/B: " << ceilResult << endl;
      cout << "Round of A/B: " << roundResult << endl;
  
      return 0;
  }
  ```

  - I

  ```c++
  #include <iostream>
  using namespace std;
  int main() {
      double a, b;
  	cout << "enter number a : ";
      cin >>a;
      cout <<endl<< "enter number b : ";
      cin >>b;
     
      if (a >= b){
          cout << "Yes";
      }
      else 
          cout << "No";
      return 0;
  }
  ```

  

- J

```c++
#include <iostream>
using namespace std;
int main() {
     int a, b;
	cout << "enter number a : ";
    cin >>a;
    cout <<endl<< "enter number b : ";
    cin >>b;
    if (a % b ==0 || b % a ==0){
	cout << " Multiples " << endl ;
    }
    else 
        	cout << "No Multiples " << endl ;
    
    return 0;
}
```

- K

```c++
#include <iostream>
using namespace std;
int main() {
     int a, b,c , max , min;
	cout << "enter number three number : ";
    cin >>a>>b>>c;
   if(a > b and a > c){
        max = a;
       if(b > c ){
           min = c;
       }
       else 
           min = b;
   }
    else if(b > c and b > a){
        max = b;
       if(a > c ){
           min = c;
       }
       else 
           min = a;
   }
    else {
        max =c ;
        if (a > b)
            min = b; 
        else 
            min = a; 
        
    }
    cout << "the max number is " << max << endl;
    cout << "the min number is " << min;
     
    
    return 0;
}
```

- L

```c++

#include <iostream>

// #include <cstring>
using namespace std;
int main() {
 	 string firstnaame1  ;
 	 string firstnaame2  ;
 	 string  scuandname1 ;
 	 string  scuandname2 ;
 	 cout<<"enter your name bilateral : ";
 	 cin>>firstnaame1>>scuandname1;
 	 cout<<"enter name any bepol bilateral : ";
 	  	 cin>>firstnaame2>>scuandname2;
 	 if (scuandname1 == scuandname2){
 	     cout << "are brather ";
 	 }
    else 
       cout << "are not brather ";
    return 0;
}
```

- M

