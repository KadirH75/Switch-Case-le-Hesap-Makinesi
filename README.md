#include <iostream>
using namespace std;
int main()
{
char secim;
int sayi1, sayi2;
cout << "yapmak istediğiniz işlemi ve sayıları giriniz :\n";
cin >> sayi1 >> secim >> sayi2;
	switch (secim) {
	case '-':
		cout << "sonuç = " << sayi1 - sayi2;
		break;
	case '+':
		cout << "sonuç :" << sayi1 + sayi2;
		break;
	case '/':
		cout << "sonuc :" << sayi1 / sayi2;
		break;
	case '*':
		cout << "sonuc : " << sayi1 * sayi2;
		break;

	}
  return 0;
}
