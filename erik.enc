#include<iostream>
#include<stdio.h>
#include<windows.h>


using namespace std;
int a=1,n,d,c,b;

struct pasien
{
char LP;
string tiggal;
int umur;
string sehat;
string name;
int ktp;
}pas[20];

void input(pasien)
{
        d=0;
    cout<<"\nbanyak data yang di input: ";cin>>b;
            for(c=0;c<b;c++){
        d=d+1;
    cout<<"\nNO-"<<d<<endl;
    cout<<"Masukkan Ktp: ";cin>>pas[a].ktp;
    cout<<"Masukkan Nama: ";cin>>pas[a].name;
    cout<<"Masukkan Alamat: ";cin>>pas[a].tiggal;
    cout<<"Masukkan jenis kelamain L/P: ";cin>>pas[a].LP;
    cout<<"Masukkan umur: ";cin>>pas[a].umur;
    cout<<"Masukkan kondisi: ";cin>>pas[a].sehat;
        a++;}
}

void lihat(pasien)
{
        int i,j;
cout<<"\nlihat Data Pasien\n\n";
cout<<"\tNO\tKtp\t\tNama\t\tAlamat\t\tJenis Kelmain\t\tUmur\t\tKondisi\t\n";
        j=0;
    for(i=1;i<a;i++)
        {j=j+1;
cout<<"\t"<<j<<"\t";
cout<<pas[i].ktp<<"\t";
cout<<pas[i].name<<"\t\t";
    cout<<pas[i].tiggal<<"\t\t";
cout<<pas[i].LP<<"\t\t\t";
cout<<pas[i].umur<<"\t\t";
    cout<<pas[i].sehat<<"\t\t";
cout<<endl;
        }
}

void edit(pasien)
{
        int k,l;
cout<<"Pilih yang akan diedit : ";cin>>k;
        l=k-1;
cout<<"ktp\t: ";cin>>pas[l].ktp;
    cout<<"Nama\t: ";cin>>pas[l].name;
cout<<"Alamt: ";cin>>pas[l].tiggal;
cout<<"LP\t: ";cin>>pas[l].LP;
cout<<"Umur\t: ";cin>>pas[l].umur;
cout<<"Kondisi\t: ";cin>>pas[l].sehat;
        void lihat(pasien);
}

void menghapus(pasien)
{
cout<<"Pilih untuk di hapus"<<endl;
        int x,y;
cout<<"ke-";cin>>x;
y=x-1;
        a--;
for(int i=y;i<a;i++)
{pas[i]=pas[i+1];}
cout<<"data yang di hapus   :"<<x<<endl;
}

 int main(){
int pilih=0;

do {system("cls");
cout<<"Data Pasien"<<endl;
cout<<"1. Input Data Pasien"<<endl;
cout<<"2. Melihat Data"<<endl;
cout<<"3. Update data"<<endl;
cout<<"4. Hapus data"<<endl;

cout<<"plih menu :";cin>>pilih;

switch(pilih)
    {
case 1: {input(pas[20]);} break;
case 2: {lihat(pas[20]);} break;
case 3: {edit(pas[20]);} break;
case 4: {menghapus(pas[20]);} break;
default:cout<<"menu tidak ada"<<endl;

    }
    system("pause");
}
while(pilih!=0);

    return 0;


}
