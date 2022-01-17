## Betrachte die folgenden Aussagen:

$A$: Die Zahl $a$ ist gerade.

$B$: $a^2$ ist gerade.

Dann ist:

$\neg A$: $a$ ist nicht gerade ($a$ ist ungerade).

$\neg B$: $a^2$ ist nicht gerade ($a^2$ ist ungerade).

## Welche Aussagen können wir überprüfen?

$A \Rightarrow B$ : Wenn $a$ gerade ist, dann ist $a^2$ gerade. 

Scheint zu stimmen. 

$A \Rightarrow \neg B$: Wenn $a$ gerade ist, dann ist $a^2$ nicht gerade.

Das ist offensichtlich falsch, denn $2$ ist gerade, aber $2^2=4$ ist auch gerade.

$\neg A \Rightarrow B$: Wenn $a$ ungerade ist, dann ist $a^2$ gerade.

Das ist offensichtlich falsch, denn $1$ ist gerade, aber $1^2=1$ ist nicht gerade.

$\neg A \Rightarrow \neg B$: Wenn $a$ ungerade, dann ist $a^2$ ungerade.

Das scheint wieder zu stimmen. 

$B \Rightarrow A$: Wenn $a^2$ gerade ist, dann ist $a$ gerade.

Scheint zu stimmen.

$B \Rightarrow \neg A$: Wenn $a^2$ gerade ist, dann ist $a$ ungerade.

Ist falsch, denn $2^2=4$ ist gerade, aber $2$ ist auch gerade.

$\neg B \Rightarrow A$: Wenn $a^2$ ungerade ist, dann ist $a$ gerade. 

Ist falsch, denn $1^2=1$ ist ungerade, aber $a$ ist auch ungerade.

$\neg B \Rightarrow \neg A$: Wenn $a^2$ ungerade ist, dann ist auch $a$ ungerade.

Das scheint wieder korrekt zu sein.

### Wir haben also folgende Aussagen, die uns wahr erscheinen:

1. $A \Rightarrow B$

2. $\neg A \Rightarrow \neg B$

3. $B \Rightarrow A$

4. $\neg B \Rightarrow \neg B$

Das können wir in einer einzigen Aussage zusammenfassen:

$A \Leftrightarrow B$ : **$a$ ist genau dann gerade, wenn $a^2$ gerade ist.** 

Das Theorem hat noch drei äquivalente Formulierungen:

1. $a^2$ ist genau dann gerade, wenn $a$ gerade ist.

2. $a$ ist genau dann ungerade, wenn $a^2$ ungerade ist.

3. $a^2$ ist genau dann ungerade, wenn $a$ ungerade ist.

*Überleg dir, warum alle vier Formulierungen dieselbe Aussage beschreiben!*

## Warum ist das Theorem eigentlich wahr?

Intuitiv scheint die Sache klar zu sein.

Man kann es ganz einfach praktisch ausprobieren:

Du nimmst ein Blatt Karopapier und schneidest 2 Quadrate aus:

Einmal z.B. mit Kantenlänge 6 und einmal mit Kantenlänge 7.

Jetzt schneidest du senkrecht und waagrecht jeweils nach jedem 2. Karo ab. Bei 6 bekommst du 9 Quadrate mit Kantenlänge 2 (4 Kästchen). Die kannst du nochmal jeweils halbieren und bekommst insgesamt 18 Schnipsel mit je 2 Kästchen. Das Quadrat hat also gerade viel Kästchen.

Wenn du das Gleiche mit dem 7er Quadrat machst, bekommst du nach dem 1. Schneiden wieder 9 kleine Quadrate mit je 4 Kästchen, 6 Schnipsel mit je 2 Kästchen und einen Schnipsel mit genau 1 Kästchen. 

Nach dem 2. Schneiden (Quadrate halbieren) hast du 24 Schnipsel mit je 2 Kästchen und genau 1 mit einem. Den einen bekommst du nicht weg und kannst ihn auch nicht mit einem anderen Einer zusammenlegen. Das Quadrat hatte also ungerade viele Kästchen.

Das kann man sich natürlich auch aufmalen, aber Schneiden macht mehr Spaß.

## Und jetzt noch der formale Beweis von $A \Leftrightarrow B$

Wir bemerken: 

Eine Zahl $a$ heißt gerade, wenn es eine Zahl $n$ gibt so, dass $a=2n$.

Eine Zahl $a$ heißt ungerade, wenn es eine Zahl $n$ gibt so, dass $a=2n+1$

### Richtung $\Rightarrow$:

Sei  $a=2n$. Dann ist $a^2 = (2n)^2 = 2^2n^2 = 2(2n^2)$ 

mit $m=2n^2$ ist dann $a^2=2m$. Also ist $a^2$ gerade.

### Richtung $\Leftarrow$ :

Die Aussage $B \Rightarrow A$ ist äquivalent zur Aussage $\neg A \Rightarrow \neg B$

Sei $a=2n+1$. Dann ist $a^2=(2n+1)^2=2^2n^2+4n+1 = 2(2n^2+2n)+1$

Mit $m=2n^2+2n$ ist dann  $a^2=2m+1$. Also ist $a^2$ ungerade.








