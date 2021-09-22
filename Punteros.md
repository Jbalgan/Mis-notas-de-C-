# Punteros 

Un puntero es una variable que guarda la dirección de otra variable a la que apunta. 

`int *p; ` 

Para que el puntero p apunte a una variable, utilizamos el operador & 

`int n=5;` 

`p=&n;`

Ahora el puntero p guarda la dirección de memoria de la variable n.  

Podemos acceder al valor guardado en la variable n utilizando el puntero mediante el operador * 

`cout << Valor guardado en n = << *p << endl; `

También podemos modificar el valor almacenado en n de forma indirecta utilizando el puntero 

` cin >> *p >> endl; ` 

Cuando definimos el puntero hay que indicar a que tipo de variable puede apuntar pues no todas las variables ocupan el mismo espacio de memoria, así una variable de tipo entero (int) 
ocupa 4 bytes mientras que una variable carácter (char) ocupa un byte. 
