# General
Simple C Code to Display the Data You Input

## Features
- Display the name you input
- Display the nim you input
- Displaying the ideals you input
  
## Configuration
```yaml
#include <stdio.h>

int main() {

    char nama[50];
    int nim;
    char citacita[50];

    /*Code Input Nama*/
    printf("Masukkan Nama Kamu: ");
    /*Menggunakan String*/
    scanf("%s", nama);

    /*Code Input NIM*/
    printf("Masukkan NIM Kamu: ");
     /*Menggunakan Decimal*/
    scanf("%d", &nim);

    /*Code Cita*/
    printf("Apa Cita-Cita Kamu?: ");
    /*Menggunakan String*/
    scanf("%s", citacita);

    /*Tambahkan Pesan Sebelum Data*/
    printf("\nData Kamu:\n\n");
    /*Output Data Yang Di Tampilkan*/
    printf("Nama: %s\n", nama);
    printf("NIM: %d\n", nim);
    printf("Cita-Cita: %s", citacita);

    return 0;
}
```
