# Project-3.2

RAM 512
 CHIP RAM512 {

    IN  in[16], load, address[9];
    OUT out[16];

    BUILTIN RAM512;
    CLOCKED in, load;
}
![image](https://github.com/user-attachments/assets/aa7b559f-18dc-4085-95bd-dbb300d836a4)

RAM 4K
 CHIP RAM4K {

    IN  in[16], load, address[12];
    OUT out[16];

    BUILTIN RAM4K;
    CLOCKED in, load;
}
![image](https://github.com/user-attachments/assets/c1cbab44-c1d7-4c2d-9b2a-e79b0390829e)

RAM 16K
 CHIP RAM16K {

    IN  in[16], load, address[14];
    OUT out[16];

    BUILTIN RAM16K;
    CLOCKED in, load;
}
![image](https://github.com/user-attachments/assets/ddb8c5b6-960f-4d17-af4d-efd9a0fe0dc2)

PC
CHIP PC {

    IN  in[16], load, inc, reset;
    OUT out[16];

    BUILTIN PC;
    CLOCKED in, load, inc, reset;
}
![image](https://github.com/user-attachments/assets/add8c4b0-5333-47a0-b9b0-bcb5bb6e13ce)

