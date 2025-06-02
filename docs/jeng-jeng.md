---
title: Tralalelo
slug: Tralala
sidebar_label: Simpansini Bananini
---
![pod.png](https://raw.githubusercontent.com/KenniHK/docusaurus_CMS/main/static/img/pod.png)


```HTML
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/js/bootstrap.min.js" integrity="sha384-RuyvpeZCxMJCqVUGFI0Do1mQrods/hhxYlcVfGPOfQtPJh0JCw12tUAZ/Mv10S7D" crossorigin="anonymous"></script>
```


```python
# Solve the quadratic equation ax**2 + bx + c = 0

# import complex math module
import cmath

a = 1
b = 5
c = 6

# calculate the discriminant
d = (b**2) - (4*a*c)

# find two solutions
sol1 = (-b-cmath.sqrt(d))/(2*a)
sol2 = (-b+cmath.sqrt(d))/(2*a)

print('The solution are {0} and {1}'.format(sol1,sol2))
```


![tesSS.png](https://raw.githubusercontent.com/KenniHK/docusaurus_CMS/main/static/img/tesSS.png)


```javascript
// program to find the sum of natural numbers using recursion

function sum(num) {
    if(num > 0) {
        return num + sum(num - 1);
    }
    else {
        return num;
    }
 }

// take input from the user
const number = parseInt(prompt('Enter a positive integer: '));

const result = sum(number);

// display the result
console.log(`The sum is ${result}`);
```


:::note Testing Note
Ini Testing Admonition Node
::::


:::tip Testing TIP
testing admonition tip
::::



:::danger Testing admoni
DANGER
::::



import Tabs from '@theme/Tabs'; 
import TabItem from '@theme/TabItem';

<Tabs>
 <TabItem value="apple" label="Apple" default>
      Ini apple
      </TabItem>
 <TabItem value="banana" label="Banana">
      Ini banana
      </TabItem>
 <TabItem value="melon" label="Melon">
      ini melon
      </TabItem>
</Tabs>


