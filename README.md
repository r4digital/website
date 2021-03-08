# Website R4 Digital

## Instalar

```bash
gem install bundler
```

## Executar

```bash
bundle exec jekyll serve --watch --livereload
```

## Bugs

### Unable to load the EventMachine C extension; To use the pure-ruby reactor, require 'em/pure_ruby'

```bash
gem uninstall eventmachine
gem install eventmachine --platform ruby
bundle exec jekyll clean
```
