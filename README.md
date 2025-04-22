# Ejercicio 1: Los Primeros Inventos de Joy

```python
# Inicio del Ejercicio 1
lista_inventos_tempranos = ["Granja de Papel", "Collar Antipulgas (idea inicial)", 
                            "Un dispositivo para ordenar juguetes", 
                            "Un sistema de riego automático para plantas pequeñas", 
                            "Un tipo de tendedero retráctil"]

# Inicio del ciclo for
for invento in lista_inventos_tempranos:
    print("Joy ideó:", invento)
# Fin del ciclo for

# Fin del Ejercicio 1

Explicación:
Este código crea una lista llamada lista_inventos_tempranos con nombres de inventos hipotéticos de Joy. Luego, el ciclo for itera sobre cada elemento de esta lista, asignando cada invento a la variable invento en cada iteración, y finalmente imprime una frase indicando que Joy ideó ese invento.

Ejercicio 2: Los Obstáculos en la Venta del Trapeador

import random

# Inicio del Ejercicio 2
numero_de_tiendas = 10
rechazos = 0

# Inicio del ciclo for
for intento in range(1, numero_de_tiendas + 1):
    resultado = random.choice(["rechazado", "aceptado"])  # Simula la respuesta de la tienda

    if resultado == "rechazado":
        rechazos += 1
        print(f"Intento {intento}: La tienda rechazó el trapeador.")
    else:
        print(f"Intento {intento}: ¡La tienda aceptó el trapeador!")
        break  # Detiene la ejecución del ciclo for
# Fin del ciclo for

print(f"Joy enfrentó {rechazos} rechazos antes de lograr una aceptación.")

# Fin del Ejercicio 2
