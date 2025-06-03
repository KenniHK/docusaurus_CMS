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
print(isinstance(obj_triangle, Polygon))	# true
```


Testing Tab :
import Tabs from '@theme/Tabs'; 
import TabItem from '@theme/TabItem';

<Tabs>
 <TabItem value="tab 1" label="Ini Tab 1" default>
      Testing tab 1
      </TabItem>
 <TabItem value="tab 2" label="Ini Tab 2">
      Testing tab 2
      </TabItem>
 <TabItem value="tab 3" label="Ini Tab 3">
      Testing tab 3
      </TabItem>
 <TabItem value="tab 4" label="Ini tab 4">
      Testing tab 4
      </TabItem>
 <TabItem value="tab 5" label="Ini tab 5">
      Testing tab 5
      </TabItem>
</Tabs>
