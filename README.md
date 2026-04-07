#include <iostream>
using namespace std;
int main() {
 string product;
 int quantity;
 float price, total;
 cout << "Enter Product Name: ";
 cin >> product;
 cout << "Enter Price: ";
 cin >> price;
 cout << "Enter Quantity: ";
 cin >> quantity;
 total = price * quantity;
 cout << "\n--- Shopping Cart Bill ---\n";
 cout << "Product: " << product << endl;
 cout << "Price: " << price << endl;
 cout << "Quantity: " << quantity << endl;
 cout << "Total Amount: " << total << endl;
 return o;
}
