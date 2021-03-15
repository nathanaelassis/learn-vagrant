# Learning Vagrant

## How to use?
Execute the commands below in cmd.

1. Run
```vagrant up```.
2. Run ```vagrant ssh mysqlserver```.
3. Run ```mysql -u atividade -p atividade -h 10.80.4.10```. The password is **atividade**.
4. Run ```select * from vets;``` and you'll see all results from the database.
## Prerequisite
- Vagrant
- Oracle Virtual Machine or other VM
## Essential Commands
```vagrant init``` - Criar vagranfile.
```vagrant up``` - Iniciar VM.
```vagrant status``` - Status VM.
```vagrant ssh``` - Conectar via SSH.
```vagrant halt``` - Desligar VM.
```vagrant destroy``` - Apagar VM.
```vagrant provision``` - Rodar provision.
```vagrant box list``` - Listar boxes.
```vagrant --help``` - Obter ajuda.
