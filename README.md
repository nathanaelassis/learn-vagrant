# Learning Vagrant

## How to use?
Execute the commands below in cmd.

1. Run
```vagrant up```.
2. Run ```vagrant ssh mysqlserver```.
3. Run ```mysql -u vagrant -p vagrant -h 10.80.4.10```. The password is **vagrant**.
4. Run ```select * from vets;``` and you'll see all results from the database.
## Prerequisite
- Vagrant
- Oracle Virtual Machine or other VM
## Essential Commands
```vagrant init``` - Criar vagranfile.</p>
```vagrant up``` - Iniciar VM.</p>
```vagrant status``` - Status VM.</p>
```vagrant ssh``` - Conectar via SSH.</p>
```vagrant halt``` - Desligar VM.</p>
```vagrant destroy``` - Apagar VM.</p>
```vagrant provision``` - Rodar provision.</p>
```vagrant box list``` - Listar boxes.</p>
```vagrant --help``` - Obter ajuda.</p>
