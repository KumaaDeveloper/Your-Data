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

    /*fgets() digunakan untuk membaca input string yang mengandung spasi*/
    fgets(nama, sizeof(nama), stdin);

    /*Code Input NIM*/
    printf("Masukkan NIM Kamu: ");
     /*Menggunakan Decimal*/
    scanf("%d", &nim);

    /*getchar() digunakan untuk membersihkan karakter newline (\n) yang tersisa setelah scanf("%d", &nim); agar tidak mengganggu fgets() berikutnya*/
    getchar();

    /*Code Cita*/
    printf("Apa Cita-Cita Kamu?: ");
    fgets(citacita, sizeof(citacita), stdin);

    /*Tambahkan Pesan Sebelum Data*/
    printf("\nData Kamu:\n\n");
    /*Output Data Yang Di Tampilkan*/
    printf("Nama: %s", nama);
    printf("NIM: %d\n", nim);
    printf("Cita-Cita: %s", citacita);

    return 0;
}
```
