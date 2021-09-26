# Profit-or-loss
code

#include<iostream>
using namespace std;

int main()
{
    float sprice,pprice,profit,loss;
    cout<<"purchase price:";
    cin>> pprice;
    cout<<"sale price:";
    cin>> sprice;
    if(sprice,pprice)
    {
        loss=sprice-pprice;
        cout<<"loss is="<<loss<<endl;
    }
    else
    {
        profit=pprice-sprice;
        cout<<"profit is="<<profit<<endl;
    }
    return 0;
    
}
