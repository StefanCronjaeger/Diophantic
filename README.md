# $\frac{a}{b+c}+\frac{b}{c+a}+\frac{c}{a+b}=4$
- [Deutsche Version](#deutsch)

The solution shall consist in Natural numbers, so $a,b,c \in \mathbb{N}$. 

We use Python, Jupyter Notebooks and the Python Module Sympy. There is an English and a German version of the Jupyter notebook. 

We recommend to install Python and Jupyter through [Anaconda](https://www.anaconda.com/products/distribution) which also yields a free distribution. Sympy can be installed through `pip install sympy`. 

The solution follows an article published in [Spektrum der Wissenschaft](www.spektrum.de) 11.2022 page 73. 

It uses an elliptic curve and the construction of additional rational points through tangents at or lines through rational points and their intersection with the elliptic curve. 

### Method: 
- Multiply the equation with (a+b)(b+c)(c+a) to yield a homogenic equation of third order in a,b,c. 
- Divide this equation by $c^3$ to yield an equation in $x=a/c$ and $y=b/c$ of third order in x and y. 
- Use 2 known solutions x,y = (-4,-11) and x,y = (-11,-4) to find additional rational points on the curve.
- Use these additional points with tangents and lines through these points to find additional rational points on the curve until there is a point (x,y) with x and y both greater than 0.
- Calculate a,b,c from this x and y. 


<a id='deutsch'></a>
# Deutsche Version
Die Lösung soll in natürlichen Zahlen bestehen, also $a,b,c \in \mathbb{N}$. 

Wir verwenden Python, Jupyter Notebooks und das Python-Modul Sympy. Es gibt eine englische und eine deutsche Version des Jupyter Notebooks. 

Wir empfehlen, Python und Jupyter über [Anaconda](https://www.anaconda.com/products/distribution) zu installieren, das auch eine freie Distribution liefert. Sympy kann über `pip install sympy` installiert werden. 

Die Lösung folgt einem Artikel, der in [Spektrum der Wissenschaft](www.spektrum.de) 11.2022 Seite 73 veröffentlicht wurde. 

Sie verwendet eine elliptische Kurve und die Konstruktion zusätzlicher rationaler Punkte durch Tangenten an oder Linien durch rationale Punkte und deren Schnittpunkt mit der elliptischen Kurve. 

### Methode: 
- Multipliziere die Gleichung mit (a+b)(b+c)(c+a), um eine homogene Gleichung dritter Ordnung in a,b,c zu erhalten. 
- Dividiere diese Gleichung durch $c^3$, um eine Gleichung in $x=a/c$ und $y=b/c$ dritter Ordnung in x und y zu erhalten. 
- Benutze 2 bekannte Lösungen x,y = (-4,-11) und x,y = (-11,-4), um weitere rationale Punkte auf der Kurve zu finden.
- Benutze diese zusätzlichen Punkte mit Tangenten und Geraden durch diese Punkte, um weitere rationale Punkte auf der Kurve zu finden, bis es einen Punkt (x,y) gibt, bei dem x und y beide größer als 0 sind.
- Berechne a,b,c aus diesem x und y. 
    
