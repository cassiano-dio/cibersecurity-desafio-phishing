# Phishing para captura de senhas do Facebook

### Ferramentas:

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux:

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Custom Import ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutado Esperado

![Alt text](./passwd.png "Optional title")

### Resultado Obtido 

![Alt text](./passwd2.PNG.png "Optional title")

# Obs: Foi necessario salvar a pagina html do facebook, e logo após editar o html apagando o script que estava bloqueando a visualização de senhas por meio do setoolkit, por conta disso não foi possivel utilizar o Método de ataque: Site Cloner
