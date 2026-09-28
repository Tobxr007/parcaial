#include <iostream>
using namespace std;

int main()
{
    float Y, Z, Trabajo;

    cout << "Ingrese la fuerza en Newton: ";
    cin >> Y;

    if (Y < 0)
    {
        cout << "Datos erroneos";
    }
    else
    {
        cout << "Ingrese la distancia en metros: ";
        cin >> Z;

        if (Z < 0)
        {
            cout << "Datos erroneos";
        }
        else
        {
            Trabajo = Y * Z;

            cout << "El trabajo realizado es: "
                 << Trabajo << " J";
        }
    }

    return 0;
}
