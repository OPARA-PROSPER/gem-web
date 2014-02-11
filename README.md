# Gem::Web

This gem plugin opens the webpage for a gem. As default it tries
to find the github page.

## Installation

    $ gem install gem-web

## Usage

To open the github page of the rails gem enter this:

    $ gem web rails

You could also open the documentation or the webpage that is defined in the gemspec by
adding a paramter to the command.

    Options:
      -g, --github                     Open github page of gem, this searches all urls for a github page. This is the default.
      -c, --sourcecode                 Open sourcecode gem
      -d, --doc                        Open documentation of gem
      -w, --webpage                    Open webpage of gem

If the specified page was not found, it opens the rubygems.org page for the gem.

## Thanks

Thanks to [@grosser](http://github.com/grosser) for the inspiration to
this little gem plugin.

## Contributing

1. Fork it ( http://github.com/bitboxer/gem-web/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
