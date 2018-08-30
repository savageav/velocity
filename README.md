#include<iostream.h>
#include<conio.h>
void main()
{
    int s,t; float v;
    cout<<"Enter the magnitude of the displacement:";
    cin>>s;
    cout<<"Enter the time taken to cover the specified displacement:";
    cin>>t;
    v=s/t;
    cout<<"The velocity of the object is:"<<v;
    getch();
}
