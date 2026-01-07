# Criar-senha / Password Generator

Este repositório oferece uma ferramenta simples para gerar senhas seguras e reutilizáveis para uso pessoal e integração em scripts ou aplicações.

---

## Português (PT-BR)

### Descrição
Uma pequena suíte para gerar senhas fortes, com opções configuráveis de comprimento, inclusão de símbolos, números e uso de letras maiúsculas/minúsculas.

### Funcionalidades
- Geração de senhas aleatórias seguras
- Parâmetros configuráveis (tamanho, símbolos, dígitos, maiúsculas)
- Uso em linha de comando e como biblioteca (se aplicável)

### Instalação
Clone o repositório:

```bash
git clone https://github.com/CallmeIgor/Criar-senha.git
cd Criar-senha
```

Se o projeto tiver dependências (ex.: Node.js, Python), instale-as conforme o arquivo de configuração do repositório:

- Node.js: `npm install` ou `yarn install`
- Python: `pip install -r requirements.txt`

(Sinta-se à vontade para ajustar essas instruções conforme as dependências reais do projeto.)

### Uso
Exemplo de uso via CLI (substitua conforme o comando real do projeto):

```bash
# gerar uma senha de 16 caracteres com símbolos e números
./criar-senha --length 16 --symbols --numbers
```

Exemplo de uso em código (pseudo-exemplo):

```js
const gerar = require('criar-senha');
const senha = gerar({ length: 12, symbols: true, numbers: true });
console.log(senha);
```

### Desenvolvimento
- Crie uma branch para suas mudanças: `git checkout -b feature/minha-mudanca`
- Faça commits pequenos e claros
- Abra um Pull Request para revisão

### Testes
Adicione instruções de testes aqui caso existam (ex.: `npm test`, `pytest`).

### Contribuição
Contribuições são bem-vindas. Abra issues para reportar bugs ou sugerir melhorias e envie Pull Requests conforme necessário.

### Licença
Especifique a licença do projeto (por exemplo, MIT). Se ainda não houver, adicione um arquivo LICENSE.

---

## English (EN)

### Overview
This repository provides a simple tool to generate secure passwords for personal use or integration into scripts/apps.

### Features
- Secure random password generation
- Configurable parameters (length, symbols, digits, uppercase/lowercase)
- CLI usage and library integration (if applicable)

### Installation
Clone the repository:

```bash
git clone https://github.com/CallmeIgor/Criar-senha.git
cd Criar-senha
```

If the project has dependencies (e.g., Node.js, Python), install them according to the project's configuration files:

- Node.js: `npm install` or `yarn install`
- Python: `pip install -r requirements.txt`

(Adjust these instructions to match the repository's real dependencies.)

### Usage
Example CLI usage (replace with the actual project command):

```bash
# generate a 16-character password with symbols and numbers
./criar-senha --length 16 --symbols --numbers
```

Example in code (pseudo-example):

```js
const generate = require('criar-senha');
const password = generate({ length: 12, symbols: true, numbers: true });
console.log(password);
```

### Development
- Create a branch for your changes: `git checkout -b feature/my-change`
- Make small, focused commits
- Open a Pull Request for review

### Tests
Add test instructions here if any exist (e.g., `npm test`, `pytest`).

### Contributing
Contributions are welcome. Open issues for bugs or feature requests and send Pull Requests as needed.

### License
Specify the project license (for example, MIT). If none exists yet, add a LICENSE file.

---

If you want, I can tailor the README to the exact commands, examples, and project details — tell me which language should be the primary top-level heading and share any commands or badges you want included.
