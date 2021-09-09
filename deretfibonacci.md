## Baris Bilangan Fibonacci
```c

  using namespace std;


int main(int argc, char** argv) {
	
	int a,b,c,n;
	a=1;
	b=1;
	cout <<"Baris Bilangan Fibonacci \n";
	cout <<"\n Masukkan Banyak Bilangan :";cin>>n;
	cout <<" "<<a<<" "<<b<<" ";
	n=(n-2);
	for (c=1;c<=n;c++)
	if (n<=2){
	a=a+b;
	cout<<a<<" ";
}else{
	b=a+b;
	cout<<b<<" ";
	}
	
}
```
