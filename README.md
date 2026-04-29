# 💻 Github - Infrastructure as Code - Site Filmes 2/1

## 📌 Sobre o Projeto

Este repositório tem como objetivo demonstrar, na prática, o uso básico do **GitHub** e do **Git** para controle de versão de projetos.

A proposta é apresentar um ambiente simples, contendo arquivos HTML e estrutura inicial, para exemplificar como versionar código, registrar alterações e organizar um projeto dentro do GitHub 🚀  

![Github](imagens/imagem(1).jpg)

---

## 🎯 Objetivos

- Demonstrar o funcionamento do controle de versão com Git  
- Apresentar o fluxo básico de versionamento  
- Exemplificar a criação e organização de repositórios  
- Servir como base para estudos e projetos futuros  

---
## 🏗️ Etapas do Projeto

### ✅ Etapa 1 – CloudFormation (Infraestrutura como Código)

Criação da infraestrutura inicial utilizando templates:

✔️ **Amazon S3** – Hospedagem do site estático  
✔️ **Amazon CloudFront** – Distribuição CDN + OAC 🔒  
✔️ **Amazon Route 53** – Gerenciamento de domínio  
✔️ **AWS Certificate Manager** – HTTPS 🔐  

📌 Nessa etapa, toda a infraestrutura é definida via código, permitindo reuso, padronização e automação.


### ✅ Etapa 2 – Versionamento no GitHub *(etapa atual)*

Nesta fase, estou organizando o projeto para versionamento:

✔️ Criação do repositório  
✔️ Estruturação dos diretórios  
✔️ Versionamento dos templates CloudFormation  
✔️ Boas práticas de commits  

📌 O objetivo é garantir rastreabilidade, colaboração e base para automação futura.


### ⏳ Etapa 3 – Pipeline CI/CD *(próxima etapa)*
### ⏳ Etapa 4 – Backend Serverless

---

## 🎯 Objetivo Geral

Construir um projeto completo utilizando:

✔️ Boas práticas de arquitetura em cloud  
✔️ Infraestrutura como código (IaC)  
✔️ Automação com CI/CD  
✔️ Backend serverless escalável  
## ⚙️ Tecnologias Utilizadas

- Git  
- GitHub 

---

## 🧭 Conceitos Abordados

Durante o desenvolvimento deste projeto, foram aplicados os seguintes conceitos:

- Criação de repositório  
- Versionamento de arquivos  
- Commits e histórico de alterações  
- Organização de arquivos no GitHub  

---

## 📸 Fotos do Projeto

<p align="center">
  <img src="imagens/imagem(5).png" width="30%" />
  <img src="imagens/imagem(6).png" width="30%" />
  <img src="imagens/imagem(4).png" width="30%" />
</p>

<p align="center">
  <img src="imagens/imagem(3).png" width="30%" />
  <img src="imagens/imagem(2).png" width="30%" />
  <img src="imagens/imagem(1).png" width="30%" />
</p>

---

## 📁 Estrutura do Projeto

```
github-inicio/
│
├── index.html        # Página principal
├── erro.html         # Página de erro
├── imagens/          # Arquivos de imagem
├── .gitignore        # Arquivos ignorados pelo Git
├── README.md         # Documentação do projeto
└── LICENSE           # Licença do projeto
```

---

## 🔄 Fluxo básico com Git

```bash
git clone URL_DO_REPOSITORIO
git status
git add .
git commit -m "mensagem do commit"
git push -u origin main
```

---

## ⚠️ Boas Práticas

- Utilizar o `.gitignore` para evitar subir arquivos desnecessários  
- Escrever mensagens de commit claras e objetivas  
- Manter o repositório organizado  
- Versionar frequentemente as alterações  

---

## 🧹 Remover versionamento Git

Caso seja necessário remover o controle de versão da pasta local:

```bash
rm -rf .git
```

---

## 📜 Licença

Este projeto está sob a licença **MIT**.

---

## 👨‍💻 Autor

**Luiz Augusto Souza**

<<<<<<< HEAD
* 💼 Linkedin: https://www.linkedin.com/in/luiz-inhesta-341b4b311/

=======
* 💼 LinkedIn: https://www.linkedin.com/in/luiz-inhesta-341b4b311/
>>>>>>> e636af3c5ac467db4f4fe03d601eae786e01233b
* 💻 YouTube: https://youtu.be/ORb9VypZT3A

---
