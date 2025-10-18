# Hesap-Makinesi-Projesi
C++ ile hesap makinesi yapımı




    #include <iostream>
    using namespace std;

       int main(int argc, char** argv) {
	
	
     int sayi1,sayi2,islem,devamDurumu;
	devamDurumu=1;
	
	
	
     while(devamDurumu==1)
	{
	cout << "----------HESAP MAKINESI------------\n";
	cout << "Yapilacak islemi seciniz:(1:Toplama, 2:cikarma, 3:carpma, 4:bolme)";
	cin >> islem;
	cout << "1.sayiyi girin: ";
	cin >> sayi1;
	cout << "2.sayiyi girin: ";
	cin >> sayi2;
	
	
    if(islem==1)
	{
		cout << "Sonuc: " << sayi1+sayi2;
	}
	else if(islem==2)
	{ 
		cout << "Sonuc: " << sayi1-sayi2; 
	}
	else if(islem ==3)
	{
		cout << "Sonuc: " << sayi1*sayi2;
	}
	else if(islem ==4)
	{
		cout << "Sonuc: " << sayi1/sayi2;
	} 
	else
	{
		cout << "Hatalı deger girdiniz...";
	}
	cout << "\n";
	
    cout << "devam etmek isterseniz 1 istemezseniz 0'a basiniz:";
	cin >> devamDurumu;
    }
	return 0;
    }
