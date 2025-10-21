## Crear y Activar un Entorno Virtual
Para aislar las dependencias del proyecto se crea un entorno virtual.

```bash
python -m venv venv
source venv/bin/activate # En Windows, usa: venv\Scripts\activate



python -c "import secrets; print(secrets.token_hex(32))"