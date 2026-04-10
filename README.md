# ⚠️ MALWARE EXPANDER (SCRIPT EDUCATIVO)

## 🧪 Descripción

Este script fue desarrollado **con fines estrictamente educativos** para demostrar cómo un programa puede generar carga útil (payload) de forma exponencial, simulando comportamientos de expansión de datos como los que podrían encontrarse en entornos controlados de pruebas de estrés, análisis de malware o investigación de seguridad informática.

El script escribe repetitivamente en un archivo `.txt` grandes volúmenes de datos aleatorios, texto repetitivo, hashes, Base64, y bloques hexadecimales, multiplicando su tamaño rápidamente.

**Característica clave:** La palabra `Expander` se multiplica por 64 desde el inicio (`Expander` → `ExpanderExpander`), y luego se repite aleatoriamente para generar archivos de gran tamaño.

---

## ⚠️ ADVERTENCIA IMPORTANTE

> **Este script no es malware real**, pero su comportamiento puede ser detectado por antivirus o sistemas de monitoreo como actividad sospechosa.
>
> - No lo ejecutes en sistemas que no sean de tu propiedad.
> - No lo uses para dañar, saturar discos duros ajenos o con fines maliciosos.
> - El mal uso de este script puede violar leyes de protección de datos y sistemas informáticos.
> - El autor no se hace responsable del uso indebido que se le dé a este material.

**SI NO ENTIENDES LO QUE HACE, NO LO EJECUTES.**

---

## 🚀 Comportamiento

- Genera un archivo `malware_expander.txt`
- Escribe líneas continuamente hasta que se presiona `Enter`
- La palabra `Expander` se duplica al inicio (`Expander` * 64)
- Incluye:
  - Texto repetitivo `ExpanderExpander...` multiplicado aleatoriamente
  - Bloques hexadecimales
  - Cadenas en Base64
  - Hash SHA256
  - Bytes aleatorios
  - Checkpoints con datos masivos

---

## 🖥️ Requisitos

- Python 3.6+
- Módulos estándar (no requiere instalación adicional)

---

## 📦 Instalación

No requiere dependencias externas. Solo necesitas Python 3.6 o superior.

```bash
# Verificar que tengas Python instalado
python --version

# Clonar el repositorio (opcional)
git clone https://github.com/iTzDarkoPvP/Expander.git
cd Expander

# Ejecutar el script
python Expander.py
