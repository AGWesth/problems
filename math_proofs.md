# Proof File


## Proof $(a+b)^2 = a^2+2ab+b^2$

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/b/2/csm_kvadratsaetninger_1-2_0211284f45.png)

$a$ og $b$ er to vilkårlige positive tal. På tegningen er de vist som to linjestykker med længderne $a$ og $b$.  I forlængelse af hinanden bliver de til linjestykket $a+b$.
Det samme areal kan også bestemmes som summen af to kvadrater og to rektangler, idet figuren skæres igennem med en lodret og en vandret linje som vist.
![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/f/3/csm_kvadratsaetninger1_c6a3ea3b6b.png)

$$Areal = a^2 + b^2 + ab + ab $$

Simplificeres til:

$$ Areal = a^2 + b^2 + 2ab $$

Da vi ved at Areallet af firkanten er $(a+b)^2$ kan vi nu skrive følgende:

$$ (a+b)^2 = a^2 +b^2 + 2ab $$

<div class = "pagebreak"></div>

## Proof $(a-b)^2 = a^2 +b ^2 -2ab$

Et tal i 2. potens er lig med tallet ganget med sig selv.

$(a-b)^2 = (a-b)\cdot(a-b)$

Vi bruger FOIL til at gange paranters ud

$a\cdot a - ab - ab + b\cdot b$

Som er det samme som

$a^2 - 2ab + b^2$

<div class = "pagebreak"></div>

## Proof $(a-b)(a+b) = a^2 - b^2$

**Bevis**

1:

$$(a - b) \cdot (a + b) = a \cdot a + a \cdot b - a \cdot b - b \cdot b$$

Parenteserne ganges med hinanden, idet hvert led i den ene parentes ganges med hvert af leddene i den anden.

2:

$$= a \cdot a - b \cdot b = a^2 - b^2$$

De to midterste led går ud med hinanden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof $(a+b)^3 = a^3+3a^2b + 3ab^2 + b^3$


1:

$$(a + b)^3 = (a + b)(a + b)^2 = (a + b)(a^2 + b^2 + 2ab)$$

Der omskrives så 1. kvadratsætning kan bruges.

$$= a^3 + ab^2 + 2a^2b + a^2b + b^3 + 2ab^2$$

Parenteserne ganges sammen.


$$(a + b)^3 = a^3 + 3a^2b + 3ab^2 + b^3$$

Der reduceres.

Q.E.D.

<div class = "pagebreak"></div>

## Proof $(a-b)^3 = a^3 - 3a^2b + 3ab^2 -b^3$


$$(a - b)^3 = (a - b)(a - b)^2 = (a - b)(a^2 + b^2 - 2ab)$$

Der omskrives så 2. kvadratsætning kan bruges.

$$a^3 + ab^2 - 2a^2b - a^2b - b^3 + 2ab^2$$

Parenteserne ganges sammen.


$$(a - b)^3 = a^3 - 3a^2b + 3ab^2 - b^3$$

Der reduceres.

Q.E.D.

<div class = "pagebreak"></div>

## Proof the general solution of the quadratic equation


$$ax^2 + bx + c = 0$$

Ligningen opstilles.


$$4a^2x^2 + 4abx + 4ac = 0$$

Ganger med \(4a\) på begge sider.


$$4a^2x^2 + 4abx + 4ac + b^2 = b^2$$

Lægger \($b^2$\) til på begge sider.


$$4a^2x^2 + 4abx + b^2 = b^2 - 4ac$$

Trækker \(4ac\) fra på begge sider.


$$(2ax)^2 + 2(2ax)b + b^2 = b^2 - 4ac$$

Omskriver med henblik på at bruge 1. kvadratsætning.


$$(2ax + b)^2 = b^2 - 4ac$$

Anvender 1. kvadratsætning.


$$2ax + b = \pm \sqrt{b^2 - 4ac}$$

Tager kvadratroden på begge sider.


$$2ax = -b \pm \sqrt{b^2 - 4ac}$$

Trækker \(b\) fra på begge sider.


$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

Deler med \(2a\) på begge sider.

Q.E.D.

<div class = "pagebreak"></div>

## Proof the general solution of the quadratic equation where c = 0

1:

$$ax^2 + bx = 0$$
$$x(ax + b) = 0$$

Ligningen opstilles og \( x \) sættes uden for parentes.


$$x = 0 \quad \vee \quad ax + b = 0$$

Nulreglen [1] anvendes.

3

$$x = 0 \quad \vee \quad x = -\frac{b}{a}$$

I den ene løsningsmulighed isoleres \( x \) på sædvanlig måde.

Q.E.D.

**[1] Nulreglen**

Nulreglen siger generelt, at hvis produktet af to tal er nul

$$a \cdot b = 0$$

Så gælder, at mindst det ene af tallene er nul

<div class = "pagebreak"></div>

## Proof the top-point of the parabola is $(x_{top};y_{top}) = (\frac{-b}{2a};\frac{-D}{4a})$

**Bevis**

$$y = ax^2 + bx + c$$

Ligningen skrives op.

$$y' = 2ax + b = 0$$

Ligningen differentieres og sættes lig med nul, da tangenthældningen i toppunktet må være nul.


$$x = -\frac{b}{2a}$$

Isolerer \( x \) ved at fratrække \( b \) på begge sider af lighedstegnet og efterfølgende deles med \( 2a \). Nu er første koordinatet fundet.


$$y = a\left(-\frac{b}{2a}\right)^2 + b\left(-\frac{b}{2a}\right) + c$$

Toppunktets \( x \)-koordinat indsættes i ligningen.


$$y = \frac{ab^2}{4a^2} + \frac{-b^2}{2a} + c = \frac{b^2}{4a} + \frac{-b^2}{2a} + c$$

Parenteserne hæves, og der ganges ind på brøkerne og reduceres.


$$y = \frac{b^2}{4a} + \frac{-2b^2}{4a} + \frac{4ac}{4a} = \frac{-b^2 + 4ac}{4a}$$

Brøkerne forlænges, så de får fælles nævner, og der sættes på fælles brøkstreg.


$$y = \frac{-(b^2 - 4ac)}{4a} = \frac{-D}{4a}$$

Sætter minus uden for parentes og erstatter \(b^2 - 4ac\) med \(D\).

Q.E.D.

<div class = "pagebreak"></div>

## Proof if $a<b$, then $k\cdot  a < k \cdot b$. *where $k$ is positive*


$$k \cdot a < k \cdot b$$

Uligheden opstilles.

$$k \cdot a - k \cdot b < 0$$

\($k \cdot b$\) trækkes fra på begge sider.


$$k \cdot (a - b) < 0$$

\(k\) sættes uden for parentes.

$$a - b < 0$$

Da produktet er negativt og \(k\) er positiv, må \(a - b\) være negativ.

$$a < b$$

\(b\) lægges til på begge sider.

Q.E.D.

**[1] Beviset forløber den "modsatte" vej**

Beviset forløber den "modsatte" vej – fra sætning til præmis. Men da alle trin også kan gennemføres den modsatte vej, er beviset gyldigt.

<div class = "pagebreak"></div>

## Proof if $a<b$, then $k\cdot  a > k \cdot b$. *where $k$ is negative*


$$k \cdot a > k \cdot b$$

Uligheden opstilles.

$$k \cdot a - k \cdot b > 0$$

\($k \cdot b$\) trækkes fra på begge sider.


$$k \cdot (a - b) > 0$$

\(k\) sættes uden for parentes.

$$a - b < 0$$

Da produktet er positivt og \(k\) er negativ, må \(a - b\) også være negativ.


$$a < b$$

\(b\) lægges til på begge sider.

Q.E.D.

**[1] Beviset forløber den "modsatte" vej**

Beviset forløber den "modsatte" vej – fra sætning til præmis. Men da alle trin også kan gennemføres den modsatte vej, er beviset gyldigt.

<div class = "pagebreak"></div>

## Proof Arealet af en trekant kan findes som det halve produkt af trekantens omkreds og den indskrevne cirkels radius 

$$
Areal = \frac{1}{2} \cdot \text{Omkreds} \cdot r
$$

eller

$$
Areal = s \cdot r
$$

hvor $s$ defineres som den halve omkreds

$$
s = \frac{1}{2}(a + b + c) = \frac{1}{2}(|BC| + |AC| + |AB|)
$$

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/9/c/csm_Areal_indskrevet_cirkel_48a5380028.png)

**Bevis**

Radius i den indskrevne cirkel danner højder i de tre deltrekanter $\triangle OAB$, $\triangle OBC$ og $\triangle OAC$.

1. 
$$
Areal_1 = \frac{1}{2} \cdot r \cdot |AB|
$$
$$
Areal_2 = \frac{1}{2} \cdot r \cdot |BC|
$$
$$
Areal_3 = \frac{1}{2} \cdot r \cdot |AC|
$$

Arealet i de tre deltrekanter findes som halv højde gange grundlinje.

2. 
$$
Areal = \frac{1}{2} \cdot r \cdot |AB| + \frac{1}{2} \cdot r \cdot |BC| + \frac{1}{2} \cdot r \cdot |AC|
$$

Trekantens areal er lig summen af de tre deltrekanters arealer.

3. 
$$
= \frac{1}{2} \cdot r \cdot (|AB| + |AC| + |BC|)
$$

$\frac{1}{2}r$ sættes uden for parentes.

4. 
$$
= \frac{1}{2} \cdot r \cdot 2 \cdot s = r \cdot s
$$

Da $2 \cdot s = |AB| + |AC| + |BC|$ er identisk med trekantens omkreds.

Q.E.D.

<div class = "pagebreak"></div>

## Proof En vilkårlig trekants areal kan bestemmes som $Areal = \frac{a \cdot b \cdot c}{4 \cdot R}$

hvor a,b,c er trekantens sidelængder, og R er radius i den omskrevne cirkel.

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/1/d/csm_omskrevne_cirkel_trekantareal_9eba158774.png)

I den omskrevne cirkel er der indtegnet en diameter fra punktet $A$. Diameterens andet skæringspunkt med cirklen kaldes $A'$.

1.
$$
\angle A' = \angle B
$$

Begge vinkler er perifervinkler, der spænder over samme bue.

2.
$$
\triangle AA'C \text{ er retvinklet}
$$

Da centervinklen mellem $A$ og $A'$ er $180^\circ$, må perifervinklen repræsenteret ved $\angle ACA'$ være $90^\circ$.

3.
$$
\sin(A') = \frac{b}{|AA'|} = \frac{b}{2 \cdot R}
$$

$\triangle AA'C$ er retvinklet og diameteren $|AA'| = 2 \cdot R$, og sinus til en vinkel er lig med modstående katete divideret med hypotenusen.

4.
$$
\sin(A') = \sin(B) = \frac{b}{2 \cdot R}
$$

Da $\angle A' = \angle B$.

5.
$$
\sin(C) = \frac{c}{2 \cdot R}
$$
$$
\sin(A) = \frac{a}{2 \cdot R}
$$

Ved bogstavombytning gælder det samme for de øvrige vinkler.

6.
$$
Areal = \frac{1}{2} \cdot a \cdot b \cdot \sin(C) = \frac{1}{2} \cdot a \cdot b \cdot \frac{c}{2 \cdot R}
$$

Formlen for arealet af en trekant anvendes.

7.
$$
Areal = \frac{a \cdot b \cdot c}{4 \cdot R}
$$

Der reduceres.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Arealet af en trekant kan findes som det halve produkt af to sidelængder og sinus til den mellemliggende vinkel

$$ Areal = \frac{1}{2} \cdot a \cdot b \cdot \sin(C) $$ $$ Areal = \frac{1}{2} \cdot a \cdot c \cdot \sin(B) $$ $$ Areal = \frac{1}{2} \cdot b \cdot c \cdot \sin(A) $$


![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/1/c/csm_trekantens_areal_II_48493ba997.png)

I trekanten $\triangle ABC$ er højden $h$ indtegnet. 
$$ Areal = \frac{1}{2} \cdot h \cdot g = \frac{1}{2} \cdot h \cdot b $$ Bestemmer arealet af trekanten. 
$$ \sin(C) = \frac{h}{a} \iff h = a \cdot \sin(C) $$ Bestemmer højden $h$ vha. sinus i den retvinklede trekant. 
$$ Areal = \frac{1}{2} \cdot a \cdot \sin(C) \cdot b = \frac{1}{2} \cdot a \cdot b \cdot \sin(C) $$ 
Substituerer $h$ i udregning 1 og bytter om på faktorerne. De andre versioner af formlen findes på samme måde, og sætningen er vist for en spidsvinklet trekant. 

**Bevis for stumpvinklet trekant**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/7/d/csm_Stumpvinklet_trekant_decdbc8a6b.png)


 $$ Areal = \frac{1}{2} \cdot h \cdot g = \frac{1}{2} \cdot h \cdot b $$ Bestemmer arealet af trekanten. 
 $$ \sin(180^\circ - C) = \frac{h}{a} \iff h = a \cdot \sin(180^\circ - C) $$ Bestemmer højden vha. sinus i den retvinklede trekant og isolerer $h$. 6. $$ Areal = \frac{1}{2} \cdot a \cdot \sin(180^\circ - C) \cdot b $$ Substituerer $h$ i udregning 4. 7. $$ Areal = \frac{1}{2} \cdot a \cdot b \cdot \sin(C) $$ Da $\sin(180^\circ - C) = \sin(C)$ kan sinus omskrives, og der byttes rundt på faktorerne. De andre versioner findes på samme måde. 

Q.E.D.

<div class = "pagebreak"></div>

## Proof Arealet af en trekant som halv højde gange grundlinje

$Areal = \frac{1}{2}\cdot højde \cdot grundlinje = \frac{1}{2}\cdot h \cdot g$

**Bevis 1**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/5/7/csm_Spidsvinklet_trekant_db87d9ea78.png)

Gennem $B$ trækkes en linje parallel med $AC$. Gennem $A$ og $C$ trækkes linjer parallelle med højden $h$. Derved dannes et rektangel.
 $$ Areal = h \cdot |AC| $$ Arealet af rektanglet = højde gange bredde. 
 $$ Areal = 2 \cdot A_1 + 2 \cdot A_2 $$ Rektanglet er sammensat af to mindre rektangler med $|AB|$ og $|BC|$ som diagonaler. De to mindre rektangler er igen delt op i to kongruente trekanter med arealerne $A_1$ og $A_2$. 
 $$ h \cdot |AC| = 2 \cdot A_1 + 2 \cdot A_2 = 2 \cdot (A_1 + A_2) $$ Arealet af det store rektangel findes derfor også som summen af de to mindre rektangler. 
 $$ Areal = A_1 + A_2 = \frac{1}{2} \cdot h \cdot |AC| = \frac{1}{2} \cdot h \cdot g $$ Da trekantens areal er $A_1 + A_2$. Q.E.D. 

 **Bevis del 2: Stumpvinklet trekant**
 ![Stumpvinklet trekant](https://bevissamling.systime.dk/fileadmin/_processed_/8/f/csm_trekantens_areal_I_d703add5a0.png) $$ A_r = h \cdot (b + x) $$ Arealet af hele rektanglet i figuren findes som højde gange bredde. 
 $$ Areal = h(b + x) - \frac{1}{2} hx - \frac{1}{2} h(b + x) = \frac{1}{2} hb = \frac{1}{2} hg $$ 
Arealet af trekanten findes som arealet $A_r$ af rektanglet fratrukket de to spidsvinklede trekanters arealer. 

Q.E.D.

<div class = "pagebreak"></div>

## Proof Vinkelsummen i en vilkårlig trekant er 180°

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/4/f/csm_trekantens_vinkelssum_86de721864.png)

Gennem en af trekantens vinkelspidser, i dette tilfælde $B$, tegnes en linje, der er parallel med $AC$. Dernæst forlænges $|AB|$ og $|CB|$ gennem $B$. Derved dannes vinklerne $m$, $u$, $v$, $w$, $x$, $z$.

$$
w + x + z = 180^\circ
$$
og
$$
\angle B + z + x = 180^\circ
$$

Da summen af de tre vinkler i begge tilfælde er en lige vinkel.

$$
w + x + z = \angle B + z + x
$$

De to venstresider sættes lig hinanden.

$$
\angle B = w
$$

$x$ og $z$ trækkes fra på begge sider af lighedstegnet.

$$
\angle A = x
$$
og
$$
\angle C = v
$$

Da vinklerne $\angle A$ og $x$ henholdsvis $\angle C$ og $v$ er ensliggende. [^1]

$$
v + w + x = 180^\circ
$$

Da summen af de tre vinkler er en lige vinkel.

$$
\angle A + \angle B + \angle C = 180^\circ
$$

Da $\angle A = x$, $\angle B = w$ og $\angle C = v$.

Q.E.D.

[^1]: Ensliggende vinkler er vinkler, der opstår, når en linje skærer to andre linjer og de ligger "på samme side" af den skærende linje.

<div class = "pagebreak"></div>


## Proof De tre medianer i en trekant skærer hinanden i samme punkt og deler medianerne i forholdet 1:2.

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/3/7/csm_medianer_54fc424120.png)

I trekanten er der indtegnet de tre medianer $m_a$, $m_b$ og $m_c$ samt siderens midtpunkter $M_a$, $M_b$ og $M_c$. Skæringspunktet mellem to vilkårlige medianer (her $m_a$ og $m_c$) kaldes for $M$.

$$
\triangle ABC \text{ er ensvinklet med } \triangle M_cBM_a.
$$

Fordi $M_aM_c$ er midtpunktstransversal.

Da $M_aM_c \parallel AC$ er de markerede vinkler i de farvede trekanter $\triangle AMC$ og $\triangle M_cMM_a$ lige store.

Da siden $M_cM_a$ er halvt så lang som $AC$, er alle siderne i de $\triangle M_cMM_a$ halvt så lange som siderne i $\triangle AMC$.

Derfor er $MM_a = \frac{1}{2} AM$ og $MM_c = \frac{1}{2} MC$. Altså deler $M$ disse to medianer i forholdet 1:2 regnet fra trekantens sider.

Da de to medianer var vilkårlige må der derfor gælde at alle medianer indbyrdes deler hinanden i forholdet 1:2.

Da medianerne to og to deler hinanden i forholdet 2:1 må skæringspunktet være det samme i alle tre kombinationer. Medianerne skærer derfor hinanden i det samme punkt.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Et punkt på en vinkelhalveringslinje har samme vinkelrette afstande til de to vinkelben.

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/6/d/csm_vinkelhalvering_f3b85ce270.png)


Punktet $P$ ligger på vinkelhalveringslinjen. De to vinkler $u$ er ens på grund af definitionen af en vinkelhalveringslinje.

De to trekanter $\triangle ABP$ og $\triangle ACP$ har samme vinkler og er dermed ligedannede.

$$
|BP| = |CP|
$$

Da de begge har hypotenusen $AP$ fælles, er de kongruente. Dermed er sidelængderne parvis ens.

Q.E.D.

<div class = "pagebreak"></div>

## Proof En midtpunktstransversal, der er et linjestykke, som forbinder to sidemidtpunkter i en trekant, er parallel med den tredje side i trekanten og halvt så lang som denne

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/e/9/csm_midtpunkttransversal_d2bd27afc4.png)


$$
BB' = BC = 0.5 \cdot a
$$
$$
AA' = A'C = 0.5 \cdot a
$$

I $\triangle ABC$ er der tegnet linjen $A'B'$ parallel med $AB$, og hvor punktet $A'$ er midpointet af linjestykket $AC$. Hvis vi kan vise, at $B'$ også er midtpunkt af linjestykket $BC$, er sætningen bevist.

$$
\angle A = \angle A'
$$
$$
\angle B = \angle B'
$$

Da linjestykket $A'B'$ er parallelt med $AB$.

$$
\triangle ABC \text{ ensvinklet med } \triangle A'B'C
$$

Da $\angle C$ er ens for begge trekanter, og de to andre vinkler er ensliggende ved parallelle linjer.


$$
|AA'| = 0.5 \cdot |AC|
$$

Og dermed er skaleringsfaktoren mellem de to trekanter $0.5$.

Da punktet $A'$ er midtpunktet på linjestykket $AC$.

$B'$ må være midtpunkt af linjestykket $BC$, da
$$
|BB'| = 0.5 \cdot |BC|
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Herons formular ved Pythagoras

Arealet af en trekant kan findes alene med trekantens sidelængder ved hjælp af formlen

$$
Areal = \sqrt{s \cdot (s - a) \cdot (s - b) \cdot (s - c)}
$$

hvor $s = \frac{1}{2}(a + b + c)$ er trekantens halve omkreds og $a$, $b$, $c$ er sidelængderne.

**Bevis**

![Trekant med højde](https://bevissamling.systime.dk/fileadmin/_processed_/7/5/csm_heron_561bc8452c.png)


$$
b = \sqrt{a^2 - h^2} + \sqrt{c^2 - h^2}
$$

Pythagoras benyttes til at finde sidelængden $b$ som summen af to kateter i de to retvinklede trekanter $\triangle ABB'$ og $\triangle B'BC$.


$$
b^2 = \left( \sqrt{a^2 - h^2} + \sqrt{c^2 - h^2} \right)^2
$$

Ligningen kvadreres.


$$
b^2 = \left( \sqrt{a^2 - h^2} \right)^2 + \left( \sqrt{c^2 - h^2} \right)^2 + 2 \sqrt{a^2 - h^2} \cdot \sqrt{c^2 - h^2}
$$
$$
b^2 = a^2 - h^2 + c^2 - h^2 + 2 \sqrt{a^2 - h^2} \cdot \sqrt{c^2 - h^2}
$$

Parentesen hæves vha. 1. kvadratsætning


$$
b^2 - a^2 - c^2 + 2h^2 = 2 \sqrt{a^2 - h^2} \cdot \sqrt{c^2 - h^2}
$$

Lægger $2h^2$ til på begge sider, samt trækker både $a^2$ og $c^2$ fra på begge sider.


$$
\left( b^2 - a^2 - c^2 + 2h^2 \right)^2 = \left( 2 \sqrt{a^2 - h^2} \cdot \sqrt{c^2 - h^2} \right)^2
$$

Ligningen kvadreres igen, og tilføjer parentes om de tre første led.


$$
\left( b^2 - a^2 - c^2 \right)^2 + 4h^4 + \left( b^2 - a^2 - c^2 \right)4h^2 = 4 \cdot \left( a^2 - h^2 \right) \cdot \left( c^2 - h^2 \right)
$$

Venstresiden udregnes ved hjælp af 1. kvadratsætning, og på højresiden kvadreres hver faktor.


$$
\left( b^2 - a^2 - c^2 \right)^2 + 4h^4 + 4h^2b^2 - 4h^2a^2 - 4h^2c^2 = 4c^2a^2 - 4c^2h^2 - 4a^2h^2 + 4h^4
$$

Parenteserne på nær den første ganges ud.


$$
\left( b^2 - a^2 - c^2 \right)^2 + 4h^2b^2 = 4c^2a^2
$$

Seks led går ud med hinanden.


$$
4h^2b^2 = (2 \cdot c \cdot a)^2 - \left( b^2 - a^2 - c^2 \right)^2
$$

Leddende omrokeres.


$$
4h^2b^2 = (2 \cdot c \cdot a - (b^2 - a^2 - c^2)) \cdot (2 \cdot c \cdot a + b^2 - a^2 - c^2)
$$

Højre side omskrives ved hjælp af 3. kvadratsætning

$$
4h^2b^2 = \left( a^2 + c^2 + 2 \cdot a \cdot c - b^2 \right) \cdot \left( b^2 - \left( a^2 + c^2 - 2 \cdot a \cdot c \right) \right)
$$

Minusparentes i første parentes hæves, og leddene omrokeres. I næste parentes dannes en ny minusparentes.

$$
4h^2b^2 = \left( (a + c)^2 - b^2 \right) \cdot \left( b^2 - (a - c)^2 \right)
$$

1. kvadratsætning anvendes i første parentes, og 2. kvadratsætning anvendes i sidste parentes.


$$
4h^2b^2 = (b + c - a) \cdot (b - c + a) \cdot (b + c + a) \cdot (c + a - b)
$$

Hvert led omskrives til et produkt af to led.


$$
16 \cdot Areal^2 = (b + c - a) \cdot (b - c + a) \cdot (b + c + a) \cdot (c + a - b)
$$
$$
4 \cdot h^2 \cdot b^2 = 16 \cdot \left( \frac{1}{2} h \cdot b \right)^2 = 16 \cdot Areal^2 \text{ hvilket svarer til 16 gange arealet af trekanten i anden potens.}
$$


$$
16 \cdot Areal^2 = (2s - 2a) \cdot (2s - 2c) \cdot 2s \cdot (2s - 2b)
$$

Vi benytter udtrykket for den halve omkreds $s = \frac{1}{2}(a + b + c)$.


$$
16 \cdot Areal^2 = 2(s - a) \cdot 2(s - c) \cdot 2s \cdot 2(s - b)
$$

Sætter 2 uden for parentes i alle parenteserne.


$$
Areal = \sqrt{s \cdot (s - a) \cdot (s - b) \cdot (s - c)}
$$

Ved at dividere med 16 på begge sider af lighedstegnet og dernæst tage kvadratroden på begge sider kan udtrykket reduceres til Herons formel.

Q.E.D.

<div class = "pagebreak"></div>


## Proof Herons formular ved Cosinus Relationerne

Arealet af en trekant kan findes alene med trekantens sidelængder ved hjælp af formlen

$$
Areal = \sqrt{s \cdot (s - a) \cdot (s - b) \cdot (s - c)}
$$

hvor $s = \frac{1}{2}(a + b + c)$ er trekantens halve omkreds og $a$, $b$, $c$ er sidelængderne.

**Bevis**

![Trekant med højde](https://bevissamling.systime.dk/fileadmin/_processed_/7/5/csm_heron_561bc8452c.png)


$$
Areal = \frac{1}{2} \cdot b \cdot c \cdot \sin(A) \iff 4 \cdot Areal = 2bc \sin(A)
$$

Arealet af trekanten bestemmes ved hjælp af sinus

$$
16 \cdot Areal^2 = 4 \cdot b^2 \cdot c^2 \cdot \sin^2(A)
$$

Ligningen kvadreres.


$$
= 4 \cdot b^2 \cdot c^2 \cdot (1 - \cos^2(A))
$$

[Grundrelationen](https://da.wikipedia.org/wiki/Trigonometrisk_identitet#Grundrelationen) anvendes til at erstatte $\sin$ med $\cos$.


$$
= 2 \cdot b \cdot c \cdot (1 - \cos(A)) \cdot 2 \cdot b \cdot c \cdot (1 + \cos(A))
$$

Ligningen omskrives ved hjælp af 3. kvadratsætning.


$$
= (2 \cdot b \cdot c - 2 \cdot b \cdot c \cdot \cos(A)) \cdot (2 \cdot b \cdot c + 2 \cdot b \cdot c \cdot \cos(A))
$$

$2bc$ ganges ind i parenteserne.


$$
= (2 \cdot b \cdot c - (b^2 + c^2 - a^2)) \cdot (2 \cdot b \cdot c + (b^2 + c^2 - a^2))
$$

Udtrykket $2 \cdot b \cdot c \cdot \cos(A)$ erstattes med $b^2 + c^2 - a^2$ efter cosinusrelationen.

$$
= (2 \cdot b \cdot c - b^2 - c^2 + a^2) \cdot (2 \cdot b \cdot c + b^2 + c^2 - a^2)
$$
$$
= (- (2 \cdot b \cdot c + b^2 + c^2) + a^2) \cdot ((2 \cdot b \cdot c + b^2 + c^2) - a^2)
$$

Parenteser ophæves, og to nye parenteser sættes ind for at gøre klar til kvadratsætning 2

8.
$$
= (a^2 - (b - c)^2) \cdot ((b + c)^2 - a^2)
$$

Kvadratsætning 2 anvendes.

9.
$$
(a + (b - c)) \cdot (a - (b - c)) \cdot ((b + c) - a) \cdot ((b + c) + a)
$$
$$
(a + b - c) \cdot (a - b + c) \cdot (b + c - a) \cdot (b + c + a)
$$

Kvadratsætning 3 anvendes, og hjælpeparenteserne fjernes.

Herfra følger beviset den samme rækkefølge som beviset med udgangspunkt i Pythagoras.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Højderne i en trekant skærer hinanden i samme punkt

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/c/3/csm_hoejder_525f700789.png)

Vi skal vise at punktet $P$ er skæringspunktet for de tre højder. Der er tegnet en hjælpetrekant, hvis sider er dannet ved at parallelforskyde trekantens sider ud til trekantens hjørner og forlænge linjestykkerne indtil der opstår skæringspunkter og dermed nye vinkelspidser $A'$, $B'$, $C'$ til hjælpetrekanten.

Hjælpetrekanten og den oprindelige trekant danner tre parallelogrammer
$$\square AC'BC, \square ABA'C, \text{ og } \square ABCB'$$

Det er parallelogrammer netop fordi siderne er parallelforskudte, hvilket betyder at $AB \parallel CA'$, $AC \parallel BA'$, $AB \parallel CB'$, $AC' \parallel BC$, $AC \parallel C'B$.

Dermed er sidelængderne parvis ens: $|AC| = |BA'|$, $|AB| = |A'C|$, $|AB| = |B'C|$, $|AB| = |A'C|$, $|AB'| = |BC|$, $|AC'| = |CB|$, og $|AC| = |C'B|$.

$A$, $B$, $C$ er derfor midtpunkter for siderne i den yderste trekant, da eksempelvis $|B'C| = |CA'|$.

Højderne i $\triangle ABC$ bliver dermed midtnormaler i $\triangle A'B'C'$.

Midtnormaler går gennem samme punkt.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Midtnormalerne i en trekant går gennem samme punkt

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/1/3/csm_Midtnormaler_db5f49bee0.png)


Da $O$ ligger på midtnormalen for $AB$, ligger $O$ lige langt fra $A$ og $B$.

Da $O$ ligger på midtnormalen for $BC$, ligger $O$ lige langt fra $B$ og $C$.

Af (1) og (2) fremgår det at $O$ ligger lige langt fra $A$ og $C$. Dermed er $O$ skæringspunkt for alle tre midtnormaler.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Trekantens omskrevne cirkel har centrum i midtnormalernes skæringspunkt

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/c/7/csm_omskreven_cirkel_55befaea87.png)


Linjestykkerne $OM_a$, $OM_b$, $OM_c$ er midtnormaler til $\triangle ABC$. De skærer hinanden i punktet $O$, se bevis. Vi skal vise, at $O$ også er centrum for den omskrevne cirkel.

$$
|AM_c| = |BM_c|
$$
$$
|AM_b| = |CM_b|
$$
$$
|BM_a| = |CM_a|
$$

Midtnormalerne er netop bestemt ved hjælp af linjestykkerne midtpunkter.

$$
|OA| = |OB|
$$
$$
|OA| = |OC|
$$
$$
|OB| = |OC|
$$

$\triangle BOC$, $\triangle AOB$ og $\triangle AOC$ er ligebenede, da punkterne på midtnormalerne ligger lige langt fra linjestykkerne endepunkter.

$$
|OA| = |OB| = |OC|
$$

Af ovenstående fås direkte, at afstanden fra $O$ til trekantens vinkelspidser er den samme. Altså er $O$ cirklens centrum.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Trekantens indskrevne cirkel har centrum i det punkt, hvor trekantens vinkelhalveringslinjer skærer hinanden

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/f/d/csm_Indskrevne_cirkel_bebe417ebd.png)

Linjestykkerne $AO$, $CO$, $BO$ er vinkelhalveringslinjer i $\triangle ABC$. De skærer hinanden i punktet $O$. Vi skal vise, at $O$ også er cirklens centrum.

Fra $O$ trækker vi linjestykkerne $OP_1$, $OP_2$ og $OP_3$, der står vinkelret på trekantens sider.

$$
|OP_3| = |OP_2|
$$
$$
|OP_3| = |OP_1|
$$
$$
|OP_1| = |OP_2|
$$

Punkterne på en vinkelhalveringslinje ligger lige langt fra vinklens ben. I dette tilfælde to af trekantens sider.

$$
|OP_3| = |OP_2| = |OP_1|
$$

Følger direkte af ovenstående, da eksempelvis trekanterne $AOP_2$ og $AOP_3$ er ligedannede.

$$
|OP_3| = |OP_2| = |OP_1| = r
$$

Derfor er de tre lige lange linjestykker radius i en cirkel, som tangerer trekantens sider.

Q.E.D.

<div class = "pagebreak"></div>

## Proof En periferivinkel er halvt så mange grader som den bue, den spænder over

Beviset gennemføres ved at opdele i de tre mulige situationer.

1. Det ene vinkelben går gennem centrum, dvs. det er diameter.
2. Vinkelbenene er på hver sin side af centrum.
3. Vinkelbenene er på samme side af centrum.

**Vinkelben gennem centrum**

![Vinkelben gennem centrum](https://bevissamling.systime.dk/fileadmin/_processed_/3/b/csm_Korde_centrum_f87577e9b6.png)


Trekant $AOC$ er en ligebenet trekant. Derfor vil den ene vinkel være en topvinkel og de to øvrige vinkler være ens. Hvis en af de øvrige vinkler benævnes $v$, så må topvinklen være $180^\circ - 2v$. Da $\angle AOB = 180^\circ$ må $\angle COB = 2v$, og dermed har buen $CB$ gradstørrelsen $2v$.

**Vinkelbenene på hver sin side af centrum**

![Vinkelbenene på hver sin side af centrum](https://bevissamling.systime.dk/fileadmin/_processed_/f/c/csm_Korde_vinkelsum_c3e6f371d4.png)


Efter samme princip som ovenfor opdeles i de to trekanter $\triangle OAC$ og $\triangle OAB$, der begge er ligebenede. Det betyder ligeledes, at $v$ opdeles i to vinkler på hhv $v_1$ og $v_2$.

Efter det første tilfælde har buen $CD$ gradtallet $2v_1$ og buen $BD$ gradtallet $2v_2$. Altså har buen $BC$ gradtallet $2v_1 + 2v_2$, hvilket er det dobbelte af gradtallet for vinkel $A$.

**Vinkelbenene på samme side af centrum**

![Vinkelbenene på samme side af centrum](https://bevissamling.systime.dk/fileadmin/_processed_/a/1/csm_Korde_samme2_b7205c4ffc.png)

Efter samme princip som ovenfor opdeles i de to trekanter $\triangle OAC$ og $\triangle OAB$, der begge er ligebenede. Det betyder ligeledes, at $v$ kan udtrykkes som $v = v_2 - v_1$. Centervinklen findes til $2v_2 - 2v_1 = 2v$, da $v = v_2 - v_1$. Og da $v$ er det halve, er det bevist for denne tredje og sidste situation.

Q.E.D.

<div class = "pagebreak"></div>

## Proof En konveks polygon med n sider har vinkelsummen $(n-2) \cdot 180 ^\circ$



![Fig. 1](https://bevissamling.systime.dk/fileadmin/_processed_/6/2/csm_polygon_0_6b85021340.png)

En vilkårlig trekant kan udvides til en firkant ved at trække i et vilkårligt punkt på en af siderne, som vist i figuren. Derved ses også, at den nye firkant kan opdeles i to trekanter.

![Fig. 2](https://bevissamling.systime.dk/fileadmin/_processed_/b/a/csm_polygon_1_05b4e77700.png)

Det samme kan gøres ved siden på en vilkårlig konveks polygon, således at polygonen udvides med en ny kant. Derved kan dannes en række af polygoner som vist i fig. 2.



![Fig. 3](https://bevissamling.systime.dk/fileadmin/_processed_/b/6/csm_polygon_2_cc6471adb8.png)

Af rækken ses at antallet af trekanter i polygonerne hele tiden udvides med en ny trekant. De øverste tal udtrykker antallet af kanter i polygonen og de nederste antallet af trekanter. Det danner tilsammen et logisk mønster, der betyder at en $n$-polygon kan opdeles i $n - 2$ trekanter.

![fig4](https://bevissamling.systime.dk/fileadmin/_processed_/4/e/csm_polygon_3_ee24452cde.png)


Vinkelsummen i en trekant er $180^\circ$. Vinkelsummen i polygonen er derfor lig med summen af antallet af trekanter multipliceret med $180^\circ$.

Da en polygon kan opdeles i $n - 2$ trekanter, må vinkelsummen i en vilkårlig $n$-polygon være:
$$
(n - 2) \cdot 180^\circ
$$

Q.E.D.

<div class = "pagebreak"></div>


## Proof Pythagoras Theorem

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/1/3/csm_Pythagoras_I_d655304033.png)

Tegn et kvadrat med sidelængde $a + b$ som vist.

![Kvadrat med sidelængde a + b](https://bevissamling.systime.dk/fileadmin/_processed_/7/b/csm_Pythagoras_bf3a948f5a.png)


Punkterne forbindes. Derved opstår fire kongruente retvinklede trekanter med samme hypotenuse. Da $v_1 + v_2 = 90^\circ$, må den inderste firkant være et rektangel. Da dens sider er ens, må den også være et kvadrat med arealet $c^2$.


$$
c^2 = (a + b)^2 - 4 \cdot \frac{1}{2} \cdot a \cdot b
$$

Arealet af det inderste kvadrat må være det samme som arealet af det store kvadrat minus arealet af de fire trekanter. Trekanternes areal bestemmes som halv højde gange grundlinje, der så her svarer til det halve produkt af kateterne.


$$
= (a^2 + b^2 + 2 \cdot a \cdot b) - 2 \cdot a \cdot b
$$

Kvadratsætningen led.


$$
= a^2 + b^2
$$

De to identiske led går ud med hinanden, når parentesen ophæves.

Q.E.D

<div class = "pagebreak"></div>

## Proof $\sin(v)=\frac{opposite}{hypothenus}, \cos(v) = \frac{adjacent}{hypothenus}, \tan(v) = \frac{opposite}{adjacent}$

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/1/b/csm_retvinkel_85cb20028b.png)


$$
\sin v = \frac{a}{c} = \frac{\text{opposite}}{\text{hyp}}
$$

Da den røde trekant er ligedannet med \( \triangle ABC \), er forholdene mellem de tilsvarende sider det samme.


$$
\sin A = \frac{a}{c} \lor \sin v = \frac{\text{opposite}}{\text{hyp}}
$$

Reducerer brøken med sinus og udnytter at \( \sin v = \sin A \). Hermed er sætningen vist for sinus.



$$
\cos v = \frac{b}{c} = \frac{\text{adjacent}}{\text{hyp}}
$$

Da den røde trekant er ligedannet med \( \triangle ABC \), er forholdene mellem de tilsvarende sider det samme.



$$
\cos A = \frac{b}{c} \lor \cos v = \frac{\text{adjacent}}{\text{hyp}}
$$

Reducerer brøken med cosinus og udnytter at \( \cos v = \cos A \). Hermed er sætningen vist for cosinus.



$$
\tan v = \frac{a}{b} = \frac{\text{opposite}}{\text{adjacent}}
$$

Da den blå trekant er ligedannet med \( \triangle ABC \), er forholdene mellem de tilsvarende sider det samme.



$$
\tan A = \frac{a}{b} \lor \tan v = \frac{\text{opposite}}{\text{adjacent}}
$$

Reducerer brøken med tangens og udnytter at \( \tan v = \tan A \).



$$
\tan A = \frac{a}{b} = \frac{\sin A}{\cos A} \lor \tan v = \frac{\text{opposite}}{\text{adjacent}} = \frac{\sin v}{\cos v}
$$

Forholdet mellem sinus og cosinus tilføjes, da den blå trekant også er ligedannet med den røde trekant.

Q.E.D.

<div class = "pagebreak"></div>

## Proof $\cos^2 v + sin^2  v =1$

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/0/e/csm_Grundrelation_04d8f59ee4.png)

$P_v$ er retningspunktet for en vilkårlig vinkel \( v \) i enhedscirklen med koordinaterne $\cos v, \sin v$


$$
1^2 = |\sin v|^2 + |\cos v|^2
$$

Der dannes en retvinklet trekant, hvor hhv. \( |\cos v| \) og \( |\sin v| \) udgør kateterne. Hypotenusens længde er 1. Derved gælder Pythagoras' læresætning:

$$
c^2 = a^2 + b^2
$$

Numerisktegnet bruges, da sinus og cosinus kan være negative, men trekantens katetelængder er altid positive.


$$
1 = \sin^2 v + \cos^2 v
$$

Numerisktegnene forsvinder, da

$$
|k|^2 = k^2
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Cosinus Relationerner for spidsvinklet trekant

I en vilkårlig trekant er den ene side i anden plus den anden side i anden minus to gange de to sider ganget sammen gange cosinus til vinklen imellem dem lig med den modstående side i anden. Dette forhold giver følgende sammenhænge i en sædvanlig ABC-trekant. Den første er normalt den letteste at huske da den ligner Pythagoras' læresætning.


$$
c^2 = a^2 + b^2 - 2ab \cdot \cos(C)
$$

$$
b^2 = a^2 + c^2 - 2ac \cdot \cos(B)
$$

$$
a^2 = b^2 + c^2 - 2bc \cdot \cos(A)
$$

eller

$$
C = \arccos \left( \frac{a^2 + b^2 - c^2}{2ab} \right)
$$

$$
B = \arccos \left( \frac{a^2 + c^2 - b^2}{2ac} \right)
$$

$$
A = \arccos \left( \frac{b^2 + c^2 - a^2}{2bc} \right)
$$

### Bevis

![Spidsvinklet trekant](https://bevissamling.systime.dk/fileadmin/_processed_/2/0/csm_cosinusrelationerne_spids_720b1fa6ec.png)

Vi undersøger den vilkårlige spidsvinklede trekant \( \triangle ABC \).



$$
a^2 = h^2 + x^2 \quad \land \quad c^2 = h^2 + (b - x)^2
$$

Trekanten deles op i to retvinklede trekanter ved hjælp af højden \( h \). Herefter anvendes Pythagoras' læresætning på begge trekanter.



$$
h^2 = a^2 - x^2 \quad \land \quad c^2 = h^2 + (b - x)^2
$$

\( h^2 \) isoleres i første ligning.


$$
c^2 = a^2 - x^2 + (b - x)^2
$$

\( h^2 \) substitueres i den anden ligning.



$$
c^2 = a^2 - x^2 + b^2 + x^2 - 2bx
$$

Udregner parentesen vha. kvadratsætning 2

$$
c^2 = a^2 + b^2 - 2bx
$$

De to led med \( x^2 \) går ud med hinanden.



$$
\cos(C) = \frac{x}{a} \quad \iff \quad x = a \cos(C)
$$

Anvender formlen for cosinus i den retvinklede trekant og isolerer \( x \).


$$
c^2 = a^2 + b^2 - 2ab \cos(C)
$$

Substituerer \( x \) i linje 5 og skriver faktorerne op i normal rækkefølge. De andre repræsentationer for cosinusrelationen findes på samme måde som denne.

<div class = "pagebreak"></div>

## Proof Cosinus Relationerner for stumpvinklet trekant

I en vilkårlig trekant er den ene side i anden plus den anden side i anden minus to gange de to sider ganget sammen gange cosinus til vinklen imellem dem lig med den modstående side i anden. Dette forhold giver følgende sammenhænge i en sædvanlig ABC-trekant. Den første er normalt den letteste at huske da den ligner Pythagoras' læresætning.


$$
c^2 = a^2 + b^2 - 2ab \cdot \cos(C)
$$

$$
b^2 = a^2 + c^2 - 2ac \cdot \cos(B)
$$

$$
a^2 = b^2 + c^2 - 2bc \cdot \cos(A)
$$

eller

$$
C = \arccos \left( \frac{a^2 + b^2 - c^2}{2ab} \right)
$$

$$
B = \arccos \left( \frac{a^2 + c^2 - b^2}{2ac} \right)
$$

$$
A = \arccos \left( \frac{b^2 + c^2 - a^2}{2bc} \right)
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/3/9/csm_cosinusrelationerne_stump_ba1b7dc984.png)


$$
a^2 = h^2 + x^2 \quad \land \quad c^2 = h^2 + (b + x)^2
$$

Pythagoras' læresætning anvendes på de to retvinklede trekanter.


$$
h^2 = a^2 - x^2 \quad \land \quad c^2 = h^2 + (b + x)^2
$$

\( h^2 \) isoleres i første ligning.


$$
c^2 = a^2 - x^2 + (b + x)^2
$$

\( h^2 \) substitueres i den anden ligning.


$$
c^2 = a^2 - x^2 + b^2 + x^2 + 2bx
$$

Parentesen hæves vha. 1. kvadratsætning.


$$
c^2 = a^2 + b^2 + 2bx
$$

De to led med \( x^2 \) går ud med hinanden.


$$
\cos(180^\circ - C) = \frac{x}{a} \quad \iff \quad x = a \cos(180^\circ - C)
$$

Anvender formlen for cosinus i den retvinklede trekant og isolerer \( x \).

$$
c^2 = a^2 + b^2 + 2ab \cos(180^\circ - C)
$$

Substituerer \( x \) i linje 5 og skriver faktorerne op i normal rækkefølge. De andre repræsentationer for cosinusrelationen findes på samme måde som denne.


$$
c^2 = a^2 + b^2 - 2ab \cdot \cos(C)
$$

Da $( \cos(180^\circ - C) = - \cos(C) )$, kan ligningen omskrives til det ønskede resultat. De andre repræsentationer findes på samme måde, hvis højden ligger uden for $( \triangle ABC )$ og som den spidsvinklede trekant, hvis højden ligger inde i $( \triangle ABC )$.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Sinus relationen for spidsvinklet trekant

Forholdet mellem sinus til en vinkel og dens modstående side er konstant. Dvs. at

$$
\frac{\sin A}{a} = \frac{\sin B}{b} = \frac{\sin C}{c}
$$

eller

$$
\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C}
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/0/9/csm_sinusrelation_spids_7f6b8c3305.png)

$$
\sin A = \frac{h_b}{c} \quad \land \quad \sin C = \frac{h_b}{a}
$$

Anvender sinus i den retvinklede trekant til at finde to udtryk med \( h_b \).


$$
h_b = c \sin A \quad \land \quad h_b = a \sin C
$$

Isolerer \( h_b \) i begge ligninger.



$$
c \sin A = a \sin C
$$

Substituerer $h_b$.


$$
\frac{\sin A}{a} = \frac{\sin C}{c}
$$

Deler med $a$ og $c$ på begge sider.

$$
\sin A = \frac{h_c}{b} \quad \land \quad \sin B = \frac{h_c}{a}
$$

Anvender sinus i den retvinklede trekant til at finde to udtryk med $h_c$.


$$
h_c = b \sin A \quad \land \quad h_c = a \sin B
$$

Isolerer $h_c$ i begge ligninger.

$$
b \sin A = a \sin B
$$

Substituerer $h_c$.


$$
\frac{\sin A}{a} = \frac{\sin B}{b}
$$

Deler med \( a \) og \( b \) på begge sider.


$$
\frac{\sin A}{a} = \frac{\sin B}{b} = \frac{\sin C}{c}
$$

Samler linje 4 og linje 8, og det er vist for den spidsvinklede trekant.

<div class = "pagebreak"></div>

## Proof Sinus relationen for stumpvinklet trekant

Forholdet mellem sinus til en vinkel og dens modstående side er konstant. Dvs. at

$$
\frac{\sin A}{a} = \frac{\sin B}{b} = \frac{\sin C}{c}
$$

eller

$$
\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C}
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/e/6/csm_sinusrelationerne_stump_b16dd22ebe.png)


$$
\sin A = \frac{h_b}{c} \quad \land \quad \sin(180^\circ - C) = \frac{h_b}{a}
$$

Anvender sinus i den retvinklede trekant til at finde to udtryk med $h_b$.


$$
\sin A = \frac{h_b}{c} \quad \land \quad \sin C = \frac{h_b}{a}
$$

Da $\sin(180^\circ - C) = \sin C$.

$$
\frac{\sin A}{a} = \frac{\sin C}{c}
$$

Da linje 11 er identisk med linje 1, kan der gåes direkte til resultatet fra linje 4.


$$
\sin A = \frac{h_c}{b} \quad \land \quad \sin B = \frac{h_c}{a}
$$

Anvender højden $h_c$, da den ligger inde i trekanten og bruger ligesom i linje 5 sinus i den retvinklede trekant til at finde to udtryk med $h_c$.

$$
\frac{\sin A}{a} = \frac{\sin B}{b} = \frac{\sin C}{c}
$$

Gentager beregningerne fra linje 5 til linje 9. Hvis man havde ønsket at finde sinusrelationen udtrykt med sinus i nævneren, kunne man blot have divideret med sinus på begge sider i stedet for med sidelængderne.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Sinusrelationen og den omskrevne cirkel

**Sætning**

I trekanter gælder det, at en vilkårlig side delt med sinus til den modstående vinkel er det samme som diameteren i den omskrevne cirkel.

Dvs. at

$$
\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = D = 2R
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/4/2/csm_omskrevne_cirkel_trekantareal_f584573041.png)

Først tegnes en vilkårlig trekant $\Delta ABC$; og dens omskrevne cirkel. Herefter tegnes en ny trekant $\Delta AB'C$, hvor den ene side er diameter.

1. $\Delta AB'C$ er retvinklet.

Da $|AB'|$ er diameter i cirklen, så må centervinklen til $A$ og $B'$ være $180^\circ$. Da $\angle ACB'$ er en tilhørende perifervinkel, så må den være $90^\circ$.

2. 

$$
\frac{D}{\sin 90^\circ} = \frac{b}{\sin B'}
$$

Bruger [sinusrelationen](https://example.com) i $\Delta AB'C$.

3. 

$$
\frac{D}{1} = \frac{b}{\sin B'}
$$

Da $\sin 90^\circ = 1$.

4. 

$$
D = \frac{b}{\sin B'} = \frac{b}{\sin B}
$$

Da $B'$ og $B$ begge er perifervinkler fra punkterne $A$ og $C$, må de være ens. Se [bevis](https://example.com).

5. 

$$
\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = D = 2R
$$

Da [sinusrelationen](https://example.com) jo også gælder for de andre sider og vinkler.

Q.E.D.

<div class = "pagebreak"></div>

##  Proof Vinkler med fortegnsskift

**Sætning**

Der gælder følgende trigonometriske forhold, når vinkler skifter fortegn:

$$
\cos(-v) = \cos v
$$

og

$$
\sin(-v) = -\sin v
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/b/c/csm_Fortegnsskrift_vinkler_dfe8209392.png)

1. Figuren viser vilkårlige vinkler med retningspunkt i alle fire kvadranter med angivelse af vinklen med modsat fortegn. Umiddelbart kan vi aflæse to ting af figuren:
   1. Vinklerne $v$ og $-v$ er placeret symmetrisk om x-aksen og med samme numeriske værdi.
   2. Både $v$ og $-v$ er placeret på samme side af y-aksen, og på hver sin side af x-aksen.

2. Værdien af cosinus afhænger alene af projektionen af retningspunktet på x-aksen. Sammen med (1) og (2) kan vi derfor konkludere, at cosinus til en vinkel og cosinus til vinklen med modsat fortegn er lige store. Altså gælder

$$
\cos(-v) = \cos v
$$

3. Værdien af sinus afhænger alene af projektionen af retningspunktet på y-aksen. Da $v$ og $-v$ har samme numeriske værdi pga. (1), vil projektionens størrelse kun variere på fortegnet. Altså:

$$
\sin(-v) = -\sin v
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Additionsformel I

**Sætning**

For summen af to vinkler gælder

$$
\sin(u + v) = \sin u \cdot \cos v + \cos u \cdot \sin v
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/8/6/csm_Additionsformel_I_6f313ba94f.png)

Vi tegner tre rette linjer fra enhedscirklens centrum $A$, således at der opstår to vinkler $u$ og $v$. Skæringspunkterne kalder vi $B$, $C$ og $D$.

Fra $B$ tegnes hjælpelinjen $BE$, der står vinkelret på $AD$. Fra $B$ tegnes hjælpelinjen $BF$ der står vinkelret på $AC$. Projektionen af $F$ på $BE$ er $G$. Fra $F$ tegnes linjestykket $FH$, der står vinkelret på $DA$.

$$
\angle AFG = v
$$

fordi $AD$ og $GF$ er parallelle

$$
\angle GBF = v
$$

fordi

$$
\angle GFB = 90^\circ - v
$$

1. 

$$
\sin(u + v) = \frac{|BE|}{|AB|} = \frac{|EG| + |GB|}{|AB|}
$$

$\sin(u + v)$ findes som den modstående katete divideret med hypotenusen i den retvinklede trekant $\Delta ABE$.

$$
|BE| = |EG| + |GB|
$$

fordi vi netop har inddelt linjestykket således.

2. 

$$
= \frac{|FH| + |GB|}{|AB|} = |FH| + |GB|
$$

fordi $|EG| = |FH|$ og $|AB| = 1$.

3. 

$$
= |FH| \frac{|AF|}{|AF|} + |GB| \frac{|BF|}{|BF|}
$$

Idet vi ganger hvert led med 1 i form af de to brøker med samme tæller og nævner.

4. 

$$
= \sin(u + v) = \sin(u) \cos(v) + \cos(u) \sin(v)
$$

Fordi

$$
\frac{|FH|}{|AF|} = \sin(v)
$$

$$
|AF| = \cos(u)
$$

$$
\frac{|GB|}{|BF|} = \cos(v)
$$

$$
|BF| = \sin(u)
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Additionsformel II

**Sætning**

For summen af to vinkler gælder

$$
\cos(v + u) = \cos(v)\cos(u) - \sin(v)\sin(u)
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/8/6/csm_Additionsformel_I_f0d9a741b5.png)

Vi tegner tre rette linjer fra enhedscirklens centrum $A$, således at der opstår to vinkler $u$ og $v$. Skæringspunkterne kalder vi $B$, $C$ og $D$.

Fra $B$ tegnes hjælpelinjen $BE$, der står vinkelret på $AD$. Fra $B$ tegnes hjælpelinjen $BF$ der står vinkelret på $AC$. Projektionen af $F$ på $BE$ er $G$. Fra $F$ tegnes linjestykket $FH$, der står vinkelret på $DA$.

$$
\angle AFG = v
$$

fordi $AD$ og $GF$ er parallelle

$$
\angle GBF = v
$$

fordi

$$
\angle GFB = 90^\circ - v
$$

1. 

$$
\cos(u + v) = \frac{|AE|}{|AB|} = \frac{|HA| - |EH|}{|AB|} = \frac{|HA| - |GF|}{|AB|}
$$

$\cos(v + u)$ findes som den hosliggende katete divideret med hypotenusen i den retvinklede trekant $\Delta ABE$.

$$
|AE| = |HA| - |EH| = |HA| - |GF|
$$

fordi vi netop har inddelt linjestykket således.

2. 

$$
\cos(u + v) = |HA| - |GF|
$$

fordi $|AB| = 1$.

3. 

$$
= \frac{|HA|}{|AF|} - \frac{|GF|}{|BF|} = \frac{|AF|}{|AF|} - \frac{|BF|}{|BF|} = \frac{|HA|}{|AF|} - \frac{|GF|}{|BF|}
$$

Vi ganger hvert led med 1 i form af de to brøker med samme tæller og nævner.

4. 

$$
\cos(v + u) = \cos(v)\cos(u) - \sin(v)\sin(u)
$$

Fordi

$$
\frac{|HA|}{|AF|} = \cos(v)
$$

$$
|AF| = \cos(u)
$$

$$
\frac{|GF|}{|BF|} = \sin(v)
$$

$$
|BF| = \sin(u)
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Længde af vektor
 
  **Sætning**

For en vektor givet ved

$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \end{pmatrix}
$$

gælder, at længden kan findes ved

$$
|\vec{a}| = \sqrt{a_1^2 + a_2^2}
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/a/2/csm_vektorlaengde_140fce9d4c.png)

1. 

$$
|\vec{a}|^2 = a_1^2 + a_2^2
$$

Der dannes en retvinklet trekant, hvor den numeriske værdi af vektorens to koordinater svarer til længden af de to kateter. Herefter indsættes i [Pythagoras' læresætning](https://example.com). Da koordinaterne opløftes i anden potens, kan der ses bort fra de numeriske tegn.

2. 

$$
|\vec{a}| = \sqrt{a_1^2 + a_2^2}
$$

Tager kvadratroden på begge sider af lighedstegnet, og da der er tale om en længde, kan det ikke være minus kvadratroden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Skalarproduktet - geometrisk sammenhæng

**Sætning**

Skalarproduktet af to vektorer kan findes ved formlen

$$
\vec{a} \cdot \vec{b} = |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

hvor

$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \end{pmatrix}, \quad \vec{b} = \begin{pmatrix} b_1 \\ b_2 \end{pmatrix}
$$

og skalarproduktet er defineret som

$$
\vec{a} \cdot \vec{b} = a_1 \cdot b_1 + a_2 \cdot b_2
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/9/d/csm_Prikproduktet_trekant_92c962bf90.png)

1. 

$$
\vec{a} - \vec{b} = \begin{pmatrix} a_1 - b_1 \\ a_2 - b_2 \end{pmatrix}
$$

Formlen for en differensvektors koordinater bruges.

2. 

$$
|\vec{a} - \vec{b}|^2 = |\vec{a}|^2 + |\vec{b}|^2 - 2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Ifølge [cosinusrelationen](https://example.com), gælder denne sammenhæng.

3. 

$$
\sqrt{(a_1 - b_1)^2 + (a_2 - b_2)^2} = \sqrt{a_1^2 + a_2^2} + \sqrt{b_1^2 + b_2^2} - 2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

De tre første vektorlængder findes vha. længdeformlen for en vektor.

4. 

$$
(a_1 - b_1)^2 + (a_2 - b_2)^2 = a_1^2 + a_2^2 + b_1^2 + b_2^2 - 2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Kvadratroden og kvadratet går ud med hinanden.

5. 

$$
a_1^2 + b_1^2 - 2 a_1 b_1 + a_2^2 + b_2^2 - 2 a_2 b_2 = a_1^2 + a_2^2 + b_1^2 + b_2^2 - 2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Parenteserne udregnes vha. [kvadratsætningen](https://example.com).

6. 

$$
-2 a_1 b_1 - 2 a_2 b_2 = -2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Ligningen reduceres ved at fratrække de fire identiske led på begge sider af lighedstegnet.

7. 

$$
a_1 b_1 + a_2 b_2 = |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Deler med $-2$ på begge sider af lighedstegnet.

8. 

$$
\vec{a} \cdot \vec{b} = |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Venstresiden substitueres med definitionen på skalarproduktet.

Q.E.D.

<div class = "pagebreak"></div>

## Proof En vektors koordinater vha. begyndelses- og slutpunkt

**Sætning**

Givet to punkter

$$
A = (x_A; y_A) \quad B = (x_B; y_B)
$$

findes vektorkoordinaterne ved formlen

$$
\overrightarrow{AB} = \begin{pmatrix} x_B - x_A \\ y_B - y_A \end{pmatrix}
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/2/2/csm_vektorkoordinater_bea7c4443c.png)

1. 

$$
\overrightarrow{AB} = \begin{pmatrix} \Delta x \\ \Delta y \end{pmatrix}
$$

En vektor beskriver en ændring. Fra punkt $A$ til punkt $B$ ændres $x$-koordinaten med $\Delta x$ og $y$-koordinaten med $\Delta y$.

2. 

$$
x_A + \Delta x = x_B \quad \land \quad y_A + \Delta y = y_B
$$

Det betyder, at hvis man lægger $\overrightarrow{AB}$'s koordinater til punkt $A$'s koordinater, så får man punkt $B$'s koordinater.

3. 

$$
\Delta x = x_B - x_A \quad \land \quad \Delta y = y_B - y_A
$$

Isolerer hhv. $\Delta x$ og $\Delta y$.

4. 

$$
\overrightarrow{AB} = \begin{pmatrix} x_B - x_A \\ y_B - y_A \end{pmatrix}
$$

Substituerer ind i udtrykket for $\overrightarrow{AB}$.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Enhedsvektorens koordinater

** Sætning**

En enhedsvektor i planen har følgende koordinater

$$
\vec{e} = \begin{pmatrix} \cos(v) \\ \sin(v) \end{pmatrix}
$$

hvor $v$ angiver vinklen i positiv regneretning i forhold til x-aksen.

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/1/2/csm_enhedsvektoren_5c9057250f.png)

1. 

$$
\vec{e} = \begin{pmatrix} \cos(v) \\ \sin(v) \end{pmatrix}
$$

Enhedsvektorens koordinater hentes direkte fra enhedscirklens definitioner.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Sammenhæng mellem koordinater og længde/retning

**Sætning**

En vektor med kendt længde og retning har følgende koordinater

$$
\vec{a} = \begin{pmatrix} |\vec{a}| \cos(v) \\ |\vec{a}| \sin(v) \end{pmatrix}
$$

### Bevis

1. 

$$
\vec{e} = \frac{\vec{a}}{|\vec{a}|}
$$

Da en vektor delt med sin egen længde må have længden 1, og derfor også er en enhedsvektor.

2. 

$$
\vec{a} = |\vec{a}| \cdot \vec{e}
$$

Isolerer $\vec{a}$.

3. 

$$
\vec{a} = |\vec{a}| \cdot \begin{pmatrix} \cos(v) \\ \sin(v) \end{pmatrix}
$$

Anvender formlen for [enhedsvektorens koordinater](https://example.com).

4. 

$$
\vec{a} = \begin{pmatrix} |\vec{a}| \cos(v) \\ |\vec{a}| \sin(v) \end{pmatrix}
$$

Ganger længden ind på hvert koordinat vha. formlen for [konstant gange vektor](https://example.com).

Q.E.D.

<div class = "pagebreak"></div>

## Proof Vinkelrette vektorer

**Sætning**

Om to egentlige vektorer gælder, at

$$
\vec{a} \cdot \vec{b} = 0 \iff \vec{a} \perp \vec{b}
$$

### Bevis

1. 

$$
\vec{a} \cdot \vec{b} = |\vec{a}| \cdot |\vec{b}| \cdot \cos(v) = 0
$$

Skalarproduktet opskrives [geometrisk](https://example.com) og sættes lig med nul.

2. 

$$
\cos(v) = 0
$$

Da nulvektoren ikke har nogen retning, kan hverken $|\vec{a}|$ eller $|\vec{b}|$ være nul, hvis de to vektorer er vinkelrette på hinanden. Så den eneste mulighed for, at skalarproduktet giver nul, er, hvis cosinus til vinklen giver nul.

3. 

$$
v = 90^\circ \quad \lor \quad v = -90^\circ
$$

Begge muligheder svarer til, at vektorerne er vinkelrette på hinanden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Tværvektor

**Sætning**

Hvis $\vec{a}$ er vektoren

$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \end{pmatrix},
$$

findes tværvektoren som

$$
\hat{a} = \begin{pmatrix} -a_2 \\ a_1 \end{pmatrix}
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/6/4/csm_tvaervektor_0b2539437b.png)

1. 

$$
\hat{a} = \begin{pmatrix} -a_2 \\ a_1 \end{pmatrix}
$$

$\hat{a}$ kaldes for tværvektoren til $\vec{a}$, og den fremkommer ved, at $\vec{a}$ roteres $90^\circ$ i positiv omløbsretning. Den viste trekant, hvor vektorkoordinaterne repræsenterer kateterne, er ligeledes roteret.

På figuren fremgår det tydeligt, at de to trekanter er **kongruente**. Altså kan man konkludere, at førstekoordinaten for $\hat{a}$ svarer til størrelsen på andenkoordinaten for $\vec{a}$ og omvendt.

I den viste figur er begge koordinater positive, da vektor $\vec{a}$ peger skråt op til højre. Tværvektoren $\hat{a}$ peger her skråt op til venstre. Derfor må dens førstekoordinat være negativ, og dens andenkoordinat må være positiv. Når man kobler disse informationer, er formlen som postuleret. Det overlades til læseren at gennemskue, at det også gælder for andre retninger for $\vec{a}$.

Q.E.D.

<div class = "pagebreak"></div>

##  Proof Areal af vektorernes udspændte trekant

**Sætning**

Arealet af to vektorers udspændte trekant er givet ved

$$
\text{Areal} = \frac{1}{2} |\vec{a} \cdot \vec{b}|
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/0/8/csm_Udspaendt_trekant_f72e107169.png)

Beviset gennemføres i to dele.

### 1. For $0^\circ < v \leq 90^\circ$

1. 

$$
\text{Areal} = \frac{1}{2} |\vec{a}| \cdot |\vec{b}| \cdot \sin(v) \quad \land \quad 0^\circ < v \leq 90^\circ
$$

Arealet af trekanten findes som [areal af vilkårlig trekant](https://example.com).

2. 

$$
= \frac{1}{2} \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(90^\circ - v)
$$

Da $\sin(v) = \cos(90^\circ - v)$.

3. 

$$
= \frac{1}{2} \cdot |\hat{a}| \cdot |\vec{b}| \cdot \cos(90^\circ - v)
$$

Da længden af vektor og tværvektor er den samme.

4. 

$$
= \frac{1}{2} \hat{a} \cdot \vec{b}
$$

Da $90^\circ - v$ svarer til vinklen mellem $\hat{a}$ og $\vec{b}$, hvis $0^\circ < v \leq 90^\circ$, kan det omskrives til de to vektorers skalarprodukt.

### 2. For $90^\circ < v < 180^\circ$

5. 

$$
\text{Areal} = \frac{1}{2} |\vec{a}| \cdot |\vec{b}| \cdot \sin(v) \quad \land \quad 90^\circ < v < 180^\circ
$$

Finder igen arealet som [areal af vilkårlig trekant](https://example.com).

6. 

$$
= \frac{1}{2} \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v - 90^\circ)
$$

Da $\sin(v) = \cos(v - 90^\circ)$.

7. 

$$
= \frac{1}{2} \cdot |\hat{a}| \cdot |\vec{b}| \cdot \cos(v - 90^\circ)
$$

Da længden af vektor og tværvektor er den samme.

8. 

$$
= \frac{1}{2} \hat{a} \cdot \vec{b}
$$

Da $v - 90^\circ$ svarer til vinklen mellem $\hat{a}$ og $\vec{b}$, hvis $90^\circ < v < 180^\circ$, kan det omskrives til de to vektorers skalarprodukt.

9. 

$$
\text{Areal} = \frac{1}{2} \vec{b} \cdot \hat{a}
$$

Hvis vinklen gik fra $\vec{b}$ til $\vec{a}$ og ikke som vist på figuren, så ville man i stedet komme frem til denne formel, svarende til at der var byttet om på $\vec{a}$ og $\vec{b}$ på figuren.

10. 

$$
= \frac{1}{2} \vec{a} \cdot \vec{b} = -\frac{1}{2} \hat{a} \cdot \vec{b}
$$

Da $\hat{b} \cdot \hat{a} = \vec{a} \cdot \vec{b} = -\hat{a} \cdot \vec{b}$.

11. 

$$
\text{Areal} = \frac{1}{2} |\hat{a} \cdot \vec{b}|
$$

Da arealet ikke kan være negativt, tages den numeriske værdi.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Vektoraddition

**Sætning**

Hvis $\vec{a}$ og $\vec{b}$ er vektorerne

$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \end{pmatrix}, \quad \vec{b} = \begin{pmatrix} b_1 \\ b_2 \end{pmatrix},
$$

findes sumvektoren som

$$
\vec{a} + \vec{b} = \begin{pmatrix} a_1 + b_1 \\ a_2 + b_2 \end{pmatrix}
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/8/e/csm_vektoraddition_ac5ee00422.png)

1. 

$$
\vec{a} = a_1 \cdot \vec{i} + a_2 \cdot \vec{j} \quad \text{og} \quad \vec{b} = b_1 \cdot \vec{i} + b_2 \cdot \vec{j}
$$

Da en vektor kan opløses i en vandret og en lodret komposant, hvor de respektive koordinater er ganget på hhv. den vandrette basisvektor $\vec{i}$ og den lodrette basisvektor $\vec{j}$.

2. 

$$
\vec{a} + \vec{b} = a_1 \cdot \vec{i} + a_2 \cdot \vec{j} + b_1 \cdot \vec{i} + b_2 \cdot \vec{j}
$$

De to vektorer lægges sammen.

3. 

$$
= (a_1 + b_1) \cdot \vec{i} + (a_2 + b_2) \cdot \vec{j}
$$

Leddene flyttes rundt, og basisvektorerne sættes uden for parenteser.

4. 

$$
\vec{a} + \vec{b} = \begin{pmatrix} a_1 + b_1 \\ a_2 + b_2 \end{pmatrix}
$$

Tallene, der ganges på basisvektorerne, svarer til en vektors koordinater.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Vektorsubtraktion

**Sætning**

Hvis $\vec{a}$ og $\vec{b}$ er vektorerne

$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \end{pmatrix}, \quad \vec{b} = \begin{pmatrix} b_1 \\ b_2 \end{pmatrix},
$$

findes differensvektoren som

$$
\vec{a} - \vec{b} = \begin{pmatrix} a_1 - b_1 \\ a_2 - b_2 \end{pmatrix}
$$

### Bevis

1. 

$$
\vec{a} = a_1 \cdot \vec{i} + a_2 \cdot \vec{j} \quad \text{og} \quad \vec{b} = b_1 \cdot \vec{i} + b_2 \cdot \vec{j}
$$

Da en vektor kan opløses i en vandret og en lodret komposant, hvor de respektive koordinater er ganget på hhv. den vandrette basisvektor $\vec{i}$ og den lodrette basisvektor $\vec{j}$.

2. 

$$
\vec{a} - \vec{b} = a_1 \cdot \vec{i} + a_2 \cdot \vec{j} - (b_1 \cdot \vec{i} + b_2 \cdot \vec{j})
$$

Differensvektoren findes.

3. 

$$
= a_1 \cdot \vec{i} + a_2 \cdot \vec{j} - b_1 \cdot \vec{i} - b_2 \cdot \vec{j}
$$

Parentesen hæves.

4. 

$$
= (a_1 - b_1) \cdot \vec{i} + (a_2 - b_2) \cdot \vec{j}
$$

Leddene flyttes rundt, og basisvektorerne sættes uden for parenteser.

5. 

$$
\vec{a} - \vec{b} = \begin{pmatrix} a_1 - b_1 \\ a_2 - b_2 \end{pmatrix}
$$

Tallene, der ganges på basisvektorerne, svarer til en vektors koordinater.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Konstant gange vektor

**Sætning**

Hvis $\vec{a} = \begin{pmatrix} a_1 \\ a_2 \end{pmatrix}$, er $k \cdot \vec{a} = \begin{pmatrix} k \cdot a_1 \\ k \cdot a_2 \end{pmatrix}$.

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/b/6/csm_konstant_vektor_136f693dc8.png)

1. 

$$
\vec{a} = a_1 \vec{i} + a_2 \vec{j}
$$

$\vec{a}$ opdeles i komposanter.

2. 

$$
k \cdot \vec{a} = k \cdot (a_1 \vec{i} + a_2 \vec{j})
$$

Ganger med $k$ på begge sider.

3. 

$$
= k \cdot a_1 \vec{i} + k \cdot a_2 \vec{j}
$$

Ganger $k$ ind i parentesen.

4. 

$$
k \cdot \vec{a} = \begin{pmatrix} k \cdot a_1 \\ k \cdot a_2 \end{pmatrix}
$$

Koefficienterne foran $\vec{i}$ og $\vec{j}$ er det samme som den tilhørende vektors koordinater.

Q.E.D.

<div class = "pagebreak"></div>

##  Proof Vinklen mellem to vektorer

**Sætning**

Vinklen mellem to egentlige vektorer findes ved

$$
v = \arccos\left( \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|} \right)
$$

### Bevis

1. 

$$
\vec{a} \cdot \vec{b} = |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Den [geometriske](https://example.com) version af skalarproduktet opskrives.

2. 

$$
\frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|} = \cos(v)
$$

Der divideres med de to længder på begge sider af lighedstegnet.

3. 

$$
v = \arccos\left( \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|} \right)
$$

Arcus cosinus tages på begge sider af lighedstegnet, og der byttes om på siderne.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Vektorprojektion

**Sætning**

Om to vektorer givet ved

$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \end{pmatrix}, \quad \vec{b} = \begin{pmatrix} b_1 \\ b_2 \end{pmatrix}
$$

bestemmes vektorprojektion af $\vec{b}$ på $\vec{a}$ ved

$$
\vec{b}_a = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}|^2} \cdot \vec{a}
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/5/c/csm_vektorprojektion_d2f3f12316.png)

1. 

$$
\vec{b}_a = t \cdot \vec{a}
$$

Da $\vec{b}_a$ og $\vec{a}$ er parallelle, findes et tal $t$, som kan ganges på $\vec{a}$ for at få projektionsvektoren.

2. 

$$
t = \frac{|\vec{b}_a|}{|\vec{a}|}, \quad \text{hvis } v \text{ er en spids vinkel}
$$

$$
t = \frac{-|\vec{b}_a|}{|\vec{a}|}, \quad \text{hvis } v \text{ er en stump vinkel}
$$

Hvis vektorerne $\vec{a}$ og $\vec{b}_a$ har samme retning, er $v$ en spids vinkel. Hvis de er modsatrettede, er $v$ en stump vinkel. Da $t$ er en faktor, der ganges på $\vec{a}$ for at få $\vec{b}_a$, skal der først divideres med $|\vec{a}|$ for at få en enhedsvektor. Herefter skal der ganges med $|\vec{b}_a|$ for at få $\vec{b}_a$. Fortegnet korrigerer for retningen.

3. 

$$
\vec{b}_a = \frac{|\vec{b}_a|}{|\vec{a}|} \cdot \vec{a}
$$

I første omgang ser vi på tilfældet, hvor $\vec{a}$ og $\vec{b}_a$ har samme retning. $t$ substitueres ind.

4. 

$$
|\vec{b}_a| = |\vec{b}| \cdot \cos(v)
$$

Denne sammenhæng gælder, da det er en retvinklet trekant.

5. 

$$
\vec{b}_a = \frac{|\vec{b}| \cdot \cos(v)}{|\vec{a}|} \cdot \vec{a} = \frac{|\vec{a}| \cdot |\vec{b}| \cdot \cos(v)}{|\vec{a}|^2} \cdot \vec{a}
$$

Længden af projektionsvektoren substitueres ind, og brøken forlænges med $|\vec{a}|$.

6. 

$$
\vec{b}_a = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}|^2} \cdot \vec{a}
$$

Tælleren svarer til skalarproduktet, og omskrives til det. Da $\cos(v)$ skifter fortegn, hvis $90^\circ < v < 270^\circ$, har vi automatisk klaret den anden situation, hvor $t$ er negativ, svarende til at $v$ var stump.

Q.E.D.

<div class = "pagebreak"></div>

##  Proof Længde af projektionsvektor

**Sætning**

Om to vektorer givet ved

$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \end{pmatrix}, \quad \vec{b} = \begin{pmatrix} b_1 \\ b_2 \end{pmatrix}
$$

bestemmes vektorprojektionen af $\vec{b}$ på $\vec{a}$ ved

$$
|\vec{b}_a| = \frac{|\vec{a} \cdot \vec{b}|}{|\vec{a}|}
$$

###  Bevis

1. 

$$
\vec{b}_a = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}|^2} \cdot \vec{a}
$$

Selve [projektionsvektoren](https://example.com) opstilles.

2. 

$$
|\vec{b}_a| = \left| \frac{\vec{a} \cdot \vec{b}}{|\vec{a}|^2} \cdot \vec{a} \right| = \left| \frac{\vec{a} \cdot \vec{b}}{|\vec{a}|^2} \right| \cdot |\vec{a}|
$$

Tager længden af projektionsvektoren og sætter faktoren uden for længdesymbolet. Da længden stadig skal være positiv, sættes numerisktegn omkring faktoren.

3. 

$$
|\vec{b}_a| = \frac{|\vec{a} \cdot \vec{b}|}{|\vec{a}|^2} \cdot |\vec{a}|
$$

Da nævneren i brøken altid vil være positiv, fordi der både er tale om en længde og et kvadreret tal, kan man nøjes med at tage den numeriske værdi af tælleren.

4. 

$$
|\vec{b}_a| = \frac{|\vec{a} \cdot \vec{b}|}{|\vec{a}|}
$$

Der reduceres med $|\vec{a}|$.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Afstandsformlen

**Sætning**

Når $A$ og $B$ er punkter med koordinaterne

$$
A = (x_A; y_A) \quad B = (x_B; y_B)
$$

er

$$
|AB| = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2}
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/b/2/csm_Afstandsformlen_fddeeda730.png)

1.

$$
|AB| = |\vec{AB}|
$$

Afstanden fra $A$ til $B$ er lig med længden af vektoren fra punkt $A$ til $B$.

2.

$$
\vec{AB} = \begin{pmatrix} x_B - x_A \\ y_B - y_A \end{pmatrix}
$$

Bestemmer vektor $\vec{AB}$'s koordinater.

3.

$$
|\vec{AB}| = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2}
$$

Bestemmer længden af vektor $\vec{AB}$.

4.

$$
|AB| = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2}
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Cirklens ligning

**Sætning**

Cirklen med centrum $(x_0; y_0)$ og radius $r$ har ligningen:

$$
(x - x_0)^2 + (y - y_0)^2 = r^2
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/a/7/csm_Cirklens_ligning_b1717f1ca2.png)

1.

$$
|\vec{P_0P}| = r
$$

Cirklens ligning fremkommer, når man finder længden af den vektor, der går fra centrum til et vilkårligt punkt på cirkelperiferien. Længden er lig med radius.

2.

$$
\vec{P_0P} = \begin{pmatrix} x - x_0 \\ y - y_0 \end{pmatrix}
$$

Bruger formlen til at finde en [vektors koordinater](#) ud fra to kendte punkter.

3.

$$
|\vec{P_0P}| = \sqrt{(x - x_0)^2 + (y - y_0)^2} = r
$$

Bruger formlen for [længden af en vektor](#).

4.

$$
(x - x_0)^2 + (y - y_0)^2 = r^2
$$

Tager kvadratet på begge sider af lighedstegnet.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Midtpunktsformlen

** Sætning**
Når $A$ og $B$ er punkter med koordinaterne
$$
A = (x_A; y_A) \quad B = (x_B; y_B)
$$
er
$$
M = \left( \frac{x_A + x_B}{2}, \frac{y_A + y_B}{2} \right)
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/9/c/csm_Midtpunktsformel_9ddd33f7be.png)

1. 
$$
\vec{a} = \frac{1}{2} \cdot \overrightarrow{AB} = \frac{1}{2} \cdot \begin{pmatrix} x_B - x_A \\ y_B - y_A \end{pmatrix}
$$
Vektor $\vec{a}$ er lig med halvdelen af vektor $\overrightarrow{AB}$. Se formel for [konstant gange vektor](#).

2. 
$$
a_1 = \frac{x_B - x_A}{2} \quad \land \quad a_2 = \frac{y_B - y_A}{2}
$$
Bestemmer $a_1$ og $a_2$.

3. 
$$
x_M = x_A + a_1 = x_A + \frac{x_B - x_A}{2} = \frac{2x_A}{2} + \frac{x_B - x_A}{2} = \frac{x_A + x_B}{2}
$$
Bestemmer $M$'s første koordinat.

4. 
$$
y_M = y_A + a_2 = y_A + \frac{y_B - y_A}{2} = \frac{2y_A}{2} + \frac{y_B - y_A}{2} = \frac{y_A + y_B}{2}
$$
Bestemmer $M$'s anden koordinat.

5. 
$$
M = \left( \frac{x_A + x_B}{2}, \frac{y_A + y_B}{2} \right)
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Linjens ligning på normalform

**Sætning**
For en linje med normalvektoren
$$
\vec{n} = \begin{pmatrix} a \\ b \end{pmatrix}
$$
kan linjens ligning på normalform skrives som
$$
m : ax + by + c = 0
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/8/b/csm_Linjens_norm_linje_42c1869109.png)

1. 
$$
\vec{n} = \begin{pmatrix} a \\ b \end{pmatrix}
$$
Til en linje må der eksistere en normalvektor $\vec{n}$. Vælger at kalde koordinaterne $a$ og $b$.

2. 
$$
P_0 = (x_0; y_0) \quad P = (x, y)
$$
Punktet $P$ beskriver et vilkårligt punkt på linjen, og $P_0$ beskriver et vilkårligt fast punkt på linjen.

3. 
$$
\overrightarrow{P_0 P} = \begin{pmatrix} x - x_0 \\ y - y_0 \end{pmatrix}
$$
Bestemmer vektor $\overrightarrow{P_0 P}$.

4. 
$$
\vec{n} \cdot \overrightarrow{P_0 P} = \begin{pmatrix} a \\ b \end{pmatrix} \cdot \begin{pmatrix} x - x_0 \\ y - y_0 \end{pmatrix} = 0
$$
For alle mulige egentlige vektorer $\overrightarrow{P_0 P}$ giver deres skalarprodukt med en normalvektor til linjen nul.

5. 
$$
a(x - x_0) + b(y - y_0) = 0
$$
Beregener skalarproduktet.

6. 
$$
a \cdot x - a \cdot x_0 + b \cdot y - b \cdot y_0 = 0
$$
Ganger ind i parenterserne.

7. 
$$
ax + by - ax_0 - by_0 = 0
$$
Bytter om på leddene.

8. 
$$
ax + by + c = 0
$$
Da $-ax_0 - by_0$ er en konstant, substitueres med en ny konstant kaldet $c$. Det kan konstateres, at koefficienterne foran $x$ og $y$ kan bruges som koordinater til en normalvektor.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Distanceformlen

**Sætning**
Afstanden fra punkt til linje kan findes ved
$$
\text{dist}(P, m) = \frac{|ax_1 + by_1 + c|}{\sqrt{a^2 + b^2}}
$$
når
$$
P = (x_1; y_1), \quad m : ax + by + c = 0
$$

### Bevis

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/4/b/csm_Distanceformlen_35e27613ae.png)

1. 
$$
\text{dist} = |\overrightarrow{RP}|
$$
Når man taler om en afstand til en linje, så menes der altid den korteste afstand, dvs. vinkelret ind på linjen. Den korteste afstand fra et punkt $P$, der ikke ligger på linjen, svarer til længden af vektor $\overrightarrow{RP}$.

2. 
$$
|\overrightarrow{RP}| = \frac{|\overrightarrow{P_0 P} \cdot \vec{n}|}{|\vec{n}|} \quad \text{hvor} \quad \vec{n} = \begin{pmatrix} a \\ b \end{pmatrix}
$$
Længden af vektor $\overrightarrow{RP}$ kan findes ved at tage et vilkårligt punkt på linjen $P_0$ og danne en vektor $\overrightarrow{P_0 P}$. Dennes projektion på linjens normalvektor $\vec{n}$ svarer til vektor $\overrightarrow{RP}$. Koefficienterne foran hhv. $x$ og $y$ svarer til normalvektorens koordinater, når linjen er skrevet på dens normerede form $ax + by + c = 0$.

3. 
$$
\overrightarrow{P_0 P} \cdot \vec{n} = \begin{pmatrix} x_1 - x_0 \\ y_1 - y_0 \end{pmatrix} \cdot \begin{pmatrix} a \\ b \end{pmatrix} = a x_1 - a x_0 + b y_1 - b y_0 = a x_1 + b y_1 + c
$$
$c = -a x_0 - b y_0$, da $P_0$ ligger på linjen, og punktet derfor må tilfredsstille linjens ligning.

4. 
$$
\text{dist}(P, m) = \frac{|a x_1 + b y_1 + c|}{\sqrt{a^2 + b^2}}
$$
Skalarproduktet ovenfor substitueres ind i tælleren i udregning 2, og længden af normalvektoren findes vha. formlen for længden af en vektor.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Ortogonale linjer

** Sætning**
Om to ortogonale linjer gælder det, at produktet af deres hældningskoefficienter er -1.
$$
l : y = \alpha_1 x + \beta_1 \quad \land \quad m : y = \alpha_2 x + \beta_2 \quad \land \quad l \perp m
$$
$$
\alpha_1 \cdot \alpha_2 = -1
$$

### Bevis
![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/2/a/csm_Ortogonale_linier_dd64014622.png)

1. 
$$
\vec{r}_1 = \begin{pmatrix} 1 \\ \alpha_1 \end{pmatrix} \quad \vec{r}_2 = \begin{pmatrix} 1 \\ \alpha_2 \end{pmatrix}
$$
Enhver ret linje har en retningsvektor med førstekoordinat 1 og andenkoordinat svarende til dens hældningskoefficient $\alpha$.

2. 
$$
\vec{r}_1 \cdot \vec{r}_2 = 0
$$
Skalarproduktet af to ortogonale vektorer er altid 0.

3. 
$$
\begin{pmatrix} 1 \\ \alpha_1 \end{pmatrix} \cdot \begin{pmatrix} 1 \\ \alpha_2 \end{pmatrix} = 0
$$
Koordinaterne indsættes.

4. 
$$
1 \cdot 1 + \alpha_1 \cdot \alpha_2 = 0
$$
Skalarproduktet udregnes.

5. 
$$
\alpha_1 \cdot \alpha_2 = -1
$$
Vi trækker 1 fra på begge sider af lighedstegnet.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Linjens parameterfremstilling

** Sætning**
Linjens parameterfremstilling kan skrives som
$$
\begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} x_0 \\ y_0 \end{pmatrix} + t \cdot \begin{pmatrix} r_1 \\ r_2 \end{pmatrix}, \quad t \in \mathbb{R}
$$
hvor $P(x, y)$ er et vilkårligt løbende punkt på linjen, $P_0(x_0, y_0)$ er et vilkårligt fast punkt på linjen, og $\vec{r} = \begin{pmatrix} r_1 \\ r_2 \end{pmatrix}$ er en retningsvektor for linjen.

### Bevis


![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/3/2/csm_linjens_parameter_8e570bac62.png)
1. 
$$
\vec{r} \parallel \overrightarrow{P_0 P}
$$
De to vektorer ligger begge på linjen og må derfor være parallelle.

2. 
$$
\overrightarrow{P_0 P} = t \cdot \vec{r}, \quad t \in \mathbb{R}
$$
Derfor kan de to vektorer udtrykkes ud fra hinanden.

3. 
$$
\overrightarrow{P} - \overrightarrow{P_0} = t \cdot \vec{r}, \quad t \in \mathbb{R}
$$
Udtrykker $\overrightarrow{P_0 P}$ ud fra de to punkters stedvektorer.

4. 
$$
\overrightarrow{P} = \overrightarrow{P_0} + t \cdot \vec{r}, \quad t \in \mathbb{R}
$$
Lægger $\overrightarrow{P_0}$ til på begge sider.

5. 
$$
\begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} x_0 \\ y_0 \end{pmatrix} + t \cdot \begin{pmatrix} r_1 \\ r_2 \end{pmatrix}, \quad t \in \mathbb{R}
$$
Omskriver til vektorernes koordinater.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Naturlige logaritme til et produkt

**Sætning**

Om den naturlige logaritme til et produkt gælder følgende
$$\ln(a \cdot b) = \ln a + \ln b, \quad a > 0 \quad \land \quad b > 0$$

**Bevis**

1.
$$a b = a b$$

Da begge sider af lighedstegnet er identiske, må lighedstegnet gælde.

2.
$$a b = e^{\ln a} e^{\ln b}$$

Tager $\ln x$ og $e^x$ til hvert tal på højresiden. Da $\ln x$ og $e^x$ er hinandens inverse funktioner, bliver der ikke lavet om på tallene.

3.
$$a b = e^{\ln a + \ln b}$$

Bruger reglen $x^a \cdot x^b = x^{a + b}$.

4.
$$\ln(a b) = \ln a + \ln b$$

Tager $\ln x$ på begge sider.

Q.E.D.

**Note**

Denne regel gælder for alle logaritmer og fremgangsmåden er den samme. Se [bevis](#) udført vha. titalslogaritmen.

<div class = "pagebreak"></div>

## Proof Titalslogaritmen til et produkt

**Sætning**

Om titalslogaritmen til et produkt gælder følgende
$$\log(a \cdot b) = \log a + \log b, \quad a > 0 \quad \land \quad b > 0$$

**Bevis**

1  
$$ab = ab$$  
Da begge sider af lighedstegnet er identiske, må lighedstegnet gælde.

2  
$$ab = 10^{\log a} \cdot 10^{\log b}$$  
Tager $\log x$ og $10^x$ til hvert tal på højresiden. Da $\log x$ og $10^x$ er hinandens inverse funktioner, bliver der ikke lavet om på tallene.

3  
$$ab = 10^{\log a + \log b}$$  
Bruger reglen $x^a \cdot x^b = x^{a+b}$.

4  
$$\log(ab) = \log a + \log b$$  
Tager $\log(x)$ på begge sider.

Q.E.D.

**Note**

Denne regel gælder for alle logaritmer, og fremgangsmåden er den samme. Se bevis udført vha. den naturlige logaritme.

<div class = "pagebreak"></div>

## Proof Naturlige logaritme til en brøk

**Sætning**

Om den naturlige logaritme til en brøk gælder følgende
$$
\ln \left( \frac{a}{b} \right) = \ln a - \ln b, \quad a > 0 \land b > 0
$$

**Bevis**

**1**
$$
\ln a = \ln a
$$
Da begge sider af lighedstegnet er identiske, må lighedstegnet gælde.

**2**
$$
\ln \left( \frac{a}{b} \cdot b \right) = \ln a
$$
Ganger og dividerer med $b$ inde i logaritmen på venstre side.

**3**
$$
\ln \left( \frac{a}{b} \right) + \ln b = \ln a
$$
Bruger regnereglen om logaritmen til et produkt.

**4**
$$
\ln \left( \frac{a}{b} \right) = \ln a - \ln b
$$
Trækker $\ln b$ fra på begge sider.

Q.E.D.

**Note**

Denne regel gælder for alle logaritmer og fremgangsmåden er den samme. Se [bevis](#) udført vha. titalslogaritmen.

<div class = "pagebreak"></div>

## Proof Titalslogaritmen til en brøk

**Sætning**

Om titalslogaritmen til en brøk gælder følgende
$$
\log \left( \frac{a}{b} \right) = \log a - \log b, \quad a > 0 \land b > 0
$$

**Bevis**

**1**
$$
\log a = \log a
$$
Da begge sider af lighedstegnet er identiske, må lighedstegnet gælde.

**2**
$$
\log \left( \frac{a}{b} \cdot b \right) = \log a
$$
Ganger og dividerer med $b$ inde i logaritmen på venstre side.

**3**
$$
\log \left( \frac{a}{b} \right) + \log b = \log a
$$
Bruger regnereglen om logaritmen til et produkt.

**4**
$$
\log \left( \frac{a}{b} \right) = \log a - \log b
$$
Trækker $\log b$ fra på begge sider.

Q.E.D.

**Note**

Denne regel gælder for alle logaritmer, og fremgangsmåden er den samme. Se [bevis](#) udført vha. den naturlige logaritme.

<div class = "pagebreak"></div>

## Proof Titalslogaritmen til en brøk version 2

**Sætning**

Om titalslogaritmen til en brøk gælder følgende
$$
\log \left( \frac{a}{b} \right) = \log a - \log b, \quad a > 0 \land b > 0
$$

**Bevis**

**1**
$$
\frac{a}{b} = \frac{a}{b}
$$
Da begge sider af lighedstegnet er identiske, må lighedstegnet gælde.

**2**
$$
\frac{a}{b} = \frac{10^{\log a}}{10^{\log b}}
$$
Tager $\log x$ og $10^x$ til hvert tal på højresiden. Da $\log x$ og $10^x$ er hinandens inverse funktioner, bliver der ikke lavet om på tallene.

**3**
$$
\frac{a}{b} = 10^{\log a - \log b}
$$
Omskriver og bruger reglen $\frac{x^a}{x^b} = x^{a - b}$.

**4**
$$
\log \left( \frac{a}{b} \right) = \log a - \log b
$$
Tager $\log x$ på begge sider.

Q.E.D.

**Note**

Denne regel gælder for alle logaritmer, og fremgangsmåden er den samme. Se [bevis](#) udført vha. den naturlige logaritme.

<div class = "pagebreak"></div>

## Proof Den naturlige logaritme til en potens

**Sætning**

Om den naturlige logaritme til en potens gælder følgende
$$
\ln \left( a^b \right) = b \ln a, \quad a > 0
$$

**Bevis**

**1**
$$
a^b = a^b
$$
Da begge sider af lighedstegnet er identiske, må lighedstegnet gælde.

**2**
$$
a^b = \left( e^{\ln a} \right)^b
$$
Omskriver $a$ vha. $\ln x$ og $e^x$. Da $\ln x$ og $e^x$ er hinandens inverse funktioner, bliver der ikke lavet om på tallene.

**3**
$$
a^b = e^{b \ln a}
$$
Omskriver højresiden vha. reglen $\left( x^a \right)^b = x^{ab}$.

**4**
$$
\ln \left( a^b \right) = b \ln a
$$
Tager $\ln x$ på begge sider.

Q.E.D.

**Note**

Denne regel gælder for alle logaritmer, og fremgangsmåden er den samme. Se [bevis](#) udført vha. titalslogaritmen.

<div class = "pagebreak"></div>

## Proof Titalslogaritmen til en potens

**Sætning**

Om titalslogaritmen til en potens gælder følgende
$$
\log \left( a^b \right) = b \log a, \quad a > 0
$$

**Bevis**

**1**
$$
a^b = a^b
$$
Da begge sider af lighedstegnet er identiske, må lighedstegnet gælde.

**2**
$$
a^b = \left( 10^{\log a} \right)^b
$$
Omskriver $a$ vha. $\log x$ og $10^x$. Da $\log x$ og $10^x$ er hinandens inverse funktioner, bliver der ikke lavet om på tallene.

**3**
$$
a^b = 10^{b \log a}
$$
Omskriver højresiden vha. reglen $\left( x^a \right)^b = x^{ab}$.

**4**
$$
\log \left( a^b \right) = b \log a
$$
Tager $\log x$ på begge sider.

Q.E.D.

**Note**

Denne regel gælder for alle logaritmer, og fremgangsmåden er den samme. Se [bevis](#) udført vha. den naturlige logaritme.	

<div class = "pagebreak"></div>

## Proof Fordoblingskonstanten

**Sætning**

Ved en eksponentiel udvikling kan fordoblingskonstanten bestemmes ved
$$
T_2 = \frac{\log 2}{\log a} = \frac{\ln 2}{\ln a}, \quad \text{hvor} \quad y = b \cdot a^x, \; a > 0, \; a \neq 1
$$

**Bevis**

**1**
$$
f(x + T_2) = 2 \cdot f(x)
$$
For fordoblingskonstanten $T_2$ må denne sammenhæng gælde.

**2**
$$
b \cdot a^{x + T_2} = 2 \cdot b \cdot a^x
$$
Indsætter i $f(x) = b \cdot a^x$.

**3**
$$
a^{x + T_2} = 2 \cdot a^x
$$
Deler med $b$ på begge sider.

**4**
$$
a^x \cdot a^{T_2} = 2 \cdot a^x
$$
Bruger regnereglen $a^{p+q} = a^p \cdot a^q$.

**5**
$$
a^{T_2} = 2
$$
Deler med $a^x$ på begge sider.

**6**
$$
\ln \left( a^{T_2} \right) = \ln 2
$$
Tager den naturlige logaritme på begge sider.

**7**
$$
T_2 \cdot \ln a = \ln 2
$$
Bruger regnereglen om logaritmen til en potens.

**8**
$$
T_2 = \frac{\ln 2}{\ln a}
$$
Deler med $\ln a$ på begge sider.

Q.E.D.

**Note**

Beviset kan lige så let gennemføres ved at bruge $\log x$ i stedet for $\ln x$, da der gælder samme regneregler for begge.

<div class = "pagebreak"></div>

## Proof Halveringskonstanten

**Sætning**

Ved en eksponentiel udvikling kan halveringskonstanten bestemmes ved
$$
T_{0,5} = \frac{\log(0,5)}{\log a} = \frac{\ln(0,5)}{\ln a}, \quad \text{hvor} \quad y = b \cdot a^x, \; a > 0, \; a \neq 1
$$

**Bevis**

**1**
$$
f(x + T_{0,5}) = 0,5 \cdot f(x)
$$
Hvis der findes en halveringskonstant $T_{0,5}$, må denne sammenhæng gælde.

**2**
$$
b \cdot a^{x + T_{0,5}} = 0,5 \cdot b \cdot a^x
$$
Indsætter i $f(x) = b \cdot a^x$.

**3**
$$
a^{x + T_{0,5}} = 0,5 \cdot a^x
$$
Deler med $b$ på begge sider.

**4**
$$
a^x \cdot a^{T_{0,5}} = 0,5 \cdot a^x
$$
Bruger regnereglen $a^{p+q} = a^p \cdot a^q$.

**5**
$$
a^{T_{0,5}} = 0,5
$$
Deler med $a^x$ på begge sider.

**6**
$$
\ln \left( a^{T_{0,5}} \right) = \ln(0,5)
$$
Tager den naturlige logaritme på begge sider.

**7**
$$
T_{0,5} \cdot \ln a = \ln(0,5)
$$
Bruger regnereglen om logaritmen til en potens.

**8**
$$
T_{0,5} = \frac{\ln(0,5)}{\ln a}
$$
Deler med $\ln a$ på begge sider.

Q.E.D.

**Note**

Beviset kan lige så let gennemføres ved at bruge $\log x$ i stedet for $\ln x$, da der gælder samme regneregler for begge.

<div class = "pagebreak"></div>

## Proof Sammenhæng mellem fordoblings- og halveringskonstant

**Sætning**

En halveringskonstant og en fordoblingskonstant kan udtrykkes ved hinanden, men med modsat fortegn.
$$
T_{0,5} = -T_2
$$

**Bevis**

**1**
$$
T_{0,5} = \frac{\ln(0,5)}{\ln a}
$$
Opstiller formlen for en halveringskonstant.

**2**
$$
= \frac{\ln \left(2^{-1}\right)}{\ln a}
$$
Omskriver $0,5$ til en potens.

**3**
$$
= \frac{-\ln 2}{\ln a}
$$
Bruger regnereglen om logaritmen til en potens.

**4**
$$
T_{0,5} = \frac{-\ln 2}{\ln a} = -T_2
$$
Substituerer formlen for en fordoblingskonstant ind.

Q.E.D.

**Note**

Beviset kan lige så let gennemføres ved at bruge $\log x$ i stedet for $\ln x$, da der gælder samme regneregler for begge.

<div class = "pagebreak"></div>

## Proof Logaritmen med vilkårligt grundtal

**Sætning**

En logaritmefunktion med vilkårligt grundtal $g$ er proportional med $\ln(x)$. Dvs.
$$
\log_g(x) = \frac{1}{\ln(g)} \cdot \ln(x) = \frac{\ln(x)}{\ln(g)}
$$

**Bevis**

**1**
$$
x = x
$$
Da begge sider er identiske, må lighedstegnet gælde.

**2**
$$
g^{\log_g(x)} = x
$$
Tager logaritmen med et vilkårligt grundtal $g$ og dens inverse på venstresiden. De to funktioner ophæver hinanden, og der er derfor ikke lavet om på tallet.

**3**
$$
\ln \left( g^{\log_g(x)} \right) = \ln(x)
$$
Tager den naturlige logaritme på begge sider af lighedstegnet.

**4**
$$
\log_g(x) \cdot \ln(g) = \ln(x)
$$
Bruger reglen om logaritmen til en potens.

**5**
$$
\log_g(x) = \frac{1}{\ln(g)} \cdot \ln(x) = \frac{\ln(x)}{\ln(g)}
$$
Deler med $\ln(g)$ på begge sider.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af potensfunktion

**Sætning**

Differentialkvotienten af en potensfunktion er givet ved
$$
(x^n)' = n \cdot x^{n-1}
$$

**Bevis**

**1**
$$
(x^n)' = \left( e^{\ln(x^n)} \right)'
$$
$x^n$ omskrives ved at tage både den naturlige logaritme og eksponentialfunktionen til $x^n$. Da eksponentialfunktionen og den naturlige logaritme ophæver hinanden, er tallet ikke lavet om.

**2**
$$
= \left( e^{n \cdot \ln x} \right)'
$$
Bruger reglen om logaritmen til en potensfunktion $\ln(x^n) = n \cdot \ln x$.

**3**
$$
= e^{n \cdot \ln x} \cdot n \cdot \frac{1}{x}
$$
Der er tale om en sammensat funktion, så kædereglen $(f(g))' = f'(g) \cdot g'$ bruges. Eksponentialfunktionen differentieret giver sig selv $\left(e^x\right)' = e^x$.

**4**
$$
= x^n \cdot n \cdot \frac{1}{x}
$$
Omskriver eksponentialfunktionen til $x^n$, da $e^{n \cdot \ln x} = \left(e^{\ln x}\right)^n = x^n$.

**5**
$$
= \frac{n \cdot x^n}{x}
$$
Bytter om på faktorerne og sætter på samme brøkstreg.

**6**
$$
(x^n)' = n \cdot x^{n-1}
$$
Bruger reglen om en brøk af to potensfunktioner $\frac{x^a}{x^b} = x^{a - b}$.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af kvadratfunktion

**Sætning**

Differentialkvotienten af en kvadratfunktion er givet ved
$$
(x^2)' = 2x
$$

**Bevis**

**1**
$$
y = x^2
$$
Sætter $y = x^2$.

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{(x_0 + \Delta x)^2 - x_0^2}{\Delta x}
$$
Beviser vha. tretrins-reglen. Opstiller differenskvotienten.

**3**
$$
= \frac{x_0^2 + (\Delta x)^2 + 2x_0 \Delta x - x_0^2}{\Delta x}
$$
Udregner parentesen vha. reglen om kvadratet på en to-leddet størrelse.

**4**
$$
= \frac{(\Delta x)^2 + 2x_0 \Delta x}{\Delta x}
$$
Fjerner begge led med $x_0^2$, da de går ud med hinanden.

**5**
$$
= \Delta x + 2x_0
$$
Forkorter med $\Delta x$.

**6**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} (\Delta x + 2x_0) = 2x_0
$$
Tager grænseværdien og $\Delta x$ forsvinder, da det går mod nul.

**7**
$$
\frac{dy}{dx} = 2x
$$
Grænseværdien til en differenskvotient er den tilsvarende differentialkvotient.

**8**
$$
y' = 2x
$$
Omskriver til Lagranges notation.

**9**
$$
(x^2)' = 2x
$$

Q.E.D.

**Note**

Dette er selvfølgelig et specialtilfælde af $(x^n)' = n \cdot x^{n-1}$, hvor $n = 2$.

<div class = "pagebreak"></div>

## Proof Differentiation af reciprokfunktion

**Sætning**

Differentialkvotienten af en reciprokfunktion er givet ved
$$
\left( \frac{1}{x} \right)' = -\frac{1}{x^2}, \quad x \neq 0
$$

**Bevis**

**1**
$$
y = \frac{1}{x}
$$
Sætter $y = \frac{1}{x}$.

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{\frac{1}{x_0 + \Delta x} - \frac{1}{x_0}}{\Delta x}
$$
Beviser vha. tretrins-reglen. Opstiller differenskvotienten.

**3**
$$
= \frac{\frac{1}{x_0 + \Delta x} \cdot \frac{x_0}{x_0} - \frac{1}{x_0} \cdot \frac{x_0 + \Delta x}{x_0 + \Delta x}}{\Delta x}
$$
Forlænger brøkerne i tælleren for at sætte på fælles brøkstreg.

**4**
$$
= \frac{x_0 - (x_0 + \Delta x)}{(x_0 + \Delta x) x_0 \cdot \Delta x}
$$
Sætter tæller på fælles brøkstreg.

**5**
$$
= \frac{-\Delta x}{(x_0 + \Delta x) x_0 \cdot \Delta x}
$$
Fjerner de to led med $x_0$, da de går ud med hinanden.

**6**
$$
= \frac{-1}{(x_0 + \Delta x) x_0}
$$
Deler med $\Delta x$ i både tæller og nævner.

**7**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{-1}{(x_0 + \Delta x) x_0} = \frac{-1}{x_0 \cdot x_0} = -\frac{1}{x_0^2}
$$
Tager grænseværdien, og $\Delta x$ forsvinder, da det går mod nul.

**8**
$$
\frac{dy}{dx} = -\frac{1}{x^2}
$$
Grænseværdien af en differenskvotient er den tilsvarende differentialkvotient.

**9**
$$
y' = -\frac{1}{x^2}
$$
Omskriver til Lagranges notation.

**10**
$$
\left( \frac{1}{x} \right)' = -\frac{1}{x^2}
$$

Q.E.D.

**Note**

Dette er selvfølgelig et specialtilfælde af $(x^n)' = n \cdot x^{n-1}$, hvor $n = -1$.

<div class = "pagebreak"></div>

## Proof Differentiation af kvadratrodsfunktion

**Sætning**

Differentialkvotienten af en kvadratrodsfunktion er givet ved
$$
(\sqrt{x})' = \frac{1}{2\sqrt{x}}
$$

**Bevis**

**1**
$$
y = \sqrt{x}
$$
Sætter $y = \sqrt{x}$.

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{\sqrt{x_0 + \Delta x} - \sqrt{x_0}}{\Delta x}
$$
Beviser ved hjælp af tretrins-reglen. Opstiller differenskvotienten.

**3**
$$
= \frac{\sqrt{x_0 + \Delta x} - \sqrt{x_0}}{\Delta x} \cdot \frac{\sqrt{x_0 + \Delta x} + \sqrt{x_0}}{\sqrt{x_0 + \Delta x} + \sqrt{x_0}}
$$
Forlænger brøken.

**4**
$$
= \frac{(x_0 + \Delta x) - x_0}{\Delta x \cdot (\sqrt{x_0 + \Delta x} + \sqrt{x_0})}
$$
Bruger kvadratsætningen $(a + b)(a - b) = a^2 - b^2$.

**5**
$$
= \frac{\Delta x}{\Delta x \cdot (\sqrt{x_0 + \Delta x} + \sqrt{x_0})}
$$
Kvadratroden og kvadratet går ud med hinanden i begge led i tælleren.

**6**
$$
= \frac{1}{\sqrt{x_0 + \Delta x} + \sqrt{x_0}}
$$
Forkorter med $\Delta x$ i både tæller og nævner.

**7**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{1}{\sqrt{x_0 + \Delta x} + \sqrt{x_0}} = \frac{1}{2\sqrt{x_0}}
$$
Tager grænseværdien, og $\Delta x$ forsvinder, da det går mod nul.

**8**
$$
\frac{dy}{dx} = \frac{1}{2\sqrt{x}}
$$
Grænseværdien til en differenskvotient er den tilsvarende differentialkvotient.

**9**
$$
y' = \frac{1}{2\sqrt{x}}
$$
Omskriver til Lagranges notation.

**10**
$$
(\sqrt{x})' = \frac{1}{2\sqrt{x}}
$$

Q.E.D.

**Note**

Dette er selvfølgelig et specialtilfælde af $(x^n)' = n \cdot x^{n-1}$, hvor $n = \frac{1}{2}$.

<div class = "pagebreak"></div>

## Proof Differentiation af reciprokfunktion - Øvelse

**Sætning**

Differentialkvotienten af en reciprokfunktion er givet ved
$$
\left( \frac{1}{x} \right)' = -\frac{1}{x^2}, \quad x \neq 0
$$

**Bevis**

**1**
$$
y = \frac{1}{x}
$$
Sætter $y = \frac{1}{x}$.

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{\frac{1}{x_0 + \Delta x} - \frac{1}{x_0}}{\Delta x}
$$

**3**
$$
= \frac{\frac{1}{x_0 + \Delta x} \cdot \frac{x_0}{x_0} - \frac{1}{x_0} \cdot \frac{x_0 + \Delta x}{x_0 + \Delta x}}{\Delta x}
$$
Forlænger brøkerne i tælleren for at sætte på fælles brøkstreg.

**4**
$$
= \frac{x_0 - (x_0 + \Delta x)}{(x_0 + \Delta x) x_0 \cdot \Delta x}
$$

**5**
$$
= \frac{-\Delta x}{(x_0 + \Delta x) x_0 \cdot \Delta x}
$$

**6**
$$
= \frac{-1}{(x_0 + \Delta x) x_0}
$$
Deler med $\Delta x$ i både tæller og nævner.

**7**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{-1}{(x_0 + \Delta x) x_0} = \frac{-1}{x_0 \cdot x_0} = -\frac{1}{x_0^2}
$$

**8**
$$
\frac{dy}{dx} = -\frac{1}{x^2}
$$

**9**
$$
y' = -\frac{1}{x^2}
$$

**10**
$$
\left( \frac{1}{x} \right)' = -\frac{1}{x^2}
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af kvadratrodsfunktion - øvelse

**Sætning**

Differentialkvotienten af en kvadratrodsfunktion er givet ved
$$
(\sqrt{x})' = \frac{1}{2\sqrt{x}}
$$

**Bevis**

**1**
$$
y = \sqrt{x}
$$
Sætter $y = \sqrt{x}$.

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{\sqrt{x_0 + \Delta x} - \sqrt{x_0}}{\Delta x}
$$

**3**
$$
= \frac{\sqrt{x_0 + \Delta x} - \sqrt{x_0}}{\Delta x} \cdot \frac{\sqrt{x_0 + \Delta x} + \sqrt{x_0}}{\sqrt{x_0 + \Delta x} + \sqrt{x_0}}
$$
Forlænger brøken.

**4**
$$
= \frac{(x_0 + \Delta x) - x_0}{\Delta x \cdot (\sqrt{x_0 + \Delta x} + \sqrt{x_0})}
$$
Bruger kvadratsætningen $(a + b)(a - b) = a^2 - b^2$.

**5**
$$
= \frac{\Delta x}{\Delta x \cdot (\sqrt{x_0 + \Delta x} + \sqrt{x_0})}
$$

**6**
$$
= \frac{1}{\sqrt{x_0 + \Delta x} + \sqrt{x_0}}
$$
Forkorter med $\Delta x$ i både tæller og nævner.

**7**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{1}{\sqrt{x_0 + \Delta x} + \sqrt{x_0}} = \frac{1}{2\sqrt{x_0}}
$$
Tager grænseværdien, og $\Delta x$ forsvinder, da det går mod nul.

**8**
$$
\frac{dy}{dx} = \frac{1}{2\sqrt{x}}
$$

**9**
$$
y' = \frac{1}{2\sqrt{x}}
$$

**10**
$$
(\sqrt{x})' = \frac{1}{2\sqrt{x}}
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af eksponentialfunktionen

**Sætning**

Differentialkvotienten af eksponentialfunktionen er givet ved
$$
(e^x)' = e^x
$$

**Bevis**

**1**
$$
y = e^x
$$
Sætter $y = e^x$.

**2**
$$
\ln y = x
$$
Tager den naturlige logaritme på begge sider af lighedstegnet.

**3**
$$
\frac{1}{y} = \frac{dx}{dy}
$$
Differentierer begge sider med hensyn til $y$.

**4**
$$
dy = y \cdot dx
$$
Ganger begge sider med $y$ og $dy$.

**5**
$$
\frac{dy}{dx} = y
$$
Deler begge sider med $dx$.

**6**
$$
\frac{dy}{dx} = e^x
$$
Substituerer $y$ med $e^x$.

**7**
$$
y' = e^x
$$
Omskriver til Lagranges notation.

**8**
$$
(e^x)' = e^x
$$

Q.E.D.

**Note**

Dette resultat viser, at eksponentialfunktionen $e^x$ er unik, da den er sin egen afledte.

<div class = "pagebreak"></div>

## Proof Differentiation af en eksponentialfunktion

**Sætning**

Differentialkvotienten af en eksponentialfunktion er givet ved
$$
(a^x)' = a^x \cdot \ln a
$$

**Bevis**

**1**
$$
y = a^x
$$
Sætter $y = a^x$.

**2**
$$
y = \left( e^{\ln a} \right)^x
$$
Omskriver $a$ ved at tage både eksponentialfunktionen og den naturlige logaritme til $a$.

**3**
$$
y = e^{x \ln a}
$$
Bruger regnereglen $\left( x^a \right)^b = x^{a \cdot b}$.

**4**
$$
y' = e^{x \ln a} \cdot \ln a
$$
Det er en sammensat funktion og differentieres vha. kædereglen.

**5**
$$
y' = a^x \cdot \ln a
$$
Erstatter $e^{x \ln a}$ med $a^x$ svarende til omskrivningen i bevisets første to linjer.

**6**
$$
(a^x)' = a^x \cdot \ln a
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af den naturlige logaritme

**Sætning**

Differentialkvotienten af den naturlige logaritme er givet ved
$$
(\ln x)' = \frac{1}{x}
$$

**Bevis**

Da man kan definere $\ln a$ som arealfunktionen $\ln a = \int_1^a \frac{1}{x} \, dx$, $x > 0$, følger det af definitionen, at reglen må gælde. En funktion, der angiver arealet under en kurve, har jo netop kurven som sin afledede funktion, jf. infinitesimalregningens fundamentalsætning.

**1**
$$
(\ln x)' = \frac{1}{x}
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af titalslogaritmen

**Sætning**

Differentialkvotienten af titalslogaritmen er givet ved
$$
(\log x)' = \frac{1}{x \cdot \ln 10}
$$

**Bevis**

**1**
$$
y = \log x = \frac{1}{\ln 10} \ln x
$$
Omskriver logaritmen med grundtal 10, så den udtrykkes ved $\ln$.

**2**
$$
y' = \frac{1}{\ln 10} \cdot \frac{1}{x} = \frac{1}{x \cdot \ln 10}
$$
Differentierer og bruger reglen om differentiation af $\ln x$ og differentiation af konstant gange funktion.

**3**
$$
(\log x)' = \frac{1}{x \cdot \ln 10}
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af logaritmen med grundtal \( g \)

**Sætning**

Differentialkvotienten af logaritmen med grundtallet \( g \) er givet ved
$$
(\log_g x)' = \frac{1}{x \cdot \ln g}
$$

**Bevis**

**1**
$$
y = \log_g x = \frac{1}{\ln g} \ln x
$$
Omskriver logaritmen med grundtal \( g \), så den udtrykkes ved \( \ln \).

**2**
$$
y' = \frac{1}{\ln g} \cdot \frac{1}{x} = \frac{1}{x \cdot \ln g}
$$
Differentierer og bruger reglen om differentiation af \( \ln x \) og differentiation af konstant gange funktion.

**3**
$$
(\log_g x)' = \frac{1}{x \cdot \ln g}
$$

Q.E.D.
<div class = "pagebreak"></div>

## Proof Differentiation af sinus

**Sætning**

Differentialkvotienten af sinus er givet ved
$$
(\sin x)' = \cos x
$$

**Bevis**

![Circle Diagram with Sin and Cos](https://bevissamling.systime.dk/fileadmin/_processed_/d/8/csm_sinus_9736f504db.png)

**1**
$$
y = \sin x
$$
Sætter $y = \sin x$.

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{\sin(x_0 + \Delta x) - \sin x_0}{\Delta x}
$$
Beviser vha. tretrins-reglen. Opstiller differenskvotienten.

**3**
$$
= \frac{|AC|}{\Delta x}
$$
$\Delta y$ svarer til afstanden fra $A$ til $C$.

**4**
$$
= \frac{|AB| \cos v}{\Delta x}
$$
Anvender sammenhængen med cosinus i den retvinklede trekant. $|AC| = |AB| \cos v$.

**5**
$$
= \frac{|AB| \cos(x_0 + \frac{1}{2} \Delta x)}{\Delta x}
$$
Da $v$ er en periferivinkel, må der gælde, at $v$ er det halve af $x_0 + (x_0 + \Delta x)$. Dvs. $v = x_0 + \frac{1}{2} \Delta x$.

**6**
$$
= \frac{|AB|}{\Delta x} \cos(x_0 + \frac{1}{2} \Delta x)
$$
Adskiller brøken $\frac{|AB|}{\Delta x}$, da hypotenusens længde $|AB|$ jo nærmer sig cirkelbuens længde $\Delta x$ jo mindre $\Delta x$ bliver.

**7**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{|AB|}{\Delta x} \cos(x_0 + \frac{1}{2} \Delta x) = \cos x_0
$$
Tager grænseværdien og $\frac{1}{2} \Delta x$ forsvinder, da leddet jo går mod nul, og $\frac{|AB|}{\Delta x} \to 1$.

**8**
$$
\frac{dy}{dx} = \cos x
$$
Grænseværdien til en differenskvotient er den tilsvarende differentialkvotient.

**9**
$$
y' = \cos x
$$
Omskriver til Lagranges notation.

**10**
$$
(\sin x)' = \cos x
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af cosinus

**Sætning**

Differentialkvotienten af cosinus er givet ved
$$
(\cos x)' = -\sin x
$$

**Bevis**

![Circle Diagram with Sin and Cos](https://bevissamling.systime.dk/fileadmin/_processed_/a/3/csm_cosinus_c111e2a7bd.png)

**1**
$$
y = \cos x
$$
Sætter $y = \cos x$.

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{\cos(x_0 + \Delta x) - \cos x_0}{\Delta x}
$$
Beviser vha. tretrins-reglen. Opstiller differenskvotienten.

**3**
$$
= -\frac{|BC|}{\Delta x}
$$
$\Delta y$ svarer til afstanden fra $B$ til $C$, men med et negativt fortegn, da $\Delta y$ er negativ.

**4**
$$
= -\frac{|AB| \sin(v)}{\Delta x}
$$
Anvender sammenhængen med sinus i den retvinklede trekant. $|BC| = |AB| \sin(v)$.

**5**
$$
= -\frac{|AB| \sin(x_0 + \frac{1}{2} \Delta x)}{\Delta x}
$$
Da $v$ er en periferivinkel, må der gælde, at $v$ er det halve af $x_0 + (x_0 + \Delta x)$. Dvs. $v = x_0 + \frac{1}{2} \Delta x$.

**6**
$$
= -\frac{|AB|}{\Delta x} \sin(x_0 + \frac{1}{2} \Delta x)
$$
Adskiller brøken $\frac{|AB|}{\Delta x}$, da hypotenusens længde $|AB|$ jo nærmer sig cirkelbuens længde $\Delta x$ jo mindre $\Delta x$ bliver.

**7**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} -\frac{|AB|}{\Delta x} \sin(x_0 + \frac{1}{2} \Delta x) = -\sin x_0
$$
Tager grænseværdien og $\frac{1}{2} \Delta x$ forsvinder, da leddet jo går mod nul, og $\frac{|AB|}{\Delta x} \to 1$.

**8**
$$
\frac{dy}{dx} = -\sin x
$$
Grænseværdien til en differenskvotient er den tilsvarende differentialkvotient.

**9**
$$
y' = -\sin x
$$
Omskriver til Lagranges notation.

**10**
$$
(\cos x)' = -\sin x
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af tangens

**Sætning**

Differentialkvotienten af tangens er givet ved
$$
(\tan x)' = 1 + \tan^2 x = \frac{1}{\cos^2 x}
$$

**Bevis**

**1**
$$
y = \tan x
$$
Sætter $y = \tan x$.

**2**
$$
y = \frac{\sin x}{\cos x}
$$
Omskriver da $\tan x = \frac{\sin x}{\cos x}$.

**3**
$$
y' = \frac{(\sin x)' \cdot \cos x - \sin x \cdot (\cos x)'}{\cos^2 x}
$$
Bruger reglen om differentiation af en brøk.

**4**
$$
= \frac{\cos x \cdot \cos x - \sin x \cdot (-\sin x)}{\cos^2 x}
$$
Differentierer hhv. $\sin x$ og $\cos x$.

**5**
$$
= \frac{\cos^2 x + \sin^2 x}{\cos^2 x} = \frac{1}{\cos^2 x}
$$
Reducerer vha. grundrelationen, der jo siger, at $\sin^2 x + \cos^2 x = 1$.

**6**
$$
= \frac{\cos^2 x}{\cos^2 x} + \frac{\sin^2 x}{\cos^2 x} = \frac{1}{\cos^2 x}
$$
Opdeler i to brøker.

**7**
$$
= 1 + \frac{\sin^2 x}{\cos^2 x} = \frac{1}{\cos^2 x}
$$
Reducerer venstre brøk og omskriver anden brøk vha. reglen $\frac{a^2}{b^2} = \left( \frac{a}{b} \right)^2$.

**8**
$$
= 1 + \tan^2 x = \frac{1}{\cos^2 x}
$$
Erstatter $\frac{\sin x}{\cos x}$ med $\tan x$.

**9**
$$
(\tan x)' = 1 + \tan^2 x = \frac{1}{\cos^2 x}
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af en sum

**Sætning**

Om differentiation af en sum gælder følgende
$$
(f(x) + g(x))' = f'(x) + g'(x)
$$

**Bevis**

**1**
$$
h(x) = f(x) + g(x)
$$
Definerer funktionen $h$ ud fra $f$ og $g$. Gennemfører beviset vha. tretrins-reglen.

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{h(x_0 + \Delta x) - h(x_0)}{\Delta x}
$$
Opstiller differenskvotienten for $h$.

**3**
$$
= \frac{(f(x_0 + \Delta x) + g(x_0 + \Delta x)) - (f(x_0) + g(x_0))}{\Delta x}
$$
Omskriver til $f$ og $g$.

**4**
$$
= \frac{f(x_0 + \Delta x) - f(x_0) + g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$
Hæver minusparentesen og flytter rundt på de forskellige led.

**5**
$$
= \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} + \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$
Opdeler i to brøker, der viser differenskvotienterne for hhv. $f$ og $g$.

**6**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} + \lim_{\Delta x \to 0} \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$
Tager grænseværdien.

**7**
$$
\frac{d h(x)}{dx} = \frac{d f(x)}{dx} + \frac{d g(x)}{dx}
$$
Grænseværdien til differenskvotienten er pr. definition lig med differentialkvotienten.

**8**
$$
h'(x) = f'(x) + g'(x)
$$
Omskriver til Lagranges notation.

**9**
$$
(f(x) + g(x))' = f'(x) + g'(x)
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af en sum - øvelse - kun udregninger

**Sætning**

Om differentiation af en sum gælder følgende
$$
(f(x) + g(x))' = f'(x) + g'(x)
$$

**Bevis**

**1**
$$
h(x) = f(x) + g(x)
$$

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{h(x_0 + \Delta x) - h(x_0)}{\Delta x}
$$

**3**
$$
= \frac{(f(x_0 + \Delta x) + g(x_0 + \Delta x)) - (f(x_0) + g(x_0))}{\Delta x}
$$

**4**
$$
= \frac{f(x_0 + \Delta x) - f(x_0) + g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$

**5**
$$
= \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} + \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$

**6**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} + \lim_{\Delta x \to 0} \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$

**7**
$$
\frac{d h(x)}{dx} = \frac{d f(x)}{dx} + \frac{d g(x)}{dx}
$$

**8**
$$
h'(x) = f'(x) + g'(x)
$$

**9**
$$
(f(x) + g(x))' = f'(x) + g'(x)
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af en differens

**Sætning**

Om differentiation af en differens gælder følgende
$$
(f(x) - g(x))' = f'(x) - g'(x)
$$

**Bevis**

**1**
$$
h(x) = f(x) - g(x)
$$
Definerer funktionen $h$ ud fra $f$ og $g$. Gennemfører beviset vha. tretrins-reglen.

**2**
$$
\frac{\Delta y}{\Delta x} = \frac{h(x_0 + \Delta x) - h(x_0)}{\Delta x}
$$
Opstiller differenskvotienten for $h$.

**3**
$$
= \frac{(f(x_0 + \Delta x) - g(x_0 + \Delta x)) - (f(x_0) - g(x_0))}{\Delta x}
$$
Omskriver til $f$ og $g$.

**4**
$$
= \frac{f(x_0 + \Delta x) - f(x_0) - (g(x_0 + \Delta x) - g(x_0))}{\Delta x}
$$
Hæver minusparentesen og bytter om på andet og tredje led. Sætter en ny minusparentes om tredje og fjerde led.

**5**
$$
= \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} - \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$
Opdeler i to brøker, der hver især viser differenskvotienterne for hhv. $f$ og $g$.

**6**
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} - \lim_{\Delta x \to 0} \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$
Tager grænseværdien.

**7**
$$
\frac{d h(x)}{dx} = \frac{d f(x)}{dx} - \frac{d g(x)}{dx}
$$
Grænseværdien til differenskvotienten er pr. definition lig med differentialkvotienten.

**8**
$$
h'(x) = f'(x) - g'(x)
$$
Omskriver til Lagranges notation.

**9**
$$
(f(x) - g(x))' = f'(x) - g'(x)
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af en sum - øvelse - kun forklaringer

**Sætning**

Om differentiation af en sum gælder følgende
$$
(f(x) + g(x))' = f'(x) + g'(x)
$$

**Bevis**

**1**

Definerer funktionen $h$ ud fra $f$ og $g$. Gennemfører beviset vha. tretrins-reglen.
$$
h(x) = f(x) + g(x)
$$

**2**

Opstiller differenskvotienten for $h$.
$$
\frac{\Delta y}{\Delta x} = \frac{h(x_0 + \Delta x) - h(x_0)}{\Delta x}
$$

**3**

Omskriver til $f$ og $g$.
$$
= \frac{(f(x_0 + \Delta x) + g(x_0 + \Delta x)) - (f(x_0) + g(x_0))}{\Delta x}
$$

**4**

Hæver minusparentesen og flytter rundt på de forskellige led.
$$
= \frac{f(x_0 + \Delta x) - f(x_0) + g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$

**5**

Opdeler i to brøker, der viser differenskvotienterne for hhv. $f$ og $g$.
$$
= \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} + \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$

**6**

Tager grænseværdien.
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} + \lim_{\Delta x \to 0} \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}
$$

**7**

Grænseværdien til differenskvotienten er pr. definition lig med differentialkvotienten.
$$
\frac{d h(x)}{dx} = \frac{d f(x)}{dx} + \frac{d g(x)}{dx}
$$

**8**

Omskriver til Lagranges notation.
$$
h'(x) = f'(x) + g'(x)
$$

**9**

$$
(f(x) + g(x))' = f'(x) + g'(x)
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af konstant gange funktion

**Sætning**

Om differentiation af konstant gange en funktion gælder følgende
$$
(k \cdot f(x))' = k \cdot f'(x)
$$

**Bevis**

**1**

Gennemfører beviset vha. tretrins-reglen og opstiller differenskvotienten.
$$
\frac{\Delta y}{\Delta x} = \frac{k \cdot f(x_0 + \Delta x) - k \cdot f(x_0)}{\Delta x}
$$

**2**

Sætter $k$ uden for brøken (svarer til at sætte uden for en parentes).
$$
= k \cdot \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
$$

**3**

Udregner grænseværdien.
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} k \cdot \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
$$

**4**

Sætter $k$ uden for grænseværdien.
$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = k \cdot \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
$$

**5**

Grænseværdien til differenskvotienten er lig med differentialkvotienten.
$$
\frac{dy}{dx} = k \cdot \frac{d f(x)}{dx}
$$

**6**

Omskriver til Lagranges notation.
$$
y' = k \cdot f'(x)
$$

**7**

Da $y = k \cdot f(x)$,
$$
(k \cdot f(x))' = k \cdot f'(x)
$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af produkt

**Sætning**

Om differentiation af produkt gælder følgende
$$(f(x) \cdot g(x))' = f'(x) \cdot g(x) + f(x) \cdot g'(x)$$

**Bevis**

**1**

Definerer funktionen $h$ ud fra $f$ og $g$. Gennemfører beviset vha. tretrins-reglen.
$$h(x) = f(x) \cdot g(x)$$

**2**

Opstiller differenskvotienten for $h$.
$$\frac{\Delta y}{\Delta x} = \frac{h(x_0 + \Delta x) - h(x_0)}{\Delta x}$$

**3**

Omskriver til $f$ og $g$.
$$= \frac{f(x_0 + \Delta x) \cdot g(x_0 + \Delta x) - f(x_0) \cdot g(x_0)}{\Delta x}$$

**4**

Lægger $f(x_0) \cdot g(x_0 + \Delta x)$ til i tælleren og trækker det fra igen.
$$= \frac{f(x_0 + \Delta x) \cdot g(x_0 + \Delta x) - f(x_0) \cdot g(x_0 + \Delta x) + f(x_0) \cdot g(x_0 + \Delta x) - f(x_0) \cdot g(x_0)}{\Delta x}$$

**5**

Bytter om på andet og fjerde led i tælleren.
$$= \frac{f(x_0 + \Delta x) \cdot g(x_0 + \Delta x) - f(x_0) \cdot g(x_0 + \Delta x)}{\Delta x} + \frac{f(x_0) \cdot g(x_0 + \Delta x) - f(x_0) \cdot g(x_0)}{\Delta x}$$

**6**

Opdeler i to brøker.
$$= \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} \cdot g(x_0 + \Delta x) + f(x_0) \cdot \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}$$

**7**

Sætter hhv. $g(x_0 + \Delta x)$ og $f(x_0)$ uden for deres respektive brøker.
$$\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} \cdot g(x_0 + \Delta x) + \lim_{\Delta x \to 0} f(x_0) \cdot \frac{g(x_0 + \Delta x) - g(x_0)}{\Delta x}$$

**8**

Grænseværdien til de respektive brøker svarer til differentialkvotienterne for $f$ og $g$. Da $g$ er kontinuert i $x_0$ gælder, at grænseværdien til $g(x_0 + \Delta x) \to g(x_0)$ for $\Delta x \to 0$.
$$\frac{d h(x)}{dx} = \frac{d f(x)}{dx} \cdot g(x) + f(x) \cdot \frac{d g(x)}{dx}$$

**9**

Omskriver til Lagranges notation.
$$h'(x) = f'(x) \cdot g(x) + f(x) \cdot g'(x)$$

**10**

Da $h(x) = f(x) \cdot g(x)$,
$$(f(x) \cdot g(x))' = f'(x) \cdot g(x) + f(x) \cdot g'(x)$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiation af en brøk

**Sætning**

Om differentiation af en brøk gælder følgende
$$\left( \frac{f(x)}{g(x)} \right)' = \frac{f'(x) \cdot g(x) - f(x) \cdot g'(x)}{(g(x))^2}$$

**Bevis**

**1**

Definerer funktionen $h$ ud fra $f$ og $g$. Gennemfører beviset vha. tretrins-reglen.
$$h(x) = \frac{f(x)}{g(x)}$$

**2**

Opstiller differenskvotienten for $h$.
$$\frac{\Delta y}{\Delta x} = \frac{h(x_0 + \Delta x) - h(x_0)}{\Delta x}$$

**3**

Omskriver til $f$ og $g$.
$$= \frac{\frac{f(x_0 + \Delta x)}{g(x_0 + \Delta x)} - \frac{f(x_0)}{g(x_0)}}{\Delta x}$$

**4**

Forlænger brøkerne i tælleren for at sætte på fælles brøkstreg.
$$= \frac{\frac{f(x_0 + \Delta x) \cdot g(x_0) - f(x_0) \cdot g(x_0 + \Delta x)}{g(x_0 + \Delta x) \cdot g(x_0)}}{\Delta x}$$

**5**

Sætter tælleren på fælles brøkstreg.
$$= \frac{f(x_0 + \Delta x) \cdot g(x_0) - f(x_0) \cdot g(x_0 + \Delta x)}{g(x_0 + \Delta x) \cdot g(x_0) \cdot \Delta x}$$

**6**

Samler de to nævnere idet $\left( \frac{a}{b} \right) = \frac{a}{b \cdot c}$.
$$= \frac{f(x_0 + \Delta x) \cdot g(x_0) - f(x_0) \cdot g(x_0 + \Delta x)}{g(x_0 + \Delta x) \cdot g(x_0) \cdot \Delta x}$$

**7**

Lægger $f'(x_0) \cdot g(x_0)$ til og trækker det fra i tælleren.
$$= \frac{\left( f(x_0 + \Delta x) \cdot g(x_0) - f(x_0) \cdot g(x_0 + \Delta x) + f(x_0 + \Delta x) \cdot g(x_0 + \Delta x) - f(x_0) \cdot g(x_0) \right)}{g(x_0 + \Delta x) \cdot g(x_0) \cdot \Delta x}$$

**8**

Flytter tællerens fjerde led ind mellem tællerens første og andet led. Indsætter en minusparentes om det nye tredje og fjerde led.
$$= \frac{(f(x_0 + \Delta x) - f(x_0)) \cdot g(x_0) - f(x_0) \cdot (g(x_0 + \Delta x) - g(x_0))}{g(x_0 + \Delta x) \cdot g(x_0) \cdot \Delta x}$$

**9**

Sætter hhv. $f(x_0)$ og $g(x_0)$ uden for parenteser.
$$= \frac{(f(x_0 + \Delta x) - f(x_0)) \cdot g(x_0) - f(x_0) \cdot (g(x_0 + \Delta x) - g(x_0))}{g(x_0 + \Delta x) \cdot g(x_0) \cdot \Delta x}$$

**10**

Opdeler nævneren i to vha. samme regel ovenfor hvor de to nævnere blev samlet.
$$= \frac{(f(x_0 + \Delta x) - f(x_0)) \cdot g(x_0) - f(x_0) \cdot (g(x_0 + \Delta x) - g(x_0))}{g(x_0 + \Delta x) \cdot g(x_0) \cdot \Delta x}$$

**11**

Opdeler tælleren i to brøker.
$$= \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} - \frac{f(x_0) \cdot g(x_0)}{\Delta x \cdot g(x_0)}$$

**12**

Tager grænseværdien.
$$\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} - f(x_0)$$

<div class = "pagebreak"></div>

## Proof Differentiation af sammensat funktion (kædereglen)

**Sætning**

Om differentiation af en sammensat funktion gælder følgende
$$(f(g(x)))' = f'(g(x)) \cdot g'(x)$$
Hvor $g$ er differentiabel i $x$ og $f$ er differentiabel i $g(x)$.

**Bevis**

**1**

Definerer $h$.
$$h(x) = f(g(x))$$

**2**

Sætter $y = h(x)$.
$$y = h(x)$$

**3**

Opskriver differentialkvotienten vha. Leibniz' notation.
$$h'(x) = \frac{dy}{dx}$$

**4**

Forlænger brøken og bytter om på nævnerne.
$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$$

**5**

Vender tilbage til Lagranges notation, og $u$ erstattes af $g(x)$.
$$= f'(u) \cdot u' = f'(g(x)) \cdot g'(x)$$

**6**

$$\left(f(g(x))\right)' = f'(g(x)) \cdot g'(x)$$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Tangentens ligning

**Sætning**

For en differentierbar funktion $f$ findes ligningen for en tangent i punktet $(x_0, f(x_0))$ som
$$ y = f'(x_0)(x - x_0) + f(x_0) $$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/7/3/csm_Tangtens_ligning_ab9b5ce8ce.png)

**1**

Tangentes hældningskoefficient svarer til differentialkvotienten $f'(x_0)$.
$$ \frac{\Delta y}{\Delta x} = f'(x_0) $$

**2**

Omskriver $\Delta y$ og $\Delta x$.
$$ \frac{y - f(x_0)}{x - x_0} = f'(x_0) $$

**3**

Ganger med $x - x_0$ på begge sider.
$$ y - f(x_0) = f'(x_0)(x - x_0) $$

**4**

Lægger $f(x_0)$ til på begge sider.
$$ y = f'(x_0)(x - x_0) + f(x_0) $$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Rolles sætning

**Sætning**

For en funktion $f(x)$, der er kontinuert i intervallet $[a; b]$ og differentiabel i $]a; b[$ og hvor $f(a) = f(b)$, gælder, at der findes mindst et punkt $c$ i $]a; b[$ hvor
$$ f'(c) = 0 $$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/4/2/csm_rolle_bd7ddf78d5.png)

**1**

Da funktionen er kontinuert i hele intervallet, må $f(x)$ have et maksimumspunkt ved $x_{\text{max}}$ og et minimumspunkt ved $x_{\text{min}}$ et sted i intervallet. Funktionsværdierne må derfor ligge i det angivne interval.
$$ f(x_{\text{min}}) \leq f(x) \leq f(x_{\text{max}}) $$

**2**

Gælder når funktionen er konstant i hele intervallet, og sætningen må gælde, da $f'(x) = 0$ i hele intervallet.
$$ f(a) = f(b) = f(x_{\text{min}}) = f(x_{\text{max}}) $$

**3**

Gælder pga. sætningen om "Minimum og Maksimum".
$$ \text{Hvis } f(x_{\text{min}}) < f(b) = f(a) \text{ må } a < x_{\text{min}} < b \text{ og dermed } f'(x_{\text{min}}) = 0 $$

**4**

Gælder pga. sætningen om "Minimum og Maksimum".
$$ \text{Hvis } f(x_{\text{min}}) = f(a) = f(b) \text{ må enten ovenstående gælde eller } f(x_{\text{max}}) > f(a) = f(b). \text{ Og dermed er } f'(x_{\text{max}}) = 0 $$

**5**

I alle ovennævnte tre tilfælde er der fundet et $x = c$ i det indre interval, hvor $f'(c) = 0$.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Middelværdisætningen

**Sætning**

For en funktion $f(x)$ differentiabel i $]a; b[$ gælder, at der findes et punkt $x = c$, hvor
$$ f'(c) = \frac{f(b) - f(a)}{b - a} $$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/1/c/csm_miiddelvaerdi_002079aa24.png)

**1**

Sekanten imellem punkterne $(a, f(a))$ og $(b, f(b))$ har hældningen $\alpha$.
$$ \alpha = \frac{f(b) - f(a)}{b - a} $$

**2**

Den lineære funktion, hvis graf går igennem de to punkter, kalder vi for $s(x)$. Den har samme hældning som sekanten.
$$ s'(x) = \frac{f(b) - f(a)}{b - a} $$

**3**

Differensen mellem $s(x)$ og $f(x)$ kalder vi for $h(x)$.
$$ h(x) = s(x) - f(x) $$

**4**

Da $s$ og $f$ har samme funktionsværdier for $x = a$ og $x = b$.
$$ h(a) = h(b) = 0 $$

**5**

For den differentiable funktion $h(x)$ gælder derfor Rolles sætning, og der må findes et $c$ så $h'(c) = 0$.
$$ h'(c) = (s(c) - f(c))' = 0 $$

**6**

Reglen om differentiation af en differens benyttes.
$$ (s(c) - f(c))' = s'(c) - f'(c) = 0 $$

**7**

Ved at sammenkæde (2) med (6).
$$ s'(c) = f'(c) = \frac{f(b) - f(a)}{b - a} $$

Q.E.D.

<div class = "pagebreak"></div>


## Proof Monotonisætningen

**Sætning**

Hvis $f$ er differentiabel i et interval $I$, så gælder:
1. $f'(x) > 0$ for alle $x \in I \Rightarrow f$ er voksende i $I$
2. $f'(x) < 0$ for alle $x \in I \Rightarrow f$ er aftagende i $I$
3. $f'(x) = 0$ for alle $x \in I \Rightarrow f$ er konstant i $I$

**Bevis - del 1**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/6/2/csm_Monotonisaetningen_I_1547aa9884.png)

**1**

Der vælges et $x_2$, der er større end $x_1$.

**2**

Ifølge middelværdisætningen eksisterer der et $c$ mellem $x_1$ og $x_2$, hvor tangentens hældning er lig med sekantens hældning fra $x_1$ til $x_2$.
$$ x_1 < c < x_2 \quad \text{og} \quad f'(c) = \frac{f(x_2) - f(x_1)}{x_2 - x_1} $$

**3**

Ganger med $x_2 - x_1$ på begge sider.
$$ f(x_2) - f(x_1) = f'(c) \cdot (x_2 - x_1) $$

**4**

Da $f'(c) > 0$, og da $x_1 < x_2$ så $x_2 - x_1 > 0$. Da begge faktorer i højresiden er positive, må venstresiden være positiv.
$$ f(x_2) - f(x_1) > 0 $$

**5**

Lægger $f(x_1)$ til på begge sider af ulighedstegnet, og vi kan se, at $f$ må være voksende. Hermed er første del bevist.
$$ f(x_2) > f(x_1) $$

**Bevis - del 2**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/4/6/csm_Monotonisaetningen_II_3c497e394c.png)

**6**

Gennemfører samme udregninger som i linje 1-3.
$$ f(x_2) - f(x_1) = f'(c) \cdot (x_2 - x_1) $$

**7**

Da $f'(c) < 0$, og da $x_1 < x_2$, så må $x_2 - x_1 > 0$. Da de to faktorer har forskelligt fortegn, så må venstresiden være negativ.
$$ f(x_2) - f(x_1) < 0 $$

**8**

Lægger $f(x_1)$ til på begge sider af uligheden i (7), og vi kan se, at $f$ må være aftagende. Hermed er anden del bevist.
$$ f(x_2) < f(x_1) $$

**Bevis - del 3**

**9**

Gennemfører samme udregninger som i linje 1-3.
$$ f(x_2) - f(x_1) = f'(c) \cdot (x_2 - x_1) $$

**10**

Da $f'(c) = 0$, så må højresiden fra linje 9 være nul.
$$ f(x_2) - f(x_1) = 0 $$

**11**

Lægger $f(x_1)$ til på begge sider, og vi kan se, at $f$ må være konstant. Hermed er tredje del bevist.
$$ f(x_2) = f(x_1) $$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Minimum og maksimum

**Sætning**

For en differentiabel funktion $f$ i intervallet $]a; b[$, som har et maksimum eller minimum for $x = c$ beliggende i intervallet, gælder, at
$$ f'(c) = 0 $$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/5/0/csm_maxmin_3b34c23d4e.png)

**1**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/6/2/csm_maxmin2_c233191ac2.png)

Hvis funktionen har et maksimum for $x = c$, vil sekanthældningen være positiv i en lille omegn til venstre for $c$ og modsat negativ umiddelbart til højre for $c$.
$$ \frac{\Delta y}{\Delta x} < 0 $$

**2**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/8/7/csm_maxmin1_396c0d79c0.png)

$$ \frac{\Delta y}{\Delta x} > 0 $$

**3**

Grænseværdien fra højre kan kun være negativ eller nul.
$$ \lim_{\Delta x \to 0^+} \left( \frac{\Delta y}{\Delta x} \right) \leq 0 $$

**4**

Grænseværdien fra venstre kan kun være positiv eller nul.
$$ \lim_{\Delta x \to 0^-} \left( \frac{\Delta y}{\Delta x} \right) \geq 0 $$

**5**

Grænseværdien kan altså kun være nul, når begge kriterier skal være opfyldt.
$$ \lim_{\Delta x \to 0} \left( \frac{\Delta y}{\Delta x} \right) = 0 $$

**6**

Idet differentialkvotienten netop er denne grænseværdi.
$$ \lim_{\Delta x \to 0} \left( \frac{\Delta y}{\Delta x} \right) = 0 \Rightarrow f'(c) = 0 $$

Q.E.D.

<div class = "pagebreak"></div>

## Proof Differentiabilitet medfører kontinuitet

**Sætning**

Hvis en funktion $f$ er differentiabel i et punkt, er den også kontinuert i punktet.

**Bevis**

**1**
$$ \lim_{\Delta x \to 0} \left( \frac{\Delta y}{\Delta x} \right) = f'(x) $$
Da netop denne grænseværdi afgør, at funktionen er differentiabel for et givet punkt $x$.

**2**
$$ \Delta y = \frac{\Delta y}{\Delta x} \cdot \Delta x $$
Den simple ligning opstilles for at kunne opstille følgende grænseværdi:

**3**
$$ \lim_{\Delta x \to 0} \Delta y = \lim_{\Delta x \to 0} \left( \frac{\Delta y}{\Delta x} \right) \cdot \lim_{\Delta x \to 0} \Delta x $$
Grænseværdien på højresiden af lighedstegnet opdeles i produktet til grænseværdien af de enkelte faktorer.

**4**
$$ \lim_{\Delta x \to 0} \Delta y = f'(x) \cdot 0 = 0 $$
Gælder jvf. trin 1 og da $\lim_{\Delta x \to 0} \Delta x = 0$.

**5**
$$ \lim_{\Delta x \to 0} \Delta y = 0 $$
er netop betingelsen for at funktionen $f$ er kontinuert.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Infinitesimalregningens fundamentalsætning

**Sætning**

Infinitesimalregningens fundamentalsætning er givet ved
$$
\int_a^b f(x) \, dx = \left[ F(x) \right]_a^b = F(b) - F(a)
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/d/9/csm_hovedsaetning_5109917fc1.png)

Der defineres en arealfunktion $A(x)$, som repræsenterer arealet under kurven $f(x)$ fra $a$ til $x$, hvor $x \in [a; b]$. Det antages, at funktionen er monoton og kontinuert i det udvalgte interval. I dette bevis regnes på en voksende funktion, men den samme argumentation gælder for en aftagende funktion.

**1**
$$
A(x_0 + \Delta x) - A(x_0)
$$
Arealet under kurven i intervallet $\left[ x_0; x_0 + \Delta x \right]$ må således kunne beskrives som arealfunktionen til $x_0 + \Delta x$ fratrukket arealfunktionen til $x_0$.

**2**
$$
f(x_0) \cdot \Delta x \leq A(x_0 + \Delta x) - A(x_0) \leq f(x_0 + \Delta x) \cdot \Delta x
$$
Arealet af rektanglet $ABCD$ findes som $f(x_0) \cdot \Delta x$, og arealet af rektanglet $ABFE$ kan beregnes som $f(x_0 + \Delta x) \cdot \Delta x$. Arealfunktionens værdi må således ligge et sted mellem disse to værdier.

**3**
$$
f(x_0) \leq \frac{A(x_0 + \Delta x) - A(x_0)}{\Delta x} \leq f(x_0 + \Delta x)
$$
Deler med $\Delta x$ på alle sider, hvorved arealfunktionens differenskvotient fremkommer. Det er lovligt, da $\Delta x > 0$.

**4**
$$
\lim_{\Delta x \to 0} f(x_0) \leq \lim_{\Delta x \to 0} \frac{A(x_0 + \Delta x) - A(x_0)}{\Delta x} \leq \lim_{\Delta x \to 0} f(x_0 + \Delta x)
$$
Tager grænseværdien på alle sider.

**5**
$$
f(x_0) \leq A'(x_0) \leq f(x_0)
$$
Grænseværdien til en differenskvotient giver den tilsvarende differentialkvotient. Og da $f(x_0 + \Delta x) \to f(x_0)$ for $\Delta x \to 0$, fordi $f$ er kontinuert i $x_0$.

**6**
$$
A'(x_0) = f(x_0)
$$
Dette må gælde, da det er eneste måde, hvorpå dobbeltuligheden kan tilfredsstilles. Dvs. at arealfunktionens afledte svarer til $f$, og dermed er arealfunktionen en stamfunktion til funktionen $f$.

**7**
$$
\text{Areal} = \int_a^b f(x) \, dx = A(b) - A(a)
$$
Arealet under kurven fra $a$ til $b$ findes ved hjælp af arealfunktionen. Se desuden formel for areal under kurve.

**8**
$$
\text{Areal} = \int_a^b f(x) \, dx = \left[ F(x) \right]_a^b = F(b) - F(a)
$$
Da arealfunktionen er en stamfunktion til $f(x)$ erstattes den med $F(x)$, og skrivemåden med den firkantede parentes indføres.

Q.E.D.

**Note**

Hvis $f$ er aftagende, gennemføres beviset på samme måde, hvor ulighedstegnene vendes om.

<div class = "pagebreak"></div>

## Proof Stamfunktionen til en potensfunktion

**Sætning**

Stamfunktionen til en potensfunktion er givet ved
$$
\int x^n \, dx = \frac{1}{n + 1} x^{n+1} + k, \quad n \neq -1
$$
$$
\int x^{-1} \, dx = \int \frac{1}{x} \, dx = \ln |x| + k
$$

**Bevis - del 1**

**1**
$$
\int x^n \, dx = \frac{1}{n + 1} x^{n+1} + k
$$
Det postuleres, at formlen gælder. For $n = -1$ se nedenfor.

**2**
$$
\left( \int x^n \, dx \right)' = \left( \frac{1}{n + 1} x^{n+1} + k \right)'
$$
Begge sider differentieres. Det indses, at formlen ikke gælder for $n = -1$, da nævneren så er nul.

**3**
$$
x^n = \frac{1}{n + 1} (n + 1) x^{n+1-1} + 0
$$
Regnereglerne for differentiation af potens anvendes. Differentiation ophæver integrationstegnet.

**4**
$$
x^n = x^n
$$
Vi ser, at venstresiden er eksakt lig med højresiden. Første del er hermed vist.

**Bevis - del 2**

**1**
$$
\int x^{-1} \, dx = \int \frac{1}{x} \, dx = \ln |x| + k
$$
Det postuleres, at formlen gælder.

**2**
$$
\left( \int \frac{1}{x} \, dx \right)' = (\ln |x| + k)'
$$
Begge sider differentieres.

**3**
$$
\frac{1}{x} = \frac{1}{|x|} \cdot \frac{|x|}{x} + 0
$$
Regnereglerne for [differentiation af $\ln$](https://www.mathonline.dk/differentiering-af-naturlig-logaritme), kædereglen og at $\left( |x| \right)' = \frac{|x|}{x}$ anvendes. Differentiation ophæver integrationstegnet.

**4**
$$
\frac{1}{x} = \frac{1}{x}
$$
Reducerer højresiden og ser, at venstresiden er eksakt lig med højresiden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Stamfunktionen til eksponentialfunktionen

**Sætning**

Stamfunktionen til en eksponentialfunktion er givet ved
$$
\int e^x \, dx = e^x + k
$$

**Bevis**

**1**
$$
\int e^x \, dx = e^x + k
$$
Det postuleres, at formlen gælder.

**2**
$$
\left( \int e^x \, dx \right)' = (e^x + k)'
$$
Begge sider differentieres.

**3**
$$
e^x = e^x + 0
$$
Regnereglerne for [differentiation af $e^x$](https://www.mathonline.dk/differentiation-af-exponentialfunktionen) anvendes. Differentiation ophæver integrationstegnet.

**4**
$$
e^x = e^x
$$
Vi ser, at venstresiden er eksakt lig med højresiden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Stamfunktionen til en eksponentialfunktion

**Sætning**

Stamfunktionen til en eksponentialfunktion er givet ved
$$
\int a^x \, dx = \frac{a^x}{\ln a} + k
$$

**Bevis**

**1**
$$
\int a^x \, dx = \frac{a^x}{\ln a} + k
$$
Det postuleres, at formlen gælder.

**2**
$$
\left( \int a^x \, dx \right)' = \left( \frac{a^x}{\ln a} + k \right)'
$$
Begge sider differentieres.

**3**
$$
a^x = \frac{a^x}{\ln a} \cdot \ln a + 0
$$
Regnereglerne for [differentiation af $a^x$](https://www.mathonline.dk/differentiation-af-exponentialfunktionen) anvendes. Differentiation ophæver integrationstegnet.

**4**
$$
a^x = a^x
$$
Vi ser, at venstresiden er eksakt lig med højresiden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Bevis ved hjælp af integrationsprøven

**Sætning**

Stamfunktionen til den naturlige logaritme er givet ved
$$
\int \ln x \, dx = x \cdot \ln x - x + k
$$

**Bevis**

**1**
$$
\int \ln(x) \, dx = x \cdot \ln(x) - x + k
$$
Det postuleres, at formlen gælder.

**2**
$$
\left( \int \ln x \, dx \right)' = \left( x \cdot \ln x - x + k \right)'
$$
Begge sider differentieres.

**3**
$$
\ln x = 1 \cdot \ln x + x \cdot \frac{1}{x} - 1 + 0
$$
Regnereglerne for differentiation af produkt, differens og den naturlige logaritme anvendes. Differentiation ophæver integrationstegnet.

**4**
$$
\ln x = \ln x
$$
Vi ser, at venstresiden er lig med højresiden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Bevis ved hjælp af partiel integration

**Sætning**

Stamfunktionen til den naturlige logaritme er givet ved
$$
\int \ln x \, dx = x \cdot \ln x - x + k
$$

**Bevis**

1.
$$
\int \ln x \, dx = \int 1 \cdot \ln x \, dx
$$

Der ganges med 1 i integralet med henblik på at bruge formlen for partiel integration.

2.
$$
= x \cdot \ln x - \int x \cdot \frac{1}{x} \, dx
$$

Formlen for partiel integration anvendes:
$$
\int f(x) \cdot g(x) \, dx = F(x) \cdot g(x) - \int F(x) \cdot g'(x) \, dx
$$

3.
$$
= x \cdot \ln x - \int 1 \, dx
$$

Integralet reduceres.

4.
$$
\int \ln x \, dx = x \cdot \ln x - x + k
$$

Sidste simple integration udføres.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Stamfunktionen til sinus

**Sætning**

Stamfunktionen til sinus er givet ved
$$
\int \sin x \, dx = -\cos x + k
$$

**Bevis**

1.
$$
\int \sin x \, dx = -\cos x + k
$$

Det postuleres, at formlen gælder.

2.
$$
\left( \int \sin x \, dx \right)' = (-\cos x + k)'
$$

Begge sider differentieres.

3.
$$
\sin x = \sin x + 0
$$

Regnereglen for **differentiation af cosinus** anvendes. Differentiation ophæver integrationstegnet.

4.
$$
\sin x = \sin x
$$

Vi ser, at venstresiden er eksakt lig med højresiden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Stamfunktionen til cosinus

**Sætning**

Stamfunktionen til cosinus er givet ved
$$
\int \cos x \, dx = \sin x + k
$$

**Bevis**

1.
$$
\int \cos x \, dx = \sin x + k
$$

Det postuleres, at formlen gælder.

2.
$$
\left( \int \cos x \, dx \right)' = (\sin x + k)'
$$

Begge sider differentieres.

3.
$$
\cos x = \cos x + 0
$$

Regnereglen for **differentiation af sinus** anvendes. Differentiation ophæver integrationstegnet.

4.
$$
\cos x = \cos x
$$

Vi ser, at venstresiden er eksakt lig med højresiden.

Q.E.D.


<div class = "pagebreak"></div>


## Proof Stamfunktionen til tangens

**Sætning**

Stamfunktionen til tangens er givet ved
$$
\int \tan x \, dx = -\ln | \cos x | + k
$$

**Bevis**

1.
$$
\int \tan x \, dx = -\ln | \cos x | + k
$$

Det postuleres, at formlen gælder.

2.
$$
\left( \int \tan x \, dx \right)' = (-\ln | \cos x | + k)'
$$

Begge sider differentieres.

3.
$$
\tan x = \frac{-1}{| \cos x |} \cdot \frac{| \cos x |}{\cos x} \cdot (-\sin(x)) + 0
$$

Regnereglerne for **differentiation af sammensat funktion**, **ln**, **cosinus** og reglen $\frac{|x|}{x}$ anvendes. Differentiation ophæver integrationstegnet.

4.
$$
\tan(x) = \frac{\sin(x)}{\cos(x)} = \tan(x)
$$

Reducerer højresiden og omskriver til tangens, så venstresiden er lig med højresiden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Indskudsreglen

**Sætning**

Et integral kan opdeles i to integraler på følgende måde
$$
\int_a^b f(x) \, dx = \int_a^k f(x) \, dx + \int_k^b f(x) \, dx
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/c/c/csm_Indskudsreglen_bdfd052b54.png)

1.
$$
A = A_1 + A_2
$$

Arealet fra $a$ til $b$ under $f$ opdeles i to delarealer.

2.
$$
A = \int_a^b f(x) \, dx
$$
$$
A_1 = \int_a^k f(x) \, dx
$$
$$
A_2 = \int_k^b f(x) \, dx
$$

Hvert af delarealerne beregnes på sædvanlig vis (se formel for **areal under kurve**).

3.
$$
\int_a^b f(x) \, dx = \int_a^k f(x) \, dx + \int_k^b f(x) \, dx
$$

De to delarealer lægges sammen.

Q.E.D.

**Note**

Hvis $k$ ligger udenfor intervallet mellem $a$ og $b$ bliver resultatet det samme. Her skal man blot trække det lille areal fra det store.

<div class = "pagebreak"></div>

## Proof Integration af sum

**Sætning**

Integralet af en sum er givet ved
$$
\int \left( f(x) + g(x) \right) \, dx = \int f(x) \, dx + \int g(x) \, dx
$$

**Bevis**

1.
$$
\int \left( f(x) + g(x) \right) \, dx = \int f(x) \, dx + \int g(x) \, dx
$$

Det postuleres at sætningen gælder.

2.
$$
\left( \int \left( f(x) + g(x) \right) \, dx \right)' = \left( \int f(x) \, dx + \int g(x) \, dx \right)'
$$

Begge sider differentieres.

3.
$$
f(x) + g(x) = f(x) + g(x)
$$

Regnereglen for **differentiation af sum** anvendes. Differentiation ophæver integration.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Integration af differens

**Sætning**

Integralet af en differens er givet ved
$$
\int \left( f(x) - g(x) \right) \, dx = \int f(x) \, dx - \int g(x) \, dx
$$

**Bevis**

1.
$$
\int \left( f(x) - g(x) \right) \, dx = \int f(x) \, dx - \int g(x) \, dx
$$

Det postuleres at sætningen gælder.

2.
$$
\left( \int \left( f(x) - g(x) \right) \, dx \right)' = \left( \int f(x) \, dx - \int g(x) \, dx \right)'
$$

Begge sider differentieres.

3.
$$
f(x) - g(x) = f(x) - g(x)
$$

Regnereglen for **differentiation af differens** anvendes. Differentiation ophæver integration.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Integration af konstant gange funktion

**Sætning**

Integralet af konstant gange funktion er givet ved
$$
\int k \cdot f(x) \, dx = k \int f(x) \, dx
$$

**Bevis**

1.
$$
\int k \cdot f(x) \, dx = k \int f(x) \, dx
$$

Det postuleres at sætningen gælder.

2.
$$
\left( \int k \cdot f(x) \, dx \right)' = \left( k \int f(x) \, dx \right)'
$$

Begge sider differentieres.

3.
$$
k \cdot f(x) = k \cdot f(x)
$$

Regnereglen for **differentiation af konstant gange funktion** anvendes. Differentiation ophæver integration.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Partiel integration

**Sætning**

Integralet af et produkt af to funktioner kan opdeles på følgende måde
$$
\int f(x) \cdot g(x) \, dx = F(x) \cdot g(x) - \int F(x) \cdot g'(x) \, dx
$$

**Bevis**

1.
$$
\int f(x) \cdot g(x) \, dx = F(x) \cdot g(x) - \int F(x) \cdot g'(x) \, dx
$$

Det postuleres at formlen gælder.

2.
$$
\left( \int f(x) \cdot g(x) \, dx \right)' = \left( F(x) \cdot g(x) - \int F(x) \cdot g'(x) \, dx \right)'
$$

Begge sider differentieres.

3.
$$
f(x) \cdot g(x) = (F(x) \cdot g(x))' - \left( \int F(x) \cdot g'(x) \, dx \right)'
$$

På venstresiden ophæver integration og differentiation hinanden. På højresiden differentieres hvert led.

4.
$$
f(x) \cdot g(x) = F'(x) \cdot g(x) + F(x) \cdot g'(x) - F(x) \cdot g'(x)
$$

På højresiden anvendes reglen for **differentiation af et produkt**. Ved sidste led ophæver differentiation integrationstegnet.

5.
$$
f(x) \cdot g(x) = f(x) \cdot g(x)
$$

De to identiske led på højresiden går ud med hinanden, og vi ser at venstresiden er lig med højresiden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Integration ved substitution

**Sætning**

Der gælder følgende sætning for integraler, som anvendes til at substituere dele af en sammensat funktion.
$$
F(g(x)) = \int f \left( g(x) \right) g'(x) \, dx = \int f(u) \, du
$$
Hvor
$$
u = g(x)
$$

**Bevis**

1.
$$
\left( F(g(x)) \right)' = \left( \int f \left( g(x) \right) g'(x) \, dx \right)'
$$

Der differentieres på begge sider.

2.
$$
f \left( g(x) \right) g'(x) = f \left( g(x) \right) g'(x)
$$

På venstresiden differentieres en sammensat funktion ved at gange den afledte ydre funktion med den afledte indre funktion.

På højresiden ophæver integraltegn og differentialtegn hinanden. Derved bliver venstre- og højresiden ens.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Areal under kurve

**Sætning**

For en kontinuer funktion $f$ findes arealet i et lukket interval $\left[ a; b \right]$ mellem kurven, x-aksen og de lodrette linjer $x = a$ og $x = b$ som
$$
A = \int_a^b f(x) \, dx
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/4/2/csm_Areal_under_kurve_f0cb92a3e2.png)

Arealet under kurven opdeles i $n$ rektangler med bredden $\Delta x$ og højden $f(x_i)$, hvor $x_i$ er den midterste $x$-værdi i hvert rektangel.

1.
$$
A_i = f(x_i) \cdot \Delta x
$$

Arealet af det $i$'te rektangel.

2.
$$
A \approx \sum_{i=1}^n f(x_i) \cdot \Delta x
$$

Lægger alle $n$ rektangler sammen og får et estimat på arealet. Jo større $n$ er, jo bedre estimat.

3.
$$
A = \lim_{\Delta x \to 0} \sum_{i=1}^n f(x_i) \cdot \Delta x = \int_a^b f(x) \, dx
$$

Tager grænseværdien, som må være det korrekte areal. Når $\Delta x$ går mod nul, må $n$ gå mod uendeligt. Skifter $\sum$ ud med $\int$, da man også kan se på et integral som en sum af infinitesimale størrelser.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Areal mellem to funktioners grafer

**Sætning**

Arealet mellem to funktioners grafer er givet ved
$$
A = \int_a^b \left( f(x) - g(x) \right) \, dx,
$$
hvor
$$
f(x) \geq g(x)
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/6/c/csm_Areal_ml_funktioner_0467819ccc.png)

Arealet under kurven opdeles i $n$ rektangler med bredden $\Delta x$ og højden $\left( f(x_i) - g(x_i) \right)$, hvor $x_i$ er den midterste $x$-værdi i hvert rektangel.

1.
$$
A_i = \left( f(x_i) - g(x_i) \right) \cdot \Delta x
$$

Arealet af det $i$'te rektangel.

2.
$$
A \approx \sum_{i=1}^n \left( f(x_i) - g(x_i) \right) \cdot \Delta x
$$

Lægger alle $n$ rektangler sammen og får et estimat på arealet. Jo større $n$ er, jo bedre estimat.

3.
$$
A = \lim_{\Delta x \to 0} \sum_{i=1}^n \left( f(x_i) - g(x_i) \right) \cdot \Delta x = \int_a^b \left( f(x) - g(x) \right) \, dx
$$

Tager grænseværdien, som må være det korrekte areal. Når $\Delta x$ går mod nul, må $n$ gå mod uendeligt. Skifter $\sum$ ud med $\int$, da det netop var sådan, at Leibniz i sin tid definerede et integral.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Længde af kurve

**Sætning**

For en kontinuer funktion $f$ defineret i intervallet $[a; b]$ findes længden af funktionens graf ved formlen:
$$
L = \int_a^b \sqrt{1 + (f'(x))^2} \, dx
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/b/4/csm_Laenge_kurve_19c0b072b4.png)


![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/e/0/csm_Laenge_kurve_udsnit_296f29e189.png)
Længden af funktionens graf fremkommer ved at opdele kurven i $n$ linjestykker, hvor længden af hvert linjestykke er $\Delta S_i$. $\Delta S_i$ er samtidig hypotenusen i de retvinklede trekanter med lige stor vandret katete $\Delta x$ og lodret katete $\Delta y_i$.

1.
$$
\Delta S_i = \sqrt{\Delta x^2 + \Delta y_i^2}
$$

Hypotenusen beregnes vha. **Pythagoras**.

2.
$$
\Delta y_i = \alpha \cdot \Delta x = f'(x_i) \cdot \Delta x
$$

Da hældningskoefficienten $\alpha$ for en linje er $\alpha = \frac{\Delta y}{\Delta x}$.

3.
$$
\Delta S_i = \sqrt{(\Delta x)^2 + (f'(x_i) \cdot \Delta x)^2} = \sqrt{(\Delta x)^2 + f'(x_i)^2 \cdot (\Delta x)^2}
$$

Da $f'(x_i)$ svarer til hældningen af det enkelte linjestykke.

4.
$$
\Delta S_i = \sqrt{\left( 1 + f'(x_i)^2 \right) \cdot (\Delta x)^2}
$$

Sætter $(\Delta x)^2$ uden for en parentes.

5.
$$
\Delta S_i = \sqrt{1 + f'(x_i)^2} \cdot \sqrt{(\Delta x)^2} = \sqrt{1 + f'(x_i)^2} \cdot \Delta x
$$

Bruger regnereglen $\sqrt{a \cdot b} = \sqrt{a} \cdot \sqrt{b}$.

6.
$$
L \approx \sum_{i=1}^n \sqrt{1 + f'(x_i)^2} \cdot \Delta x
$$

Lægger alle $n$ elementer sammen og får et estimat på længden. Jo større $n$ er, jo bedre estimat.

7.
$$
L = \lim_{\Delta x \to 0} \sum_{i=1}^n \sqrt{1 + f'(x_i)^2} \cdot \Delta x = \int_a^b \sqrt{1 + (f'(x))^2} \, dx
$$

Tager grænseværdien, som må være den korrekte længde. Når $\Delta x$ går mod nul, må $n$ gå mod uendeligt. Skifter $\sum$ ud med $\int$, da man også kan se på et integral som en sum af infinitesimale størrelser.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Volumen af omdrejningslegemet ved drejning om x-aksen

**Sætning**

For en kontinuer funktion $f$ defineret i intervallet $[a; b]$ findes volumen af omdrejningslegemet der opstår ved rotation af funktionens graf om x-aksen som:
$$
V_x = \pi \int_a^b \left( f(x) \right)^2 \, dx
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/6/3/csm_Volumen_kurve_0b25f5a3bd.png)

Volumen for omdrejningslegemet omkring x-aksen opdeles i $n$ skiver med bredden $\Delta x$ og radius $f(x_i)$, hvor $x_i$ er den midterste x-værdi i skiven.

1.
$$
V_i = \pi \cdot \left( f(x_i) \right)^2 \cdot \Delta x
$$

Volumen af den $i$'te skive.

2.
$$
V_x \approx \sum_{i=1}^n \pi \cdot \left( f(x_i) \right)^2 \cdot \Delta x
$$

Lægger alle $n$ skiver sammen, og får et estimat på volumenet. Jo større $n$ er, jo bedre estimat.

3.
$$
V_x = \lim_{\Delta x \to 0} \sum_{i=1}^n \pi \cdot \left( f(x_i) \right)^2 \cdot \Delta x
$$
$$
V_x = \pi \int_a^b \left( f(x) \right)^2 \, dx
$$

Tager grænseværdien som må være det korrekte volumen. Når $\Delta x$ går mod nul, så må $n$ gå mod uendeligt. Skifter $\sum$ ud med $\int$, da vi går til at summere infinitesimale størrelser.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Volumen af omdrejningslegemet ved drejning om y-aksen

**Sætning**

For en kontinuer funktion $f$ defineret i intervallet $[a; b]$ findes volumen af omdrejningslegemet om y-aksen som
$$
V_y = 2\pi \int_a^b x \cdot f(x) \, dx
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/0/0/csm_Volumen_kurve_y_9eb288c591.png)

Volumen for omdrejningslegemet omkring y-aksen opdeles i $n$ cylinderringe med bredden $\Delta x$ og radius $x_i$ og højde $f(x_i)$, hvor $x_i$ er den midterste x-værdi i skiven.

1.
$$
V_i = 2 \cdot \pi \cdot x_i \cdot f(x_i) \cdot \Delta x
$$

Volumen af den i'te cylinderring. Volumen af cylinderringen findes som areal af cirkelring gange højden.

2.
$$
V_y \approx \sum_{i=1}^n 2 \cdot \pi \cdot x_i \cdot f(x_i) \cdot \Delta x
$$

Lægger alle $n$ cylinderringe sammen, og får et estimat på volumenet. Jo større $n$ er, jo bedre bud.

3.
$$
V_y = \lim_{\Delta x \to 0} \sum_{i=1}^n 2 \cdot \pi \cdot x_i \cdot f(x_i) \cdot \Delta x
$$
$$
V_y = 2\pi \int_a^b x \cdot f(x) \, dx
$$

Tager grænseværdien som må være det korrekte areal. Når $\Delta x$ går mod nul, så må $n$ gå mod uendeligt. Skifter $\sum$ ud med $\int$, da vi går til at summere infinitesimale størrelser.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Overfladeareal ved drejning om x-aksen

**Sætning**

For en kontinuer funktion defineret i intervallet $[a; b]$ findes overfladearealet af omdrejningslegemet om x-aksen ved formlen:
$$
O_x = 2\pi \int_a^b f(x) \sqrt{1 + (f'(x))^2} \, dx
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/6/1/csm_Overfladeareal_88a8d03ea5.png)

Overfladearealet for omdrejningslegemet omkring x-aksen opdeles i $n$ "skiver" med bredden $\Delta x$ og radius $f(x_i)$, hvor $x_i$ er den midterste x-værdi i "skiven" og $s_i$ er sekanten for stykket $\Delta x$.

1.
$$
A_{\text{stub}} = \pi \cdot s \cdot (R + r)
$$

Arealet af omdrejningslegemet af en skive svarer til en arealet af en keglestub. (se **formel**)

2.
$$
r_m = \frac{R + r}{2}
$$

Definerer middelradius som $r_m$.

3.
$$
A_{\text{stub}} = \pi \cdot s \cdot \frac{R + r}{2} \cdot 2 = \pi \cdot s \cdot r_m \cdot 2
$$

Omskriver formlen så middelradius let kan substitueres ind.

4.
$$
s_i = \sqrt{1 + (f'(x_i))^2} \cdot \Delta x
$$

På samme måde som man finder **længden af en kurve** findes $s_i$.

5.
$$
O_i = 2 \cdot \pi \cdot f(x_i) \sqrt{1 + (f'(x_i))^2} \cdot \Delta x
$$

Overfladeareal af den i'te keglestub, da $f(x_i)$ svarer til middelradius og $s_i$ som vist ovenfor.

6.
$$
O_x \approx \sum_{i=1}^n 2 \cdot \pi \cdot f(x_i) \sqrt{1 + (f'(x_i))^2} \cdot \Delta x
$$

Lægger alle $n$ arealer sammen, og får et estimat på overfladearealet. Jo større $n$ er, jo bedre estimat.

7.
$$
O_x = \lim_{\Delta x \to 0} \sum_{i=1}^n 2 \cdot \pi \cdot f(x_i) \sqrt{1 + (f'(x_i))^2} \cdot \Delta x
$$
$$
O_x = 2 \cdot \pi \int_a^b f(x) \sqrt{1 + (f'(x))^2} \, dx
$$

Tager grænseværdien som må være det korrekte overfladeareal. Når $\Delta x$ går mod nul, så må $n$ gå mod uendeligt. Skifter $\sum$ ud med $\int$, da vi går til at summere infinitesimale størrelser.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Overfladeareal ved drejning om y-aksen

**Sætning**

For en kontinuer funktion defineret i intervallet $[a; b]$ findes overfladearealet af omdrejningslegemet om y-aksen ved formlen:
$$
O_y = 2\pi \int_a^b x \sqrt{1 + (f'(x))^2} \, dx
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/4/b/csm_overfladeareal_y_e0c0b51b14.png)

Overfladearealet for omdrejningslegemet omkring y-aksen opdeles i $n$ "skiver" med bredden $\Delta x$ og radius $x_i$, hvor $x_i$ er den midterste x-værdi i "skiven".

1.
$$
A_{\text{stub}} = \pi \cdot s \cdot (R + r)
$$

Omdrejningslegemet svarer til en keglestub (se **formel**).

2.
$$
r_m = \frac{R + r}{2}
$$

Definerer middelradius som $r_m$.

3.
$$
A_{\text{stub}} = \pi \cdot s \cdot \frac{R + r}{2} \cdot 2 = \pi \cdot s \cdot r_m \cdot 2
$$

Omskriver formlen så middelradius let kan substitueres ind.

4.
$$
s_i = \sqrt{1 + (f'(x_i))^2} \cdot \Delta x
$$

På samme måde som man finder **længden af en kurve** findes $s_i$.

5.
$$
O_i = 2 \cdot \pi \cdot x_i \sqrt{1 + (f'(x_i))^2} \cdot \Delta x
$$

Overfladeareal af den i'te keglestub, da $x_i$ svarer til middelradius og $s_i$ som vist ovenfor.

6.
$$
O_y \approx \sum_{i=1}^n 2 \cdot \pi \cdot x_i \sqrt{1 + (f'(x_i))^2} \cdot \Delta x
$$

Lægger alle $n$ arealer sammen, og får et estimat på overfladearealet. Jo større $n$ er, jo bedre estimat.

7.
$$
O_y = \lim_{\Delta x \to 0} \sum_{i=1}^n 2 \cdot \pi \cdot x_i \sqrt{1 + (f'(x_i))^2} \cdot \Delta x
$$
$$
O_y = 2 \cdot \pi \int_a^b x \sqrt{1 + (f'(x))^2} \, dx
$$

Tager grænseværdien som må være det korrekte overfladeareal. Når $\Delta x$ går mod nul, må $n$ gå mod uendeligt. Skifter $\sum$ ud med $\int$, da vi går til at summere infinitesimale størrelser.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Længde af vektor

**Sætning**

For en vektor givet ved
$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \\ a_3 \end{pmatrix}
$$
gælder, at længden kan findes ved
$$
|\vec{a}| = \sqrt{a_1^2 + a_2^2 + a_3^2}
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/b/5/csm_vektorlaengde_3D_86cf92148f.png)

For at visualisere en tredimensional vektor er det lettest at tegne en kasse, hvor siderne er parallelle med koordinatsystemets akser. Siderne i kassen svarer så til vektorens koordinater som vist på figuren.

1.
$$
d = \sqrt{a_1^2 + a_2^2}
$$

Bestemmer diagonalen $d$ i rektanglet i $xy$-planen. Den beregnes vha. **Pythagoras' sætning**.

2.
$$
|\vec{a}| = \sqrt{d^2 + a_3^2} = \sqrt{a_1^2 + a_2^2 + a_3^2}
$$

Længden af vektoren svarer til hypotenusen i den retvinklede trekant, hvor diagonalen svarer til den ene katete, og $a_3$ svarer til den anden katete. Herefter indsættes $d$.

3.
$$
|\vec{a}| = \sqrt{a_1^2 + a_2^2 + a_3^2}
$$

Den indre kvadratrod udregnes.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Skalarproduktet af rumlige vektorer

**Sætning**

Om to rumlige vektorer givet ved
$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \\ a_3 \end{pmatrix} \quad \text{og} \quad \vec{b} = \begin{pmatrix} b_1 \\ b_2 \\ b_3 \end{pmatrix}
$$
kan deres skalarprodukt findes ved
$$
\vec{a} \cdot \vec{b} = a_1 b_1 + a_2 b_2 + a_3 b_3
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/f/b/csm_Skalarproduktet_834f16874d.png)

Selvom der er tale om tredimensionale vektorer, vil de to vektorer udspænde en plan. Derfor er tilgangen den samme som med vektorer i to dimensioner.

1.
$$
\vec{a} - \vec{b} = \begin{pmatrix} a_1 - b_1 \\ a_2 - b_2 \\ a_3 - b_3 \end{pmatrix}
$$

Formlen for en **differensvektors** koordinater bruges.

2.
$$
|\vec{a} - \vec{b}|^2 = |\vec{a}|^2 + |\vec{b}|^2 - 2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Ifølge cosinusrelationen må denne sammenhæng gælde.

3.
$$
\sqrt{(a_1 - b_1)^2 + (a_2 - b_2)^2 + (a_3 - b_3)^2} = \sqrt{a_1^2 + a_2^2 + a_3^2} + \sqrt{b_1^2 + b_2^2 + b_3^2} - 2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Længden for alle tre vektorer findes vha. **længdeformlen for en vektor**.

4.
$$
(a_1 - b_1)^2 + (a_2 - b_2)^2 + (a_3 - b_3)^2 = a_1^2 + a_2^2 + a_3^2 + b_1^2 + b_2^2 + b_3^2 - 2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Kvadratroden og kvadratet går ud med hinanden.

5.
$$
a_1^2 + b_1^2 - 2a_1b_1 + a_2^2 + b_2^2 - 2a_2b_2 + a_3^2 + b_3^2 - 2a_3b_3 = a_1^2 + a_2^2 + a_3^2 + b_1^2 + b_2^2 + b_3^2 - 2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Parenteserne hæves vha. **kvadratsætning 2**.

6.
$$
-2a_1b_1 - 2a_2b_2 - 2a_3b_3 = -2 \cdot |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Ligningen reduceres ved at subtrahere de seks identiske led på begge sider af lighedstegnet.

7.
$$
a_1b_1 + a_2b_2 + a_3b_3 = |\vec{a}| \cdot |\vec{b}| \cdot \cos(v)
$$

Deler med $-2$ på begge sider af lighedstegnet.

8.
$$
a_1b_1 + a_2b_2 + a_3b_3 = \vec{a} \cdot \vec{b}
$$

Højresiden svarer til skalarproduktet.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Linjens parameterfremstilling

**Sætning**

Linjens parameterfremstilling kan skrives som
$$
\begin{pmatrix} x \\ y \\ z \end{pmatrix} = \begin{pmatrix} x_0 \\ y_0 \\ z_0 \end{pmatrix} + t \cdot \begin{pmatrix} r_1 \\ r_2 \\ r_3 \end{pmatrix}, \quad t \in \mathbb{R}
$$
hvor $P(x, y, z)$ er et vilkårligt løbende punkt på linjen, $P_0 (x_0, y_0, z_0)$ er et vilkårligt fast punkt på linjen, og $\vec{r} = \begin{pmatrix} r_1 \\ r_2 \\ r_3 \end{pmatrix}$ er en retningsvektor for linjen.

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/c/a/csm_Parameterfremstilling_294fd66312.png)

1.
$$
\vec{r} \parallel \overrightarrow{P_0 P}
$$

De to vektorer ligger begge på linjen og må derfor være parallelle.

2.
$$
\overrightarrow{P_0 P} = t \cdot \vec{r}, \quad t \in \mathbb{R}
$$

Derfor kan de to vektorer udtrykkes ud fra hinanden.

3.
$$
\overrightarrow{P} - \overrightarrow{P_0} = t \cdot \vec{r}, \quad t \in \mathbb{R}
$$

Udtrykker $\overrightarrow{P_0 P}$ ud fra de to punkters stedvektorer.

4.
$$
\overrightarrow{P} = \overrightarrow{P_0} + t \cdot \vec{r}, \quad t \in \mathbb{R}
$$

Lægger $\overrightarrow{P_0}$ til på begge sider.

5.
$$
\begin{pmatrix} x \\ y \\ z \end{pmatrix} = \begin{pmatrix} x_0 \\ y_0 \\ z_0 \end{pmatrix} + t \cdot \begin{pmatrix} r_1 \\ r_2 \\ r_3 \end{pmatrix}, \quad t \in \mathbb{R}
$$

Omskriver til vektorernes koordinater.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Planens ligning

**Sætning**

En plan med normalvektoren
$$
\vec{n} = \begin{pmatrix} a \\ b \\ c \end{pmatrix}
$$
har følgende ligning
$$
ax + by + cz + d = 0
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/9/b/csm_planens_ligning_5320a39ab7.png)

1.
$$
\vec{n} \cdot \overrightarrow{P_0 P} = 0
$$

Skalarproduktet af normalvektoren og en vilkårlig vektor i planen vil altid give 0.

2.
$$
\begin{pmatrix} a \\ b \\ c \end{pmatrix} \cdot \begin{pmatrix} x - x_0 \\ y - y_0 \\ z - z_0 \end{pmatrix} = 0
$$

Sætter $P$'s koordinater til $(x, y, z)$ og $P_0$'s koordinater til $(x_0, y_0, z_0)$. Herefter indsættes koordinaterne.

3.
$$
a(x - x_0) + b(y - y_0) + c(z - z_0) = 0
$$

**Skalarproduktet** udregnes.

4.
$$
ax - ax_0 + by - by_0 + cz - cz_0 = 0
$$

Der ganges ind i parenteserne.

5.
$$
ax + by + cz + d = 0
$$

Alle konstantleddene erstattes med en ny konstant $d$, idet $d = -ax_0 - by_0 - cz_0$.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Kuglens ligning

**Sætning**

En kugle med radius $r$ og med centrum i $(x_0, y_0, z_0)$ har ligningen:
$$
(x - x_0)^2 + (y - y_0)^2 + (z - z_0)^2 = r^2
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/6/7/csm_kuglens_ligning_0981cab2dd.png)

1.
$$
|\overrightarrow{P_0 P}| = r
$$

Kuglens ligning fremkommer, når man finder længden af den vektor, der går fra centrum til et vilkårligt punkt på kuglens overflade, og hvis længde er lig med radius.

2.
$$
\overrightarrow{P_0 P} = \begin{pmatrix} x - x_0 \\ y - y_0 \\ z - z_0 \end{pmatrix}
$$

Sætter $P$'s koordinater til $(x, y, z)$ og $P_0$'s koordinater til $(x_0, y_0, z_0)$. Bestemmer vektorens koordinater som slutkoordinater minus begyndelseskoordinater.

3.
$$
|\overrightarrow{P_0 P}| = \sqrt{(x - x_0)^2 + (y - y_0)^2 + (z - z_0)^2} = r
$$

Bruger formlen for **længden af en vektor**.

4.
$$
(x - x_0)^2 + (y - y_0)^2 + (z - z_0)^2 = r^2
$$

Tager kvadratet på begge sider af lighedstegnet.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Vinkel mellem plan og plan

**Sætning**

Vinklen mellem to planer med normalvektorerne $\vec{n}_\alpha$ og $\vec{n}_\beta$ findes ved
$$
v = \arccos \left( \frac{\vec{n}_\alpha \cdot \vec{n}_\beta}{|\vec{n}_\alpha| \cdot |\vec{n}_\beta|} \right)
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/f/b/csm_vinkel_plan_plan_5096a79883.png)

Vinklen mellem to planer er det samme som vinklen mellem to normalvektorer fra de to planer. Det ses ved at betragte figuren, hvor man kigger ind på planerne, så de fremstår som linjer. Vinklen mellem planerne må være den samme som mellem normalvektorerne, da normalvektorerne repræsenterer begge planer roteret $90^\circ$ i samme retning.

1.
$$
\vec{n}_\alpha \cdot \vec{n}_\beta = |\vec{n}_\alpha| \cdot |\vec{n}_\beta| \cdot \cos(v)
$$

Finder normalvektorernes **skalarprodukt**.

2.
$$
\cos(v) = \frac{\vec{n}_\alpha \cdot \vec{n}_\beta}{|\vec{n}_\alpha| \cdot |\vec{n}_\beta|}
$$

Deler med de to længder på begge sider af lighedstegnet.

3.
$$
v = \arccos \left( \frac{\vec{n}_\alpha \cdot \vec{n}_\beta}{|\vec{n}_\alpha| \cdot |\vec{n}_\beta|} \right)
$$

Tager arcus cosinus på begge sider af lighedstegnet.

Q.E.D.

**Note**

Hvis den ene normalvektor peger modsat af den, der er vist på tegningen, gælder formlen stadig, idet linjen fra retningsvektoren blot kan forlænges bagud. Formlen giver da blot en stump vinkel i stedet for en spids vinkel eller vice versa.

<div class = "pagebreak"></div>

## Proof Vinkel mellem linje og linje

**Sætning**

Vinklen mellem to linjer med retningsvektorerne $\vec{r}_n$ og $\vec{r}_m$ findes som
$$
v = \arccos \left( \frac{\vec{r}_m \cdot \vec{r}_n}{|\vec{r}_m| \cdot |\vec{r}_n|} \right)
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/a/3/csm_vinkel_linie_linie_3bddd834fa.png)

Vinklen mellem to linjer svarer til vinklen mellem de to linjers retningsvektorer, da hhv. linje og retningsvektor har samme retning.

1.
$$
\vec{r}_m \cdot \vec{r}_n = |\vec{r}_m| \cdot |\vec{r}_n| \cdot \cos(v)
$$

Finder retningsvektorernes **skalarprodukt**.

2.
$$
\cos(v) = \frac{\vec{r}_m \cdot \vec{r}_n}{|\vec{r}_m| \cdot |\vec{r}_n|}
$$

Deler med de to længder på begge sider af lighedstegnet.

3.
$$
v = \arccos \left( \frac{\vec{r}_m \cdot \vec{r}_n}{|\vec{r}_m| \cdot |\vec{r}_n|} \right)
$$

Tager arcus cosinus på begge sider af lighedstegnet.

Q.E.D.

**Note**

Det betyder ikke noget, om linjerne skærer hinanden, eller om de er vindskeve.

<div class = "pagebreak"></div>

## Proof Vinkel mellem linje og plan

**Sætning**

Vinklen mellem en plan med normalvektoren $\vec{n}$ og linjen med retningsvektoren $\vec{r}$ findes som
$$
v = 90^\circ - \arccos \left( \frac{\vec{n} \cdot \vec{r}}{|\vec{n}| |\vec{r}|} \right)
$$

Vinklen mellem linje og plan svarer til $90^\circ$ minus vinklen mellem retningsvektor og normalvektor, da normalvektoren er vinkelret på planen.

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/a/e/csm_vinkel_linje_plan_ce80babbf9.png)

1.
$$
\vec{n} \cdot \vec{r} = |\vec{n}| |\vec{r}| \cos(90^\circ - v)
$$

Bestemmer skalarproduktet af normal og retningsvektor.

2.
$$
\cos(90^\circ - v) = \frac{\vec{n} \cdot \vec{r}}{|\vec{n}| |\vec{r}|}
$$

Deler med de to længder på begge sider af lighedstegnet.

3.
$$
v = 90^\circ - \arccos \left( \frac{\vec{n} \cdot \vec{r}}{|\vec{n}| |\vec{r}|} \right)
$$

Tager arcus cosinus på begge sider af lighedstegnet.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Vektorproduktets definition

**Definition**

Om to rumlige vektorer givet ved
$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \\ a_3 \end{pmatrix} \quad \text{og} \quad \vec{b} = \begin{pmatrix} b_1 \\ b_2 \\ b_3 \end{pmatrix}
$$
defineres deres vektorprodukt til
$$
\vec{v} = \vec{a} \times \vec{b} = \begin{pmatrix} a_2 b_3 - a_3 b_2 \\ a_3 b_1 - a_1 b_3 \\ a_1 b_2 - a_2 b_1 \end{pmatrix}
$$

**Udledning**

1.
$$
\vec{n} = \begin{pmatrix} x \\ y \\ 1 \end{pmatrix}
$$
$$
\vec{a} \cdot \vec{n} = 0 \quad \land \quad \vec{b} \cdot \vec{n} = 0
$$

Definerer en vektor $\vec{n}$, der er vinkelret på både vektor $\vec{a}$ og vektor $\vec{b}$. Da skalarprodukterne skal give nul, bestemmes $\vec{n}$ med en $z$-koordinat på 1, som er vilkårlig men praktisk for udledning.

2.
$$
a_1 x + a_2 y + a_3 = 0
$$
$$
b_1 x + b_2 y + b_3 = 0
$$

Skalarprodukterne beregnes.

3.
$$
a_1 b_2 x + a_2 b_2 y + a_3 b_2 = 0
$$
$$
a_2 b_1 x + a_2 b_2 y + a_2 b_3 = 0
$$

Forlænger øverste ligning med $b_2$ og nederste ligning med $a_2$.

4.
$$
a_1 b_2 x - a_2 b_1 x - a_3 b_2 + a_2 b_3 = 0
$$

Trækker nederste ligning fra den øverste.

5.
$$
(a_1 b_2 - a_2 b_1)x = a_2 b_3 - a_3 b_2
$$

Sætter $x$ uden for en parentes og isolerer $x$.

6.
$$
x = \frac{a_2 b_3 - a_3 b_2}{a_1 b_2 - a_2 b_1}
$$

Dividere med parentesen på begge sider af lighedstegnet.

7.
$$
a_2 b_1 x + a_3 b_1 + a_2 b_1 = 0
$$
$$
a_1 b_1 x + a_3 b_2 = 0
$$

De to linjer forlænger med henblik på at løse to ligninger med hensyn til $x$.

8.
$$
a_2 b

<div class = "pagebreak"></div>

## Proof Vektorproduktet ud fra geometrisk definition

**Sætning**

Defineres krydsproduktet som den vektor $\vec{a} \times \vec{b}$, der er vinkelret på både $\vec{a}$ og $\vec{b}$ og hvor $|\vec{a} \times \vec{b}| = |\vec{a}| \cdot |\vec{b}| \cdot \sin v$, hvor $v$ er vinklen mellem vektor $\vec{a}$ og vektor $\vec{b}$, og under forudsætning af at både højrehåndsreglen og den distributive lov skal gælde, så er
$$
\vec{a} \times \vec{b} = \begin{pmatrix} a_2 b_3 - a_3 b_2 \\ a_3 b_1 - a_1 b_3 \\ a_1 b_2 - a_2 b_1 \end{pmatrix}
$$
hvor
$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \\ a_3 \end{pmatrix} \quad \text{og} \quad \vec{b} = \begin{pmatrix} b_1 \\ b_2 \\ b_3 \end{pmatrix}.
$$

**Bevis**

1.
$$
\vec{i} \times \vec{i} = \vec{0} \quad \vec{i} \times \vec{j} = \vec{k} \quad \vec{i} \times \vec{k} = -\vec{j}
$$
$$
\vec{j} \times \vec{i} = -\vec{k} \quad \vec{j} \times \vec{j} = \vec{0} \quad \vec{j} \times \vec{k} = \vec{i}
$$
$$
\vec{k} \times \vec{i} = \vec{j} \quad \vec{k} \times \vec{j} = -\vec{i} \quad \vec{k} \times \vec{k} = \vec{0}
$$

Da vinklen mellem to forskellige basisvektorer altid er $90^\circ$ og deres længder er $1$, vil længden af vektorproduktet også være 1, da $\sin(90^\circ) = 1$. Hvis to forskellige basisvektorer krydses, vil deres vektorprodukt også have samme retning som den tredje basisvektor. Højrehåndsreglen giver orienteringen. Da vinklen mellem to parallelle vektorer er $0^\circ$, vil deres vektorprodukt give $\vec{0}$, da $\sin(0^\circ) = 0$.

2.
$$
\vec{a} \times \vec{b} = (a_1 \vec{i} + a_2 \vec{j} + a_3 \vec{k}) \times (b_1 \vec{i} + b_2 \vec{j} + b_3 \vec{k})
$$

De to vektorer skrives op ud fra deres basisvektorer.

3.
$$
\vec{a} \times \vec{b} = a_1 b_1 \vec{i} \times \vec{i} + a_1 b_2 \vec{i} \times \vec{j} + a_1 b_3 \vec{i} \times \vec{k} + a_2 b_1 \vec{j} \times \vec{i} + a_2 b_2 \vec{j} \times \vec{j} + a_2 b_3 \vec{j} \times \vec{k} + a_3 b_1 \vec{k} \times \vec{i} + a_3 b_2 \vec{k} \times \vec{j} + a_3 b_3 \vec{k} \times \vec{k}
$$

De to parenteser krydses ved hjælp af den distributive lov, som også er den lov, der fortæller, hvordan to parenteser ganges sammen.

4.
$$
\vec{a} \times \vec{b} = a_2 b_3 \vec{i} - a_3 b_2 \vec{i} + a_3 b_1 \vec{j} - a_1 b_3 \vec{j} + a_1 b_2 \vec{k} - a_2 b_1 \vec{k}
$$

Leddende med nulvektorerne forsvinder, og de resterende led ordnes i rækkefølge efter basisvektorerne.

5.
$$
\vec{a} \times \vec{b} = (a_2 b_3 - a_3 b_2) \cdot \vec{i} + (a_3 b_1 - a_1 b_3) \cdot \vec{j} + (a_1 b_2 - a_2 b_1) \cdot \vec{k}
$$

Basisvektorerne sættes uden for hver deres parentes.

6.
$$
\vec{a} \times \vec{b} = \begin{pmatrix} a_2 b_3 - a_3 b_2 \\ a_3 b_1 - a_1 b_3 \\ a_1 b_2 - a_2 b_1 \end{pmatrix}
$$

Vektorproduktet skrives på vektorform.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Vektorprodukt og areal

**Sætning**

Om to rumlige vektorer og deres vektorprodukt
$$
\vec{a} = \begin{pmatrix} a_1 \\ a_2 \\ a_3 \end{pmatrix}, \quad \vec{b} = \begin{pmatrix} b_1 \\ b_2 \\ b_3 \end{pmatrix}, \quad \vec{a} \times \vec{b} = \begin{pmatrix} a_2 b_3 - a_3 b_2 \\ a_3 b_1 - a_1 b_3 \\ a_1 b_2 - a_2 b_1 \end{pmatrix}
$$
gælder, at arealet af vektor $\vec{a}$ og vektor $\vec{b}$'s udspændte parallelogram findes ved
$$
Areal = |\vec{a} \times \vec{b}| = |\vec{a}| \cdot |\vec{b}| \cdot \sin(v)
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/8/0/csm_krydsprodukt_areal_a1f2df1408.png)

Arealet af et parallelogram svarer til arealet af to trekanter som vist på figuren. Derfor må arealet svare til $2 \cdot \frac{1}{2} \cdot |\vec{a}| \cdot |\vec{b}| \cdot \sin(v)$, hvor $\frac{1}{2} \cdot |\vec{a}| \cdot |\vec{b}| \cdot \sin(v)$ svarer til arealet af en vilkårlig trekant. I et parallelogram er to modstående vinkler altid ens.

1.
$$
|\vec{a} \times \vec{b}| = |\vec{a}| \cdot |\vec{b}| \cdot \sin(v)
$$

Det postuleres, at denne formel gælder.

2.
$$
|\vec{a} \times \vec{b}|^2 = (|\vec{a}| \cdot |\vec{b}| \cdot \sin(v))^2 = |\vec{a}|^2 \cdot |\vec{b}|^2 \cdot \sin^2(v)
$$

Begge sider sættes i anden potens og omskrives. Bemærk at vinklen $v$ i et parallelogram altid ligger i intervallet $0 < v < 180$.

3.
$$
= |\vec{a}|^2 \cdot |\vec{b}|^2 \cdot (1 - \cos^2(v))
$$

Omskrives vha. grundrelationen.

4.
$$
= |\vec{a}|^2 \cdot |\vec{b}|^2 - |\vec{a}|^2 \cdot |\vec{b}|^2 \cdot \cos^2(v)
$$

Der ganges ind i parentesen.

5.
$$
= |\vec{a}|^2 \cdot |\vec{b}|^2 - (\vec{a} \cdot \vec{b})^2
$$

Omskriver sidste led til kvadratet på skalarproduktet.

6.
$$
(a_2 b_3 - a_3 b_2)^2 + (a_3 b_1 - a_1 b_3)^2 + (a_1 b_2 - a_2 b_1)^2
$$
$$
= (a_1^2 + a_2^2 + a_3^2) \cdot (b_1^2 + b_2^2 + b_3^2) - (a_1 b_1 + a_2 b_2 + a_3 b_3)^2
$$

Koordinater indsættes i udregning 2 ved hjælp af længdeformlen for en vektor.

7.
$$
(a_2 b_3)^2 + (a_3 b_2)^2 - 2 a_2 b_3 a_3 b_2 + (a_3 b_1)^2 + (a_1 b_3)^2 - 2 a_3 b_1 a_1 b_3
$$
$$
+ (a_1 b_2)^2 + (a_2 b_1)^2 - 2 a_1 b_2 a_2 b_1
$$
$$
= a_1^2 b_1^2 + a_2^2 b_2^2 + a_3^2 b_3^2 + a_1^2 b_2^2 + a_2^2 b_1^2 + a_2^2 b_3^2 + a_3^2 b_2^2 + a_3^2 b_1^2 + a_1^2 b_3^2
$$
$$
- [(a_1 b_1)^2 + a_1 b_1 a_2 b_2 + a_1 b_1 a_3 b_3 + a_2 b_2 a_1 b_1 + (a_2 b_2)^2 + a_2 b_2 a_3 b_3 + a_3 b_3 a_1 b_1 + a_3 b_3 a_2 b_2 + (a_3 b_3)^2]
$$

Parenteserne ganges ud fx vha. kvadratsætning 1 og kvadratsætning 2.

8.
$$
0 = 0
$$

Det ses, at alle leddene går ud med hinanden.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Afstanden mellem punkt og punkt

**Sætning**

Om to punkter i rummet givet ved
$$
A = (x_A; y_A; z_A) \quad B = (x_B; y_B; z_B)
$$
så kan afstanden mellem $A$ og $B$ findes ved
$$
\text{dist}(A, B) = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2 + (z_B - z_A)^2}
$$

**Bevis**

1.
$$
\overrightarrow{AB} = \begin{pmatrix} x_B - x_A \\ y_B - y_A \\ z_B - z_A \end{pmatrix}
$$
Bestemmer vektoren fra $A$ til $B$.

2.
$$
\text{dist}(A, B) = |\overrightarrow{AB}|
$$
Afstanden $\text{dist}(A, B)$ er det samme som længden af vektor $\overrightarrow{AB}$.

3.
$$
\text{dist}(A, B) = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2 + (z_B - z_A)^2}
$$
Bestemmer længden af vektoren.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Afstanden mellem punkt og plan

**Sætning**

Hvis
$$
P = (x_1; y_1; z_1) \quad P_0 = (x_0; y_0; z_0) \quad \alpha : ax + by + cz + d = 0
$$
hvor $P_0$ er et vilkårligt punkt i planen, findes afstanden fra $P$ til $\alpha$ ved
$$
\text{dist}(P, \alpha) = \frac{|\overrightarrow{P_0P} \cdot \vec{n}|}{|\vec{n}|} = \frac{|ax_1 + by_1 + cz_1 + d|}{\sqrt{a^2 + b^2 + c^2}}
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/9/6/csm_afstand_punkt_plan_6c80074711.png)

Når man taler om en afstand til en plan, så menes der altid den korteste afstand, dvs. vinkelret på planen.

1.
$$
\text{dist} = |\overrightarrow{RP}|
$$
Den korteste afstand fra et punkt $P$, der ikke ligger i planen, svarer til længden af vektor $\overrightarrow{RP}$, da $R$ er projektionen af $P$ på planen.

2.
$$
|\overrightarrow{RP}| = \left| \frac{\overrightarrow{P_0P} \cdot \vec{n}}{|\vec{n}|} \right| 
$$
$$
\vec{n} = \begin{pmatrix} a \\ b \\ c \end{pmatrix}
$$
Længden af vektor $\overrightarrow{RP}$ kan findes ved at tage et vilkårligt punkt i planen $P_0$ og danne en vektor $\overrightarrow{P_0P}$. Dennes projektion på planens normalvektor $\vec{n}$ svarer til vektor $\overrightarrow{RP}$. Koefficienterne til $x$, $y$ og $z$ er normalvektorens koordinater i planens ligning $ax + by + cz + d = 0$.

3.
$$
\overrightarrow{P_0P} \cdot \vec{n} = \begin{pmatrix} x_1 - x_0 \\ y_1 - y_0 \\ z_1 - z_0 \end{pmatrix} \cdot \begin{pmatrix} a \\ b \\ c \end{pmatrix} 
= ax_1 - ax_0 + by_1 - by_0 + cz_1 - cz_0
$$
Beregner skalarproduktet.

4.
$$
= ax_1 + by_1 + cz_1 + d
$$
$$
d = -ax_0 - by_0 - cz_0 
$$
da $P_0$ ligger i planen, og punktet derfor må tilfredsstille planens ligning.

5.
$$
\text{dist}(P, \alpha) = \frac{|\overrightarrow{P_0P} \cdot \vec{n}|}{|\vec{n}|} = \frac{|ax_1 + by_1 + cz_1 + d|}{\sqrt{a^2 + b^2 + c^2}}
$$
Længden af normalvektoren findes vha. formlen for længden af en vektor.

Q.E.D.

<div class = "pagebreak"></div>


## Proof Afstandsformlen mellem linje og linje (ikke-parallelle)

**Sætning**

Afstanden mellem to linjer $l$ og $m$ findes ved formlen:
$$
\text{dist}(l, m) = \frac{|\overrightarrow{AB} \cdot \vec{n}|}{|\vec{n}|}
$$
hvor linjerne er beskrevet ved parameterfremstillinger og normalvektoren $\vec{n}$ ved krydsproduktet af de to retningsvektorer:
$$
l : \begin{pmatrix} x \\ y \\ z \end{pmatrix} = \begin{pmatrix} x_A \\ y_A \\ z_A \end{pmatrix} + s \cdot \vec{r}_l 
\quad \quad
m : \begin{pmatrix} x \\ y \\ z \end{pmatrix} = \begin{pmatrix} x_B \\ y_B \\ z_B \end{pmatrix} + t \cdot \vec{r}_m
$$
$$
\vec{n} = \vec{r}_l \times \vec{r}_m
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/2/9/csm_afstand_linje_linje_00709caa8f.png)

Afstanden mellem to linjer findes, hvor de to linjer "krydser lodret" over hinanden. Man lader de to linjers retningsvektorer sammen med et punkt på den ene linje (på figuren er punkt $A$ valgt) udspænde en plan. Afstanden mellem de to linjer svarer så til afstanden fra et vilkårligt punkt (på figuren er valgt punkt $B$) på den anden linje til denne plan.

1.
$$
\text{dist}(l, m) = \frac{|\overrightarrow{AB} \cdot \vec{n}|}{|\vec{n}|}
$$
Indsætter i formlen for afstand fra punkt til plan, og normalvektoren $\vec{n}$ beregnes som vektorproduktet af de to linjers retningsvektorer.

Q.E.D.

**Note**

For to parallelle linjer er afstanden enten nul (hvis de er sammenfaldende) eller konstant. Hvis afstanden er konstant vælger vi et vilkårligt punkt på den ene linje og bruger formlen for afstand fra punkt til linje.

<div class = "pagebreak"></div>

## Proof Afstandsformlen for punkt til linje

**Sætning**

Hvis 
$$
P = (x_1, y_1, z_1) \quad P_0 = (x_0, y_0, z_0) \quad l : \begin{pmatrix} x \\ y \\ z \end{pmatrix} = \begin{pmatrix} x_0 \\ y_0 \\ z_0 \end{pmatrix} + s \cdot \vec{r}
$$
hvor $P_0$ er et tilfældigt punkt på linjen, så findes afstanden fra $P$ til $l$ ved
$$
\text{dist}(P, l) = \frac{|\overrightarrow{P_0 P} \times \vec{r}|}{|\vec{r}|}
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/f/7/csm_afstand_punkt_linje_5ead9c5f9d.png)

Når man taler om en afstand til en linje, så menes der altid den korteste afstand, dvs. vinkelret ind på linjen.

1.
$$
\text{dist} = |\overrightarrow{RP}|
$$
Den korteste afstand fra et punkt $P$, der ikke ligger på linjen, svarer til længden af vektor $\overrightarrow{RP}$, hvor $R$ er projektionen af $P$ på linjen.

2.
$$
= |\overrightarrow{P_0 P}| \cdot \sin(v)
$$
Omskriver $|\overrightarrow{RP}|$ vha. reglen for sinus i den retvinklede trekant.

3.
$$
= \frac{|\overrightarrow{P_0 P}| \cdot \sin(v) \cdot |\vec{r}|}{|\vec{r}|}
$$
Ganger med $|\vec{r}|$ i både tæller og nævner.

4.
$$
\text{dist}(P, l) = \frac{|\overrightarrow{P_0 P} \times \vec{r}|}{|\vec{r}|}
$$
Nu svarer tælleren til længden af vektorproduktet af de to vektorer.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Volumen for en kugle

**Sætning**

En kugle med radius $r$ har volumen
$$
V_{\text{kugle}} = \frac{4}{3} \pi \cdot r^3
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/0/9/csm_kugle_overflade_ff827062b4.png)

1.
$$
x^2 + y^2 = r^2
$$
Opstiller cirklens ligning for en cirkel med centrum i $(0,0)$ og radius $r$.

2.
$$
y^2 = r^2 - x^2
$$
Trækker $x^2$ fra på begge sider af lighedstegnet.

3.
$$
y = \pm \sqrt{r^2 - x^2} \\
y = \sqrt{r^2 - x^2}
$$
Tager kvadratroden på begge sider og vælger kun at se på den positive del.

4.
$$
f(x) = \sqrt{r^2 - x^2} \quad Dm(f) = [-r, r]
$$
Definerer en funktion, hvis graf beskriver den øvre halvcirkel.

5.
$$
V_x = \pi \int_{-r}^{r} \sqrt{r^2 - x^2}^2 \, dx = \pi \int_{-r}^{r} (r^2 - x^2) \, dx
$$
Bruger formlen for volumen af omdrejningslegeme omkring x-aksen. Kvadratroden og kvadratet går ud med hinanden.

6.
$$
= \pi \left[ r^2 x - \frac{1}{3} x^3 \right]_{-r}^{r} = \pi \left( r^3 - \frac{1}{3} r^3 - \left( -r^3 + \frac{1}{3} r^3 \right) \right)
$$
Finder stamfunktion og indsætter grænserne efter samme metode som ved Infinitesimalregningens fundamental sætning.

7.
$$
= \pi \left( \frac{2}{3} r^3 - \left( -\frac{2}{3} r^3 \right) \right) = \pi \left( \frac{2}{3} r^3 + \frac{2}{3} r^3 \right)
$$
Reducerer og hæver minusparentesen.

8.
$$
V_x = V_{\text{kugle}} = \frac{4}{3} \pi \cdot r^3
$$
Reducerer, og formlen fremkommer.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Volumen for en kuglekalot

**Sætning**

Volumen af en kuglekalot med højde $h$ og med kugleradius $r$:
$$
V_{\text{kalot}} = \pi \cdot h^2 \left( r - \frac{h}{3} \right)
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/1/e/csm_kalot_f47996cc36.png)

1.
$$
x^2 + y^2 = r^2
$$
Opstiller cirklens ligning for en cirkel med centrum i $(0,0)$ og radius $r$.

2.
$$
y^2 = r^2 - x^2
$$
Trækker $x^2$ fra på begge sider af lighedstegnet.

3.
$$
y = \pm \sqrt{r^2 - x^2} \\
y = \sqrt{r^2 - x^2}
$$
Tager kvadratroden på begge sider og vælger kun at se på den positive del.

4.
$$
f(x) = \sqrt{r^2 - x^2} \quad Dm(f) = [r - h; r]
$$
Definerer en funktion, hvis graf har den øvre halvcirkel. Venstre grænse sættes til $r - h$, da det kun er kalotten, der er interessant.

5.
$$
V_x = \pi \int_{r - h}^{r} \sqrt{r^2 - x^2}^2 \, dx = \pi \int_{r - h}^{r} (r^2 - x^2) \, dx
$$
Bruger formlen for volumen af omdrejningslegeme omkring x-aksen. Kvadratroden og kvadratet går ud med hinanden.

6.
$$
= \pi \left[ r^2 x - \frac{1}{3} x^3 \right]_{r - h}^{r} = \pi \left( r^3 - \frac{1}{3} r^3 - \left( r^2 (r - h) - \frac{1}{3} (r - h)^3 \right) \right)
$$
Finder stamfunktion og indsætter grænserne efter samme metode som ved Infinitesimalregningens fundamental sætning.

7.
$$
= \pi \left( \frac{2}{3} r^3 - \left( r^3 - r^2 h - \frac{1}{3} (r^3 - 3r^2 h + 3r h^2 - h^3) \right) \right)
$$
Reducerer; ganger ind i parentes og bruger 2. kvadratsætning.

8.
$$
= \pi \left( \frac{2}{3} r^3 - \left( \frac{1}{3} r^3 + r^2 h - \frac{h^3}{3} \right) \right)
$$
Ganger $-\frac{1}{3}$ ind i den inderste parentes.

9.
$$
= \pi \left( \frac{2}{3} r^3 - \left( \frac{2}{3} r^3 + \frac{h^3}{3} - r h^2 \right) \right)
$$
Reducerer inderste parentes.

10.
$$
= \pi \left( -\frac{h^3}{3} + r h^2 \right) = \pi \cdot h^2 \left( -\frac{h}{3} + r \right)
$$
Minusparentesen hæves, og der reduceres igen. Herefter sættes $h^2$ uden for parentesen.

11.
$$
V_x = V_{\text{kalot}} = \pi \cdot h^2 \left( r - \frac{h}{3} \right)
$$
Der byttes om på leddene i parentesen.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Volumen for en kegle

**Sætning**

Volumen af en kegle med højde $h$ og med radius $r$:
$$
V_{\text{kegle}} = \frac{h}{3} \cdot \pi \cdot r^2
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/6/e/csm_kegle_rumfang_9fb5b1faa8.png)

1.
$$
f(x) = \frac{r}{h} x, \quad 0 \leq x \leq h
$$
En kegle fremkommer ved rotation af $f$ omkring x-aksen. $f$ er en ret linje af typen $ax + b$. Her er $b = 0$, fordi linjen går gennem $(0,0)$. Hældningskoefficienten $a$ er det samme som $\frac{\Delta y}{\Delta x} = \frac{r}{h}$.

2.
$$
V_x = \pi \int_0^h \left( \frac{r}{h} x \right)^2 dx = \pi \int_0^h \frac{r^2}{h^2} x^2 \, dx
$$
Indsætter $f(x)$ i formlen for volumen af omdrejningslegemer om x-aksen, og hæver parentesen.

3.
$$
= \frac{\pi r^2}{h^2} \int_0^h x^2 \, dx = \frac{\pi r^2}{h^2} \left[ \frac{1}{3} x^3 \right]_0^h
$$
Konstanterne flyttes uden for integralet, og stamfunktionen findes.

4.
$$
= \frac{\pi r^2}{h^2} \left( \frac{1}{3} h^3 - 0 \right) = \frac{\pi r^2}{h^2} \cdot \frac{1}{3} h^3
$$
Grænserne indsættes, og der reduceres.

5.
$$
V_x = V_{\text{kegle}} = \frac{h}{3} \cdot \pi \cdot r^2
$$
Udtrykket reduceres og omskrives.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Volumen for en keglestub

**Sætning**

Volumen af en keglestub med højde $h$ og storradius $R$ og lillerradius $r$ findes ved formlen:
$$
V_{\text{keglestub}} = \frac{h}{3} \pi \cdot \left( R^2 + r^2 + R \cdot r \right)
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/9/3/csm_keglestub_rumfang_220e0b6ad7.png)

1.
$$
f(x) = \frac{R - r}{h} x + r, \quad 0 \leq x \leq h
$$
En keglestub fremkommer ved rotation af en ret linje omkring x-aksen. $f$ er en ret linje af typen $ax + b$. Det ses, at $b = r$. Hældningskoefficienten $a$ er det samme som $\frac{\Delta y}{\Delta x} = \frac{R - r}{h}$.

2.
$$
V_x = \pi \int_0^h \left( \frac{R - r}{h} x + r \right)^2 dx = \pi \int_0^h \left( \left( \frac{R - r}{h} x \right)^2 + r^2 + 2 \frac{R - r}{h} x r \right) dx
$$
Indsætter $f(x)$ i formlen for volumen af omdrejningslegemer omkring x-aksen. Herefter udregnes kvadratet på parentesen vha. 1. kvadratsætning.

3.
$$
= \pi \int_0^h \left( \left( \frac{R - r}{h} \right)^2 x^2 + r^2 + 2 \frac{R - r}{h} x r \right) dx
$$
$x^2$ sættes uden for parentesen.

4.
$$
= \pi \left[ \left( \frac{R - r}{h} \right)^2 \frac{x^3}{3} + r^2 x + 2 \frac{R - r}{h} r \frac{x^2}{2} \right]_0^h
$$
Bestemmer stamfunktionen.

5.
$$
= \pi \left( \frac{R^2 h}{3} + \frac{r^2 h}{3} - \frac{2Rrh}{3} + r^2 h + Rrh - r^2 h \right)
$$
Indsætter grænserne efter samme princip som i Infinitesimalregningens fundamentalsætning.

6.
$$
= \pi \left( \frac{R^2 h}{3} + \frac{r^2 h}{3} + \frac{Rrh}{3} \right)
$$
Ganger brøkerne sammen og reducerer.

7.
$$
V_x = V_{\text{keglestub}} = \frac{h}{3} \pi \left( R^2 + r^2 + R \cdot r \right)
$$
Sætter $\frac{h}{3}$ uden for parentesen.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Volumen for en pyramide

**Sætning**

En pyramide med højden $h$ og grundfladearealet $A_G$ har volumen
$$
V_{\text{pyramide}} = \frac{1}{3} h \cdot A_G
$$

**Bevis (pyramide med kvadratisk grundflade og toppunkt vinkelret over kvadratets centrum)**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/c/0/csm_volumen_pyramide_kvadrat_4b0163ead2.png)

En pyramide med højden $h$ og sidebredde $s$ anbringes i et koordinatsystem med spidsen i origo og pyramidens højde langs x-aksen.

1.
$$
f(x) = \frac{1}{2} \frac{s}{h} x
$$
Opstiller en funktion $f$ for den rette linje, som løber fra pyramidens spids til midtpunktet for en af siderne i pyramidens bund. $s$ er sidelængden i pyramidens kvadratiske bund. Den lineære funktion har hældningen $\frac{0.5 \cdot s}{h}$.

2.
$$
A(x) = \left( \frac{1}{2} \frac{s}{h} x \right)^2 = \left( \frac{s}{h} x \right)^2
$$
Arealet af et vilkårligt lodret tværsnit i pyramiden for en given $x$-værdi findes som kvadratet af den dobbelte funktionsværdi.

3.
$$
\Delta V_x \approx A(x) \cdot \Delta x = \left( \frac{s}{h} x \right)^2 \cdot \Delta x
$$
For stykket $\Delta x$ kan volumenet af en skive i pyramiden tilnærmet bestemmes som rumfanget af en kasse.

4.
$$
V \approx \sum_{i=1}^n \left( \frac{s}{h} x \right)^2 \cdot \Delta x
$$
For hele pyramiden opdelt i $n$ stykker kan det samlede volumen tilnærmet bestemmes som en sum.

5.
$$
V_x = \lim_{\Delta x \to 0} \sum_{i=1}^n \left( \frac{s}{h} x \right)^2 \cdot \Delta x
$$
Tager grænseværdien af summen.

6.
$$
V = \int_0^h \left( \frac{s}{h} x \right)^2 \, dx = \frac{s^2}{h^2} \int_0^h x^2 \, dx
$$
Erstatter med det bestemte integral og sætter konstanten $\frac{s^2}{h^2}$ uden for integraltegnet.

7.
$$
= \frac{s^2}{h^2} \left[ \frac{1}{3} x^3 \right]_0^h = \frac{s^2}{h^2} \left( \frac{1}{3} h^3 - 0 \right) = \frac{1}{3} h \cdot s^2
$$
Finder stamfunktionen, sætter øvre og nedre integrationsgrænser ind og reducerer udtrykket.

8.
$$
= \frac{1}{3} h \cdot A_G
$$
Da $A_G = s^2$ fremkommer formlen.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Overfladeareal af en kugle

**Sætning**

En kugle med radius $r$ har overfladearealet:
$$
A_{\text{kugle}} = 4 \pi r^2
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/0/9/csm_kugle_overflade_ad97350575.png)

1.
$$
x^2 + y^2 = r^2
$$
Opstiller cirklens ligning for en cirkel med centrum i $(0,0)$ og radius $r$.

2.
$$
y^2 = r^2 - x^2
$$
Trækker $x^2$ fra begge sider af lighedstegnet.

3.
$$
y = \pm \sqrt{r^2 - x^2} \\
y = \sqrt{r^2 - x^2}
$$
Tager kvadratroden på begge sider og vælger kun at se på den positive del.

4.
$$
f(x) = \sqrt{r^2 - x^2} \quad Dm(f) = [-r, r]
$$
Definerer en funktion, der beskriver den øvre halvcirkel.

5.
$$
f'(x) = \frac{1}{\sqrt{r^2 - x^2}} \cdot (-2x) = \frac{-x}{\sqrt{r^2 - x^2}}
$$
Differentiere $f$ med hensyn til $x$ for at bruge formlen for overfladeareal af omdrejningslegemer omkring x-aksen. Da $f$ er en sammensat funktion, bruges kædereglen til at differentiere.

6.
$$
O_x = 2 \pi \int_{-r}^r f(x) \sqrt{1 + \left( f'(x) \right)^2} \, dx
$$
Indsætter $f(x)$ og $f'(x)$ i formlen for overfladeareal af omdrejningslegemer omkring x-aksen.

7.
$$
= 2 \pi \int_{-r}^r \sqrt{r^2 - x^2} \sqrt{1 + \frac{x^2}{r^2 - x^2}} \, dx
$$
Udregner parentesen i den sidste kvadratrod.

8.
$$
= 2 \pi \int_{-r}^r \sqrt{r^2 - x^2 + \frac{x^2(r^2 - x^2)}{r^2 - x^2}} \, dx
$$
Samler de to kvadratrødder til én.

9.
$$
= 2 \pi \int_{-r}^r \sqrt{r^2} \, dx = 2 \pi \int_{-r}^r r \, dx
$$
Reducerer brøken.

10.
$$
= 2 \pi \int_{-r}^r r \, dx = 2 \pi r \int_{-r}^r \, dx
$$
De to $x^2$-led går ud med hinanden, og derefter går kvadratroden og kvadratet ud med hinanden.

11.
$$
= 2 \pi r [x]_{-r}^r
$$
Nu er integralet tilstrækkelig simpelt, og stamfunktionen findes og bruges med infinitesimalregningens fundamentalsætning.

12.
$$
= 2 \pi r (r - (-r)) = 2 \pi r (2r)
$$
Grænserne indsættes, og parentesen beregnes.

13.
$$
O_x = A_{\text{kugle}} = 4 \pi r^2
$$
Der ganges ind i parentesen.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Overfladeareal af en kuglekap

**Sætning**

En kuglekap med radius $r$ og højden $h$ har overfladearealet:
$$
A_{\text{kuglekap}} = 2 \pi r h
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/a/9/csm_kuglekalot_overflade_3c50aa3682.png)

1.
$$
x^2 + y^2 = r^2
$$
Opstiller cirklens ligning for en cirkel med centrum i $(0,0)$ og radius $r$.

2.
$$
y^2 = r^2 - x^2
$$
Trækker $x^2$ fra begge sider af lighedstegnet.

3.
$$
y = \pm \sqrt{r^2 - x^2} \\
y = \sqrt{r^2 - x^2}
$$
Tager kvadratroden på begge sider og vælger kun at se på den positive del.

4.
$$
f(x) = \sqrt{r^2 - x^2} \quad Dm(f) = [r - h, r]
$$
Definerer en funktion, der er graf for den øvre halvcirkel.

5.
$$
f'(x) = \frac{1}{\sqrt{r^2 - x^2}} \cdot (-2x) = \frac{-x}{\sqrt{r^2 - x^2}}
$$
Differentiere $f$ med hensyn til $x$ for at bruge formlen for overfladeareal af omdrejningslegemer omkring x-aksen. Da $f$ er en sammensat funktion, bruges kædereglen til at differentiere.

6.
$$
O_x = 2 \pi \int_{r - h}^r f(x) \sqrt{1 + \left( f'(x) \right)^2} \, dx
$$
Indsætter $f(x)$ og $f'(x)$ i formlen for overfladeareal af omdrejningslegemer omkring x-aksen.

7.
$$
= 2 \pi \int_{r - h}^r \sqrt{r^2 - x^2} \sqrt{1 + \frac{x^2}{r^2 - x^2}} \, dx
$$
Udregner parentesen i den sidste kvadratrod.

8.
$$
= 2 \pi \int_{r - h}^r \sqrt{r^2 - x^2 + \frac{x^2(r^2 - x^2)}{r^2 - x^2}} \, dx
$$
Samler de to kvadratrødder til én.

9.
$$
= 2 \pi \int_{r - h}^r \sqrt{r^2} \, dx = 2 \pi \int_{r - h}^r r \, dx
$$
Reducerer brøken.

10.
$$
= 2 \pi \int_{r - h}^r r \, dx = 2 \pi r \int_{r - h}^r \, dx
$$
De to $x^2$-led går ud med hinanden, og derefter går kvadratroden og kvadratet ud med hinanden.

11.
$$
= 2 \pi r [x]_{r - h}^r
$$
Nu er integralet tilstrækkelig simpelt, og stamfunktionen findes og bruges med infinitesimalregningens fundamentalsætning.

12.
$$
= 2 \pi r (r - (r - h)) = 2 \pi r (r - r + h)
$$
Grænserne indsættes, og den inderste parentes beregnes.

13.
$$
= 2 \pi r (r - r + h) = 2 \pi r h
$$
Minusparentesen hæves, og derefter går de to led med $r^2$ ud med hinanden.

14.
$$
O_x = A_{\text{kuglekap}} = 2 \pi r h
$$
Der ganges ind i parentesen.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Overfladeareal af en kegle

**Sætning**

En kegle med radius $r$, højde $h$ og sidelængden $s$ har overfladearealet:
$$
A_{\text{kegle}} = \pi \cdot r \cdot s
$$
hvor
$$
s = \sqrt{r^2 + h^2}
$$

**Bevis**

![enter image description here](https://bevissamling.systime.dk/fileadmin/_processed_/9/a/csm_kegle_geometrisk_264aed8b4f.png)

1.
$$
s = \sqrt{r^2 + h^2}
$$
Længden $s$ findes vha. Pythagoras' formel.

2.
$$
\frac{v}{360^\circ} = \frac{2 \pi r}{2 \pi s} = \frac{r}{s}
$$
Forholdet mellem $v$ og $360^\circ$ må være det samme som længden af den røde cirkelbue i forhold til omkredsen af hele cirklen.

3.
$$
A_{\text{kegle}} = \pi \cdot s^2 \cdot \frac{v}{360^\circ} = \pi \cdot s^2 \cdot \frac{r}{s} = \pi r s
$$
Arealet af cirkeludsnittet findes som den forholdsmæssige del af en hel cirkel. $\frac{v}{360^\circ}$ erstattes med udtrykket i (2).

4.
$$
A_{\text{kegle}} = \pi \cdot r \cdot s
$$
Q.E.D.

<div class = "pagebreak"></div>

## Proof Overfladeareal af en keglestub

**Sætning**

Arealet af en keglestubs krumme overflade findes ved
$$
A_{\text{keglestub}} = \pi \cdot s \cdot (R + r)
$$
hvor
$$
s = \sqrt{h^2 + (R - r)^2}
$$

Til denne sætning viser vi beviserne for forskellige metoder.

---

**Bevis 1**

![Diagram af keglestub](https://bevissamling.systime.dk/fileadmin/_processed_/f/7/csm_keglestub_geometrisk_25034f5b48.png)

En keglestub er en kegle, hvor man har fjernet toppen, der igen er en mindre kegle. Derfor kan arealet af en keglestubs krumme overflade findes ved at tage arealet af den store kegle minus arealet af den lille kegle. Radius for den store kegles grundflade er $R$, og radius for den lille kegles grundflade er $r$. Højden i den lille kegle kaldes $h_1$.

1. 
   $$
   A_{\text{keglestub}} = \pi \cdot R \cdot s_1 - \pi \cdot r \cdot s_2
   $$
   Arealet af keglestubben findes som arealet af den store kegle minus arealet af den lille kegle.

2. 
   $$
   s_1 = \sqrt{h^2 + R^2} \quad \text{og} \quad s_2 = \sqrt{h^2 + r^2}
   $$
   $s_1$ og $s_2$ findes vha. Pythagoras' sætning.

3. 
   $$
   A_{\text{keglestub}} = \pi \cdot (R - r) \cdot s + \pi \cdot r \cdot s
   $$
   $s_1$ og $s_2$ sættes uden for parentes.

4. 
   $$
   A_{\text{keglestub}} = \pi \cdot s \cdot (R + r)
   $$
   Ved at kombinere de to led får vi det ønskede resultat.


<div class = "pagebreak"></div>


## Proof y' = ay

**Sætning**

Differentialligningen $y' = ay$ har den fuldstændige løsning
$$
y = c \cdot e^{ax}
$$
hvor $a$ er et reelt tal $(a \neq 0)$, og $c$ er en konstant.

**Bevis**

Vi anvender metoden *separation af variable*.

For $y = 0$ ses direkte, at sætningen gælder, da $y' = 0$ har løsningen $y = k$, der netop kun kan være 0.

For $y < 0$ eller $y > 0$ gælder:

1.  
$$
\frac{dy}{dx} = ay \iff \frac{1}{y} \, dy = a \, dx
$$
$$
\int \frac{1}{y} \, dy = \int a \, dx
$$

Vi integrerer på begge sider.

2.  
$$
\ln |y| + c_1 = ax + c_2
$$

Integralet udregnes.

3.  
$$
\ln |y| = ax + c_3
$$

De to integrationskonstanter samles i en fælles konstant $c_3$.

4.  
$$
e^{\ln |y|} = e^{ax + c_3}
$$
$$
|y| = e^{ax + c_3}
$$

Den naturlige eksponentialfunktion benyttes på begge sider af lighedstegnet.

5.  
$$
y = e^{ax + c_3} = c \cdot e^{ax} \quad \text{for } y > 0
$$
$$
y = -e^{ax + c_3} = c \cdot e^{ax} \quad \text{for } y < 0
$$

Idet $e^{c_3}$ og $-e^{c_3}$ i hvert tilfælde kaldes for $c$.

Q.E.D.

<div class = "pagebreak"></div>

## Proof y' + ay = b ved separation af variable

**Sætning**

Differentialligningen $y' + ay = b$ har den fuldstændige løsning
$$
y = \frac{b}{a} + c \cdot e^{-ax}
$$
Hvor $a$ og $b$ er reelle tal, $a \neq 0$, og $c$ er en konstant, der afgør den specifikke løsning.

**Bevis**

1.  
$$
y' = b - ay
$$

$ay$ trækkes fra på begge sider. Ved indsættelse af $y = \frac{b}{a}$ fremgår det også, at dette er en nullløsning, da $y'$ giver nul. Denne løsning svarer til, at konstanten $c = 0$.

2.  
$$
\frac{dy}{dx} = b - ay
$$

Omskriver til Leibniz' notation.

3.  
$$
\frac{1}{b - ay} \, dy = dx
$$

Der ganges med $dx$ og deles med $b - ay$ på begge sider. Se bemærkning om at betragte $\frac{dy}{dx}$ som en brøk i introduktionen.

4.  
$$
u = b - ay
$$

Definerer en variabel $u$ med henblik på substitution.

5.  
$$
\frac{du}{dy} = -a
$$

Differentiere med hensyn til $y$ på begge sider.

6.  
$$
\frac{du}{-a} = dy
$$

Ganger med $dy$ og deler med $-a$ på begge sider.

7.  
$$
\frac{du}{u} = -a \, dx
$$

Substituerer (4) og (6) ind i (3).

8.  
$$
\frac{du}{u} = -a \, dx
$$

Ganger med $-a$ på begge sider.

9.  
$$
\int \frac{1}{u} \, du = \int -a \, dx
$$

Integrerer på begge sider.

10.  
$$
\ln |u| = -ax + k
$$

Integration udføres.

11.  
$$
|u| = e^{-ax + k} = e^{-ax} \cdot e^k
$$

Eksponentialfunktionen tages på begge sider, og potensreglen $x^{r+s} = x^r \cdot x^s$ anvendes.

12.  
$$
u = \pm e^k \cdot e^{-ax}
$$

Det numeriske tegn hæves.

13.  
$$
b - ay = \pm e^k \cdot e^{-ax}
$$

(4) substitueres i (12).

14.  
$$
ay = -b \pm e^k \cdot e^{-ax}
$$

Trækker $b$ fra på begge sider.

15.  
$$
y = \frac{b}{a} \pm \frac{e^k}{-a} e^{-ax}
$$

Deler med $-a$ på begge sider.

16.  
$$
y = \frac{b}{a} + c \cdot e^{-ax}
$$

Der reduceres, og da $\pm \frac{e^k}{a}$ er en konstant, erstattes den med en ny konstant $c$. Da $e^k$ altid er positiv, kan $c$ ikke være nul. Men fra (1) ved vi, at $c$ også kan være nul, og $c$ kan derfor være et vilkårligt tal.

Q.E.D.

<div class = "pagebreak"></div>

## Proof y' + h(x)y = g(x)

**Sætning**

Til en lineær differentialligning af første orden på formen
$$
y' + h(x) \cdot y = g(x)
$$
er den fuldstændige løsning givet ved
$$
y = e^{-H(x)} \cdot \left( \int e^{H(x)} \cdot g(x) \, dx + c \right)
$$
hvor $H(x)$ er stamfunktionen til $h(x)$ og $h$ og $g$ er kontinuerte i et givet interval.

Formlen kaldes panserformlen.

**Bevis**

1.  
$$
y' + h(x) \cdot y = g(x)
$$

Vi tager udgangspunkt i selve differentialligningen.

2.  
$$
(y' + h(x) \cdot y) \cdot e^{H(x)} = g(x) \cdot e^{H(x)}
$$

Vi ganger med $e^{H(x)}$ på begge sider af lighedstegnet. Da $h$ er kontinuer, findes stamfunktionen $H(x)$.

3.  
$$
y' \cdot e^{H(x)} + h(x) \cdot y \cdot e^{H(x)} = g(x) \cdot e^{H(x)}
$$

Ganger ind i parentesen på venstresiden.

4.  
$$
\left( e^{H(x)} \cdot y \right)' = g(x) \cdot e^{H(x)}
$$

Venstresiden reduceres, idet vi anvender reglen for differentiation af produkt.

5.  
$$
\int \left( e^{H(x)} \cdot y \right)' dx = \int g(x) \cdot e^{H(x)} \, dx
$$

Der integreres på begge sider af lighedstegnet.

6.  
$$
e^{H(x)} \cdot y = \int g(x) \cdot e^{H(x)} \, dx + c
$$

Integration og differentiation ophæver hinanden. Der dannes en konstant $c$.

7.  
$$
y = e^{-H(x)} \cdot \left( \int e^{H(x)} \cdot g(x) \, dx + c \right)
$$

Der ganges med $e^{-H(x)}$ på begge sider af lighedstegnet.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Logistisk vækst

**Sætning**

Hvis en vækst både er proportional med den aktuelle værdi $y$ og forskellen til den maksimale værdi $(m - y)$, svarende til
$$
y' = k \cdot y \cdot (m - y) \quad \land \quad 0 < y < m \quad \land \quad k > 0
$$
så gælder det, at
$$
y = \frac{m}{1 + c \cdot e^{-kmx}}
$$

**Bevis**

1.  
$$
y' = k \cdot y \cdot (m - y)
$$

Beviset gennemføres ved at anvende reglen om separation af variable.

2.  
$$
\frac{dy}{dx} = k \cdot y \cdot (m - y)
$$

Vi går fra Lagranges notation til Leibniz' notation og substituerer $\frac{dy}{dx} = y'$.

3.  
$$
\frac{1}{y \cdot (m - y)} \, dy = k \, dx
$$

Vi isolerer alt, hvad der har med $y$ og $x$ at gøre, på hver sin side af lighedstegnet, hvilket kan lade sig gøre, da $y' = k \cdot y \cdot (m - y)$. Se bemærkning om at betragte $\frac{dy}{dx}$ som en brøk i introduktionen.

4.  
$$
\frac{1}{y \cdot (m - y)} = \frac{1}{m} \cdot \frac{1}{y} + \frac{1}{m} \cdot \frac{1}{m - y}
$$

Brøken kan opdeles i to partialbrøker. Kontroller evt. ved at lægge de to brøker på højresiden sammen.

5.  
$$
\left( \frac{1}{y} + \frac{1}{m - y} \right) \, dy = k \, dx
$$

Indsætter de to partialbrøker i (3).

6.  
$$
\frac{1}{y} \, dy + \frac{1}{m - y} \, dy = k \cdot dx
$$

Ganger med $m$ på begge sider og ganger $dy$ ind i parentesen.

7.  
$$
\int \frac{1}{y} \, dy + \int \frac{1}{m - y} \, dy = \int k \cdot dx
$$

Integrerer på begge sider af lighedstegnet. Anvender reglen om integration af en sum.

8.  
$$
\ln |y| - \ln |m - y| = k \cdot m \cdot x + k_1
$$

Udregner integralene og tilføjer den arbitrære konstant, der udgør forskellen på de to sider.

9.  
$$
\ln \left( \frac{y}{m - y} \right) = k \cdot m \cdot x + k_1
$$

Samler venstresiden vha. regnereglen om logaritmen til en brøk.

10.  
$$
\frac{y}{m - y} = e^{k \cdot m \cdot x + k_1}
$$

Tager den naturlige eksponentialfunktion på begge sider for at isolere $y$.

11.  
$$
y = (m - y) \cdot e^{k \cdot m \cdot x + k_1}
$$

Ganger med $(m - y)$ på begge sider.

12.  
$$
y = m \cdot e^{k \cdot m \cdot x + k_1} - y \cdot e^{k \cdot m \cdot x + k_1}
$$

Ganger ind i parentesen.

13.  
$$
y + y \cdot e^{k \cdot m \cdot x + k_1} = m \cdot e^{k \cdot m \cdot x + k_1}
$$

Samler alle led med $y$ på venstresiden.

14.  
$$
y \cdot \left( 1 + e^{k \cdot m \cdot x + k_1} \right) = m \cdot e^{k \cdot m \cdot x + k_1}
$$

Sætter $y$ uden for parentes.

15.  
$$
y = \frac{m \cdot e^{k \cdot m \cdot x + k_1}}{1 + e^{k \cdot m \cdot x + k_1}}
$$

Deler med parentesen på begge sider.

16.  
$$
y = \frac{m}{\frac{1}{e^{k \cdot m \cdot x + k_1}} + 1}
$$

Forkorter brøken med $e^{k \cdot m \cdot x + k_1}$.

17.  
$$
y = \frac{m}{e^{-k \cdot m \cdot x - k_1} + 1}
$$

Omskriver brøken i nævneren vha. reglen $\frac{1}{x} = x^{-1}$.

18.  
$$
y = \frac{m}{1 + c \cdot e^{-kmx}}
$$

Omskriver vha. reglen $x^{r+s} = x^r \cdot x^s$.

Da $e^{-k_1}$ er en konstant, så erstattes den med en anden konstant $c$, og der byttes om på leddene i nævneren.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Logistisk vækst - den maksimale hældning

**Sætning**

Den største tangenthældning for en logistisk vækstkurve findes, hvor $y = \frac{m}{2}$, hvis $y' = ky(m - y)$.

**Bevis**

1.  
$$
\alpha(y) = ky(m - y) = kmy - ky^2
$$

$y'$ svarer til hældningen, og denne defineres som $\alpha$. $\alpha$ er afhængig af $y$ som differentialligningen viser, og kan betragtes som en funktion af $y$. Herefter ganges ind i parentesen.

2.  
$$
\alpha'(y) = km - 2ky = 0
$$

Differentiere $\alpha$ med hensyn til $y$ og sætter lig med nul for at finde den maksimale hældning.

3.  
$$
-2ky = -km
$$

Trækker $km$ fra begge sider af lighedstegnet.

4.  
$$
y = \frac{m}{2}
$$

Deler med $-2k$ på begge sider.

Q.E.D.

<div class = "pagebreak"></div>

## Proof Separation af variable

**Sætning**

For differentialligninger af typen
$$
\frac{dy}{dx} = g(y) \cdot h(x)
$$
kan løsninger $y = f(x)$ findes ved ligningen
$$
\int \frac{1}{g(y)} \, dy = \int h(x) \, dx + k
$$
Når $g(y) \neq 0$ og $h$ og $g$ er kontinuerte.

**Bevis**

1.  
$$
\frac{1}{g(y)} \frac{dy}{dx} = h(x)
$$

Da $g$ er kontinuer og forskellig fra nul, er den reciprokke funktion $\frac{1}{g(y)}$ også kontinuer, og vi kan derfor dividere med $g(y)$ på begge sider af lighedstegnet.

2.  
$$
\frac{1}{g(y)} f'(x) = \frac{1}{g(f(x))} \cdot f'(x) = h(x)
$$

Vi bruger den gængse skrivemåde for differentialkvotient og funktion.

3.  
$$
g^{-1}(y) f'(x) = H'(x)
$$

Da $h$ er kontinuer, har den en stamfunktion $H$, hvor $H'(x) = h(x)$. Og vi definerer funktionen
$$
g^{-1}(y) = \int \frac{1}{g(y)} \, dy
$$
(se note om notation).

4.  
$$
(G^{-1}(y)) f'(x) = (G^{-1}(f(x)))' = H'(x)
$$

Da funktionen $g^{-1}(y)$ også er kontinuer, har den stamfunktionen
$$
G^{-1}(y) = \int \frac{1}{g(y)} \, dy
$$
og der må gælde
$$
g^{-1}(y) = (G^{-1}(y))'
$$

5.  
$$
(G^{-1}(f(x)))' = H'(x)
$$

Venstresiden af lighedstegnet $(G^{-1}(f(x)))' f'(x)$ erstattes med
$$
(G^{-1}(f(x)) f'(x) = (G^{-1}(f(x)))'
$$
pga. reglen for differentiation af sammensat funktion.

6.  
$$
G^{-1}(f(x)) - H(x) = 0
$$

$H'(x)$ flyttes over på venstresiden.

7.  
$$
G^{-1}(f(x)) - H(x) = 0
$$

Differentiation af en differens.

8.  
$$
G^{-1}(f(x)) - H(x) = k
$$

Da differenskvotienten af differensen er nul, må funktionen $G^{-1}(f(x)) - H(x)$ være konstant.

9.  
$$
G^{-1}(y) = H(x) + k
$$

Vi genindfører $y = f(x)$ og flytter $H(x)$ over på højresiden.

10.  
$$
\int \frac{1}{g(y)} \, dy = \int h(x) \, dx + k
$$

Vi skriver stamfunktionerne som integraler.

Q.E.D.

<div class = "pagebreak"></div>

## Proof y'' = h(x)

**Sætning**

Differentialligningen
$$
y'' = h(x)
$$
eller
$$
\frac{d^2 y}{dx^2} = h(x)
$$
har den fuldstændige løsning
$$
y = H_2(x) + k_1 x + k_2
$$
hvor $k_1$ og $k_2$ er konstanter, og
$$
H_2(x) = \int \int h(x) \, dx
$$
altså funktionen $h$ integreret to gange.

**Bevis**

1.  
$$
f''(x) = h(x)
$$
idet $y = f(x)$.

2.  
$$
\int f''(x) \, dx = \int h(x) \, dx
$$

Der integreres på begge sider af lighedstegnet.

3.  
$$
f'(x) = H_1(x) + k_1
$$

Vi kalder stamfunktionen til $h$ for $H_1$, fordi der integreres én gang.

4.  
$$
\int f'(x) \, dx = \int H_1(x) \, dx + \int k_1 \, dx
$$

Der integreres én gang mere.

5.  
$$
f(x) = \int H_1(x) \, dx + \int k_1 \, dx
$$

Reglen for integration af en sum anvendes.

6.  
$$
y = f(x) = H_2(x) + k_1 x + k_2
$$

De to integraler løses, og de to udløste konstanter samles i en fælles konstant $k_2$. Vi genindfører betegnelsen $y = f(x)$.

Q.E.D.

<div class = "pagebreak"></div>

## Proof y'' = k

**Sætning**

Differentialligningen $y'' = k$ har den fuldstændige løsning
$$
y = kx^2 + k_1 x + k_2
$$
hvor $k$, $k_1$ og $k_2$ er vilkårlige konstanter.

**Bevis**

1.  
$$
\int y'' \, dx = \int k \, dx
$$

Integration på begge sider af lighedstegnet.

2.  
$$
y' = kx + k_1
$$

Integralerne løses.

3.  
$$
\int y' \, dx = \int (kx + k_1) \, dx
$$

Integration på begge sider af lighedstegnet for anden gang.

4.  
$$
y = kx^2 + k_1 x + k_2
$$

Q.E.D.
