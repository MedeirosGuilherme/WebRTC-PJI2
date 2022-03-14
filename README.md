# WebRTC com Firebase - PJI2

Transmissão de vídeo e áudio por WebRTC com Firebase.
Aplicação encontrada em https://webrtc.org/getting-started/firebase-rtc-codelab e https://github.com/webrtc/FirebaseRTC , adaptada pelo grupo.

## Passo a passo:

Certifique-se de que você tenha o Node.js instalado. Caso não tenha, poderá baixá-lo em: https://nodejs.org

### Firebase:

Acesse: https://firebase.google.com

Clique em:
1: "Go to console"
2: "Create a project"
3: Insira o nome do projeto
4: "continue"
5: "continue"
6: Selecione "Default account for Firebase"
7: "Create project"
8: "Firestone Database"
9: "Start in test mode"
10: "Next"
11: "Enable"
12: "Enable"
13: Clone o seguinte repositório com o comando:
```bash
git clone https://github.com/webrtc/FirebaseRTC
```
14: Entre no repositório:
```bash
cd FirebaseRTC
```
15: Instale a interface de linha de comando do Firebase (cogite utilizar "sudo" antes do comando)
```bash
npm -g install firebase-tools
```
16: Verifique se versão do Firebase CLI é v6.7.1 ou maior
```bash
firebase --version
```
17: Autorize o Firebase:
```bash
firebase login
```
18: No site Firebase clique em "Realtime Database"
19: "Create database"
20: "Next"
21: "Start in test mode"
22: "Enable"
23: Associe a aplicação ao projeto Firebase:
```bash
firebase use --add
```
24: Selecione o ID que você acabou de criar nos passos anteriores
25: Escreva um alias ao seu projeto, por exemplo, "default"
26: Hospede com o Firebase:
```bash
firebase deploy
```
27: Pronto, esse comando disponibilizou a url para ser utilizada

