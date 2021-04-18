/*
-----TO ASSIST WITH PROJECT REQUIREMENTS:-----
{a} selections: if...else, if... else if... else if...else, and switch;
{b} loops : "for" loop, "do...while" loop, and "while" loop;
{c} arrays : 1 - d array and 2 - d array;
{d} define a class having at least one constructor, one instance method, and one static method;
{e} call the instance method(s);
{f} call the static method(s);
*/
/*
-----THIS PROGRAM CAN BE RAN ON THE FOLLOWING ONLINE COMPILERS:-----
https://repl.it/languages/cpp
https://www.onlinegdb.com/online_c_compiler#
https://www.jdoodle.com/online-compiler-c++/
*/
/*
COPY AND PASTE THE CODE BELOW INTO A COMPILER AND PRESS RUN/EXECUTE/DEBUG TO BEGIN!
*/

#include <iostream>//always needed
#include <stdlib.h>//defines four variable types,...
//...several macros, and various functions for performing general functions
#include <time.h>//defines four variable types,...
//...two macro and various functions for manipulating date and time
#include <iomanip>
using namespace std; //should always have

class AddSub		//{d} class
{

public:			//{d} instance
	static int problem1()		//{d} static method/Constructor
	{
		cout << " " << endl;
		cout << "Answer the following questions: " << endl;
		cout << " " << endl;

		int right = 0;
		for (int a = 1; a < 11; a++)
		{
			cout << "Q" << a << ": ";
			int answer;

			int arr[2] = { 1,2 };		 //{c} 1d array

			int i = (rand() % 2);
			int r = (rand() % 10);
			int d = (rand() % 10 + 1);

			if (arr[i] == 1)		//{a} if else statements
			{
				switch (0)		//{a} switch
				{
				case 0:
					int p = d + r;
					cout << d << " + " << r << " = ";
					cin >> answer;
					if (answer == p)
					{
						cout << "Correct!" << endl;
						right++;
					}
					else
					{
						cout << "Incorrect! The answer was " << p << endl;
					}
					cout << " " << endl;
				}
			}
			else
			{
				switch (1)		//{a} switch
				{
				case 1:
					int p = d - r;
					cout << d << " - " << r << " = ";
					cin >> answer;
					if (answer == p)
					{
						cout << "Correct!" << endl;
						right++;
					}
					else
					{
						cout << "Incorrect! The answer was " << p << endl;
					}
					cout << " " << endl;
				}
			}

		}
		cout << " ===========================" << endl;
		cout << "| You got " << right << " questions right |" << endl;
		cout << " ===========================" << endl;
		return 0;
	}
private:
};

class MultDiv		 //{d} class
{
public:

	static int problem2()		//{d} static method /constructor
	{
		int a = 1;
		cout << " " << endl;
		cout << "***MAKE SURE TO ROUND TO THE 2ND DECIMAL PLACE***" << endl;
		cout << "***DECIMALS WITHOUT '0.' DO NOT COUNT***" << endl;
		cout << endl;
		cout << "Answer the following questions: " << endl;
	
		cout << " " << endl;

		int right = 0;
		while (a < 11)		 //{b} while loop
		{
			cout << "Q" << a << ": ";
			float answer;

			int arr[3][2] = { 0,1,2,3,4,5 };			//{c} 2d array
			int i = (rand() % 3);
			int b = (rand() % 2);
			int r = (rand() % 10);
			int d = (rand() % 10) + 1;

			cout << fixed << setprecision(0);

			if (arr[i][b] < 2)
			{
				switch (0)			//{a} switch
				{
				case 0:
					float p = (r * d);
					cout << r << " * " << d << " = ";
					cin >> answer;
					if (answer == p)
					{
						cout << "Correct!" << endl;
						right++;
					}
					else
					{
						cout << "Incorrect! The answer was " << p << endl;
					}
					cout << " " << endl;
				}
			}
			else
			{
				switch (1)		//{a} switch
				{
				case 1:
					float j = (float)d;
					cout << fixed << setprecision(0);

					float p = (r / j);
					cout << r << " / " << j << " = ";
					cin >> answer;


					if (answer == p)
					{
						cout << fixed << setprecision(2);
						cout << "Correct!" << endl;
						right++;
					}
					else
					{
						cout << fixed << setprecision(2);
						cout << "Incorrect! The answer was " << p << endl;

					}
					cout << " " << endl;
					break;
				}
			}
			a++;
		}
		cout << " ===========================" << endl;
		cout << "| You got " << right << " questions right |" << endl;
		cout << " ===========================" << endl;
		return 0;
	}
private:
}
;

int main()
{
	int x = 0;
	do	//{b} do/while loop
	{
		int Response;
		cout << "Please pick what kind of 10 question (Q) quiz you want to work on today!" << endl;
		cout << endl;
		cout << "Type '1' for Addition (+) & Subtraction (-)" << endl;
		cout << "Type '2' for Multiplication (*) & Division (/)" << endl;
		cout << "Type number selection here --> ";
		cin >> Response;
		

		AddSub as;		 //{e} called instance
		MultDiv md;

		x++;
		switch (Response)		 //{a} switch
		{
		case 1:
			cout << "-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-" << endl;
			srand(time(NULL));
			as.problem1();		//{f} called static
			x = 4;
			break;

		case 2:
			cout << "-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-" << endl;
			srand(time(NULL));
			md.problem2();	//{f} called static
			x = 4;
			break;

		default:
			cout << "Please try again (The quiz ends in " << 3 - x << " more miss clicks)." << endl;
			cout << " " << endl;
		}
	} while (x < 3);

	return 0;
}
