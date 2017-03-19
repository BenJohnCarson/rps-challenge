# RPS Challenge
#### Technologies: Sinatra, Ruby, RSpec/Capybara

## Index
* [Task](#Task)
* [Installation](#Install)
* [Usage](#Usage)
* [User Stories](#Stories)
* [Approach](#Approach)

## <a name="Task">Task</a>
To build an oline Rock. Paper. Scissors. game.

## <a name="Install">Installation</a>
* Clone from github
```
$ git clone https://github.com/BenJohnCarson/rps-challenge
```

* Switch to ruby 2.2.3
```
$ rvm use 2.2.3
```

* Install gems
```
$ gem install bundler
$ bundle
```

## <a name="Usage">Usage</a>
* To run the app
```
rackup app.rb -p 4000
```
Navigate to http://localhost:4000

* To play
  * Enter your name
  * Make a choice
  * See the result!

* Running tests
```
$ rspec
```

## <a name="Stories">User Stories</a>
```
As a marketeer
So that I can see my name in lights
I would like to register my name before playing an online game

As a marketeer
So that I can enjoy myself away from the daily grind
I would like to be able to play rock/paper/scissors
```

## <a name="Approach">Approach</a>
To approach this challenge, I broke down the second user story into several several user stories:
```
As a user
So I can select Rock, Paper or Scissors
I'd like to see my options

As a user
So I see my choice
I'd like confirmation after choosing

As a user
So I can play
I'd like the computer to make a random choice

As a user
So I can see if I've won
I'd like to see the result
```
