# Configuración en MacOS y Linux

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
source .venv/bin/activate
source setup.sh
```

# Configuración en Windows

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
.venv\Scripts\activate
setup
```

# Ejecución de pruebas

Ejecute el siguiente comando en el terminal:

```bash
pytest
```

# Conectar al repositorio de la organización

```bash
git remote add origin https://github.com/ORGANIZACION/REPO.git
git add .
git commit -m "mensaje"
git pull --rebase origin main #solo la primera vez
git push origin main
```