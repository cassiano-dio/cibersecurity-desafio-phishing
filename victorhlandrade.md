# Criado por: [Victor Andrade](https://linkedin.com/in/victorhlandrade).

## Profissional de Redes com Especialização em Cybersecurity.
Atualmente estou participando do Bootcamp de Cibersegurança do Santander provido pela [DIO](https://dio.me/).

## Conecte-se comigo: 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victorhlandrade/) 

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/victorhlandrade)

Em cumprimento ao desafio "Criação de um Phishing com Kali Linux", proposto pelo [professor Cassiano](https://github.com/cassiano-dio), abaixo deixo o passo a passo de como criar uma págnia falsa do Facebook.

## ⚙ Ferramenta Utilizada
- Social-Engineer Toolkit (SET)
Esta ferramenta já vem instalada no Kali Linux por padrão.

## 🗝 Pré-requisitos

- Sistema Kali instalado com a rede em modo Bridge-adapter.

## ▶ Let's Get Started!

### Iremos apresentar esse tutorial em um formato de passo a passo para ficar mais fácil compreender e termos sucesso no resultado final.

1. Com o Kali Linux já instalado e com a Interface no modo Bridge-adapter, confirma se o mesmo está com o endereço IP adequado e com acesso à Internet utilizando o comando Ping.

<p float="left">

 <img src="https://github.com/victorhlandrade/prints-lab-phishing-set/blob/main/0-Ping.PNG" width="400" />

</p>

2. Com o Kali conectado corretamente à Internet, iremos iniciar a ferramenta Social-Enginner Toolkit (SET) digitando o comando **setoolkit** no terminal como Root. Neste menu inicial iremos selecionar a opção 1 **Social-Engineering Attacks**.

<p float="left">

 <img src="https://github.com/victorhlandrade/prints-lab-phishing-set/blob/main/1-inicial.PNG" width="400" />

</p>

3. Agora iremos selecionar a opção 2 **Website Attack Vectors**.

<p float="left">

 <img src="https://github.com/victorhlandrade/prints-lab-phishing-set/blob/main/2-website-attack-vectors.PNG" width="400" />

</p>

4. Neste próximo passo selecionaremos a opção 3 **Credential Harvester Attack Method**.

<p float="left">

 <img src="https://github.com/victorhlandrade/prints-lab-phishing-set/blob/main/3-Credential-Harvester-Attack-Method.PNG" width="400" />

</p>

5. E agora selecionaremos a opção 2 **Site Cloner** para clonarmos o site do Facebok.

<p float="left">

 <img src="https://github.com/victorhlandrade/prints-lab-phishing-set/blob/main/4-Site-Cloner.PNG" width="400" />

</p>

6. Nessa tela iremos confirmar o IP da página fake que será acessada pela vítima. Digite enter para confirmar. E em seguida informe o site que deseja clonar: **http://www.facebook.com**.
Observer que precisa ser HTTP e não HTTPS.

<p float="left">

 <img src="https://github.com/victorhlandrade/prints-lab-phishing-set/blob/main/5-Confirma-IP.PNG" width="400" />

</p>

7. Agora podemos abrir a página falsa digitando http://ip-do-servidor.

<p float="left">

 <img src="https://github.com/victorhlandrade/prints-lab-phishing-set/blob/main/7-pagina-exibida.PNG" width="400" />

</p>

8. E após inserir as informações de login e senha, podemos ver essas informações capturadas no nosso Kali.

<p float="left">

 <img src="https://github.com/victorhlandrade/prints-lab-phishing-set/blob/main/8-Credentials.PNG" width="400" />

</p>

## 📚 Documentação
- [Documentação do Cassiano da DIO] (https://academiapme-my.sharepoint.com/:p:/g/personal/kawan_dio_me/EVC5IlsbPCRHqGmpWiJ6LpYBODplb07kU4SyM6y9p05zCA?e=dpSgnR)

# 🔍 Referências

- [Digital Innovation One] (https://www.dio.me/)
