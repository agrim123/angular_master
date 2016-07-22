# Angular Master

Angular Master gem allow you to easily include angularjs and associated libraries easily into your rails app. All the libraries of AngularJS are open sourced.
[![Gem Version](https://badge.fury.io/rb/angular_master.svg)](https://badge.fury.io/rb/angular_master)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'angular_master'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install angular_master

## Usage

### a. CSS

require the following files in application.css to use [Angular Material](https://material.angularjs.org/latest/). 

```css
	*= require angular-material
```
### b. Javascript
 require the following files in application.js

#### for AngularJS
```js
	//= require angular
```
#### for Angular UI Router
```js
	//= require angular-ui-router
```
#### for Angular Moment
```js
	//= require angular-moment
```
#### for Angular Filter
```js
	//= require angular-filter
```
#### for Angular Material (remember to use this while including css file for angular material)
```js
	//= require angular-material
```
## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/agrim123/angular_master.

## License

MIT