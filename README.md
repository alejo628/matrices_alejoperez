[matrices_recu.py](https://github.com/user-attachments/files/33569186/matrices_recu.py)# matrices_alejoperez
[Uploaventas = [
    [],
    [],
    [],
    []
]
print("matriz de ventas")
for i in range(4):
    mes= int(input("que mes vas a querer llenar? (es del 0 al 3)\n"))
    for i in range(4):
        venta=int(input("ingresa las ventas que hizo en ese mes"))
        ventas[mes].append(venta)
print("MARTIZ: ")
for fila in ventas:
    print(fila)

mes_promedio = int(input("Elige el mes para sacar el promedio: "))
mes_elegido = ventas[mes_promedio]
suma = 0
for numero in mes_elegido:
    suma = suma + numero

promedio = suma / len(mes_elegido)
print(f"El promedio es {promedio}")

suma = 0
longitudes = 0
for fila in ventas:
    for numero in fila:
        suma = suma + numero
    longitudes = longitudes + len(fila)

promedio_total = suma / longitudes
print(f"El promedio total es {promedio_total}")ding matrices_recu.py…]()
