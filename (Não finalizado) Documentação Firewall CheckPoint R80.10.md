# FIREWALL CHECKPOINT R80.10

![bannerr801705160645 10-2](https://user-images.githubusercontent.com/26627633/45485223-2f504080-b72d-11e8-987c-e7e4ac897e52.png)

# Sistemas operacionais e softwares utilizados: 
- **Windows 7**
- **Check_Point_R80.10_T462_Gaia**
- **Check_Point_SmartConsole_R80_10_jumbo_HF_B056_Win**
- **Oracle VM VirtualBox 5.2.18 r124319 (Qt5.6.2)**

## Instalação do Security Gateway:
- **1° Abrir o Oracle VM VirtualBox**
- **2° Criar uma nova maquina virtual**

![ps](https://user-images.githubusercontent.com/26627633/45486011-f9f92200-b72f-11e8-9dd5-e14691b1b2e3.png)

- **3° Defina o nome do seu Firewall de acordo com a sua preferencia**
- **4° Em 'Tipo' selecione 'Other'**
- **5° Em 'Versão' selecione 'Other/Unknown (64-bit)**

![ps2](https://user-images.githubusercontent.com/26627633/45486497-b1daff00-b731-11e8-9ab3-308c5aaa53b4.png)

- **6° Em 'tamanho da memória', trabalhamos com 2GB (2048Mb) mas o recomendado seria 4GB (4096Mb)!**

![ps3](https://user-images.githubusercontent.com/26627633/45486773-b05e0680-b732-11e8-8982-e7e5f0bd5a58.png)

- **7° Em 'Disco rígido' podemos manter a opção 'Criar um novo disco virtual agora'**

![ps4](https://user-images.githubusercontent.com/26627633/45487053-878a4100-b733-11e8-91d0-fe76720fb9b7.png)

- **8° Em 'Tipo de arquivo de disco rígido' vamos utilizar o modelo VMDK (Virtual Machine Disk) por conta da sua flexibilidade** 

![ps5](https://user-images.githubusercontent.com/26627633/45487480-d4bae280-b734-11e8-82df-85cf2d199652.png)

- **9° Em 'Armazenamento em disco rígido físico' podemos manter o 'Dinamincamente alocado'**

![ps6](https://user-images.githubusercontent.com/26627633/45487622-527eee00-b735-11e8-9810-9efe5980f64a.png)

- **10° Em 'Localização e tamanho do arquivo' vamos definir 50GB de armazenamento**

![ps7](https://user-images.githubusercontent.com/26627633/45488010-6b3bd380-b736-11e8-91a6-6d9cf5f62b74.png)

- **11° Com a maquina criada, vamos ir as configurações da própria**

![ps8](https://user-images.githubusercontent.com/26627633/45488162-e1403a80-b736-11e8-8137-65207853bffe.png)

- **12° Para o checkpoint R80.10 trabalhar tranquilamente é necessario que ele tenha 2 Processadores. Para isso, vamos até a aba 'Sistema' em seguida vamos nos direcionar a aba 'Processador', assim conseguimos adicionar nosso segundo processador**

![ps9](https://user-images.githubusercontent.com/26627633/45488582-3892da80-b738-11e8-867e-9d273bf3e517.png)

- **13° Agora vamos na aba 'Armazenamento' para podermos colocar nosso Sistema Operacional que esta no formato '.ISO'. Para isso, vamos clicar no ícone do CD escrito 'Vazio', em seguida vamos clicar no ícone de um CD, que está ao lado de 'IDE Secundário Master'**

![ps10](https://user-images.githubusercontent.com/26627633/45489117-ce7b3500-b739-11e8-8ee5-48c1f299fc4f.png)

- **14° Agora vamos selecionar a .iso que será utilizada como nosso Sistema Operacional**

![ps11](https://user-images.githubusercontent.com/26627633/45489377-74c73a80-b73a-11e8-9e42-e92fffcd2ba0.png)

- **15° O proximo passo é a criação da nossa rede NAT. Para isso teremos que ir até as preferencias do Oracle VM VirtualBox**

![ps12](https://user-images.githubusercontent.com/26627633/45489681-47c75780-b73b-11e8-9c65-56609502f749.png)

- **16° Dentro das preferencias, vamos na aba 'Rede' e clicar no ícone de uma placa de rede com o símbolo de mais**

![ps13](https://user-images.githubusercontent.com/26627633/45489981-48acb900-b73c-11e8-8946-96646490c020.png)

- **17° Com a rede criada, vamos dar um duplo clique em cima de 'NatNetwork'. Vamos definir o 'Nome da Rede' como 'CP R80.10' e em 'CIDR  da Rede', vamos definir nosso range de IP´s de acordo com a rede: 172.16.20.0/24, assim podendo finalizar a criação da nossa Rede NAT**

![ps14](https://user-images.githubusercontent.com/26627633/45490811-7d217480-b73e-11e8-93e2-b1f63f1e2846.png)







