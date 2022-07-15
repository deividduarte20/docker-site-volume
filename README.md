# Dockerfile que provisiona um container com o apache2 e um site de exemplo

## Requisitos

| git | docker |
|-----|--------|

## Primeiro clone este repositório

git clone https://github.com/deividduarte20/docker-site-volume.git

## Acesse o diretório

cd docker-site-volume/

## Build a imagem

docker image build -t nome_de_sua_escolha:1.0 .

## Subir o container

docker run -dti -p 80:80 nome_escolhido_etapa_antereior:1.0
