Testing Format Text :
**Bold**
*Italic*
## Heading
***Bold italic***

List :
- List 1
- List 2
- List 3
- List 4
- List 5

![pod.png](https://raw.githubusercontent.com/KenniHK/docusaurus_CMS/main/static/img/pod.png)

Snippet Code :

```python
class Polygon:
    def sides_no(self):
        pass

class Triangle(Polygon):
    def area(self):
        pass

obj_polygon = Polygon()
obj_triangle = Triangle()

print(type(obj_triangle) == Triangle)   	# true
print(type(obj_triangle) == Polygon)    	# false

print(isinstance(obj_polygon, Polygon)) 	# true
print(isinstance(obj_triangle, Polygon))
```
