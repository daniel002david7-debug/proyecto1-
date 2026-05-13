# Sistema Integral de Gestión de Clientes, Servicios y Reservas

## 📌 Descripción
Este proyecto fue desarrollado por un equipo de cinco estudiantes de Ingeniería de Sistemas para la empresa ficticia **Software FJ**.  
El objetivo es construir una aplicación **orientada a objetos**, modular y extensible, capaz de gestionar clientes, servicios y reservas sin el uso de bases de datos.  
Toda la información se maneja mediante **objetos, listas internas y archivos de logs** para registrar eventos y errores.

---

## 🎯 Objetivos
- Implementar rigurosamente los principios de **abstracción, herencia, polimorfismo, encapsulación**.  
- Manejar excepciones avanzadas con bloques `try/except`, `try/except/else`, `try/except/finally` y excepciones personalizadas.  
- Garantizar que el sistema siga funcionando aun cuando ocurran errores.  
- Simular al menos 10 operaciones completas (válidas e inválidas).  

---

## 🧩 Arquitectura del sistema
- **Clase abstracta Entidad**: Representa elementos generales del sistema.  
- **Clase Cliente**: Encapsula datos personales y valida información.  
- **Clase abstracta Servicio**: Base para servicios especializados.  
  - `ReservaSala`  
  - `AlquilerEquipo`  
  - `AsesoriaEspecializada`  
- **Clase Reserva**: Integra cliente, servicio, duración y estado.  
- **Archivo de logs**: Registra errores y eventos relevantes.  

---

## ⚙️ Requisitos
- Python 3.10 o superior  
- Editor de código (VS Code, PyCharm, etc.)  
- Cuenta en GitHub para clonar y colaborar en el repositorio  

---


