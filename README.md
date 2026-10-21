# FitControl - Sistema de Gestion de Gimnasio

Proyecto Final - Algoritmos y Estructuras de Datos - Elizabeth Quiroz - Cibertec

**Pagina para ejecutar:** https://elizabeth120109.github.io/fitcontrol/

## Instrucciones

1. Tener **Java 8** instalado (incluye Java Web Start): https://www.java.com/es/download/
2. Agregar el sitio a la lista de excepciones (solo la primera vez):
   **Configurar Java** > **Seguridad** > **Editar lista de sitios** > **Agregar** > `https://elizabeth120109.github.io` > **Aceptar**.
3. Abrir https://elizabeth120109.github.io/fitcontrol/ y hacer clic en **Ejecutar FitControl (JNLP)**, o desde CMD:
   ```
   javaws https://elizabeth120109.github.io/fitcontrol/fitcontrol.jnlp
   ```
4. En el aviso de seguridad, marcar **"Acepto el riesgo"** > **Ejecutar**.

La aplicacion abre con datos de ejemplo (socios, planes, membresias y suspensiones).

## Si algo falla

- **"Aplicacion bloqueada por la seguridad de Java"**: falta el paso 2.
- **Abre una version antigua o da error**: ejecutar `javaws -uninstall` en CMD y volver a intentar.
- **"javaws" no se reconoce**: instalar Java 8 (Java 11+ ya no incluye Java Web Start).

## Detalles tecnicos

- Compilado para Java 8. JAR firmado con certificado propio.
- Datos guardados en archivos `.txt`.
- Modulos: Mantenimiento (Socios, Planes), Registro (Membresias, Suspensiones), Consultas y Reportes.
