# Desafio de Phishing Santander Cibersegurança
### Ferramentas

- Kali Linux
- setoolkit
- VM Virtual Box
- Windows XP - Internet Explorer

No meu navegador não foi possível coletar os dados, alguma opção de segurança (que eu não sei ainda qual seria exatamente,
ou muito provavelmente é um conjunto de proteções) impedia o SEtoolkit de capturar as entradas na página. 

Tentei em modo privado no navegador, tentei desligando antivírus, fireall, proteções do Chrome, ainda sem resultado. 
Testei em outros navegadores (FireFox, Edge), o problema continuava.

No meu sistema operacional, não houve jeito. 
No Kali Linux mesmos resultados não importa o que eu fizesse.

Minha resolução para conseguir o resultado final foi:

Máquina virtual rodando WindowsXP (O mesmo disponibilizado pelo professor Cassio no próprio curso)
Interner Explorer (bem desatualizado, a página não conseguir carregar nem o CSS, só o HTML com os campos de entrada de texto)
aí sim, o Kali Linux realmente conseguiu capturar o email de login e a senha utilizados na página gerada pelo SEtoolkit. 

### Configurando o Phishing no Kali Linux

-atualização de todo o SO Kali
-atualização dos pacotes de Python
- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com
- acesso ao site clonado através de máquina virtual rodando WinXP (modo de rede Bridge)
- Internet Explorer 

### Resutados

![desafio de phishing](https://github.com/DanyBC/cibersecurity-desafio-phishing/assets/119118430/3cceef1a-ddff-4717-8913-de0bfd7380eb)
