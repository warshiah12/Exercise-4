# Exercise-4
# C++Basics
#include<iostream>
using namespace std;
int main()
{
	int sides;  //declaring data type to variable sides
	cout << "Enter the number of sides : " << endl;   //asking for user input
	cin >> sides;   //the input value by the user will be stored in variable sides
	if (sides == 3) //using else if statement
	{
		cout << "TRIANGLE " << endl;
	}
	else if (sides == 4)
	{
		cout << "SQUARE " << endl;
	}
	else if (sides == 5)
	{
		cout << "PENTAGON " << endl;
	}
	else if (sides == 6)
	{
		cout << "HEXAGON " << endl;
	}
	else if (sides == 7)
	{
		cout << "HEPTAGON " << endl;
	}
	else if (sides == 8)
	{
		cout << "OCTAGON " << endl;
	}
	else if (sides == 9)
	{
		cout << "NONAGON " << endl;
	}
	else if (sides == 10)
	{
		cout << "DECAGON " << endl;
	}
	else
	{
		cout << "Invalid data entered! " << endl;
	}
	return 0;
}
