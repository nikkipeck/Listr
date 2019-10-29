# Listr
A list app for Shareworks, to access Ruby on Rails knowledge. This is a time-boxed exercise with 4 issues to replicate the issues that may arise day to day.

## Rules
**You have 4 hours to resolve as many as these issues as you can**
Select 1 issue to work on at a time.
Please read each issue carefully as their requirements are sometimes not as simple as they suggest.

## Mentaility
If you have questions about the tickets you are working on, please feel free to reach out to a member of our team. 
This project is to access your technical skills as well as your working process. 
We believe that questions should be asked early and often, just like out commits :).

## Installing ruby
Homebrew is a common way to install system dependancies on Mac Osx. We suggest that you use it to install Ruby, if you don't have it checkout the following link:

`https://docs.brew.sh/Installation`

We also suggest using rbenv for your ruby version manager, using homebrew you can do this by running:
```
brew install rbenv
rbenv init
echo "eval('rbenv -int')" > ~/.bash_profile
source ~/.bash_profile
```

Then simply install the ruby version you desire. In this case it would be the following:
```
rbenv install 2.5.1
```

## Dependancies

We have the following depenancies in the system that you need to be aware of.
* [Minitest](https://github.com/seattlerb/minitest)
* [Fixtures](https://guides.rubyonrails.org/testing.html#the-low-down-on-fixtures)
* [Milligram](https://milligram.io/)

## Getting Started
```
bundle install
bundle exec rails s
```

## Running Tests
```
bundle exec rails test
```

## Contributing

To contribute to this repo, follow the steps below.
* Fork the repo
* Code some magic. **1 pull request per issue**
* Add tests around new features
* Request reviewers for PR.
