# FestiDAW
El festival de música FestiDAM va a implantar un sistema informático centralizado para controlar las taquillas de acceso, la emisión y recarga de pulseras Cashless (pago sin contacto), el control de aforo por escenarios, la venta en barras con cálculo de cambio en efectivo y el cierre económico de la jornada con devolución de saldo no consumido.


**Código base**

```
Algoritmo FestiDAM_Master
	
	// =========================================================================
	// DECLARACIÓN E INICIALIZACIÓN DE VARIABLES GLOBALES
	// =========================================================================
	Definir aforoFestival, aforoMaximoRecinto, pulserasActivas Como Entero
	Definir recaudacionEntradas, recaudacionCashless, recaudacionBarras Como Real
	Definir alertaAforoCritico Como Logico
	Definir opcionMenu Como Entero
	
	// Valores iniciales según plantilla maestra
	aforoFestival <- 0
	aforoMaximoRecinto <- 100
	recaudacionEntradas <- 0.0
	recaudacionCashless <- 0.0
	recaudacionBarras <- 0.0
	pulserasActivas <- 0
	alertaAforoCritico <- Falso
	
	// =========================================================================
	// BUCLE PRINCIPAL DE NAVEGACIÓN Y MENÚ
	// =========================================================================
	Repetir
		Escribir ""
		Escribir "=================================================="
		Escribir "     SISTEMA DE GESTIÓN CENTRALIZADA FESTIDAM     "
		Escribir "=================================================="
		Escribir "1. Taquilla, Abonos y Control de Acceso"
		Escribir "2. Recarga de Pulseras Cashless"
		Escribir "3. Control de Aforo y Alerta VIP"
		Escribir "4. TPV de Barras y Consumiciones"
		Escribir "5. Cierre de Jornada y Devolución Cashless"
		Escribir "0. Salir del programa"
		Escribir "--------------------------------------------------"
		Escribir "Seleccione una opción (0-5):"
		Leer opcionMenu
		Escribir ""
		
		Segun opcionMenu Hacer
			1:
				// TODO: [Issue #2] Implementado por Developer 1
				Escribir "[PENDIENTE] Caso 1 no integrado. Esperando revisión."
			2:
				// TODO: [Issue #2] Implementado por Developer 1
				Escribir "[PENDIENTE] Caso 1 no integrado. Esperando revisión."	
			3:
				// TODO: [Issue #2] Implementado por Developer 1
				Escribir "[PENDIENTE] Caso 1 no integrado. Esperando revisión."
			4:
				// TODO: [Issue #2] Implementado por Developer 1
				Escribir "[PENDIENTE] Caso 1 no integrado. Esperando revisión."
			5:
				// TODO: [Issue #6] Implementado por Developer 5
				Escribir "[PENDIENTE] Caso 5 no integrado. Esperando revisión."
			0:
				Escribir "Cerrando el sistema FestiDAM... ¡Hasta pronto!"
			De Otro Modo:
				Escribir "[ERROR] Opción no válida. Valor entre 0 y 5."
		FinSegun	
	Hasta Que opcionMenu = 0
FinAlgoritmo

```
