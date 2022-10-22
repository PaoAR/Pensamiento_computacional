Funcion aleatorio

![image](https://user-images.githubusercontent.com/113804528/197361891-1d5eba35-908c-4369-9f7d-6a012569556a.png)


Repetir, funcion para que se este repitiendo una actividad hasta que suceda algo dicho por el usuario.

![image](https://user-images.githubusercontent.com/113804528/197362586-99d149c0-239a-49be-9d2a-f5baa4921f21.png)


Encontrar el numero que la maquina esta pensando

![image](https://user-images.githubusercontent.com/113804528/197362270-c1ddde46-5781-4931-bd15-0a09503054ab.png)


PSint

Se agrega condicionante si, para ayuda del usuario a encontrar el numero

![image](https://user-images.githubusercontent.com/113804528/197362366-9022e18b-099b-4118-8f97-fb70dfe4181d.png)


Se finaliza con una leyenda de que se encontro el numero

![image](https://user-images.githubusercontent.com/113804528/197362514-e8370a7e-c0c0-4d92-a5ad-53787cb58d33.png)

Completo

![image](https://user-images.githubusercontent.com/113804528/197362538-f0410061-9d3b-4a26-885a-08396e147234.png)


Simulación


![image](https://user-images.githubusercontent.com/113804528/197362668-91e28b8d-f8b1-4d90-8afd-33d443a97d4e.png)



Agregar que el usuario solo tenga 5 oportunidades para encontrar el numero e ir restando vidas cada que no le atine usaando mientras


![image](https://user-images.githubusercontent.com/113804528/197363506-a3e2241a-0793-4c99-82db-ad4ebbb7e2ee.png)

Algoritmo

  Algoritmo sin_titulo

	num_sec<-azar(100)
	num<-0
	vidas<-5
	Escribir "Adivina el número"
	Leer num
	
	Mientras num<>num_sec y vidas>1 Hacer
		Escribir "Te quedan ", vidas-1, " oportunidades"
		Si num>num_sec Entonces
			Escribir "Tu número es mayor"
		SiNo
			Escribir "Tu número es menor"
		Fin Si
		
		Escribir "Adivina el número"
		Leer num
		
		vidas<-vidas-1
	Fin Mientras
	
	
	Si num=num_sec Entonces
		Escribir "Felicidades, encontraste el numero"
	SiNo
		Escribir "Fin del juego, se agotaron las vidas, el número era ", num_sec
	Fin Si
	
  FinAlgoritmo


SIMULACIÓN

No se encuentra el numero

![image](https://user-images.githubusercontent.com/113804528/197363539-db34424b-fb0d-4beb-a772-7ccda1e1c182.png)


Se encuentra el numero

![image](https://user-images.githubusercontent.com/113804528/197363562-77b3caae-1c9e-42b5-b176-f688165ee251.png)
