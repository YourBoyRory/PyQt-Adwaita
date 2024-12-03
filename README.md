# PyQt-Adwaita

Simple style sheet to makee PyQt look like Sorta like Adwaita<br>
make sure to add ``setObjectName("Frame")`` to make sure the window color is correct
```python
class MyFrame(QWidget):
  def __init__(self):
    self.setObjectName("Frame")
    with open("/path/to/Adwaita-Dark.qss", "r") as f:
      self.setStyleSheet(f.read())
```
