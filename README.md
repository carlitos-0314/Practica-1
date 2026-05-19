#include <iostream>
using namespace std;
int main () {
int num1, num2, num3;
cout <<INGRESA EL PRIMER NUMERO;
cin >> num1;
cout <<INGRESA EL SEGUNDO NUMERO;
cin >> num2;
cout <<INGRESA EL TERCER NUMERO;
cin >> num3;
if (num1>=num2&&num1>=num3){
cout<< EL NUMERO MAYOR ES: <<num 1;
}
if (num2>=num1&&num2>=num3){
cout<< EL NUMERO MAYOR ES: <<num 2;
}
if (num3>=num1&&num3>=num2){
cout<<EL NUMERO MAYOR ES: << num 3;
}
return 0;
}
