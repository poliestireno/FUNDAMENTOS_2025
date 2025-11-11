Ejercicio 5 + 11 = 16 --> M7  
 
0  ['00000100'],     + 5                                         
1		['00000101'],     + 11                                        
2		['01100111'],     Mover a la Memoria 7                        
3		['01110000'],     Fin                                         
4		['00000101'],  Dato con valor 5                                               
5		['00001011'],  Dato con valor 11                                               
6		['00000000'],                                                 
7		['00000000']                                                  

Ejercicio 12 - 7 = 5 --> M6  
0   00000111    + 12  
1   00010101         - 7  
2   01100110              mover a la memoria 6  
3   0111----                                     Fin  
4   --------  
5   00000111    Data con valor 7  
6     
7   00001100    Dato con valor 12   

Ejercicio 2 + 4 + 2 = 8 --> M1    

0  00000111  + 2  
1  00000110       + 4  
2  00000111            + 2  
3  01100001                 Mover a la posición de memoria 1  
4  01110000                                                     Fin  
5  
6  00000100  Dato con valor 4  
7  00000010  Dato con valor 2  






Códigos de operación:  
|  Inst  |  D  |  Comentario      |  
+--------+-----+-------------------+  
|  0000  |  +  |  Suma             |  
|  0001  |  -  |  Resta            |  
|  0010  |  *  |  Producto         |  
|  0011  |  ^  |  Exponente        |  
|  0100  |  &  |  Operador AND     |  
|  0101  |  |  |  Operador OR      |  
|  0110  |  M  |  Mover a memoria  |  
|  0111  |  …  |  Finalizar    


Memoria de 8 bytes, cada celda de memoria guarda 1 byte (8 bits)  
Hay 8 instrucciones de 8 bits cada una.  

 Una instrucción se puede interpretar de 2 maneras:  
        1.- Código operación (primeros 4 bits) + posición memoria(los siguiente 4 bits)  
        2.- Dato ó valor en binario(los 8 bits)  





