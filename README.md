<!-- Banner estilizado -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6e40c9,100:ff8c00&height=120&section=header&text=Sistema%20de%20Controle%20de%20Ve%C3%ADculos&fontSize=30&fontColor=fff"/>
</p>

<h1 align="center">🚗 Sistema de Controle de Veículos</h1>

<p align="center">
  <b>Projeto Fullstack • Flutter (Mobile) + Laravel (Backend)</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

---

## 📖 Sobre o Projeto

Este sistema foi desenvolvido como parte do meu aprendizado prático em desenvolvimento fullstack, integrando um aplicativo mobile em **Flutter** com um backend em **Laravel**. O objetivo é facilitar o controle da frota de veículos da Alfa Engenharia, permitindo cadastro, consulta e gerenciamento de veículos, motoristas e viagens.

Como iniciante, enfrentei desafios importantes, especialmente para entender e implementar **APIs REST** e realizar a comunicação entre o app mobile e o backend. Esses obstáculos foram fundamentais para meu crescimento técnico, me ensinando sobre integração de sistemas, autenticação, consumo de endpoints e boas práticas de desenvolvimento.

---

## 🛠️ Tecnologias Utilizadas

- **Frontend Mobile:** Flutter (Dart)
- **Backend:** Laravel (PHP)
- **Banco de Dados:** MySQL
- **API:** RESTful

---

## 📦 Funcionalidades

- Cadastro e edição de veículos
- Cadastro de motoristas
- Registro de viagens
- Consulta e relatórios
- Interface mobile intuitiva

---

## 🚀 Como Rodar o Projeto

### 1. Preparando o Backend (Laravel)

1. **Clone o repositório do backend:**
git clone https://github.com/PierreOtavio/projAlfa/main/Alfa_back-broken.git
cd seu-projeto-laravel

2. **Instale as dependências do Laravel:**
composer install

3. **Configure as variáveis de ambiente:**
- Copie o arquivo de exemplo:
  ```
  cp .env.example .env
  ```
- Abra o arquivo `.env` e preencha as informações do seu banco de dados (host, usuário, senha, nome do banco).

4. **Gere a chave da aplicação:**
php artisan key:generate

5. **Execute as migrações do banco de dados:**
php artisan migrate

6. **Inicie o servidor local do Laravel:**
php artisan serve

O backend estará disponível em `http://localhost:8000` (ou a porta exibida no terminal).
---

### 2. Preparando o Mobile (Flutter)

1. **De preferência baixe o arquivo zip:**
git clone https://github.com/PierreOtavio/projAlfa/main/flutter_app_2.git
cd seu-projeto-flutter

2. **Instale as dependências do Flutter:**
flutter pub get

3. **Configure a URL da API:**
- No código do Flutter, localize onde está definida a URL base da API e ajuste para o endereço do backend Laravel (ex: `http://localhost:8000/api` ou o IP da sua máquina na rede local).

4. **Execute o aplicativo:**
flutter run

Você pode rodar em um emulador Android/iOS ou em um dispositivo físico conectado.
---

### 3. Pronto para Usar!

- Certifique-se de que o backend está rodando antes de iniciar o app Flutter.
- Agora, basta utilizar o aplicativo normalmente: cadastre veículos, motoristas, registre viagens e consulte os dados!

---

## 🖼️ Exemplos de Uso

> Adicione aqui prints ou GIFs do app e da interface web para ilustrar o funcionamento.

---

## 💡 Aprendizados

- Integração de sistemas via API REST
- Autenticação e consumo de endpoints
- Boas práticas de versionamento e organização de código
- Trabalho em equipe e resolução de problemas práticos

---

## 👨‍💻 Sobre Mim

Sou Otávio Pierre, estudante do 2º ano do Ensino Médio e do curso técnico de Desenvolvimento de Sistemas no Senac MG, apaixonado por tecnologia e desenvolvimento fullstack. Tenho experiência com PHP, Dart, JavaScript, Flutter, Laravel e Nest.js. Gosto de trabalhar em equipe, sou comunicativo e estou sempre buscando aprender mais.

---

## 📄 Currículo Resumido

- **Experiência:** Desenvolvedor fullstack na Alfa Engenharia (2024-2025), criando sistema web e mobile para controle de veículos.
- **Formação:**  
- Desenvolvimento de Sistemas – Senac MG (2024-2025, em andamento)  
- Aperfeiçoamento Desafio AlfaID – Senac MG (2025)  
- Inglês do Básico ao Avançado (em andamento)  
- Matemática para o ENEM (em andamento)
- **Habilidades:** Trabalho em equipe, tomada de decisões, boa comunicação, inteligência emocional
- **Idiomas:** Inglês (Básico)
- **Objetivos:** Seguir carreira em tecnologia, cursar Ciência da Computação, atingir inglês avançado e aprimorar lógica matemática.

---

## 📬 Contato

- **E-mail:** perresla111@gmail.com
- **Telefone:** (37) 99832-0306
- **Endereço:** R. Maria Mascarenhas de Oliveira, 251. Cidade Jardim, Divinópolis/MG

---

<p align="center">
<img src="https://komarev.com/ghpvc/?username=PierreOtavio&color=orange" alt="Profile views"/>
</p>
