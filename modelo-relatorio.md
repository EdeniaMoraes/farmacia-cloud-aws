# 📝 Relatório do Projeto — FarmaCloud

## 🎯 Objetivo do Projeto
Desenvolver uma plataforma simples de farmácia fictícia utilizando serviços básicos da AWS para aplicar conceitos de computação em nuvem estudados no bootcamp.

---

## 🏗️ Arquitetura da Solução

A arquitetura utiliza:

- **Amazon S3** para hospedagem do site estático.
- **Amazon CloudFront** para distribuir o site com menor latência.
- **Arquivo JSON** com uma simulação de catálogo de produtos.
- **HTML básico** como interface da farmácia.

Essa arquitetura atende os requisitos do projeto por ser escalável, de baixo custo e ideal para iniciantes.

---

## 📦 Serviços AWS Utilizados

### ✔️ Amazon S3
Hospeda o arquivo `index.html` e serve como o backend estático da aplicação.

### ✔️ Amazon CloudFront
Cria uma distribuição CDN que otimiza a entrega global da página.

---

## 🔄 Fluxo de Funcionamento

1. Usuário acessa o domínio público da CloudFront.  
2. CloudFront busca o arquivo HTML no S3.  
3. Página é carregada no navegador.  
4. Catálogo é exibido a partir do arquivo `produtos.json`.

---

## 🗺️ Diagrama da Arquitetura

O diagrama está no arquivo:  
**arquitetura-farmacloud.png**

---

## 🧠 O que aprendi

- Conceitos básicos de computação em nuvem.  
- Criar e configurar buckets S3.  
- Habilitar hospedagem estática.  
- Criar distribuição no CloudFront.  
- Organizar um projeto em repositório GitHub.

---

## 🚀 Melhorias Futuras

- Criar API no API Gateway  
- Armazenar produtos no DynamoDB  
- Criar funções Lambda para lógica do site  
- Adicionar autenticação de usuários

---

## 🙌 Finalização
Este projeto representa minha aplicação prática dos conhecimentos adquiridos no bootcamp DIO.
