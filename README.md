# frequent-algorithm

`frequent-algorithm` is a Ruby implementation of the FREQUENT algorithm
for identifying frequent items in a data stream in sliding windows.
Please refer to [Identifying Frequent Items in Sliding Windows over On-Line
Packet Streams](http://erikdemaine.org/papers/SlidingWindow_IMC2003/), by
Golab, DeHaan, Demaine, L&#243;pez-Ortiz and Munro (2003).

## Getting Started

Bacon ipsum dolor amet short loin flank swine ham hock tail. T-bone biltong
beef shoulder salami, leberkas pork chop ribeye pork belly ground round. Filet
mignon pork chop spare ribs brisket pastrami picanha bacon, biltong beef ribs
corned beef ham hock tail. Meatloaf kielbasa turducken, salami chuck beef ribs
venison hamburger t-bone landjaeger pork chop drumstick sausage bacon.


## Usage

    require 'frequent-algorithm'

## Development 

The development of this gem requires the following:

* [Ruby 2.0 or greater](https://www.ruby-lang.org/en/)
* [rubygems](https://rubygems.org/pages/download)
* [`bundler`](https://github.com/bundler/bundler)
* [`rake`](https://github.com/ruby/rake)
* [`yard`](https://rubygems.org/gems/yard) (documentation)
* [`rdiscount`](https://rubygems.org/gems/rdiscount) (Markdown)

Building, testing and release of this rubygem uses the following
`rake` commands:


    rake build    # Build frequent-algorithm-n.n.n.gem into the pkg directory
    rake clean    # Remove any temporary products
    rake clobber  # Remove any generated file
    rake install  # Build and install frequent-algorithm-n.n.n.gem into system gems
    rake release  # Create tag vn.n.n and build and push frequent-algorithm-n.n.n.gem to Rubygems
    rake test     # Execute unit tests


### Documentation

`frequent-algorithm` uses [`yard`](https://rubygems.org/gems/yard) and
[`rdiscount`](https://rubygems.org/gems/rdiscount) for Markdown documentation.
Check out [Getting Started with
Yard](http://www.rubydoc.info/gems/yard/file/docs/GettingStarted.md).

### Unit Testing

`frequent-algorithm` uses
[`MiniTest::Unit`](https://github.com/seattlerb/minitest) for
unit testing.

### Releasing

Please refer to Publishing To Rubygems.org in the
[Rubygems Guide](http://guides.rubygems.org/make-your-own-gem/).

### Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## License

frequent-algorithm is provided under the terms of the MIT license.

Copyright &copy; 2015, Willie Tong &amp; Brooke M. Fujita. All rights reserved.
