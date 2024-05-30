# Příprava prostředí
    sudo apt update
    sudo apt install python3 python3-pip
    python3 -m venv homeassistant-venv
    source homeassistant-venv/bin/activate

### Instalace Home Assistant Core
    pip install homeassistant

### Klonování repozitáře
    git clone https://github.com/home-assistant/core.git
    cd core

### Instalace závislostí pro vývoj
    pip install -r requirements_test.txt

### Použití skriptu scaffold pro vytvoření nové integrace
    python3 -m script.scaffold integration

### Spuštění Home Assistant Core
    hass
