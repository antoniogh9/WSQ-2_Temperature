# WSQ-2_Temperature
This Program asks the user for a temperature in Fahrenheit and then converts it to Celsius. After that, the program can tell you if that temperature is enough to boil water under typical conditions (100 degrees Celsius). 
/*
Temperature.cpp
Aug 18, 2017
Dulca
*/
#include <iostream>
using namespace std;
int main()
{
	int Fahrenheit, Celsius ;

	//User input
	cout << "Write your temperature in Farenheit here:" << endl ;
	cin >> Fahrenheit ;

	//Formula
	Celsius = (5*(Fahrenheit-32))/9 ;

	//Output
	cout << "A temperature of " << Fahrenheit << "° Fahrenheit is " << Celsius << "° Celsius." << endl ;
	if(Celsius >= 100)
		cout << "Water does boil at this temperature." << endl ;
	else
		cout << "Water does not boil at this temperature." << endl ;
return 0;
}
