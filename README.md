13.
#include <iostream.h>


void swapNumbers(int &a, int &b) {
    int temp = a;  
    a = b;         
    b = temp;     
}
void main() {
    int x, y;

    cout << "Enter two numbers: ";
    cin >> x >> y;

    cout << "\nBefore swapping: ";
    cout << "x = " << x << ", y = " << y << endl;

   
    swapNumbers(x, y);

    cout << "After swapping: ";
    cout << "x = " << x << ", y = " << y << endl;

    getch();
}
