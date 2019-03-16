# FreeCAD A3 Size TitleBlock

## Usage
* Copy this code to FreeCAD python console.
* Change various strings accordingly.
```def my_title_block():
    t = TitleBlock()
    t.scale = 'Scale 2:1'
    t.company = 'UET Inc.'
    t.title = 'Quick Title bar'
    t.designer = ('H.S','9/1/19')
    t.drawer = ('Python', '2/2/19')
    t.checker = ('J.H', '2/2/20')
    t.standard = ('ISO', '2018')
    t.approver = ('A.A', '8/12/21')
    t.sheet = (1,10)
    t.draw()
    ```
* It'll automatically create title block centered at origin.
