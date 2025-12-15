<div align="center">
  <img src="logo.png" alt="Mupi Systems Logo" width="200"/>
</div>

# 🚀 Teste Técnico - Desenvolvedor Jr. Full Stack
### *Foco Frontend/UI-UX*

--## 🚀 Como Rodar a Aplicação (Template para seu README)

> **Dica:** No seu README.md, inclua uma seção similar a esta:

### 📦 Instalação e Execução 🎯 Objetivo

Criar uma aplicação **Django** com duas páginas principais:
- 📄 **Landpage** com formulário de contato
- 🔐 **Área administrativa** para visualização das mensagens recebidas

---

## 📋 Instruções

### 🔀 Fork do Repositório

1. Faça um **fork** deste repositório para sua conta pessoal do GitHub
2. Trabalhe em seu próprio fork

### 💻 Implementação

- Desenvolva o projeto conforme os requisitos abaixo
- Use **Django**, **Django Templates**, **TailwindCSS**, **HTMX** e **Alpine.js** conforme apropriado

### 📤 Submissão

1. Após finalizar, abra um **Pull Request** do seu fork para o repositório original
2. Aguarde o agendamento da reunião para avaliação do teste

### 📝 Documentação

Inclua um arquivo `README.md` com:
- ✅ Descrição do projeto
- ✅ Passo a passo para rodar a aplicação
- ✅ Decisões técnicas importantes

---

## 🛠️ Requisitos Técnicos Mínimos

### 🐍 Backend (Django)

| Requisito | Descrição |
|-----------|-----------|
| **Versão** | Django 3.2+ |
| **Templates** | `landpage.html` - Página inicial com formulário<br>`admin_messages.html` - Área de visualização de mensagens |
| **Model** | Mensagem com campos: `nome`, `email`, `mensagem`, `data_envio`, `lido` (boolean) |
| **Autenticação** | Sistema de autenticação para área administrativa |
| **API** | Endpoint para receber mensagens do formulário |
| **Migrações** | Migrações funcionais |

### 🎨 Frontend

#### Tecnologias Obrigatórias

- **TailwindCSS** - Para estilização (obrigatório)
- **HTMX** - Para interações assíncronas (pelo menos uma implementação)
- **Alpine.js** - Para interatividade (pelo menos uma implementação)

#### Requisitos de Interface

- Design **responsivo**
- Formulário **funcional** na landpage
- Tabela/listagem de mensagens na área admin

### 🧹 Qualidade de Código

- Versionamento com **commits semânticos**
- Estrutura de projeto Django **organizada**
- Código **limpo** e bem documentado
- Arquivos estáticos organizados

---

## 🎨 Critérios de Avaliação

### 🔴 Prioridade Alta

#### UI/UX Design (30%)
- Estética visual atraente
- Experiência de usuário intuitiva
- Consistência visual
- Responsividade

#### Qualidade de Código (25%)
- Organização do projeto
- Clareza e legibilidade
- Boas práticas Django
- Separação de responsabilidades

#### Funcionalidade (20%)
- Todos os requisitos mínimos atendidos
- Funcionamento correto das features
- Tratamento de erros

### 🟡 Prioridade Média

#### Versionamento (15%)
- Commits descritivos e organizados
- Estrutura de branches (se aplicável)
- Mensagens de commit claras

#### Uso das Tecnologias (10%)
- Aplicação apropriada de HTMX e Alpine.js
- Eficiência no uso do Tailwind
- Decisões técnicas justificadas

---

## 💡 Diretrizes Criativas

### 🌐 Landpage

> **Liberdade total!** Escolha qualquer produto/serviço de sua preferência (pode ser real ou fictício)

**Exemplos na pasta `/examples`** (boas referências de design)

#### Elementos Essenciais

| Seção | Descrição |
|-------|-----------|
| **Header** | Menu de navegação |
| **Hero Section** | Banner principal chamativo |
| **Features/Benefícios** | Destaques do produto/serviço |
| **Formulário de Contato** | Form funcional e validado |
| **Footer** | Informações de rodapé |

### 🔐 Área Administrativa

#### Características

- Design **clean** e funcional
- Listagem de mensagens
- Indicador de mensagens lidas/não lidas
- Logout funcional

---

## 📁 Estrutura Esperada

```text
seu-projeto/
├── README.md
├── requirements.txt
├── manage.py
├── core/
│   ├── settings.py
│   └── urls.py
├── app_principal/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│       ├── base.html
│       ├── landpage.html
│       └── admin_messages.html
├── static/
├── media/
└── examples/
    └── (referências visuais)
```

---
## 🚀 Como Rodar a Aplicação (Template para seu README)

> **💡 Dica:** No seu README.md, inclua uma seção similar a esta:

### � Instalação e Execução

#### 1️⃣ Clone o repositório
```bash
git clone https://github.com/seu-usuario/seu-projeto.git
cd seu-projeto
```

#### 2️⃣ Crie e ative um ambiente virtual
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate  # Windows
```

#### 3️⃣ Instale as dependências
```bash
pip install -r requirements.txt
```

#### 4️⃣ Configure o banco de dados
```bash
python manage.py migrate
```

#### 5️⃣ Crie um superusuário
```bash
python manage.py createsuperuser
```

#### 6️⃣ Execute o servidor
```bash
python manage.py runserver
```

#### 7️⃣ Acesse a aplicação

| Página | URL |
|--------|-----|
| **Landpage** | http://localhost:8000 |
| **Área Admin** | http://localhost:8000/admin |

---
## 📝 Notas Importantes

| Aspecto | Observação |
|-----------|--------------|
| **Liberdade Criativa** | Você tem total liberdade para escolher o tema da landpage |
| **Exemplos** | Consulte a pasta `/examples` para inspiração em design |
| **Foco** | Apesar de ser full stack, **valorizamos muito** as habilidades de UI/UX |
| **Performance** | Considere a experiência do usuário final |
| **Acessibilidade** | Boas práticas de acessibilidade são um **diferencial** |

---

<div align="center">

### Boa sorte com o teste técnico! 🌟

**Mostre suas habilidades e criatividade!**

</div>

