
# Obligatorio 2025

## #Equipo Bastion Centos
Instalar git

```bash
  sudo dnf install git
```
Copiamos el repositorio

```bash
  git clone https://github.com/octavioadm/Obligatorio2025.git
```
Editar archivo inventory.ini
modificando el valor de las variables ansible_host y ansible_user segun IP y usuario de equipo destino

```bash
  sudo vi Obligatorio2025/inventories/inventory.ini
```

Instalar Ansible Core

```bash
  sudo dnf install -y ansible-core
```

Instalar requerimientos para playbook

```bash
  ansible-galaxy install -r Obligatorio2025/collections/requirements.yaml
```
Crear clave publica / privada para conexion SSH

```bash
  ssh-keygen
  ssh-copy-id + IP_Host_Destino
```

Ejecutar playbook nfs_setup.yml desde el directorio "Obligatorio2025"
```bash
  ansible-playbook playbooks/nfs_setup.yml -K
```

Ejecutar playbook hardening.yml desde el directorio "Obligatorio2025"
```bash
  ansible-playbook playbooks/hardening.yml -K
```


## Authors

- [@octavio y Micaela](https://www.github.com/octavioadm/Obligatorio2025)
