# 🚀 Projeto Flask - CyberShield & Pokédex Lendária

## 📌 Descrição do Projeto

Este projeto consiste em uma aplicação web desenvolvida utilizando **Python com Flask**, que integra duas propostas principais:

* 🔐 **CyberShield**: uma interface simulando um sistema de segurança digital com login e funcionalidades como proteção, backup e recuperação.
* 📖 **Pokédex Lendária**: uma página interativa que exibe Pokémons com busca e visualização detalhada.

O objetivo do projeto é demonstrar a utilização de rotas no Flask e a integração entre **frontend (HTML, CSS, JavaScript)** e **backend (Python)**.

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* Flask
* HTML5
* CSS3
* JavaScript

---

## 📂 Estrutura do Projeto

```
daphne/
│
├── app.py
│
├── static/
│   ├── style.css
│   └── script.js
│
└── templates/
    ├── index.html
    ├── login.html
    └── home.html
```

---

## ⚙️ Como Executar o Projeto

### 1. Instalar o Flask

No terminal, execute:

```
pip install flask
```

ou:

```
python -m pip install flask
```

---

### 2. Executar a aplicação

Dentro da pasta do projeto, rode:

```
python app.py
```

---

### 3. Acessar no navegador

Abra:

```
http://127.0.0.1:5000/
```

---

## 🌐 Rotas da Aplicação

* `/` → Página inicial (CyberShield)
* `/login` → Tela de login
* `/home` → Pokédex Lendária

---

## 💡 Funcionalidades

✔ Sistema de navegação entre páginas
✔ Interface de login e cadastro (simulada)
✔ Exibição de Pokémons
✔ Busca de Pokémons
✔ Modal com detalhes
✔ Simulação de backup e recuperação de arquivos

---

## ⚠️ Observações

* O projeto utiliza arquivos estáticos corretamente através do Flask (`url_for`).
* A aplicação não possui banco de dados — os dados são simulados.
* Deve ser executada via Flask (não abrir os arquivos HTML diretamente).

---

## 👨‍💻 Autor

Desenvolvido por **Daphne Carvalho**.

---

## 📚 Conclusão

Este projeto demonstra conceitos fundamentais de desenvolvimento web com Flask, incluindo:

* Criação de rotas
* Renderização de templates
* Organização de arquivos
* Integração entre frontend e backend

---
