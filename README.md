# Lecture-10
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 7; i >0; i--)
	{ //execute the outer loop 7 times 
		for (int j = i; j > 0; j--)
		{//execute the inner loop 7 x 7 times
			cout << "*"; //print 1 stars
		}
		cout << endl; //print to a new console line 
	}
	for (int i = 0; i <= 5; i++)
		{ //execute the outer loop 7 times 
			for (int j = 0; j < i; j++)
			{//execute the inner loop 7 x 7 times
				cout << "*"; //print 1 stars
			}
			cout << endl; //print to a new console line 
		}
	for (int i = 0; i <= 5; i++)
	{ //execute the outer loop 7 times 
		for (int j = 0; j < i; j++)
		{//execute the inner loop 7 x 7 times
			cout << "*"; //print 1 stars
		}
		cout << endl; //print to a new console line 
	}
	for (int i = 4; i > 0; i--)
	{ //execute the outer loop 7 times 
		for (int j = i; j > 0; j--)
		{//execute the inner loop 7 x 7 times
			cout << "*"; //print 1 stars
		}
		cout << endl; //print to a new console line 
	}
}
