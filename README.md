#include <iostream>
using namespace std;
int main()
{
	cout << "What is the Capital of Farance?" << endl
		<< "A.Africa" << endl
		<< "B.China" << endl
		<< "C.Paris" << endl
		<< "D.Germany" << endl;
	char input;
	cin >> input;

	switch (input) {
	case'A':
	case'a':
	case'B':
	case'b':
	case'D':
	case'd':

	{
		cout << "Opps Incorrect Answer!" << endl;
		break;
	}

	case'C':
	case'c':
	{
		cout << "Congratulation your Aanswer is correct!" << endl;
		break;

	}
	default:
		cout << "Invalid Input" << endl;
	}
}
