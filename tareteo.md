#### 3
### Edició avançada

#### Emojis

Si la taula de caracters de la nostra màquina accepta emojis, els podem incloure :star:.

Tingueu present que es mostraràn si l'equip visualitzador en disposa. Si el conversor
de PDF's no el té, no els mostrarà :star:.

#### Integrar HTML

Markdown serveix per generar contingut, no per formatar-lo, per tant integrar HTML
dintre de markdown pot donar problemes.

Això no vol dir que no es pugui fer servir . Tot i que el parser de [dillinger.io](https://dillinger.io/) no ho
mostri bé, quan ho pasem a PDF, es mostra el text ben formatat

- Nivells
  
  <h4>Nivell 4 de capçalera d'HTML</h4>
- Negreta <b>Negreta en HTML</b>
- Subindexos i superindexos 2<sub>16</sub><sup>4</sup>

#### Llenguatges

##### Shell

Escriure comandes de shell, dintre de markdown

Amb triples cometes invertides "\`\`\`", seguit de "sh/bash". Per tancar el paragraf,
triples cometes invertides.

```sh

for ((i=0;i<$(($TOTAL));i++)); do MAC_ADDR=`echo ${MACS{$i}`; echo `wget -qO-
http://api.macvendors.com/$MAC_ADDR`; done

```

##### Notes

Amb el simbol matemàtic "major que" >

> Això es un quadre de notes Mentre posi linies amb el "major que" continuarà la
nota Quan vulgui acabar, deixaré un espai entre aquest paragraf i el següent.

##### HTML

Igual que shell/bash, comencem amb "\`\`\`" Segut de "HTML", per iniciar el paragraf, \`\`\`
per acabar-lo.

```HTML

<H4>Nivell 4 de capçalera d'HTML</H4>
<strong>Negreta en HTML</strong>
2<sub>16</sub><sup>4</sup>

```

#### Altres formats

Amb altres plugins es poden integrar altres formats. Es cosa vostra que investigueu, i
els descobriu.

#### Referències

Posant entre [ ] el text alternatiu que vull que aparegui, i a continuació, entre ( ),
l'hipervincle:

[Procastrination time] (https://www.asciimation.co.nz/#)

Puc carregar imatges externes i posar-hi hipervincles:

Format: \[!\[TextAlternatiu](HipervincleDeLaImatge)](HipervincleWeb)

Exemple:

[![TextAlternatiu](https://thumbs.dreamstime.com/z/creative-illustration-pixel-glasses-thug-life-meme-background-ghetto-lifestyle-culture-art-design-mock-up-template-144857468.jpg)](https://www.itb.cat/)

Puc fer referencies internes des de els estils de nivells (#, ##, etc..)

Exemple:

[Taules](#taules)

Altres referencies.

Es pot fer un recull de referencies. Es pot crear de manera genèrica i després cridala dintre del document

- Creació: [NomIntern]: \<Link\>. El resultat no es mostra al document renderitzat, però es pot cridar: [Bettlejuice]: <https://static2.srcdn.com/wordpress/wp-content/uploads/2020/10/Beetlejuice-SM.jpg>, [Bettlejuice]: <https://static2.srcdn.com/wordpress/wp-content/uploads/2020/10/Beetlejuice-SM.jpg>, [Bettlejuice!!!!!]: <https://static2.srcdn.com/wordpress/wp-content/uploads/2020/10/Beetlejuice-SM.jpg> Canviant un cop la referencia interna, em canvia totes les referencies al document.

#### Comentaris

Els comentaris, apareixeràn en el document .md (extensió per defecte de markdown),
però no en el document renderitzat. Podeu, així, descarregar la vostra ira capa
l'equip docent, per fer-vos fer la documentació en Markdown, però aquest no la podrà
veure.... (Esteu segurs???)

Format: [//]: # (Llista de improperis per qualificar l'equip docent... Aneu amb compte
amb els salts de linia, que després hi han zeros...)

#### 4

### Bibliografia

[Getting started with MarkDown](https://www.markdownguide.org/getting-started/)


















