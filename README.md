---
description: Robert Johansson, Numerical Python
---

# Integrais-com-Python

### Integrais

Cobrimos aqui diferentes aspectos das integrais, com foco principal na integração numérica. Por razões históricas, integrais também são conhecidas como quadraturas. Integração é significativamente mais difícil do que sua operação inversa: diferenciação. Para realizarmos a integração simbólica, podemos usar o **SymPy**, e para calcular as integrais, podemos usar principalmente o módulo _Integrate_ do **SciPy**.

### Importando os módulos

Vamos usar de modo usual as bibliotecas **NumPy** e **Matplolib** para numeração básica e a ajuda de gráficos e, além disso, usamos o módulo _Integrate_ do **SciPy** e a biblioteca matemática **mpmath**.

```python
import numpy as np
import matplotlib.pyplot as plt 
import maplotlib as mpl
from scipy import integrate
import sympy
import mpmath
```

Para um output bem formatado do **SymPy**, vamos configurar seu sistema de impressão.
