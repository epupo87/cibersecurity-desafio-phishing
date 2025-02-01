# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurar a ferramenta setoolkit para criar uma cópia de uma pagina de uma conhecida rede social, com o objetivo de capturar as credenciais de um usuário hipotético.

### Configurando a ferramenta setoolkit para realizar ataque de Phishing no Kali Linux

- Acessar o terminal
- Acessar como usuário root por meio do comando: ``` sudo su ```
- Iniciazilar a ferramenta setoolkit com o comando: ``` setoolkit ```
- Selecionar o tipo de ataque por meio da opção número 1: ``` Social-Engineering Attacks ```
- Selecionar o Vetor de ataque por meio da opção número 2: ``` Web Site Attack Vectors ```
- Selecionar o Método de ataque por meio da opção 3 (que em uma explicação meio grosseira seria algo como realizar a "coleta" das credenciais do usuário: ```Credential Harvester Attack Method ```
- Selecionar o Método de ataque por meio da opção 2, objetivando criar uma cópia do site que será utilizado para realizar a coleta das credenciais de usuário: ``` Site Cloner ```
- Obter o endereço da máquina - necessário endereçar para a ferramenta para onde as informações coletadas deverão ser enviadas. A ferramenta buscou a informação automaticamente. Caso isso não fosse possível, as informações poderiam ser obtidas mediante a inserção do comando: ``` ifconfig ```
- Informar URL da página que será clonada: http://www.facebook.com

### Resutados

Como era de se esperar, o resultado foi a captura das credenciais do usuário, sendo as mesmas enviadas diretamente para o servidor configurado na máquina Kali, pela ferramenta setoolkit.
