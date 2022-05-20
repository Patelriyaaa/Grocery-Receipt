include <iostream>
#include <string>
#include <Windows.h>
using namespace std;

void main()
{
	char total_answer;
	string purchased_product[30]; // created arrays
	double amount_of_weight[30];
	double cost_per_item[30];
	int size = 0;
	double total[30];

	for (int i = 0; i < 30; i++) // created a loops
	{
		cout << "Enter the product name you purchased: " << endl;
		cin >> purchased_product[i];
		cout << "Enter weight of product: " << purchased_product[i] << endl;
		cin >> amount_of_weight[i];
		cout << "Enter the cost of product per pound " << purchased_product[i] << endl;
		cin >> cost_per_item[i];
		cout << "Do you have another product? (Y/N)" << endl;
		total[i] = amount_of_weight[i] * cost_per_item[i];
		cin >> total_answer;

		if (total_answer == 'n')
		{
			break;
		}
		size++; // counts the products enters
	}
	double netcost = 0;
	cout << "Item name  weight  cost Per Pound  total Per Item" << endl;


	cout << "                 RECEIPT                      " << endl;
	for (int i = 0; i <= size; i++) // loops for the billing
	{
		cout << "**********************************************" << endl;
		cout << purchased_product[i] << "   " << amount_of_weight[i] << "   " << cost_per_item[i] << "   $" << total[i] <<  endl;
		netcost += total[i];
		cout << "**********************************************" << endl;
		
	}
	cout << "Total Amount of all the purchases is $" << netcost << endl; // prints the total amount of all the purchases.
	cout << "**********************************************" << endl;

	SetConsoleTextAttribute(GetStdHandle(STD_OUTPUT_HANDLE), 8);
	cout << "               " << char(221) << char(179) << char(221) << char(221) << char(186) << char(221) << endl;
	cout << "               " << char(221) << char(179) << char(221) << char(221) << char(186) << char(221) << endl;
	cout << "               " << char(221) << char(179) << char(221) << char(221) << char(186) << char(221) << endl;
	cout << "               " << char(221) << char(179) << char(221) << char(221) << char(186) << char(221) << endl;
	cout << "               " << char(221) << char(179) << char(221) << char(221) << char(186) << char(221) << endl;
	cout << "               " << char(221) << char(179) << char(221) << char(221) << char(186) << char(221) << endl;
	system("pause");
}
