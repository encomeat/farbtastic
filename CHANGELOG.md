
# Change Log


## 2014-09-08

(by mach3 <http://github.com/mach3>)

- Fix: $.fn.bind/unbind is deprecated
- Fix: Fail to parse options when it is key-value object  
  (options should be validated whether it's function or string)
- Fix: $.brower object is deperecated  
  Instead of it, add `$.support.canvas` and `$.support.excanvas`
- Improvement: Add `$.support.farbtastic` to check supports for running farbtastic
- Improvement: Trigger "farbtastic.change" event when color changed at instance/container
- Improvement: Add "color" option to set default color
- Improvement: Add on/off/trigger to instance to deal with event
