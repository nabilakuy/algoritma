```c
#include <iostream>
using namespace std;

int main() 
{
	int pil,pokok,istri,anak,janak,lembur,jlembur,gaji,pajak,bpjs,total;
	
	cout<<"================================"<<endl;
	cout<<"Golongan          = ";
	cin>>pil;
	if (pil==1)
	{
	pokok=1700000;
	cout<<"Gaji Pokok        = Rp ";
	cout<<pokok<<endl;
	istri=300000;
	cout<<"Tunjangan Istri   = Rp ";
	cout<<istri<<endl;	
	cout<<"Jumlah Anak       = ";
	cin>>janak;
	anak=janak*100000;
	cout<<"Tunjangan Anak    = Rp ";
	cout<<anak<<endl;
	cout<<"Jumlah Jam Lembur = ";
	cin>>jlembur;
	lembur=jlembur*50000;
	cout<<"Lembur            = Rp ";
	cout<<lembur<<endl;
	}
	else if (pil==2)
	{
	pokok=2000000;
	cout<<"Gaji Pokok        = Rp ";
	cout<<pokok<<endl;
	istri=400000;
	cout<<"Tunjangan Istri   = Rp ";
	cout<<istri<<endl;	
	cout<<"Jumlah Anak       = ";
	cin>>janak;
	anak=janak*150000;
	cout<<"Tunjangan Anak    = Rp ";
	cout<<anak<<endl;
	cout<<"Jumlah Jam Lembur = ";
	cin>>jlembur;
	lembur=jlembur*75000;
	cout<<"Lembur            = Rp ";
	cout<<lembur<<endl;
	}
	else if (pil==3)
	{
	pokok=2500000;
	cout<<"Gaji Pokok        = Rp ";
	cout<<pokok<<endl;
	istri=750000;
	cout<<"Tunjangan Istri   = Rp ";
	cout<<istri<<endl;	
	cout<<"Jumlah Anak       = ";
	cin>>janak;
	anak=janak*200000;
	cout<<"Tunjangan Anak    = Rp ";
	cout<<anak<<endl;
	cout<<"Jumlah Jam Lembur = ";
	cin>>jlembur;
	lembur=jlembur*100000;
	cout<<"Lembur            = Rp ";
	cout<<lembur<<endl;
	}
	cout<<"--------------------------------"<<endl;
	gaji=pokok+istri+anak+lembur;

	cout<<"Gaji Kotor        = Rp ";
	cout<<gaji<<endl;
	cout<<"--------------------------------"<<endl;
	cout<<"Potongan"<<endl;
	bpjs=100000;
	cout<<"a. BPJS           = Rp ";
	cout<<bpjs<<endl;
	pajak=gaji*0.05;
	cout<<"b. Pajak          = Rp ";
	cout<<pajak<<endl;
  
	cout<<"================================"<<endl;
	total=gaji-bpjs-pajak;
	cout<<"Total Gaji        = Rp ";
	cout<<total<<endl;
	cout<<"================================";
	
	return 0;
}
```
