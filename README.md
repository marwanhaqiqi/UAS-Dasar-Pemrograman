# UAS-Dasar-Pemrograman
# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar Pemrograman
<br> Nama		: Gallung Marwan Haqiqi Hafidz
<br>NIM		:	1227050049
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
Program Transpose Matriks di C++
Matriks merupakan kumpulan-kumpulan bilangan yang disusun secara baris (vertikal) dan kolom (horizontal) bisa disebut juga array dua dimensi (multi-dimensional). Transpose Matriks adalah memperoleh sebuah matriks dengan cara menukar baris menjadi kolom dan kolom menjadi baris dari sebuah matriks.

## Source Code
```
#include <iostream>

using namespace std;

int main()
{
    #include <iostream>

using namespace std;

int main()
{
    #include <iostream>

using namespace std;


int main()
{
	cout << "========================================================================" << endl;
	cout << "Gallung Marwan Haqiqi Hafidz" << endl;
	cout << "NIM	: [1227050049]" <<  endl;
	cout << "========================================================================" << endl;
	cout << endl;
    //1. Menginput Banyaknya Baris Dan Kolom 
    //Mengisi Dengan Nilai
    //Setelah Diisi Menukar Baris dan Kolom
    int baris, kolom;
    cout << "Masukkan banyaknya baris : ";
	cin >> baris;
    cout << "Masukkan banyaknya kolom : ";
	cin >> kolom;
    const int baris_A = baris;
    const int kolom_A = kolom;
    int array[baris_A][kolom_A];
    int menukar[kolom_A][baris_A];
    cout << "Masukkan nilai		 : " << endl;
    for(int i = 0; i < baris_A; i++){
        for(int j = 0; j < kolom_A; j++){
            cout << "Tentukan baris ke-" << i+1 << " dan kolom ke-" << j+1 << "	: ";
            cin >> array[i][j]; 
        }
    }
    cout << "Dari bentuk awalnya adalah	: " << endl;
    for(int i = 0; i < baris_A; i++){
        for(int j = 0; j < kolom_A; j++){
            cout << array[i][j] << " ";
        }
        cout << endl;
    }
    for(int i = 0; i < baris_A; i++){
        for(int j = 0; j < kolom_A; j++){
            menukar[j][i] = array[i][j];
        }
    }
    cout << "Menjadi bentuk akhir senilai	: " << endl;
    for(int i = 0; i < kolom_A; i++){
        for(int j = 0; j < baris_A; j++){
            cout << menukar[i][j] << " ";
        }
        cout << endl;
    }
    
            
    return 0;
}
```
## Output
![image](https://user-images.githubusercontent.com/121102747/208850925-bbb233ce-65e8-4265-b765-5a21e3ad6500.png)
