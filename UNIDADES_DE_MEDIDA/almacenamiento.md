## Ejercicios Almacenamiento
**1. ¿Cuántos bytes se almacenan en un pendrive de 4GB?.**  
1 GB = 1024 * 1024 * 1024 B  
4 GB = 4 * 1024 * 1024 * 1024 B  
4 GB = 4294967296 B  

**4. Investiga la capacidad de un disquete de 3 1⁄2. ¿Cuántos disquetes puedes grabar en un DVD de DOBLE CAPA?. ¿Y en un CD de 700 MB?**  
1 disquete 3 1/2 = 1.44 MB  
1 DVD de doble capa = 8.5 GB = 8.5 * 1024 MB = 8704 MB  
8704 / 1.44 = 6044,44 --> 6044 disquetes se pueden grabar en un DVD de doble cara.  

**5. ¿A cuántos CD's necesito para meter un DVD? ¿Y un pendrive de 8 GB?**  
1 CD = 700 MB  
1 DVD = 4.7 GB = 4.7 * 1024 MB = 4812,8 MB  
4812,8 / 700 = 6,87 --> Se necesitan 7 CDs para meter todos los datos de un DVD  

**6. Si te compras un disco duro portatil (USB) de 1 TB, ¿cuántos DVD's enteros podrías volcar en él?**  
1 DVD = 4.7 GB  
1 TB = 1024 GB  
1024/4.7 = 217,87 --> 217 DVD enteros podemos volcar en el USB  

## Ejercicios Velocidad de transmisión
**Ejercicio página 9**  
Velocidad WIFI 54 Mb/s  
Película de tamaño 3Gb  
Duración de la película 156 minutos  
¿Se para la película al transmitirla en esta WIFI?  

3Gb = 1024 * 3Gb = 3072Mb  
156 minutos = 156 minutos * 60 = 9360 segundos  
para saberlo vamos a ver si se transmiten los 3072Mb antes de final del peli, osea antes de 9360 segundos.  
3072Mb / 54 Mb/s = 56.88 segundos tarda en transmitir toda la peli.  
Como 56.88 es menor que la duración (9360) entonces la peli se ve perfectamente, no hay parones y además habría un montón buffer almacenado.  

¿Tiempo de descarga de la misma película con la velocidad de transferencia de 87 Kb/s?  
3Gb = 1024 * 1024 * 3Gb = 3145728 Kb  
3145728 Kb / 87 Kb/s = 36157.8 segundos  --> 36157.8s / 60 = 602 min --> 602 min / 60 = 10 horas  

**2. ¿Cuántos KB/s bajas con una línea ADSL de 6 Mb?**  
1B = 8b  --> 1 byte es igual a 8 bits  
6Mb = 6Mb / 8 = 0.75 MB  
0.75 MB/s = 0.75MB/s * 1024 = 768 KB/s 

**3 ¿Cuántos MB puedes bajarte al minuto con la línea ADSL anterior?**  

768 KB/s * 60 = 46080 KB/min = 46080 KB/min / 1024 = 45 MB/min  


## Ejercicios frecuencia de procesador    
**Dado una CPU de 10GHz. Si el tipo de instrucciones es de tipo RISC (reducida, 1 instrucción cada 5 ciclos de reloj)**    
**¿Cuantas instrucciones se ejecutan en 1 segundo?**  
**¿y en 2 minutos?**  

(ejercicios de frecuencia osea Hz(Hercios) se multiplica por 1000 en vez de 1024)  
1Hz = 1 ciclo/segundo  
10GHz = 10 * 1000 * 1000 * 1000 = 10000000000Hz    
1 instrucción cada 5 ciclos de reloj  
10000000000Hz/5Hz por instrucción = 2000000000 instrucciones / segundo  
¿y en 2 minutos?
2000000000 instrucciones / segundo * 120 segundos = 240000000000 instrucciones en 2 minutos

**Con el mismo procesador si fuera de CISC, con estos porcentajes de ejecución:**  
**(15%) instrucciones cada 2 ciclos de reloj**  
**(25%) instrucciones cada 3 ciclos de reloj**  
**(60%) instrucciones cada 5 ciclos de reloj** 
**Se pide, nº de instrucciones de media que se ejecutan en un segundo**  
10000000000Hz/2Hz por instrucción = 5000000000 instrucciones / segundo  
10000000000Hz/3Hz por instrucción = 3333333333,3 instrucciones / segundo  
10000000000Hz/5Hz por instrucción = 2000000000 instrucciones / segundo  

5000000000 instrucciones / segundo * 0.15 = 750000000 instrucciones / segundo  
3333333333,3 instrucciones / segundo * 0.25 = 833333333,3 instrucciones / segundo  
2000000000 instrucciones / segundo * 0.60 = 1200000000 instrucciones / segundo  
Media de instrucciones al segundo = 750000000+833333333,3+1200000000 =  2783333333,3 instrucciones / segundo  


