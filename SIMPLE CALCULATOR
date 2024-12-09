#include<iostream> 
using namespace std; 
int main() { 
    int n1,n2; 
    char operation; 
    cout<<"Enter two integer values : "; 
    cin>>n1>>n2; 
    cout<<"Enter an arithmetic operator : "; 
    cin>>operation; 
    switch(operation) { 
        case '+': 
        cout<<n1<<" + "<<n2<<" = "<<(n1+n2)<<endl;
        break; 
        case '-': 
        cout<<n1<<" - "<<n2<<" = "<<(n1-n2)<<endl; 
        break; 
        case '*': 
        cout<<n1<<" * "<<n2<<" = "<<(n1*n2)<<endl; 
        break; 
        case '/': 
        if(n2 !=0) { 
            cout<<n1<<" / "<<n2<<" = "<<(n1/(float)n2)<<endl;
            }else { 
                cout<<"Error! Division by zero"<<endl; 
                } 
                break; 
                case '%': 
                cout<<n1<<" % "<<n2<<" = "<<(n1%n2)<<endl; 
                break; 
                default: 
                cout<<"Error! Operator is not correct"<<endl; 
                break; 
        } 
    return 0;
 }
