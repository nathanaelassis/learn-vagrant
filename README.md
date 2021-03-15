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
<p>```vagrant init``` - Criar vagranfile.</p>
<p>```vagrant up``` - Iniciar VM.</p>
<p>```vagrant status``` - Status VM.</p>
<p>```vagrant ssh``` - Conectar via SSH.</p>
<p>```vagrant halt``` - Desligar VM.</p>
<p>```vagrant destroy``` - Apagar VM.</p>
<p>```vagrant provision``` - Rodar provision.</p>
<p>```vagrant box list``` - Listar boxes.</p>
<p>```vagrant --help``` - Obter ajuda.</p>
