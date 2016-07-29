# Git af sidtiroulerisch

Butega, wia die Paschgla mit ihre Rechna so a Toal nomens `git`
(ibeasetzt: `Rotzleffl`) heanemm, isch oft lei mea a Casino.
_"Kannsch amo bitte pullen"_ oder _"Hasche schun gepusht"_... Na
fahlts da sauber? So geat des oba echt net.

Oba fia des gibs ja des jetzt!

## So kannat ma sel mochn

| Tuanwort    | Wia mas jetz sog   | Wia mas gscheit sog   |
|-------------|--------------------|-----------------------|
| init        | initten            | semaumochn            |
| add         | adden              | zuachn tian           |
| pull        | pullen             | einaziachn            |
| push        | pushen             | ausidruckn            |
| clone       | clonen             | headamit              |
| fetch       | fetchen            | ochahoul              |
| branch      | branchen           | ostia                 |
| commit      | commiten           | heb mo fescht         |
| rebase      | rebasen            | ruck an orsch         |
| diff        | diffen             | magari                |
| merge       | mergen             | zommtian              |
| fork        | forken             | ondosch               |
| stash       | stashen            | gholtau               |
| tag         | tagen              | markier               |
| cherry-pick | cherry-picken      | klaub pfiffra         |
| checkout    | checkouten         | wort amo              |

| Hauptwort     | Wia mas jetz sog   | Wia mas gscheit sog  |
|---------------|--------------------|----------------------|
| git           | git                | Rotzleffl            |
| github        | github             | Rom                  |
| gitlab        | gitlab             | Boazn                |
| repository    | repo               | Speckkellda          |
| branch        | branch             | Ost                  |
| commit        | commit             | augschriebnszuig     |
| log           | log                | Zettl                |
| pull request  | pull request       | Einaziacha           |
| merge request | merge request      | Zommtianer           |
| stash         | stash              | Truch                |
| status        | status             | wiatuats             |
| tag           | tag                | Kartl                |
| origin        | origin             | unfong               |
| master        | master             | Capo                 |

## A poa satzln zum unfong

    - Kannsche mo in ost, den i grad um an orsch umigruckt hob, einaziachn und noch rom ausidruckn?

    - Dofia hob i an neuen speckkellda sem augmocht, sog a "headmit" und nimma da in ost.

    - Na, i druck des glei ausi zum capo im unfong.

    - Ostia, jetz hob i olls aus da truch magari festgholtn.

    - I will einaziachn, wenn du olls zommgetun hosch.

    - Am bestn mia klaubn die pfiffra ausm ost vom capo ausa.

    - Moch amo ondosch in rom.

## Und so nimmsch's hea

Wenns di a imma oschnagglt wenn sidtirouler über `git` redn, dann kannsche des ändern! Schoff bei deina Shell de Sachn un:

    git config --global alias.semaumochn init
    git config --global alias.headamit clone
    git config --global alias.einaziachn pull
    git config --global alias.zuachntian add
    git config --global alias.ausidruckn push
    git config --global alias.ost branch
    git config --global alias.ostia branch
    git config --global alias.habmofescht commit
    git config --global alias.ruckanorsch rebase
    git config --global alias.magari diff
    git config --global alias.zommtian merge
    git config --global alias.gholtau stash
    git config --global alias.markier tag
    git config --global alias.wortamo checkout
    git config --global alias.zettl log
    git config --global alias.wiatuats status

Donna muasche no des zu deina `~/.bashrc` (oda so epas) dazuatian

    alias rotzleffel=git
