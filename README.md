# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- Qualquer navegador antigo , no exemplo usei o IE 8.Atualmente existem diversas melhorias com relação a segurança nos browsers, dentre ela o CORS
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![Alt text](./clone-site-acessivel-por-outra-maquina.png "Optional title")
![Alt text](./credenciais_recebidas.png "Optional title")
![Alt text](./credencias-obtidas-pelo-midlleware.png "Optional title")