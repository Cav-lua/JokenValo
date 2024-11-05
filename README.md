# **Jokenpo App**

> Um aplicativo Android para jogar Jokenpo (Pedra, Papel e Tesoura) contra o computador.

## 📱 Descrição

O **Jokenpo App** permite ao usuário jogar o clássico jogo de Pedra, Papel e Tesoura contra um oponente controlado pelo computador.
O aplicativo mantém um placar das vitórias do jogador e do aplicativo, oferecendo uma experiência divertida e interativa.

## 🔧 Funcionalidades

- [x] Seleção de opções (Pedra, Papel e Tesoura)
- [x] Cálculo do resultado da partida
- [x] Exibição do resultado com mensagens personalizadas
- [x] Placar que acompanha as vitórias do jogador e do aplicativo
- [x] Interface simples e intuitiva

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView** e **ImageView** para entrada e exibição de dados
- [x] **Button** para interações do usuário

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:

    ```bash
    git clone https://github.com/Cav-lua/jokenpo-app.git
    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java/com/example/jokenpo
│   │   │   │   ├── MainActivity.java      # Atividade principal com a lógica do jogo
│   │   │   ├── res
│   │   │   │   ├── layout
│   │   │   │   │   ├── activity_main.xml   # Layout da tela principal
│   │   │   │   └── drawable
│   │   │   │       ├── pedra.png           # Imagem de Pedra
│   │   │   │       ├── papel.png           # Imagem de Papel
│   │   │   │       └── tesoura.png         # Imagem de Tesoura
│   │   │   └── values
│   │   │       ├── strings.xml             # Strings usadas no app
│   │   │       ├── colors.xml              # Cores definidas no projeto
│   └── build.gradle                          # Configuração do Gradle
└── README.md                                 # Este arquivo
```
🎨 Design e Prototipagem
A interface do app foi criada usando ConstraintLayout para garantir responsividade em diferentes tamanhos de tela.
O design é minimalista e focado na usabilidade, proporcionando uma experiência intuitiva ao jogador.

🖥️ Telas do Aplicativo
Tela Principal
Na tela principal, o usuário pode escolher entre Pedra, Papel e Tesoura, e o resultado da partida é exibido, junto com o placar atualizado.

![Captura de tela 2024-11-05 014637](https://github.com/user-attachments/assets/b1f5a92f-8336-4c97-8eea-e505dd229c38)


👨‍💻 Desenvolvedores
Cav-lua - Desenvolvedor - GitHub

📄 Licença
Este projeto está licenciado sob a MIT License.
