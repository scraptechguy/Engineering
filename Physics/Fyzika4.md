## Kapitoly

#### <a href="https://github.com/scraptechguy/Engineering/blob/main/Physics/Fyzika4.md#">Elektricky naboj a jeho vlastnosti</a>
+ <a href="https://github.com/scraptechguy/Engineering/blob/main/Physics/Fyzika4.md#coulombuv-zakon">Coulombuv zakon</a>
+ <a href="https://github.com/scraptechguy/Engineering/blob/main/Physics/Fyzika4.md#intenzita-elektrickeho-pole">Intenzita elektrickeho pole</a>
+ <a href="https://github.com/scraptechguy/Engineering/blob/main/Physics/Fyzika4.md#prace-v-homogennim-elektrickem-poli">Prace v homogennim elektrickem poli</a>
+ <a href="https://github.com/scraptechguy/Engineering/blob/main/Physics/Fyzika4.md#elektricky-potencial">Elektricky potencial</a>

# Elektricky naboj a jeho vlastnosti

...

## Coulombuv zakon

```
        Q1 * Q2
Fe = k ---------
          r^2
```

... Velikost elektricke sily `Fe` je primo umerna soucinu bodovych naboju `Q1` a `Q2` a neprimo umerna druhe mocnine jejich vzdalenosti

**Konstanta umernosti** `k` je zavisla na prostredi, v nemz na sebe naboje pusobi ...

```
         1
k = ------------
     4pi * etha
```

... kde `etha` je **permitivita prostredi** (pro vakuum je to **8,854e-12 C^2 * N^-1 * m^-2**)

***

Priklady

```
1. Jaka je vzajemna vzdalenost dvou bodovych naboju 10 microC, ktere na sebe pusobi ve vakuu silou 10 N?
```

<details>
<summary>
  Reseni
</summary>

```
        Q1 * Q2
Fe = k ---------
          r^2

r^2 = 
```

</details>

## Intenzita elektrickeho pole

Vektorova velicina charakterizujici elektricke pole ...

```
     Fe
E = ----
     +Q`
```

... intenzita elektrickeho pole je definovana podilem elektricke sily `Fe`, ktera pusobi na kladny bodovy elektricky naboj `Q` v danem miste pole a velikosti toho naboje `Q`

> Smer vektoru intenzity elektrickeho pole `E` je stejny, jako smer vektoru elektricke sily `Fe`

<div align="center">
    <img src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fkvinta-html.wz.cz%2Ffyzika%2Felektrina_a_magnetismus%2Felektricky_naboj_a_elektricke_pole%2Fobrazky%2F03.gif&f=1&nofb=1&ipt=90fff2737ff357cc3fc6adec20ed8485ecf58a3f087f3da8e127a203fc813e4e&ipo=images">

Znazornena intenzita elektrickeho pole
</div>

+ Vzajemne silove pusobeni se uskutecnuje prostrednictvim elektrickeho pole, elektricke pole je v okoli elektricky nabiteho telesa

```
       Q
E = k ---
      r^2
```

... intenzita elektrickeho pole se s rostouci vzdalenosti snizuje

### Modely elektrickych poli

Radialni 
Homogeni

Silocarovy

Vlastnosti silocar elektrickeho pole
```
1. jsou spojite, zacinaji v kladnem naboji a konci v zapornem, pri osamocenem naboji ne pri dvojici naboju se stejnym znamenkem se rozbihaji do nekonecna
2. jsou kolme k povrchu nabiteho telesa
3. navzajem se neprotinaji
```

## Prace v homogennim elektrickem poli

Pri premisteni naboje v homogennim poli elektricka sila kona praci `W` ...

```
Fe = Q * E
W = Fe * (d1 - d2)
W = Q * E * d
```
... kde `Q` je naboj, `E` intenzita elektrickeho pole a `d` vzdalenost bodu od zaporne desky

+ Vykonana prace nezavisi na delce trajektorie, ale na vzdalenosti `d`

### Energie bodoveho naboje v elektrickem poli

Elektricka potencialni energie `Ep` naboje `Q` v urcitem miste elektrickeho pole

```
W = QEd
W = Ep
```

+ Elektricka potencialni energie = prace elektrickych sil

## Elektricky potencial

Castice s elektrickym nabojem v elektrickem poli ma potencialni energii `Ep` ...

... elektricky potencial definujeme jako podil elektricke potencialni energie kladneho elektrickeho naboje `Q` v tomto bode pole a velikosti tohoto naboje ...

```
      Ep
fi = ----
      Q
```

... kde jednotkou elektrickeho potencialu `fi` je `joule / coulomb` neboli **`volt`**

```
fi = E * d
```

+ Mnozina bodu elektricho pole se stejnym elektrickym potencialem se nazyva ekvipotencialni plocha

> Elektricky potencial klesa smerem k zaporne desce

## Elektricke napeti

Aboslutni hodnota rozdilu potencialu mezi dvema body elektrickeho pole je elektricke napeti ...

```
U = |fi2 - fi1|
```

Elektricke napeti mezi kladnou a zapornou deskou je take rovno soucinu intenzity pole a vzdalenosti desek ...

```
U = E * d
```

Prace elektrickych sil pri prenaseni naboje `Q` mezi dvema body, mezi nimiz je napeti `U` ...

```
W = Q * U
```

## Ohmuv zakon pro uzavreny obvod

+ **Vnejsi cast** obvodu tvori rezistory, vodice a spotrebice

+ **Vnitrni cast** obvodu tvori vodivy prostor mezi poly uvnitr zdroje

Energie vydana zdroje se premenuje na energii ve vnejsi a vnitrni casti obvodu ...

```
Ue = U + Ui
```

... soucet napeti na vnejsi a vnitrni casti elektrickeho obvodu se rovna elektromotorickemu napeti zdroje

**Ohmuv zakon pro uzavreny obvod**... 

```
      Ue
I = -------
    R + Ri
```

... proud v uzavrenem obvodu se rovna podilu elektoromtorickeho napeti zdroje a souctu odporu vnejsi a vnitrni casti obvodu

Zatizeny zdroj ...

```
U = Ue - Ri * I
```

... pri zatizenem zdroji je svorkove napeti `U` mensi nez elektromotoricke napeti zdroje `Ue`

Spojeni nakratko (zkrat) ...

```
            Ue
I = Imax = ----
            Ri
```

... pri zkratu je odpor vnejsi casti temer nulovy, proud v obvodu dosahuje nejvetsi moznou hodnotu

## Razeni rezistoru

+ **Seriove razeni rezistoru** - seriove lze radit libovolny pocet rezistoru, celkovy odpor se vypocita jako soucet vsech odporu

+ **Paralelni razeni rezistoru** - misto kde se potkava vice vodicu se jmenuje uzel

