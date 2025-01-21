# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Preparando o site

- Abra o Facebook
- Salve o site completo
- Altere o nome do arquivo html para index.html (o setoolkit usa ele como padrão)
- Procure onde esta o script de criptografia e exclua ele
- copie o caminho da pasta e ao inves de colocar o site coloque ele

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ``` (opção 1)
- Vetor de ataque: ``` Web Site Attack Vectors ``` (opção 2)
- Método de ataque: ```Credential Harvester Attack Method ``` (opção 3)
- Método de ataque: ``` Custom Import ``` (opção 3)
- Informe o endereço IP da máquina: ``` ifconfig ```
- URL para clone: https://www.facebook.com
