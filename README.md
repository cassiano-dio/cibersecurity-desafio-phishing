# Phishing para captura de senhas do Instagram

### Ferramentas

- Kali Linux
- setoolkit

### Conteúdos revisados para esta atividade:
- Sistemas Operacionais (Kali)
- Definição de Phishing
- Git (Fork, comandos para subir um projeto)

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: (https://www.instagram.com/)

### Resutados

1) Credenciais roubadas do instagram:

![Crendenciais instagram](https://github.com/user-attachments/assets/a10260d9-7b96-4c5e-8225-bf9971986b76)

### Algumas conclusões

1) Alguns testes foram realizados com sites com login na landing page e sites com redirecionamento para a página de login.
   O ataque funciona com páginas cujo login é realizado na landing page, como facebook e instagram. Em páginas com redirecionamento,
   como gmail e badoo, o glitch redireciona para a página correta. Uma possível forma de exploração seria forçar o site original
   a redirecionar para o login falso, como em um spoofing.

2) Os clones não foram perfeitos. O mais fiel foi o do instagram, mas ao realizar o clone com a página do badoo, haviam diferenças
   grandes no estilo da fonte e no tamanho dos botões. Notar essas diferenças pode ajudar a evitar golpes:
   
Página clonada do site Badoo: 
![Badoo clonado](https://github.com/user-attachments/assets/b08e7324-3dbf-4bf6-8f27-64db9e98af88)


Página original do site Badoo:
![Badoo verdadeiro](https://github.com/user-attachments/assets/7c6b19e3-322c-473f-a93d-fc68747dc933)

Página clonada do Instagram:
![Instagram clonado](https://github.com/user-attachments/assets/4fe163de-a138-468e-96ad-b6df7d8d3f9a)

Página original do Instagram:
![Instagram original](https://github.com/user-attachments/assets/b7cf3f2e-5c82-4269-b96d-c7f83234a9b3)

