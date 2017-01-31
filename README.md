#include <iostream>

using namespace std;

int main()
{
    int num=1;
    int numar;
    int total=0;
    int totalNou;
    int superTotal;


    while(num<=5){
    cout<<"Introduceti un numar "<<endl;
    cin>>numar;
    total+=numar;
    num++;}

    cout<<"Suma nr este "<<total<<endl;

    {
        if(total<50)
        cout<<"Noul total este "<<total+100<<endl;
        totalNou=total+100;
    }
    {
        if(totalNou<1000)
        cout<<"Totalul al treilea este "<<totalNou+1000<<endl;
        superTotal=totalNou+1000;
    }
    {
        if(superTotal<10000)
            cout<<"Ultimul total este "<<superTotal+10000<<endl;
    }
    cout<<"Va pup!"<<endl<<endl<<endl;

   return 0;
}
