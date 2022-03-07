# WebRTC-PJI2

Amostra da transmissão de vídeo e áudio funcionando por WebRTC.
Aplicação encontrada em https://github.com/TannerGabriel/WebRTC-Video-Broadcast , adaptada pelo grupo.

## Iniciando o container:

```bash
docker build --tag webrtcvideobroadcast .

docker run -d -p 4000:4000 webrtcvideobroadcast
```

## Iniciando a aplicação:

No servidor:
```bash
Entrar em localhost:4000/broadcast.html para iniciar a transmissão
```

No cliente:
```bash
Entrar em localhost:4000 para ver a imagem transmitida
```