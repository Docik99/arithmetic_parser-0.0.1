#include <iostream>

using namespace std;

int main()
{
    int num1 , num2;
    char op;

    cin >> num1 >> op;

    if (op == ' > ' || op == ' < ')
    {
        cin >> op >> num2;
    }
    else
    {
        cin >> num2;
    }

    switch (op)
    {
        case '+': cout  << (num1 + num2) <<endl;
            break;
        case '-': cout   << (num1 - num2) << endl;
            break;
        case '*': cout   << ( num1 * num2) << endl;
            break;
        case '/': cout  << (double)(num1 / num2) << endl;
            break;
        case '%': cout << (num1 % num2 )<< endl;
            break;
        case '&': cout  << (num1 & num2) << endl;
            break;
        case '|': cout  << (num1 | num2) << endl;
            break;
        case '^': cout  << (num1 ^ num2) << endl;
            break;
        case '>': cout  << (num1 >> num2) << endl;
            break;
        case '<': cout  << (num1 << num2) << endl;
            break;
            


    }
    return (0);
}
