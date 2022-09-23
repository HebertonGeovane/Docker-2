# container_imc_js

## O projeto consiste em provisionar container com aplicação em javascript com calculadora imc

### Buildar imagem
docker build -t nome_image_sua_escolha .

### Executar container
docker run -dti -p 8080:80 nome_image_sua_escolha

### Acesse a aplicação web
localhost:8080