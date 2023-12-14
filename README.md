<a name="readme-top"></a>

<div align="center">
  <h3><b>Hello Rails Backend</b></h3>
</div>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features ](#key-features-)
- [💻 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

# Random Greeting <a name="about-project"></a>

The Random Greeting App is a web application that combines the power of Rails as the backend and React with Redux as the frontend to create a delightful user experience.
Link to the frontend repo [frontend](https://github.com/JuanDiegoGuerra/hello-react-front-end)
Link to the backend repo [backend](https://github.com/JuanDiegoGuerra/hello-rails-back-end)

### Tech Stack <a name="tech-stack"></a>

<details>
<summary>Ruby</summary>
  <ul>
    <li><a href="https://www.ruby-lang.org/">Ruby</a></li>
  </ul>
</details>

<details>
<summary>Rails</summary>
  <ul>
    <li><a href="https://rubyonrails.org/">Ruby</a></li>
  </ul>
</details>

<details>
<summary>React</summary>
  <ul>
    <li><a href="https://react.dev/">React</a></li>
  </ul>
</details>

<details>
<summary>Redux</summary>
  <ul>
    <li><a href="https://redux.js.org/">Redux</a></li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

- Greeting: The heart of the app lies in the "Greeting". Here, users can experience the magic of randomness as the app retrieves and displays a random greeting from the database with each visit. The greetings are stored in the backend database, which is managed by Rails.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need to run the following commands:

```sh
 gem install ruby
```

```sh
 gem install rails
```

### Setup

Clone the 2 repositorys to your desired folder:

- The frontend repository:

```sh
  git clone https://github.com/JuanDiegoGuerra/hello-react-front-end.git 
```

- The backend repository:

```sh
git clone https://github.com/JuanDiegoGuerra/hello-rails-back-end.git
```

### Install

Install this project dependencies and create database with:

```sh
  cd hello-react-front-end
  npm install
  cd ../hello-rails-back-end
  bundle install
  rails db:create
  rails db:migrate
  rails db:seed
```

### Usage

To run the project you will need to run 2 terminals.

- The first one:

```sh
  cd hello-rails-back-end
  rails s
```

- The second one:

```sh
  cd hello-react-front-end
  npm run dev
```

your default browser should be opened in this moment.

## Future Features <a name="future-features"></a>

- **Proper Styling**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Authors <a name="authors"></a>

👨🏼‍🚀 **Juan Diego Guerra (JD)** 👽
- GitHub: [@JuanDiegoGuerra](https://github.com/JuanDiegoGuerra)
- Twitter: [@jdxelric147](https://twitter.com/jdxelric147)
- LinkedIn: [Juan Guerra](https://www.linkedin.com/in/juan-guerra-65076b1ba/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing <a name="contributing"></a>

We welcome contributions to enhance the functionality and user experience of the App. If you have any ideas, suggestions, or bug reports, feel free to open an issue or submit a pull request.

Feel free to check the [issues page](https://github.com/JuanDiegoGuerra/hello-react-front-end/issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## Support <a name="support"></a>

If you encounter any issues or have any questions or suggestions, please open an issue on the [issue tracker](https://github.com/JuanDiegoGuerra/hello-react-front-end/issues).
Furthermore, if you would like to get in touch with us, you can find our contact information in the <a href="#authors">Authors</a> section.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgments <a name="acknowledgements"></a>

I would like to express our gratitude to the Ruby community and Microverse for the readme template.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>