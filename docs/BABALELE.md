BABALELE
**BABALELE BOLD**
*BABALELE ITALIC*
***BABALELE BOLD ITALIC***

List BABALELE :
- BABALELE 1
- BABALELE 2
- BABALELE 3
- BABALELE 4
- BABALELE 5

# Heading 1 BABALELE
## Heading 2 BABALELE

![docusaurus-logo.png](https://raw.githubusercontent.com/KenniHK/docusaurus_CMS/main/static/img/docusaurus-logo.png)


```python
def jpeg_res(filename):
   """"This function prints the resolution of the jpeg image file passed into it"""

   # open image for reading in binary mode
   with open(filename,'rb') as img_file:

       # height of image (in 2 bytes) is at 164th position
       img_file.seek(163)

       # read the 2 bytes
       a = img_file.read(2)

       # calculate height
       height = (a[0] << 8) + a[1]

       # next 2 bytes is width
       a = img_file.read(2)

       # calculate width
       width = (a[0] << 8) + a[1]

   print("The resolution of the image is",width,"x",height)

jpeg_res("img1.jpg")
```

:::tip python
ini isi admonition
::::

import Tabs from '@theme/Tabs'; 
import TabItem from '@theme/TabItem';

<Tabs>
 <TabItem value="swewecxvg" label="BABALELE TAB 1" default>
      BABA LELE 1
      </TabItem>
 <TabItem value="bbblll2" label="BABALELE TAB 2">
      BABA LELE 2
      </TabItem>
 <TabItem value="bbblll3" label="BABALELE TAB 3">
      BABA LELE 3
      </TabItem>
</Tabs>

