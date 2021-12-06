# Lecture-13_Exercises

//Input_Output Array
#include <iostream>
#include <string>
#include <algorithm>

using namespace std;

int main()
{
	cout << "Enter 5 numbers" << endl;
	int x[5];
	for (int y = 0; y < 5; y++) {
		cin >> x[y];
	}
	for (auto userInput : x) {
		cout << userInput << ", ";
	}
}
---------------------------------------------------
  
//Array Art
int main()
{
	string pattern[5][5] = {
		{"-", "-", "-", "-", "-"},
		{"-", "0", "-", "0", "-"},
		{"-", "@", "@", "@", "-"},
		{"-", "^", "^", "^", "-"},
		{"-", "v", "v", "v", "-"}
	};
	for (int x = 0; x < 5; x++) {
		for (int y = 0; y < 5; y++) {
			cout << pattern[x][y] << " ";
		}
		cout << endl;
	}
}
