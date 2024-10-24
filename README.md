# 𝘾𝙤𝙢𝙤 𝙚𝙣𝙫𝙞𝙖𝙧 𝙞𝙢𝙖𝙜𝙚𝙣𝙨 𝙥𝙖𝙧𝙖 𝙤 𝙙𝙤𝙘𝙠𝙚𝙧 𝙝𝙪𝙗 🧑‍💻 🐋 

## 𝘿𝙤𝙘𝙠𝙚𝙧 𝙃𝙪𝙗 é um serviço de registro (repository) para imagens Docker. Ele funciona como um repositório centralizado onde desenvolvedores e equipes podem armazenar, compartilhar e gerenciar imagens Docker.

## 𝙋𝙧𝙞𝙣𝙘𝙞𝙥𝙖𝙞𝙨 𝙁𝙪𝙣𝙘𝙞𝙤𝙣𝙖𝙡𝙞𝙙𝙖𝙙𝙚𝙨

𝘼𝙧𝙢𝙖𝙯𝙚𝙣𝙖𝙢𝙚𝙣𝙩𝙤 𝙙𝙚 𝙄𝙢𝙖𝙜𝙚𝙣𝙨:
Permite que usuários armazenem imagens Docker que podem ser usadas para criar containers.

𝘾𝙤𝙢𝙥𝙖𝙧𝙩𝙞𝙡𝙝𝙖𝙢𝙚𝙣𝙩𝙤: Facilita o compartilhamento de imagens entre desenvolvedores e equipes, permitindo que outros baixem e utilizem as imagens que você criou.

𝙄𝙢𝙖𝙜𝙚𝙣𝙨 𝙊𝙛𝙞𝙘𝙞𝙖𝙞𝙨: O Docker Hub possui uma coleção de "imagens oficiais", que são mantidas pela comunidade e pela Docker, garantindo que são confiáveis e seguras.

𝘼𝙪𝙩𝙤𝙢𝙖𝙘̧𝙖̃𝙤: Suporta a automação de builds, onde você pode configurar o Docker Hub para construir imagens automaticamente a partir de um repositório GitHub ou Bitbucket.

𝙂𝙚𝙧𝙚𝙣𝙘𝙞𝙖𝙢𝙚𝙣𝙩𝙤 𝙙𝙚 𝙑𝙚𝙧𝙨𝙞𝙤𝙣𝙖𝙢𝙚𝙣𝙩𝙤: Permite versionar suas imagens, utilizando tags para identificar diferentes versões de uma mesma imagem.

𝘾𝙤𝙣𝙩𝙧𝙤𝙡𝙚 𝙙𝙚 𝘼𝙘𝙚𝙨𝙨𝙤: Oferece a capacidade de criar repositórios públicos (acessíveis a todos) ou privados (acessíveis apenas a usuários autorizados).

𝘾𝙤𝙡𝙖𝙗𝙤𝙧𝙖𝙘̧𝙖̃𝙤: Facilita a colaboração entre equipes, permitindo que múltiplos usuários tenham acesso às mesmas imagens.

Como Funciona

Cadastro: Para usar o Docker Hub, você precisa criar uma conta.



Login: Você faz login no Docker Hub pelo terminal usando o comando docker login.



Push e Pull: Você pode enviar suas imagens para o Docker Hub com o comando docker push e baixar imagens com docker pull.

𝙀𝙣𝙫𝙞𝙖𝙧  𝙄𝙢𝙖𝙜𝙚𝙢 𝙥𝙖𝙧𝙖 𝙤 𝘿𝙤𝙘𝙠𝙚𝙧 𝙃𝙪𝙗:

Crie uma Conta no Docker Hub  : https://hub.docker.com/

Faça Login no Docker Hub

No terminal, faça login usando o comando:
```bash
docker login
```
.Insira seu nome de usuário e senha.

Marque a Imagem que Deseja Enviar

Use o comando docker tag para adicionar uma tag à sua imagem:
```bash
docker tag <IMAGE_ID> <USERNAME>/<REPOSITORY>:<TAG>
```
Envie a Imagem para o Docker Hub

Utilize o comando docker push para enviar a imagem:
```bash
docker push <USERNAME>/<REPOSITORY>:<TAG>
```
Baixar uma Imagem do Docker Hub

Use o Comando docker pull

Para baixar a imagem, execute:
```bash
docker pull <USERNAME>/<REPOSITORY>:<TAG>
```
Verifique se a Imagem Foi Baixada

Use o comando a seguir para listar as imagens locais:
```bash
docker images
```
Enviando  imagem Docker 

![dk11](https://github.com/user-attachments/assets/cc9509ab-42fc-4aa0-8152-2fa7f305044c)



Baixando imagem Docker
![dk13](https://github.com/user-attachments/assets/3bc0e5b7-ee6e-46eb-9820-5edf1708fe14)



Docker Hub

![dk14](https://github.com/user-attachments/assets/ad340d6f-7c99-45c9-b87e-6ecd084e5427)


Imagem 
![docker12](https://github.com/user-attachments/assets/389501e7-10d2-4975-b263-1cba7113dd1f)

![docker13](https://github.com/user-attachments/assets/dd8198c5-30c3-4ca3-b81e-1935309503f5)
