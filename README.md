# Consulta de Carpatis del corregimiento la Reforma 🚌
        Resumen
El proyecto consiste en el diseño y desarrollo de un prototipo interactivo no funcional para un sistema de visualización de rutas del servicio de transporte informal conocido como Carpatis, utilizado por habitantes de zonas rurales y veredales. Su propósito es ofrecer una solución tecnológica que permita a los usuarios conocer, de manera visual y sencilla, la ubicación estimada del vehículo, los tiempos aproximados de llegada y el estado del recorrido, con el fin de reducir la incertidumbre, mejorar la seguridad y optimizar los tiempos de espera en los puntos de abordaje.

# Alcance Académico
Este prototipo se utiliza para:

- Validar conceptos de diseño UX/UI.
- Representar flujos para el análisis de requerimientos.
- Complementar la sustentación del proyecto tecnológico.
- Cumplir con los requisitos de la Fase 4 del curso.
- Simular la futura aplicación sin implementar funcionalidades reales.
  
  # Componentes principales del prototipo
El prototipo incluye una estructura modular donde cada pantalla cumple una función específica dentro del sistema:

        Pantalla de Inicio

Permite seleccionar el tipo de usuario:

- Usuario
- Conductor

        Pantalla de Mapa

Incluye:

- Mapa estatico de recorrido.
- Marcador simulando la ubicación del Carpatis
- Barra de búsqueda
- Botón de notificaciones
- Ruta estimada

        Pantalla de Notificaciones

Presenta alertas como:

- Tiempo estimado de llegada
- Cambio de estado del recorrido
- Finalización del trayecto

        Pantalla del Conductor

contiene elementos como:

- Botón “Iniciar recorrido”
- Botón “Finalizar recorrido”
- Indicador de estado
- Mensaje contextual simulado

        Pantalla de Configuración

Incluye:

- Selección de idioma (no funcional)
- Información de permisos (simulado)
- Sección de ayuda

        Estructura
  El prototipo sigue la siguiente estructura
  
          Pantalla Inicial
           ├── Usuario
           │     ├── Mapa
           │     │      ├── Notificaciones
           │     │      └── Configuración
           │     └── (Retornos hacia Mapa)
           └── Conductor
                 ├── Panel del Conductor
                 │      ├── Iniciar Recorrido (cambia estado)
                 │      ├── Finalizar Recorrido (cambia estado)
                 │      ├── Notificaciones
                 │      └── Configuración
                 └── (Retornos hacia Panel)
 # Naturaleza No Funcional ⚠️
 
         El prototipo no:

- Procesa datos reales.
- Se conecta a un sistema backend o GPS.
- Representa software operativo.
- Está listo para implementarse como producto.
- Toda interacción es simulada de acuerdo con el diseño previsto en Ninjamock.
    # Contacto 📬
- Autor: Wilfer Meneses
- Correo académico: wdmeneseso@unadvirtual.edu.co
- Correo Figma: w.d8912@gmail.com
