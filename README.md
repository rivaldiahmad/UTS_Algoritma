# UTS_Algoritma



**Soal Pertama**

**Alur Program**

1. Deklarasi variable A,B,X,Y,sebagai variable input
2. Menbaca input key board cin >> A >> B >> X >> Y >>.
3. Membandingkan Variable X dengan Y jika sama.
4. karna statement **false** tidak akan terjadi ```{X!=Y}```.
5. dan jika statement **True** dengan Syantax```X = X + A```.
6. dan jika statment **False** ``` Y = Y + B```.
7. maka akan muncul ``` X = + A = (hasilnya) ```.

**Code Program**

``c++

#include<iosteam>

using namespace std;

int main(){
    int A,B,X,Y;
    cout << "Masukan Variable X =";cin >>A;
    cout <<" Masukan Variable y =";cin >>B;

    X = A;
    Y = B;
    if (X!=Y){
       if(X < Y)
         (X = X + A);
       else
	 (Y = Y + B);

    }
  
    cout << X;

}

```
*Soal Program**

1. deklarasi varaible input N,X,T, Batas;
sebagai inputnya
2. memasukan nilai N yaitu 2 angka terakhir saya, maka N dalah 12
dan batasnya adalah 152 dari hasil jumlah N + 140,.
3. masukan variable X, dan T, X nya adalah 20 dan kemudian T adalah 12(dari N).
4. dimana T kurang dari sama dengan batas, berarti tidak boleh melebihi batas 
5. kemudian menghitung ```X = X + 10;
```,dan hasinya 30 kemudian menghitung ```
T = T + X;```,
hasilnya adalah 42.
6. kemudia cetak variable T 

**Code Program**

```c++

#include<iostream>
using namespace std;

int main() {

    int n,x,t,batas;

    cout << "masukan nilai n: ";
    cin >> n;

    batas = n + 100;
    x = 20;
    t = n;
    while( t <= batas )
        { t = t + x;
          x = x + 10;
        }
    cout << t;
}
