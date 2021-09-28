# C-Exercise-1
C++ exercise for class

#include <iostream>
using namespace std;

int main()
{
    string Item;
    float Cost;
    float Discount;
    float TotalCost;


    cout << "What is the item? \n";
    cin >> Item;

    cout << "What is the cost? \n";
    cin >> Cost;

    cout << "What is the discount? \n";
    cin >> Discount;

    TotalCost = Cost - Discount;
    
    
    return 0;
}
