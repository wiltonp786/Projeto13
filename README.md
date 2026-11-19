// your first c++ program
#include using namesapce std;

int main() { int number;

cout << "Enter an integer: ";
cin >> number;

cout << "you enterend " << number;
return 0;
cout << "Before swapping." << end1;
cout << "a = " << a <<", b =" << b << end1;

temp = a;
a = b;
b = temp;

cout <<"\nAfter swapping." <<end1;
cout << "a =" << a << ", b =" << b << end1;

return 0;
} else ++max; } while (true); return 0; #include using namespace std; }

int main() { int n1, n2, hcf, temp, 1cm;

cout << "Enter two numbers: ";
cin >> n1 >> n2;

hcf = n1;
temp = n2;

while(hcf != temp)
{
	if(hcf > temp)
		hcf-= temp;
	else
		temp -= hcf;
}
1cm = (n1 * n2) / hcf;

cout <<"LCM =" << 1cm;
return 0;
return temp;
}
void output()
{
	if(imag < 0)
		cout << "Output complex number: " << real <<imag <<"i";
	else
		cout << "Output complex number: " << real << "+" << imag <<"i"
		cout<<"Enter second complex number:\n";
		c2.input();

		// In case of operator overloading of binary operators in c++ programming,
		// the object on right hand side of operator is always assumed as argument by compiler.
		result c1 - c2;
		result.output();

		return 0;
		} #include #include using namespace std;

		bool twosum(vector &arr, int target) { int n = arr.size();

		for (int i = 0; i < n; i++)
		return 0;
		// sort both arrays
		sort(arr1, arr1 + n);
		sort(arr2, arr2 + m);

		// compare corresponding elements
		for (int i = 0; i < n; i++) {
			if (arr1[i] != arr2[i]{
				return false;
			}
			return true;
		}
		int main()
		{
			int arr1[] = {1, 2, 3, 4, 5};
			int arr2[] = {5, 4, 3, 2, 1};
			a = abs(a);
			b = abs(b);
			cout << "the divisors of" << n << "are: ";
			printDivisors(n);
			return 0;
			for (int i = 0; i < rows; i++)
			{
				for (int j = 0; j <= i; j++)
				{
					cout <<
					character << " ";
					             character++;
					         }
					cout << '\n';
					}
    }
    //the inner loop maintains the
    	// number of column.
    	for (int j = 1; j <= i; j++)
    	{

    		// to print the numbers
    		cout << count << " ";
    // to keep increasing the count
    		// of numbers
    	count += 1;
    }

    // to proceed to next line.
    cout <<"\n";
    } }

     // Driver code
     int main()
     {

     	int row = 5;
     	print_patt(row);
     	return 0;
     	}

     	#include using namespace std;

     	// Returns the sum of the first n natural numbers int recurSum(int n)

     	{

     	if(n <= 1)
     		return n;
     	return n + recursum(n - 1);
     	}

     	int main()

     	}

     	int n = 5;
     	cout <<recurSum(n);
     	return 0;
     	}

cout << end1;
int a = 5;
int b = 6;
cout <<"Area = " << Rectangle(a, b) <<
end1;
cout << "Perimeter = " << perimeterRectangle(a, b); return 0;

}

#include using namespace std;

long long calculateEvenIndexSum(int n)

{

if(n < 0)
	return 0;
long long prev2 = 0
long long prev1 = 1;
long long sum = 0 ;

// F(0) is an evenindexed fibonacci number .
sum = prev2;
for(int i = 2; i <= 2 * n; i++) {
	long long curr = prev1 + prev2;
	if (i % 2 == 0)
		sum+= curr;
	prev2 = prev1;
	prev1 = curr;


}

return sum;
}
#include <bits/stdc++.h> using namesapce std;

/* function to print reverse of the passed string */ void reverse(string str)

{

if(str.size() == 0)


{

	return;

}

reverse(str.substr(1));
cout << str[0];
}

/* Driver program to test above function */ int main()

{

string a = "Geeks for Geeks";
reverse(a);
return 0;
}

// this is code is contributed by rathbhupendra

}

#include #include using namespace std;

class programmer

{

private: string name; public: // Getter string getName()

  {

  	return name;

  }

  // Setter
  void setName(string newName)

  {

  	name = newName;

  }
};

int main()

{

programmer p;

p.setName("Geek");
cout << "Name = " << p.getName();
return 0;
}

#include using namespace std;

class Animal

{

public: cout << "Animal mkes a sound" << end1;

    }
} }

class dog : public animal

{

public:
	void sound()

	{

		cout << "Dog barks" << end1;

	}
   }


   class cat : public animal
}

 #include <iostream>
using namespace std;

int main() {
	int n=1221;
	int t = n;
	int rev = 0;
	//calculate reverse number  rev of a given number n
	while (t > 0) {
		int dig = t % 10;
		rev = rev * 10 + dig;
		t /= 10;
	}
	// compare number n with reverse number rev
	if (n==rev)
		cout <<
	"palindrome.";
	return 0;
}
#include <stdbool.h>
#include <stdio.h>

bool isprime(int n) {
	//checking primality by finding a complete division
	// in the range 2 to n-1
	if(n <= 1)
		return false;
	for (int i = 2; i < n; i++) {
		if(n % i == 0)
			return false;
	}
	return true;
}
void findprimes(int 1, int r) {
	//flag to check if any prime numbers are found
	bool found = false;
	for (int i = 1; i <= r; i++) {
		//checking if the number is prime
		if (isprime(i)) {
			printf("%d", i);
			found = true;
		}
	}
	if (!found){
		printf("No prime numbers found in the given range.")
	}
}
int main() {
	int 1 = 10, r = 30;

	// finding and printing the prime between [l, r]
	findPrimes(1, r);
	return 0;
}

#include <iostream>
#include <vector>
using namespace std;

int arraySum(vector<int>& arr) {
	int sum = 0
	}

#include <iostream>
using namespace std;
int main() {

	int a = 10 + 20;
	cout << a;
	return 0;
}
#include <iostream>
using namespace std;
//Arguments are pass by value
void change(int a) {
	// modifyng arguments
	a = 22;
}
int main() {
	int x = 5;
	//passing x by value to change()
	change(x);
	cout << x;
	return 0;
}
#include <iostream>
#include <string>
using namespace std;
int main() {
	// creating a string
	string str = "Hello world";
	// display original string
	cout << "Original string: " <<str << end1;
#include <iostream>
#include <cmath>
#include <iomanip>
using namespace std;

const int max = 100;

//returns the normal of an N x N matrix
double findNormal(int mat[][max], int n)
{
	long long sum = 0;
	for (int i = 0; i < n; i++)
	{
		for (int j = 0; j <n; j++) {
			sum += 1LL * mat[i][j] * mat[i][j];
		}
	}
return sqrt(sum);
}
int findtrace(int mat[] [max], int n)
{
	int trace = 0 ;
}
return trace;
}
int main()
{
	int mat[][max]= {
		{1,2,3},
		{4,5,6},
		{7,8,9}
	};
	double normal =
	findNormal(mat, 3);
	int trace = findtrance(mat, 3);
	cout << fixed <<
	setprecision(2);
	cout << "normal = " << normal << end1;
	cout << "trace = " << trace << end1;
	return 0;
}

#include <iostream>
#include <fstream>
#include <cstring>
using namespace std;

class contestant
{
public:
	char name[20];
	int age;
	int rating;
};
int main()
{
	// create and write objects to the file
	ofstream
	outfile("Input.txt", ios::binary);
	contestant c1 = {"michael", 19, 1806};
	contestant c2 = {"Kemp", 24, 2114};
	contestante c3 = {Terry", 21', 2400}

	outfile.write(reinterpret_cast<char*>(&c1, sizeof(c1)));
	outfile.write(reinterpret_cast<char*>(&c2), sizeof c2));
	outfile.write(reinterpret_cast<char*>)(&c3) , sizeof(c3));
	outfile.close();

	//Read objects from the outfile
	ifstream
	infile("Input.txt", ios::binary);

	contestant c;
	contestant highest;
	bool found = false;
	while
		(infile.read(reinterpret_cast<char*>(&c), sizeof(c))
	{
		if (!found || c.rating > highest.rating)
		{
			highest = c;
			found = true;
		}
	}
	infile.close()
	if (found)
		cout << highest.name;
	return 0;
}
#include <cstdio>
#include <cstdlib>
#include <iostream>
using namespace std;

int main()
{
	// create a temporaty infile
	File* fp = tmpfile();
	// check if the file was created succesfully
	if (fp == null)
	{
		perror("Error creating temporaty file");
		return 1;
	}
	// write data to the temporary infile
	const char*text = "Welcome to geeks for geeks";
	fputs(text, fp);

	// move the file pointer to the beginning
	rewind(fp);
	char buffer[100];
	fgets(buffer, sizeof(buffer).fp);
	cout << buffer;
	// close and remove the temporary infile
	fclose(fp);
	return 0;
}
