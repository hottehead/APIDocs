# Classes

## Class 1
```lua
-- Meta class
Rectangle = {area = 0, length = 0, breadth = 0}

-- Derived class method new
function Rectangle:new (o,length,breadth)
o = o or {}
  setmetatable(o, self)
  self.__index = self
  self.length = length or 0
  self.breadth = breadth or 0
  self.area = length*breadth;
  return o
  end
```
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At
vero eos et accusam et

<aside class="success">
Remember — Some Important Stuff!
</aside>

### Fields
Type | Name | Description
-------- | -------- | -----------
number | index | Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
boolean | isActive | Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam

### Methods
Name | Parameter | Returns | Description
-------- | -------- | ------- | -----
function1 | arg1, arg2 | nil | Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
function2 | arg1 | nil | Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
