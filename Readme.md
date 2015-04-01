## How do I... ##

I want to move folder1/some_class.rb to folder2/some_class.rb AND change it to have these contents:

```
module SomeAbstractModule
  module Something1
    class SomeClass
      def some_method
        puts "hello!"
      end
    end
  end
end
```

with a single commit so that I can run `git log --follow folder2/some_class.rb` to see the entire history of the file.
