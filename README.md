# wsq05.cpp

/*
#WSQ05
Main: XXXXXXX
By: Jorge Cervantes
#TC1017
Referencia: XXXXXXX
---------------------------------------------------------------------
*/

#include <iostream>
using namespace std;

int main(){

int celcius, fahrenheit;

cout << "Fahrenheit to celcius\n";
cout << "Please ingresa los fahrenheit a convertir: ";
cin >> fahrenheit;
celcius = (fahrenheit - 32) / 1.8;
cout << "Celcius= " << celcius << "\n";
if (celcius >= 100){
	cout << "Water se evapora a esa temperatura";
}
else{
	cout << "Water no se evapora a esa temperatura";
}

return 0;
}
