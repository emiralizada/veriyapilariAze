// BASİT ÖRNEK 1
#include<iostream>
#include <ctime>
using namespace std;

class Sayi {
public:

Sayi()
{
       mDeger = rand() % 100;
}
void yazdir(){
	
cout<<mDeger<<endl;
}


private:
	int mDeger;
};

int main(){


	setlocale(LC_ALL,"Turkish");
	
    srand(time(NULL));
    Sayi* p = new Sayi[5];	

	for(int i=0;i<5;i++){

		cout<<"Sayi:";
		p[i].yazdir();
	} 
    delete p;
	return 0;
}

