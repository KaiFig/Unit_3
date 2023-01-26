
## Example 1:

### Python 
```.py
from kivymd.app import MDApp

class example1(MDApp):
  def build(self)
    return
test = example()
test.run()
```

### Kivy

```.kv
Screen:
  size: 500, 500
  
  MDLabel:
    text: "Hello World"
    halign: "center"
    font_size: "34pt"

```

## Example 2:
### Python:

```.py
from kivymd.app import MDApp

class example2(MDApp):
  def build(self):
    return
  def close(self):
    exit()
test = example2()
test.run()
```
### Kivy:

```.kv
Screen:
  size: 500, 500
  MDBoxLayout:
    pos_hint: {"center_x": 0.5}
    size_hint: .7, .7
    md_bg_color: "#fdfcdc"
    orientation: "vertical"
    
    MDLabel:
      text: "Hello World"
      halign: "center"
      font_size: "34pt"
    
    MDRaisedButton:
      text: "Close"
      size_hint: .5, 1
      font_size: "34pt"
      md_bg_color: "#f07167"
      on_press:
        app.close()
        
```

## Example 3:
### Python: 
```.py
from kivymd.app import MDApp

class example3(MDApp):
  def build(self):
    return
  
  def change_author(self, name):
    self.root.ids.title.text = f"Author {name}"
test = example3()
test.run()
```
### Kivy
```.kv
Screen:
  size: 500, 500
  MDLabel:
    id: title
    text: ""
    font_style = "H1"
    pos_hint: {center_y: .8}
    halign: "center"
  
  MDBoxLayout:
    pos_hint: {"center_x": 0.5, "center_y": .5}
    size_hint: .7, .2
    orientation: "horizontal"
      
    MDChip:
      text: "Author A"
      pos_hint

