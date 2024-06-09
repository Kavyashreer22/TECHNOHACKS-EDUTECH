#include<iostream>
using namespace std;
int main() 
{
    int choice;
    float num1, num2, result;
    do
    {
        cout << "**************\n";
        cout << "1.ADDITION OF TWO NUMBERS\n";
        cout << "2.SUBTRACTION OF TWO NUMBERS\n";
        cout << "3.MULTIPLICATION OF TWO NUMBERS\n";
        cout << "4.DIVISION OF TWO NUMBERS\n";
        cout << "5.EXIT\n";
        cout << "***************\n";
        cout << "ENTER YOUR CHOICE(1-5): ";
        cin >> choice;

        if(choice == 5) break;

        cout << "Enter two operands: ";
        cin >> num1 >> num2;

        switch(choice)
        {
            case 1:
                result = num1 + num2;
                cout << num1 << " + " << num2 << " = " << result << "\n";
                break;

            case 2:
                result = num1 - num2;
                cout << num1 << " - " << num2 << " = " << result << "\n";
                break;

            case 3:
                result = num1 * num2;
                cout << num1 << " * " << num2 << " = " << result << "\n";
                break;

            case 4:
                if(num2 != 0.0)
                {
                    result = num1 / num2;
                    cout << num1 << " / " << num2 << " = " << result << "\n";
                }
                else
                {
                    cout << "Division by 0 exception\n";
                }
                break;

            default:
                cout << "Error! Choice is not correct\n";
        }

    } while(choice != 5);

    return 0;
}
