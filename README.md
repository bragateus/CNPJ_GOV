# Verificador de CNPJs GOV

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![Ambiente](https://img.shields.io/badge/Ambiente-Produção-green)

Um **WebApp estático** desenvolvido em **HTML, CSS e JavaScript**, que permite consultar CNPJs e identificar se a empresa é classificada como **GOV** (governamental) com base em sua natureza jurídica e CNAE principal.

---

## Sobre o projeto
O objetivo deste projeto é oferecer uma forma rápida e prática de verificar se determinado CNPJ se enquadra em categorias governamentais.  
A aplicação utiliza **APIs públicas de CNPJs** (ReceitaWS, BrasilAPI e CNPJ.WS) para obter os dados cadastrais da empresa e compara as informações retornadas com uma **lista pré-definida de CNAEs considerados GOV**.

O resultado apresenta:
- Situação cadastral  
- Razão social e nome fantasia  
- Natureza jurídica  
- CNAE principal e descrição  
- Contatos (telefone e e-mail)  
- Indicação visual se o CNPJ pertence ou não ao grupo GOV  

---

## 🛠 Tecnologias utilizadas
- **HTML5** para estrutura da aplicação  
- **CSS3** para estilização responsiva e moderna  
- **JavaScript (Vanilla)** para lógica de verificação e integração com APIs  
- **APIs públicas** para consulta de dados oficiais de CNPJs  

---

## Como usar
1. Clone este repositório ou baixe os arquivos.  
2. Abra o arquivo `Verificador de CNPJ.html` em qualquer navegador moderno.  
3. Insira um CNPJ válido e clique em **"Verificar Empresa"**.  
4. Aguarde a consulta nas APIs públicas e veja o resultado exibido na tela.  

---

## 📂 Estrutura do projeto
├── Verificador de CNPJ.html # WebApp principal
├── README.md # Documentação

---

## ⚙️ Customização
A lista de CNAEs considerados GOV pode ser ajustada dentro do arquivo HTML, na variável `cnaesGov`.  
Basta incluir ou remover códigos de acordo com os critérios da sua empresa.

---

##  Observações
- O projeto não exige instalação de dependências ou execução em servidor.  
- A aplicação funciona diretamente no navegador.  
- Como depende de **APIs públicas gratuitas**, a disponibilidade pode variar conforme estabilidade dos serviços externos.  

---

##  Autor
Desenvolvido por [Mateus Braga](https://www.linkedin.com/in/mateus-braga-lima).  
Disponível também em [GitHub](https://github.com/bragateus).  

