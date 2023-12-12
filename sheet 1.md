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

