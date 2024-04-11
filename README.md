#include<iostream>
using namespace std;
int main(){
    int num1,num2;
    cout<<"Enter two numbers "<<endl;
    cin>>num1;
    cin>>num2;
    //num=numbers given by user.
    char op;
    cout<<"Enter operator you want to use "<<endl;
    cin>>op;
    switch (op){
        case '+':
        cout<<num1<< "+"<< num2 << "="<< num1 + num2;
        break;
        case '-':
        cout<<num1<< "-"<< num2 << "="<< num1 - num2;
        break;
        case '*':
        cout<<num1<< "*"<< num2 << "="<< num1 * num2;
        break;
        case '/':
        cout<<num1<< "/"<< num2 << "="<< num1 / num2;
        break;
    }

}
