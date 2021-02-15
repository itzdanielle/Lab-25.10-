# Lab-25.10-
#include <iostream>
using namespace std;

/* _Compound Assignment_
Compound assignment operators modify the current value of a variable by performing an operation on it:

expression  |  equivalent to
y += x;         y = y + x;
x -= 5;         x = x - 5;
x /= y;         x = x / y;
y *= x;         y = y * x;

Instructions: Convert the math expressions in the code to use compound assignment operators when possible.
*/

int main() {
  int a = 1;
  int b = 3;
  int c = 21;

  b = b += 4;

  a = a *= 7;

  b = b += a;

  a = b += a;

  c = c /= 7;

  c = b -= 7;

  c = c -= 21;

  cout << "a = " << a << endl;
  cout << "b = " << b << endl;
  cout << "c = " << c << endl;

}
