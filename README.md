# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## Progress

- 3.3
- 3.7
- 3.11
- 3.15 error running test `rails test`, `sudo yum install -y tmux`
- 3.4
- 3.4.3 
- 3.4.4
- 3.5
- 3.6.2
- 4.2.2 Strings
- 5
- 5.1.2 
- 5.1.3
- 5.2
- 5.2.2
- 5.3
- 5.3.2
- 5.4.2
- 5.5.1
- 6.1.4
- 

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).