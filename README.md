<div align="center">
  <h1><b>VENOM PRECISION BACK-END</b></h1>
</div>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Frontend](#frontend)
  - [Deployment](#triangular_flag_on_post-deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📝 License](#license)

# 📖 VENOM PRECISION BACK-END <a name="about-project"></a>

VENOM PRECISION BACK-END is a Ruby on Rails application to provide endpoints for "VENOM PRECISION FRONT-END". This aplication will return information in JSON format according to requests from front-end application.
## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://rubyonrails.org/">Ruby on Rails</a></li>
  </ul>
  </details>
  <details>
  <summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

- **Data Model**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running follow these simple example steps.

### Prerequisites

> You need the following tools be installed in your computer:

> - [Ruby](https://github.com/microverseinc/curriculum-ruby/blob/main/simple-ruby/articles/ruby_installation_instructions.md)
> - [Rails](https://guides.rubyonrails.org/)
> - [Git](https://www.linode.com/docs/guides/how-to-install-git-on-linux-mac-and-windows/)
> - [Postgresql](https://www.postgresql.org/)

### Setup

Clone this repository to your desired folder:

```sh
  cd my-prefered-folder

  git clone https://github.com/limavfabio/VenomPrecision-back-end.git

```

### Install

Install this project with:

```sh
  cd VenomPrecision-back-end

  bundle install
```

### 💾 Database

Create the databases and run migrations with:

```sh
rails db:create
rails db:migrate
rails db:seed
```

### Usage

To run the project, execute the following command:

```sh
rails server
```

### Run tests

To run tests, run the following command:

```sh
rspec spec
```

If you are having problems with tests, please make sure you have executed:

```sh
rails db:migrate RAILS_ENV=test
```

### Frontend

You can find the frontend application [here](https://github.com/limavfabio/VenomPrecision-front-end)

### Deployment
To deploy this application you can use Github pages, Netlify, Railway or similar.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

👤 **Anderson Canales**

- GitHub: [@anderCM](https://github.com/anderCM)
- LinkedIn: [/andersoncanales](https://www.linkedin.com/in/andersoncanales/)

👤 **Marcelo Alarcon**

- GitHub: [@chelobotix](https://github.com/chelobotix)
- LinkedIn: [/marceloalarconb](https://www.linkedin.com/in/marceloalarconb/)

👤 **Jakaria Jishan**

- GitHub: [@JakariaJishan](https://github.com/JakariaJishan)
- LinkedIn: [/jakaria-jishan](https://www.linkedin.com/in/jakaria-jishan/)

👤 **Fábio Lima**

- GitHub: [@limavfabio](https://github.com/limavfabio)
- LinkedIn: [/fábio-lima-a28b16182](https://www.linkedin.com/in/f%C3%A1bio-lima-a28b16182/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

- [ ] **CRUD for budges**
- [ ] **Authentication**
- [ ] **Permissions**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/limavfabio/VenomPrecision-back-end.git/issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

If you like this project please give it a star 😁🌟✨

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>
Thanks to Microverse for providing us with the right material to aid this project development

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
