# Thesis Diplom Project - Models to thickness of tree in the city (Alnus glutinosa)

### You have reached the repository of my calculations for my diploma thesis

### Height curve:
- $hw=(\\frac{d_{1.3}}{1.6815+0.1704 \\cdot d_{1.3}} )^2 +1.3$

### Linear regression:
- $V=1.2489 \\cdot 10^{-3} \\cdot {d_{1.3}}^2 - 0.1830$ - model based on breast tree | Model I
- $V=4.5549 \\cdot 10^{-5} \\cdot {d_{1.3}}^2 \\cdot h + 0.0894$ - model based on breast tree and height | Model II

$q_2=\\frac{d_{1\/2h}}{d_{1.3}}$, $q_3=\\frac{d_{1\/3h}}{d_{1.3}}$
- $V=5.6277 \\cdot 10^{-5} \\cdot {d_{1.3}}^2 \\cdot h \\cdot q_3 + 0.0426$ - model based on breast tree, height and coefficient q3 | Model III
- $V=5.4955 \\cdot 10^{-5} \\cdot {d_{1.3}}^2 \\cdot h \\cdot q_2 + 0.1050$ - model based on breast tree, height and coefficient q2 | Model IV

### Power regression:

- $V={2.1346 \\cdot 10^{-5}} \\cdot ({d_{1.3}}\\cdot h \\cdot q_3)^{1.6884}$ - model based on breast tree, height and coefficient q3 | Model V
- $V={2.3013 \\cdot 10^{-5}} \\cdot ({d_{1.3}}\\cdot h \\cdot q_2)^{1.6978}$ - model based on breast tree, height and coefficient q2 | Model VI

### Multiple regression:

- $V= 0.1615 \\cdot d_{1.3} - 0.2483 \\cdot h + 1.2059$ - model based on breast tree and height | Model VII
- $V= 0.1569 \\cdot d_{1.3} - 0.2262 \\cdot h + 2.1227 \\cdot q_3 - 0.9633$ - model based on breast tree, height and coefficient q3 | Model VIII
- $V= 0.1511 \\cdot d_{1.3} - 0.2018 \\cdot h + 2.6600 \\cdot q_2 - 1.5764$ - model based on breast tree, height and coefficient q2 | Model IX
