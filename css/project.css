//Dylan Ramsey
//Professor Winiecki
//Project 1 

#include <iostream>
#include <string>
#include <iomanip>
#include <fstream>
using namespace std;

int employee_number;
string first_name;
string last_name;
string office_location;
string job_title;
char overtime;
double pay_rate;
double hours_worked;
int choice1;
int choice2;

int main()
{

	//ofstream outputFile;
	//outputFile.open("cop2224_proj1.txt");
	cout << "Welcome to the employee payroll program, please select an option below. \n";
	cout << "1. Enter employee payrate information \n";
	cout << "2. Quit program \n";
	cout << "Enter your choice \n";
	cin >> choice1;
	

	while ((choice1 < 1) || (choice1 > 2))
	{
	cout << "Invaild input, only enter 1 or 2 into the keyboard \n";
	cin >> choice1;
    }

	if (choice1 != 2)
	{
		cout << "You have selected to enter the program \n";

		cout << "----------------------------------------- \n";
		cout << "Enter your 6 digit employee number \n";
		cin >> employee_number;
		while ((employee_number < 59000) || (employee_number > 1000000))
		{
			cout << "Only enter a number consisting of 6 digits \n ";
			cin >> employee_number;
		}

		cout << "Enter your first name \n";
		cin >> first_name;
		cout << "Enter your last name \n";
		cin >> last_name;

		cout << "Enter your office location \n";
		cout << "-------------------------------\n";
		cout << "1. Tampa \n";
		cout << "2. Sarasota \n";
		cout << "3. Orlando \n";
		cout << "4. Miami \n";
		cin >> choice2;
		cout << endl;
		if (choice2 == 1)
		{
			cout << "Tampa \n";
		}
		else if (choice2 == 2)
		{
			cout << "Sarasota \n";
		}
		else if (choice2 == 3)
		{
			cout << "Orlando \n";
		}
		else if (choice2 == 4)
		{
			cout << "Miami \n";
		}
	
		cout << "Enter your payrate \n";
		cin >> pay_rate;

		cout << "Enter the amount of hours worked \n";
		cin >> hours_worked;

		cout << "Enter your job title: \n";
		cin.ignore();
		getline(cin, job_title);
		
		cout << "Is the employee eligile for overtime? (Y/N) \n";
		cin >> overtime;
		if (overtime == 'y');
		else if (overtime == 'n');
		cout << overtime;

		//outputFile << " << employee_number; << ";

		//outputFile.close();
		system("PAUSE");
		return 0;
	}
}