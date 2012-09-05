#include <cstdlib>
#include <iostream>

using namespace std;

int main(int argc, char *argv[])
{
     int num,fact=1;
    cout << "::FACTORIAL::" << endl;
    cout << "Introduce un numero: "; cin >> num;
    for(int i=2; i<=num; i++)
    {
        fact = fact * i;
    }
    cout << "Su factorial es: " << fact;
    cin.get();cin.get();
    system("PAUSE");
    return EXIT_SUCCESS;
}
