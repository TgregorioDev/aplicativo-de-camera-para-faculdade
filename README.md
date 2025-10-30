# 📸 Aplicativo de Câmera para Faculdade

### 📋 Descrição do Projeto

Este projeto consiste em um aplicativo móvel desenvolvido para demonstrar e utilizar as capacidades de acesso e manipulação de câmera em dispositivos móveis, como parte de um requisito acadêmico. O aplicativo permite ao usuário tirar fotos e, potencialmente, realizar outras operações básicas relacionadas a imagens e mídia.

É um projeto desenvolvido com tecnologias web modernas, empacotado para rodar de forma nativa em plataformas como Android, utilizando os recursos e plugins da plataforma Ionic/Capacitor.

### 🛠️ Tecnologias Utilizadas

O projeto é baseado no framework **Ionic** e **Angular**, utilizando o **Capacitor** como ponte para acesso a funcionalidades nativas do dispositivo.

* **Framework:** [Ionic](https://ionicframework.com/) (Frontend UI)
* **Linguagem Principal:** [TypeScript](https://www.typescriptlang.org/)
* **Estrutura:** [Angular](https://angular.io/)
* **Conteinerização/Nativo:** [Capacitor](https://capacitorjs.com/)
* **Estilização:** [SCSS (Sass)](https://sass-lang.com/)
* **Plataforma de Destino:** Android (presente na estrutura), podendo ser estendido para Web.

### ✨ Funcionalidades

As funcionalidades primárias esperadas para um aplicativo de câmera são:

* **Acesso à Câmera:** Capacidade de inicializar e controlar a câmera do dispositivo.
* **Captura de Foto:** Tirar fotos usando a câmera frontal ou traseira.
* **Visualização de Imagem:** Exibir a foto capturada dentro do aplicativo.
* **Galeria (Potencial):** Capacidade de acessar ou salvar a imagem na galeria do dispositivo.

***
> **Nota:** É recomendado que você adicione detalhes específicos sobre como a foto é processada, onde é salva (armazenamento local, temporário, etc.), e se há outras funcionalidades como filtros, edição ou compartilhamento.
***

### 🚀 Começando

Siga estas instruções para configurar e rodar o projeto em sua máquina local.

#### Pré-requisitos

Você precisará ter o Node.js, npm, Angular CLI e Ionic CLI instalados globalmente.

1.  **Node.js e npm:** Instale a versão LTS recomendada.
2.  **Ionic CLI e Angular CLI:**
    ```bash
    npm install -g @ionic/cli @angular/cli
    ```
3.  **Android Studio** (para rodar no Android)

#### Instalação e Execução

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/TgregorioDev/aplicativo-de-camera-para-faculdade](https://github.com/TgregorioDev/aplicativo-de-camera-para-faculdade)
    cd aplicativo-de-camera-para-faculdade
    ```
2.  **Instale as dependências:**
    ```bash
    npm install
    ```
3.  **Para rodar no navegador (Apenas para desenvolvimento/teste da UI):**
    ```bash
    ionic serve
    ```
    O aplicativo será aberto automaticamente no seu navegador padrão.

4.  **Para rodar no dispositivo ou emulador Android:**
    * Adicione a plataforma Android (se não estiver adicionada):
        ```bash
        npx cap add android
        ```
    * Sincronize o código web com o projeto nativo:
        ```bash
        npx cap sync
        ```
    * Abra o projeto no Android Studio:
        ```bash
        npx cap open android
        ```
    * A partir do Android Studio, você pode buildar e rodar o aplicativo em um emulador ou dispositivo conectado.


### 📧 Contato

* **Desenvolvedor:** Tiago Gregório Vaz Teles - Turma: Análise e Desenvolvimento de Sistemas EAD.
* **GitHub:** [https://github.com/TgregorioDev](https://github.com/TgregorioDev)
