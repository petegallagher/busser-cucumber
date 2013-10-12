[![Gem Version](https://badge.fury.io/rb/busser-cucumber.png)](http://badge.fury.io/rb/busser-cucumber) [![Dependency Status](https://gemnasium.com/RoboticCheese/busser-cucumber.png)](https://gemnasium.com/RoboticCheese/busser-cucumber) [![Build Status](https://travis-ci.org/RoboticCheese/busser-cucumber.png?branch=master)](https://travis-ci.org/RoboticCheese/busser-cucumber) [![Code Climate](https://codeclimate.com/github/RoboticCheese/busser-cucumber.png)](https://codeclimate.com/github/RoboticCheese/busser-cucumber)

# Busser::Cucumber

A Busser runner plugin for Cucumber.

## Installation

See the [Busser](https://github.com/fnichol/busser) and
[Test Kitchen](https://github.com/opscode/test-kitchen) pages for more details.

## Usage

Place test files in [COOKBOOK]/test/integration/[SUITE]/cucumber/

    cookbook
        -- test
            -- integration
                -- default
                    -- cucumber

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

- Author:: Jonathan Hartman (<j@p4nt5.com>)

Based mostly on work by [Adam Jacob](https://github.com/adamhjk) on
[busser-rspec](https://github.com/adamhjk/busser-rspec), in turn based on work
done by [Daisuke Higuchi](https://github.com/cl-lab-k) on
[busser-serverspec](https://github.com/cl-lab-k/busser-serverspec).

## License

Apache 2.0 (see [LICENSE](license.txt)).