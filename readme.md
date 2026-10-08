# 🌐 OpenSource Hub — Repositório de Ferramentas Criativas e Técnicas

Um diretório moderno, elegante e de código aberto focado em softwares livres e open-source para **CAD, Modelação 3D, Design Gráfico, Ilustração, Animação e Desenvolvimento**. 

Este repositório está configurado para funcionar de forma estática com o **GitHub Pages**, permitindo gerir e atualizar todos os links e programas de forma simples através de um único ficheiro JSON.

---

## ✨ Funcionalidades

- **Design Moderno e Responsivo:** Construído com Tailwind CSS, com suporte nativo para modo escuro (*Dark Mode*).
- **Gestão Desacoplada (Baseada em JSON):** Adicione ou edite programas sem tocar numa única linha de HTML.
- **Categorização Automática:** Organiza dinamicamente as ferramentas por categorias (ex: CAD, 3D, Design, Ilustração, etc.).
- **Pesquisa Instantânea & Filtros:** Permite procurar ferramentas por nome, descrição, tags ou categorias em tempo real.
- **Leve e Rápido:** Sem dependências pesadas de frameworks, totalmente estático.

---

## 📂 Estrutura do Repositório

```text
├── index.html       # Página principal da aplicação (Interface web)
├── programs.json    # Ficheiro de dados com a lista de programas e links
└── README.md        # Documentação do projeto
```

---

## 🛠️ Como Adicionar um Novo Programa

Adicionar novas ferramentas ao seu diretório é muito simples. Siga estes passos:

1. No seu repositório no GitHub, abra o ficheiro **`programs.json`**.
2. Clique no ícone de lápis para editar o ficheiro.
3. Adicione o novo programa seguindo a estrutura do array JSON abaixo:

```json
{
  "name": "Nome do Programa",
  "category": "CAD", 
  "description": "Breve descrição sobre o software e para que serve.",
  "url": "https://github.com/exemplo/repositorio",
  "website": "https://exemplo.org",
  "icon": "fa-solid fa-cube",
  "tags": ["3d", "modelagem", "gratuito"]
}
```

* **`name`**: O nome oficial da ferramenta.
* **`category`**: A categoria principal (cria filtros automaticamente no topo do site).
* **`description`**: Uma descrição clara e concisa.
* **`url`**: O link direto para o repositório oficial (GitHub, GitLab, etc.).
* **`website`**: O site oficial do projeto.
* **`icon`**: Uma classe de ícone do [FontAwesome 6](https://fontawesome.com/search?o=r&m=free).
* **`tags`**: Palavras-chave úteis para pesquisa rápida.

4. Clique em **Commit changes** para guardar. As alterações refletem-se no site em menos de um minuto!

---

## 🚀 Como Executar Localmente

Se quiser testar alterações no seu computador antes de enviar para o GitHub:

1. Clone este repositório:
   ```bash
   git clone https://github.com/o-seu-utilizador/nome-do-repositorio.git
   ```
2. Abra a pasta do projeto.
3. Abra o ficheiro `index.html` diretamente num navegador web ou utilize uma extensão de servidor local (como o *Live Server* no VS Code).

---

## 📄 Licença

Este projeto é distribuído sob a licença MIT. Sinta-se à vontade para utilizar, modificar e partilhar.