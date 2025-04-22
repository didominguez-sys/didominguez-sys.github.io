Ejercicio 1: Los Primeros Inventos de Joy
# Inicio del Ejercicio 1
lista_inventos_tempranos = ["Granja de Papel", "Collar Antipulgas (idea inicial)", "Un dispositivo para ordenar juguetes", "Un sistema de riego automático para plantas pequeñas", "Un tipo de tendedero retráctil"]

# Inicio del ciclo for
for invento in lista_inventos_tempranos:
    # Inicio del bloque de código dentro del ciclo for
    print("Joy ideó:", invento)
    # Fin del bloque de código dentro del ciclo for
# Fin del ciclo for

# Fin del Ejercicio 1
•
Explicación: Este código crea una lista llamada lista_inventos_tempranos con nombres de inventos hipotéticos de Joy. Luego, el ciclo for itera sobre cada elemento de esta lista, asignando cada invento a la variable invento en cada iteración, y finalmente imprime una frase indicando que Joy ideó ese invento.
Ejercicio 2: Los Obstáculos en la Venta del Trapeador
import random

# Inicio del Ejercicio 2
numero_de_tiendas = 10
rechazos = 0

# Inicio del ciclo for
for intento in range(1, numero_de_tiendas + 1):
    # Inicio del bloque de código dentro del ciclo for
    resultado = random.choice(["rechazado", "aceptado"]) # Simula la respuesta de la tienda
    # Inicio de la estructura condicional if
    if resultado == "rechazado":
        # Inicio del bloque de código dentro del if
        rechazos += 1
        print(f"Intento {intento}: La tienda rechazó el trapeador.")
        # Fin del bloque de código dentro del if
    else:
        # Inicio del bloque de código dentro del else
        print(f"Intento {intento}: ¡La tienda aceptó el trapeador!")
        # En este punto, podríamos detener el ciclo si queremos simular que Joy se detiene al conseguir una venta.
        break # Detiene la ejecución del ciclo for
        # Fin del bloque de código dentro del else
    # Fin de la estructura condicional if
# Fin del ciclo for

print(f"Joy enfrentó {rechazos} rechazos antes de (hipotéticamente) lograr una aceptación.")

# Fin del Ejercicio 2
•
Explicación: Este código simula los intentos de Joy por vender su trapeador en 10 tiendas. Utiliza la función random.choice() para simular si cada tienda acepta o rechaza el producto. Se cuenta el número de rechazos. El uso de break dentro del else simula que Joy dejaría de intentar vender si una tienda acepta su producto.
Ejercicio 3: Las Llamadas Durante la Demostración en TV
import random

# Inicio del Ejercicio 3
duracion_segmento_minutos = 5
total_llamadas = 0

# Inicio del ciclo for
for minuto in range(1, duracion_segmento_minutos + 1):
    # Inicio del bloque de código dentro del ciclo for
    llamadas_en_este_minuto = random.randint(5000, 15000) # Simula un número variable de llamadas por minuto
    print(f"Minuto {minuto}: Recibidas {llamadas_en_este_minuto} llamadas.")
    total_llamadas += llamadas_en_este_minuto
    # Fin del bloque de código dentro del ciclo for
# Fin del ciclo for

print(f"Total de llamadas recibidas durante el segmento: {total_llamadas}")

# Fin del Ejercicio 3
•
Explicación: Este ejemplo simula las llamadas recibidas durante un segmento de televisión de 5 minutos. En cada minuto (cada iteración del ciclo for), se genera un número aleatorio de llamadas entre 5000 y 15000 y se suma al total_llamadas.
Ejercicio 4: El Aumento de Pedidos en Navidad (Hipotético)
# Inicio del Ejercicio 4
incrementos_por_aparicion = 
total_pedidos_adicionales = 0
numero_de_aparicion = 1

# Inicio del ciclo for
for incremento in incrementos_por_aparicion:
    # Inicio del bloque de código dentro del ciclo for
    print(f"Después de la aparición #{numero_de_aparicion}, los pedidos aumentaron en {incremento}.")
    total_pedidos_adicionales += incremento
    numero_de_aparicion += 1
    # Fin del bloque de código dentro del ciclo for
# Fin del ciclo for

print(f"El aumento total de pedidos después de las apariciones fue de: {total_pedidos_adicionales}")

# Fin del Ejercicio 4
•
Explicación: Este código simula el aumento de pedidos después de 3 apariciones de Joy en televisión. El ciclo for itera a través de la lista incrementos_por_aparicion, y en cada iteración suma el incremento correspondiente al total_pedidos_adicionales.
Ejercicio 5: Iteraciones en la Mejora del Diseño (Hipotético)
# Inicio del Ejercicio 5
numero_de_rondas_mejora = 4

# Inicio del ciclo for
for ronda in range(1, numero_de_rondas_mejora + 1):
    # Inicio del bloque de código dentro del ciclo for
    print(f"Joy está en la ronda de mejora número: {ronda} del diseño del trapeador.")
    # Aquí podrían ir acciones específicas de mejora en cada ronda (que podríamos detallar más en otro ejercicio).
    # Fin del bloque de código dentro del ciclo for
# Fin del ciclo for

print(f"El diseño del trapeador pasó por {numero_de_rondas_mejora} rondas principales de mejora.")

# Fin del Ejercicio 5
•
Explicación: Este ejemplo simula 4 rondas de mejora en el diseño del trapeador. El ciclo for itera 4 veces utilizando la función range(), y en cada iteración imprime el número de la ronda actual.
