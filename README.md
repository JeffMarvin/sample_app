# Ruby on Rails Tutorial sample application

This is the sample applications for [*Ruby on Rails Tutorial](http://www.railstutorial.org/) by Michael Hartl

## Licence
All source code is available jointly under the MIT Licence and the Beerware Licence. See [LICENCE.md](LICENCE.md) for detais.

## Getting Started
To get started with the app, clone the repo and then install the needed gems:
```
$ bundle install --without production
```

Next migrate the database:
```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:
```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server
```
$rails server
```

For more information see the book linked above.
