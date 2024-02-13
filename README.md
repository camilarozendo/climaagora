<p align="center">
  <img src="https://camo.githubusercontent.com/a4e71a0942263821f4cb9213b2808af909e46967d9ed3ccee6e7e122f276efd6/68747470733a2f2f696d672e69636f6e73382e636f6d2f65787465726e616c2d74616c2d72657669766f2d726567756c61722d74616c2d72657669766f2f39362f65787465726e616c2d726561646d652d69732d612d656173792d746f2d6275696c642d612d646576656c6f7065722d6875622d746861742d6164617074732d746f2d7468652d757365722d6c6f676f2d726567756c61722d74616c2d72657669766f2e706e67" width="100" />
</p>
<p align="center">
    <h1 align="center">Clima Agora</h1>
</p>
<p align="center">
    <em>Aplicação Web para verificação de clima</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/camilarozendo/climaagora?style=default&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/camilarozendo/climaagora?style=default&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/camilarozendo/climaagora?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/camilarozendo/climaagora?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<hr>

## 🔗 Quick Links

> - [ Overview](#-overview)
> - [ Features](#-features)
> - [ Repository Structure](#-repository-structure)
> - [ Getting Started](#-getting-started)
>   - [ Installation](#-installation)
> - [ Contributing](#-contributing)
> - [ License](#-license)

---

## 📍 Overview

O projeto consiste em uma aplicação web que consome dados de outras APIs para trazer as condições climáticas de qualquer cidade do mundo.

---

## 🔮 Features

#### Interface de Usuário Simples:

- A interface é minimalista e fácil de usar, com um campo de entrada para o nome da cidade e um botão de pesquisa.

#### Integração com APIs:

- Utiliza a API do *OpenWeatherMap* para obter dados meteorológicos da cidade especificada pelo usuário.
- Usa a API *FlagsAPI* para exibir a bandeira do país correspondente à cidade.

#### Apresentação dos Dados Meteorológicos:

- Exibe informações como temperatura, descrição do clima, ícone de condições climáticas, umidade e velocidade do vento.
- A temperatura é exibida em graus Celsius.

#### Estilização e Layout Responsivo:

- O CSS (`style.css`) fornece uma estilização atraente e coesa para a página.
- O layout é responsivo, garantindo uma boa experiência de usuário em diferentes dispositivos.

#### Interatividade com JavaScript:

- O JavaScript (`scripts.js`) é usado para lidar com eventos, como a submissão do formulário de pesquisa.
- Implementa a lógica para buscar e exibir os dados meteorológicos da cidade digitada pelo usuário.

#### Requisições Assíncronas:

- Usa `fetch` para fazer chamadas assíncronas à API do *OpenWeatherMap*, garantindo uma experiência de usuário fluída.

### Funcionamento:

- O usuário insere o nome da cidade desejada no campo de entrada.
- Ao clicar no botão de pesquisa, o aplicativo solicita informações de clima da cidade à API do OpenWeatherMap.
- Após receber a resposta da API, o aplicativo exibe os dados meteorológicos na página, incluindo temperatura, descrição do clima, umidade, velocidade do vento e a bandeira do país correspondente à cidade.

---

## 🧩 Repository Structure

```sh

└── climaagora/
   ├── css/
   │   └── style.css
   ├── js/
   │   └── scripts.js
   └── index.html

```


---

## 🚀 Getting Started

### ⚙️ Installation

1. Clone the pucminas.exercicio2.node repository:

```sh
git clone https://github.com/camilarozendo/climaagora
```

2. Change to the project directory:

```sh
cd climaagora
```

---


## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github/camilarozendo/climaagora/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github/camilarozendo/climaagora/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github/camilarozendo/climaagora/issues)**: Submit bugs found or log feature requests for climaagora.

<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/camilarozendo/climaagora
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

## 📄 License

MIT License

Copyright (c) 2024 Camila Rozendo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[**Return**](#-quick-links)

---
