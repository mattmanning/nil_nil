# nil_nil
Calling an undefined method on nil returns nil

## Install

```
$ gem install nil_nil
```

## Usage

```
$ irb
> nil.foo
NoMethodError: undefined method `foo' for nil:NilClass

> require 'nil_nil'
 => true

> nil.foo
 => nil
