instryktsiya po rabote s git

## chto takoe git
Samaya popylyarnaya realizatsiay raspredelennoi sistemu kontrolya versii (versionnost poddergivaetsya i na servere, i y kagdogo klienta). Samoi rasprostranennoi realizatsiei ***GIT*** yavlyaetsya (GitHub) [https.//github.com]

## podgotovka repozitoriya. 
dlya sozdaniay reprozitoriya sozdaetsya komanda *git init*. dlya etogo neobxodimo otkrut v terminale papky s bydyshem repozitoriem i napisat *git init*  
dobavlenie faila {gruzdeva.ru}
## sozdanie kommitov.
dlya etogo nygno vupolnit 2 komandu *git add* readme.md dobavlyaem vse izmenennue failu v index. i 2 komanda sozdaet commit *git commit -m "commit massege"*


### Dobavlenie failov k komity. 
Dlua dobavleniya faila k komity ispolzyetsya komanda *git add*. ispolzyetsya ona sledyushim obrazom: v terminale s papkoi-reprozitoriem pishem *git add <nazvanie faila>*

## peremeshenie megdy "commitami" 
dlya togo chtobu perevodit s odnoi na drygyu vetky nygno nabrat komandy *git checkout* i imya vetki kyda xochesh pereiti.


## vetki v git 
Dlya togo chtobu sdelat novoe otvetvlenie ot vetki *master* neobxodimo vvesti komandy *git branch new_branch <imya vetki>* 
Zatem pereklychites na novyu vetky s pomosh.u komandu *git checkout*.


## sliyanir vetok i konflikt comitov
osnovnaya comanda sliyaniay *git merge* Nygno naxoditsya v chistvike, kyda xochesh vlit novui fail. Pri konflikte ybiraem v rychnyu galochki v i = i delaem pravki. ili vubiraem nygnyu ili predlogennux variantov.

### Prosmotr spiska vetok
Dlya prosmotra spiska vetok ispolzuetsya komanda *git branch*
Vudelennaya zelenoi zvevdochka vetka- eto vetka, v dannui moment na kotoroi mu naxodimsya.