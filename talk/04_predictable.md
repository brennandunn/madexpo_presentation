!SLIDE
# Predictable #

!SLIDE
    @@@ ruby

    class BlogPost
      def publish!
        update_attribute :published_at,
                          Time.now
      end
    end

!SLIDE bullets incremental
* Obvious naming
* Follows conventions
* Designed by tests

!SLIDE
    @@@ javascript
    var t = 102;

## or... ##
    
    @@@ javascript
    var tempAsFahrenheit = 102;

!SLIDE
## Be inspired by the product's domain ##

!SLIDE
    @@@ ruby

    class Assignment
      def turn_in! ; end
    end

!SLIDE
# Great code is predictable, both in structure and placement #

!SLIDE center
## Read this: ##
![CC](cleancode.jpg)
