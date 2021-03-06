# haml2erb

haml2erb is a tool for converting [Haml](http://haml-lang.com/) to Erb markup.


## Installing and loading haml2erb

haml2erb is currently distributed as a Rails plugin.

Simply move the main haml2erb directory into the vendor/plugins directory of your Rails application.


## Using haml2erb

Use the `haml2erb` command line or from Ruby call the `Haml2Erb.convert` method to have Haml markup translated into Erb.

### Example: Simple conversion

```bash
  echo '.foo' | haml2erb
  # <div class='foo'></div>
```

```ruby
  Haml2Erb.convert('.foo')
  # => "<div class='foo'></div>\n"
```


## License

[MIT_LICENSE](/elia/haml2erb/blob/master/MIT_LICENSE)


## Credits

For the [original implementation](https://github.com/c1sgo/haml2erb): 

[Chris Goddard](https://github.com/cgoddard)
[Louis Sivillo](https://github.com/BeaconInteractive)
