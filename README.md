# 123
程式碼
#include <iostream>
using namespace std;
int main()
{
	int a, b, c;
	while (cin >> a >> b)
	{
		while (b != 0)
		{
			c = b;
			b = a % b;
			a = c;
		}
		cout << a<<endl;

	}
	return 0;
	
}
