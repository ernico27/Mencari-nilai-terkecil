# Mencari-nilai-terkecil

    #include<iostream>
    #include<stdio.h>
    #include<conio.h>
    using namespace std;
    int minimum(int a,int b,int c);
    int main(void)
    {
    int a,b,c,min;
    cout << "\t\t ======================= \n";
    cout << "\t\t Program nilai terkecil \n";
    cout << "\t\t ======================= \n";
    printf("\t\t Masukkan bilangan 1 : ");
    scanf("%d",&a);
    printf("\t\t Masukkan bilangan 2 : ");
    scanf("%d",&b);
    printf("\t\t Masukkan bilangan 3 : ");
    scanf("%d",&c);

    min=minimum(a,b,c);
    printf("\t\t Bilangan terkecil = %d",min);
    getch();
    }
    int minimum(int a,int b,int c)
    {
    int min;
    if (a>b)
    {
        min=b;
    }
    else
    {
        min=a;
    }
    if (c<min)
    {
        min=c;
    }
    return (min);
    }

## Hasilnya

![img](https://github.com/ernico27/Mencari-nilai-terkecil/blob/master/nilai%20terkecil.png?raw=true)
