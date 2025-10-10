# 🚲 Bikcraft - Bicicletas Elétricas Feitas Sob Medida

![Bikcraft Banner](https://bikcraft.shop/img/bikcraft.svg)

O Bikcraft é um projeto de website **responsivo** e **funcional** para uma empresa fictícia especializada na venda de bicicletas elétricas feitas sob medida. O site apresenta os produtos, diferenciais tecnológicos, planos de seguro e, de forma crucial, possui um sistema de **Back-End funcional** para o processamento de e-mails de contato e orçamento.

Este projeto demonstra a criação de uma experiência Front-End completa, integrada a uma solução de Back-End básica para a comunicação via e-mail.

## 🎯 Objetivo do Projeto

O principal objetivo deste projeto foi aplicar e consolidar conhecimentos avançados em **HTML5, CSS3, JavaScript** e introduzir uma solução de **Back-End (PHP)** para:

* **Design Responsivo:** Garantir que o site funcione e seja visualmente atraente em qualquer dispositivo (desktop, tablet, mobile).
* **Funcionalidade de Contato:** Implementar um formulário funcional que envia e-mails, utilizando o **PHPMailer** para lidar com o SMTP do servidor de hospedagem.
* **Interatividade:** Criar galerias de imagens, navegação por abas e pré-seleção de produtos via URL (query strings).

---

## 💻 Tecnologias Utilizadas

O projeto Bikcraft utiliza uma combinação de tecnologias **Front-End e Back-End** para criar uma aplicação completa e funcional:

| Categoria | Tecnologia | Finalidade |
| :--- | :--- | :--- |
| **Front-End** | **HTML5** | Estruturação semântica de todo o conteúdo do website. |
| **Front-End** | **CSS3** | Estilização completa, layouts avançados com **Grid** e **Flexbox** e responsividade. |
| **Front-End** | **JavaScript (Puro)** | Implementação de interatividade, como galeria de imagens e navegação por abas. |
| **Back-End** | **PHP** | Processamento de dados de formulário nas páginas `contato.html` e `orcamento.html`. |
| **Back-End** | **PHPMailer** | Biblioteca essencial utilizada pelo script `enviar.php` para o envio seguro de e-mails via SMTP do servidor de hospedagem. |

---

## 📁 Estrutura do Repositório

O projeto segue uma estrutura de pastas e arquivos bem organizada:

bikcraft/
├── .vscode/          # Configurações do ambiente de desenvolvimento (VS Code).
├── bicicletas/       # Páginas de detalhes de cada modelo de bicicleta.
├── css/              # Arquivos de estilo CSS.
├── img/              # Todas as imagens, ícones e assets visuais.
├── js/               # Arquivos JavaScript para interatividade.
├── enviar.php        # Script PHP com PHPMailer para processamento de e-mails.
├── index.html        # Página inicial.
├── bicicletas.html   # Página de listagem de bicicletas.
├── contato.html      # Página de contato.
├── orcamento.html    # Página para solicitação de orçamento/personalização.
├── seguros.html      # Página com detalhes dos planos de seguro.
└── termos.html       # Página de Termos e Condições.

---

## 🚀 Etapas do Projeto (Processo de Desenvolvimento)

O desenvolvimento do Bikcraft seguiu as seguintes etapas principais:

### 1. Estruturação e Layout Estático (HTML & CSS)

* **Estrutura Semântica:** Desenvolvimento das páginas HTML, garantindo o uso correto de tags para acessibilidade e SEO.
* **Design Responsivo:** Aplicação do padrão **Mobile-First**, utilizando **CSS Grid** e **Flexbox** para layouts modernos e adaptáveis em todos os tamanhos de tela.

### 2. Interatividade do Usuário (JavaScript)

* **Funcionalidades de UX:** Implementação de scripts em **JavaScript Puro** para:
    * **Galeria de Imagens:** Criação de uma galeria funcional na página de detalhes do produto.
    * **Seleção de Opções:** Captura de parâmetros de URL para pré-selecionar o produto ou seguro na página de orçamento.

### 3. Back-End e Processamento de Formulários (PHP/PHPMailer)

* **Integração de Formulários:** Criação do script **`enviar.php`** para receber e processar os dados enviados pelos formulários de Contato e Orçamento.
* **Envio de E-mail Confiável:** Configuração do **PHPMailer** para utilizar as credenciais SMTP do servidor de hospedagem, garantindo que as mensagens de e-mail cheguem ao destinatário de forma segura e profissional.
* **Feedback:** Implementação de uma lógica de redirecionamento ou exibição de mensagens de sucesso/erro após o envio.

---

## 🔗 Acesso ao Projeto

Você pode visualizar a versão final e funcional do site através do link de hospedagem:

* **Site Publicado:** [https://bikcraft.shop/](https://bikcraft.shop/)
* **Código Fonte:** [https://github.com/dan1723/bikcraft](https://github.com/dan1723/bikcraft)

---
## 🧑‍💻 Autor

Desenvolvido por **Danilo**  
📧 Contato: dan.gomes1723@gmail.com  
🔗 GitHub: [github.com/dan1723](https://github.com/dan1723)

---

## 🪪 Licença

Este projeto é de uso educacional e foi desenvolvido como exercício do curso **Origamid**.  
Você pode modificá-lo e utilizá-lo livremente para fins **pessoais** e de **aprendizado**.