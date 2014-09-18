#include <stdio.h>
main()
{
float suhu, hasil;
int jenis;
char back;
    printf("\t=================================\n");
    printf("\t||       Konversi Suhu         ||\n");
    printf("\t=================================\n\n");
    printf("\tNama  : Lilian Nur Sasongko\n");
    printf("\tNIM   : 3143111043\n");
    printf("\tProdi : Manajemen Informatika A\n\n");
    ulang:
    printf("Pilih satuan Suhu untuk dikonversi :\n");
    printf("1. Celcius\n");
    printf("2. Farenhet\n");
    printf("3. Reamor\n");
    printf("Pilihan Nomer Suhu :");
    scanf("%d", &jenis);
switch(jenis)
    {
case 1:
    printf("Masukan Besaran Suhu :");
    scanf("%f", &suhu);
    hasil=(suhu*1.8)+32;
    printf("suhu Farenhet : %.2f F\n", hasil);
    hasil=suhu*0.8;
    printf("suhu Reamor : %.2f R\n", hasil);
    break;
case 2:
    printf("Masukan Besaran Suhu :");
    scanf("%f", &suhu);
    hasil=(suhu-32)/1.8;
    printf("suhu Celsius : %.2f C\n", hasil);
    hasil=(suhu-32)/2.25;
    printf("suhu Reamor : %.2f R\n", hasil);
    break;
case 3:
    printf("Masukan Besaran Suhu :");
    scanf("%f", &suhu);
    hasil=suhu/0.8;
    printf("suhu Celsius : %.2f C\n", hasil);
    hasil=(suhu*2.25)+32;
    printf("suhu Farenhet : %.2f F\n", hasil);
    break;
default:
    printf("maaf kode yang Anda masukkan salah :(\n");
    goto ulang;
    }
}
