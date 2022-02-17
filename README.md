# Trabajo_Algoritmos_Grupal


Ejercicio 3: Descuento.

Entrada
   k: REAL      #Importe de la compra que se ha realizado
   si k < 100 euros
      entonces
         no se realizará ningún descuento.
   si 100 ≤ k ≤ 500
      entonces
         multiplicar(k,0'95) = Resultado
   si 500 < k 
      entonces
         multiplicar(k,0'92) = Resultado
Resultado: REAL #Resultado del precio final realizado o no el descuento

Ejercicio 4: Otra vez una media.

Entrada
  n1,n2,n3,n4: REAL # Las notas con las que se obtendrá la media de cada alumno
  k: ENTERO         # La cantidad de notas de cada alumno
Resultado: REAL     # La media aritmética de las notas 

Precondición
   #Una nota está comprendida entre 0 y 20
   0 ≤ nx ≤ 20
   #La cantidad de notas es mayor o igual a 1
   1 ≤ k
Poscondición
   El resultado se obtiene de la media aritética de todas las notas, es decir, la suma de n1, n2, n3 y n4 entre el cociente k.

Realización
   #Cálculo de la media de notas
   m = (n1 + n2 + n3 + n4) / 4
   #Cálculo de la decisión
   si m > 15
      entonces
         print("Alumno con talento")
   si 15 > m > 12
      entonces
         print("Con capacidad")
   si 12 > m
      entonces
         print("Debe reorientarse")
   
   
