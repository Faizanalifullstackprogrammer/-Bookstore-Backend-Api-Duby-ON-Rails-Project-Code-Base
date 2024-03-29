![Linter workflow](https://github.com/Div685/Bookstore-Backend/actions/workflows/linters.yml/badge.svg)

# Bookstore API built with Ruby on Rails

![Screenshot](/screencapture.png)

## About the Project

This REST API was built with Ruby on Rails, and Postgres for the databases. The main goal for this project was to build a REST API for the Bookstore App and that can be used with front-end framework like React. 

This API has 3 database models
- Book model
- Category model
- appointment model


## Built With

* [Ruby on Rails](https://rubyonrails.org/)
* [Ruby](https://www.ruby-lang.org/en/)

## Live Demo

[Live Demo Link](https://bookstore-api-rails.herokuapp.com/)


## Getting Started

To get a local copy up and running follow these simple example steps.
- [ ] Open your terminal
- [ ]  Navigate to the directory where you will like to install the repo by running `cd FOLDER-NAME` 
- [ ] Clone this repository
 > `git clone https://github.com/Div685/Bookstore-Backend.git`
- [ ] To install all dependencies and necessary gems, run `bundle installl`, `yarn install`
- [ ] Run `rails db:setup`
- [ ] Run `rails server` to run rails application in your local server
- [ ] Run `rspec` to run rspec tests

## How to allow the frontend app to interact with this API
1. Go to puma.rb, located in config/puma.rb, and rewrite the port from 3000 to 3001 like below:
e.g. `port ENV.fetch("PORT") { 3001 }`

2. Go to cors.rb, located in config/initializers, and rewrite the origins path for your frontend path in both local and production

## Author

👤 **Mian Faizan Ali Full Stack Programmer**

- GitHub: [@Faizanalifullstackprogrammer](https://github.com/Faizanalifullstackprogrammer)
- Twitter: [@mianfaizanali](https://twitter.com/mianfaizanali)
- LinkedIn: [Mianfaizanali](https://pk.linkedin.com/in/mianfaizanali)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to connect anytime

## Show your support

Give a ⭐️ if you like this project!


## Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](../../issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request




## Acknowledgements
* [Ruby on Rails guide](https://guides.rubyonrails.org/api_documentation_guidelines.html)
* [Rack-cors](https://github.com/cyu/rack-cors)
* [Shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers)
* [Rspec-rails](https://github.com/rspec/rspec-rails)
