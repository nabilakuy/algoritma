## Konversi Suhu
```c
using namespace std;
int main ()
{
  cout << " KONVERSI SUHU DARI FAHRENHEIT KE CELCIUS DAN REAMUR : \n";
	float F,C,R;
	cout <<" Masukkan Nilai Suhu :";
	cin >> F;
	C=(F-32)*5/9;
	R=(F-32)*4/9;
	cout<<"\n";
	cout<<"Hasil Konversi Suhu : \n"; 
	cout <<" Fahrenheit --> Celcius : ";
	cout <<C<<" " <<"\n";
	cout << " Fahrenheit --> Reamur : ";
	cout <<R<<" ";
}
```
