[![AngularJS Express](http://i.imgur.com/nTj9QgN.png)](https://github.com/angular-express/angular-express)

## Bootstrap 3

This component adds the boilerplate for including a customized Bootstrap 3 suite to your AngularJS Express application.

It lets you select the Bootstrap 3 components you wish to include to prevent unnecessary CSS bloat.

## Installation

To install the component:

```bash
$ ngx install bs3
```

No clue what the `ngx` command line tool is? Learn more about [AngularJS Express](https://github.com/angular-express/angular-express).

## How to use

After installing the component, you can edit:
 
- [`_build/_bootstrap.less`](ngx/_build/_bootstrap.less) to select the Bootstrap 3 components you wish to include in your CSS
- [`_build/_variables.less`](ngx/_build/_variables.less) to customize the Bootstrap 3 variables to your needs

Finally, include `_bootstrap.less` in your main `app.less` file like this:

```less
# Use the path to your custom bootstrap component
@import "../components/bs3/_build/_bootstrap";
```

## License

MIT.
