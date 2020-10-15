# Cashier-receipt
//B. Create a simple cashier program.
#include <iostream>
using namespace std;

int main(){

    int prod,num,n;

        cout << "=========================================="<<endl;
        cout << "\t   ITEM    \t||\t₱Price   "<< endl;
        cout << "                             "<< endl;
        cout << "1\tChoco milk\t||\t₱52   "<< endl;
        cout << "2\tYacult(large)\t||\t₱45      "<< endl;
        cout << "3\tVitamilk \t||\t₱48  "<< endl;
        cout << "4\tPepsi cola\t||\t₱82  "<< endl;
        cout << "                             "<< endl;
        cout << "===========================================";

        cout << endl<< "Enter Number: ";
        cin >> num;
        switch (num){
            case 1:
            cout << "Enter Payment: ";
            cin >> n; 
            if (n>=52){
                prod=n-52;
                cout << "Change:₱ "<<prod<<endl;
            }
            else
                cout << "Invalid Payment"<<endl;
                break;
            case 2:
            cout << "Enter Payment: ";
            cin >> n; 
            if (n>=45){
                prod=n-45;
                cout << "Change:₱ "<<prod<<endl;
            }
            else
                cout << "Invalid Payment"<<endl;
                break;
            case 3:
            cout << "Enter Payment: ";
            cin >> n; 
            if (n>=48){
                prod=n-48;
                cout << "Change:₱ "<<prod<<endl;
            }
            else
                cout << "Invalid Payment"<<endl;
                break;
            case 4:
            cout << "Enter Payment: ";
            cin >> n; 
            if (n>=82){
                prod=n-82;
                cout << "Change:₱ "<<prod<<endl;
            }
            else
                cout << "Invalid Payment"<<endl;
                break;
            }
       cout << " by:KIAN SAGALA";

    return 0;
}
