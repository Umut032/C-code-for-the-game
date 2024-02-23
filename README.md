#include <iostream>

using namespace std;
int main() {

	int sayi1, sayi2, sayisecin, sonuc;
	 sonuc = -1;
	cout << "sayi biri giriniz:" << endl;
	cin >> sayi1;

	cout << "sayi ikiyi giriniz:" << endl;
	cin >> sayi2;

	cout << "lutfen sayi seciniz 1.+ 2.- 3.* 4./"<<endl;
	cin >> sayisecin;

	if (sayisecin == 1)
	{
		sonuc = sayi1 + sayi2;
	}

	else if (sayisecin == 2)
	{
		sonuc = sayi1 - sayi2;
	}

	else if (sayisecin == 3)
	{
		sonuc = sayi1 * sayi2;
	}

	else if (sayisecin == 4)
	{
		sonuc = sayi1 / sayi2;
	}

	else
	{
		cout << "lutfen 1 ile 4 arasi sayi giriniz" ;
	}

	if (sonuc != -1)
		cout << "sonucunuz" << sonuc; 

	return 0;
}


