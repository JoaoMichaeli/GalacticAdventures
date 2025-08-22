# 🌍 AI Character Creator

## 📌 Sobre o Projeto (PT-BR)
O **AI Character Creator** é uma aplicação desenvolvida em **Spring Boot + Thymeleaf** que permite criar, listar e gerenciar personagens com atributos personalizados. O sistema já vem preparado para **internacionalização (i18n)** com suporte a **Português, Espanhol e Inglês**.

### 🚀 Funcionalidades
- Criar novos personagens com nome, espécie, nível inicial e biografia.
- Listar personagens cadastrados.
- Suporte a múltiplos idiomas (PT, ES, EN).

### 🛠️ Tecnologias Utilizadas
- **Java 17**
- **Spring Boot 3**
- **Thymeleaf**
- **Spring MVC**
- **i18n (Internationalization)**

### 📂 Estrutura de Internacionalização
```
src/main/resources/
 ├── messages.properties       # Inglês (default)
 ├── messages_pt.properties    # Português
 └── messages_es.properties    # Espanhol
```

### ▶️ Como Executar
```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/ai-character-creator.git
cd ai-character-creator

# Executar com Maven
./mvnw spring-boot:run
```

Acesse em: `http://localhost:8080`

### 🌐 Troca de Idioma
O idioma pode ser trocado diretamente pelo menu **Idioma** na aplicação.
