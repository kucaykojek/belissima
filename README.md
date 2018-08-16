# belissima
A Beautiful start. Belissima is Stylesheet as a Service.

### Directory structures
```text
1-base/ # basic styles.
  _normalize.scss # github.com/necolas/normalize.css
  _variables.scss # placing base variables.
2-tools/ # mixins, functions, etc.
3-layouts/ # html/body, header, navigation, list, etc.
4-components/ # partials components. ex: buttons, forms, etc.
5-utils/ # utilities style. ex: whitespaces, coloring, etc.
6-vendors/ # overriding vendor styles.
```

### How to use it?
```sh
npm i --save git+https://github.com/kucaykojek/belissima.git
```

Or you can add this to your `package.json` file.

```json
"dependencies": {
    "belissima": "git+https://github.com/kucaykojek/belissima.git"
}
```

If you're using `Gemfile`

```ruby
gem 'belissima', git: 'https://github.com/kucaykojek/belissima'
```

### License
MIT