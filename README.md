//1. Cho biết năm sinh của một người và tính tuổi của người đó.
#include <iostream>

int main()
{
	int a;
	cout << "nhap nam sinh: ";
	cin >> a;
	cout << "tuoi cua ban la: " << 2022 - a;
	
	return 0;
}

//2. Cho 2 số a, b. Tính tổng, hiệu, tính và thương của hai số đó.
	
#include <iostream>

using namespace std;

int main() {

	double a, b;
	cout << "nhap 2 so lan luot la: " ;
	cin >> a >> b;
	cout << "tong 2 so la: " << a + b<<endl;
	cout << "hieu 2 so la: " << a - b<<endl;
	cout << "tich 2 so la: " << a * b << '\n';
	cout << "thuong 2 so la: " << a / b<<'\n';

	return 0;
}
	
3.//Cho biết bán kính của đường tròn. Tính chu vi và diện tích
//của hình tròn đó.
#include <iostream>

using namespace std;


int main() {
	const float Pi = 3.14;
	float r,d,e;
	cout << "Nhap ban Kinh R: " << endl;
	cin >> r;
	d = 2 * r;
	e = r * r;
	cout << "Chu vi hinh tron la: " << d * Pi << endl;
	cout << "Dien tich hinh tron la: " << e * Pi;

	return 0;
}
