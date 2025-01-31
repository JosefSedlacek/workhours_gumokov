# Workhours
Tato aplikace slouží k úpravě csv souboru Workhours, kde máme pro jednotlivé pracoviště 
nastavené dostupné strojní hodiny a lidské hodiny. Může se zde zaznamenat například 
odstávka výroby, změna ze 3 směnného provozu na dvousměnný a tak dále.

Aplikace je nyní dostupná na [workhours.streamlit.app](https://workhours.streamlit.app/)

## Nahrávání souborů

Nahrajte soubory Workhours (CSV) a Skupiny (Excel). Tyto soubory najdete na:  
`P:\All Access\TB HRA KPIs\podklady\Kapacity`  
Dejte pozor, abyste nahrávali soubor na správné místo - nesmíte nahrát 
Skupiny do pole pro nahrávání Workhours a opačně. Po nahrání se tyto 
tabulky propojí a mělo by se ukázat "Propojení bylo úspěšné". Poté můžete
pokračovat na list "Úprava dat".

---

## Úprava dat

#### 1. Výběr pracoviště
Nejprve vyberte, pro jakou skupinu pracovišť budete nabídku hodin upravovat. 
Můžete vybrat celý výrobní proces (pokud chcete uplatňovat změnu hromadně), 
nebo vybrat skupinu pracovišť nebo vybrat jedno nebo více konkrétních pracovišť.

#### 2. Výběr dnů
Vyberte dny, pro které chcete tyto změny uplatňovat. Pokud nějaké pole zůstane
prázdné tak to program chápe tak, že žádný filtr dat není nastaven. Máte zde 
možnost vybírat pro měsíce nebo pro týdny. 

#### 3. Nastavení nových hodnot. 
Zde napište číslo jak pro lidské, tak pro strojní hodiny. Ve všech řádcích, které
odpovídají vašim zadaným filtrům, se změní hodnoty ve sloupcích Lidské hodiny a 
Strojní hodiny na vámi zadané hodnoty. Nakonec klikněte na `Aktualizovat data` aby
se změna propsala.

---

## Kontrola a stažení nových dat

#### 1. Graf nabídky pro vybrané pracoviště

Tato část slouží pro kontrolu. Zde si můžete vybrat rok a pracoviště a následně 
se vám zobrazí graf - opět můžete vybrat, zda chcete zobrazit hodiny lidské 
nebo strojní.

#### 2. Stažení dat

Až budete s úpravami hotovi, klikněte na `Stáhnout Workhours.csv`. Upravený
soubor najdete ve stažených souborech na vašem PC. Tento soubor poté přetáhněte
do složky:
`P:\All Access\TB HRA KPIs\podklady\Kapacity`
a nahraďte původní soubor tímto novým souborem. 

POZOR: na této adrese `P:\All Access\TB HRA KPIs\podklady\Kapacity` se soubor
musí jmenovat Workhours.csv. Pokud se bude jmenovat jinak, nenačte se do PowerBI.
## Uploading files

Upload the Workhours (CSV) and Groups (Excel) files. These files can be found at:
`P:\All Access\TB HRA KPIs\documents\Capacities`
Be careful to upload the file to the correct location - you must not upload
Groups to the Workhours upload field and vice versa. After uploading, these
tables will be connected and "Connection was successful" should appear. You can then
continue to the "Data editing" sheet.

---

## Data editing

#### 1. Workplace selection
First, select which group of workplaces you will edit the hours offer for.
You can select the entire production process (if you want to apply the change in bulk),
or select a group of workplaces or select one or more specific workplaces.

#### 2. Day selection
Select the days for which you want to apply these changes. If any field remains
empty, the program understands that no data filter is set. You have the option to select for months or weeks.

#### 3. Set new values.
Here, type the number for both human and machine hours. In all rows that
match your specified filters, the values ​​in the Human Hours and
Machine Hours columns will change to the values ​​you specified. Finally, click `Update Data` to
apply the change.

---

## Check and download new data

#### 1. Supply graph for selected workplace

This section is for checking. Here you can select the year and workplace and then
the graph will be displayed - again you can choose whether you want to display human
or machine hours.

#### 2. Download data

When you are finished with the edits, click `Download Workhours.csv`. You can find the edited
file in the downloaded files on your PC. Then drag this file
to the folder:
`P:\All Access\TB HRA KPIs\podklady\Kapacity`
and replace the original file with this new file.

ATTENTION: at this address `P:\All Access\TB HRA KPIs\podklady\Kapacity` the file
must be named Workhours.csv. If it is named differently, it will not be loaded into PowerBI.
