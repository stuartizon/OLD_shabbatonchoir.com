---
layout: page
title: Music
albums: 
 - name: Anim Z'mirot
   year: 2016
   description: The Commemorative 25th Anniversary Album featuring 13 original compositions by the Choir's Former Musical Director Stephen Levey.
 - name: Bilvavi
   year: 2006
   description: The raison d’être of the choir is to “sing a new song” and the new CD follows in this tradition. It is a synthesis of old and contemporary Jewish liturgical and folk music. The CD features the well known synagogue pieces, “Tsadik Katamar” and “Uv’nucho Yomar”. A new arrangement of the Pesach prayer “Tal” and also the title track “Bilvavi” are both contemporary pieces written by the choir’s musical director Stephen Levey. Amongst the other pieces are the beautiful Talmon “Ein Keloheinu”, the evocative “Lo Teida Milchama” and an up beat arrangement of “Shehecheyanu”.
 - name: Shir Chadash 
   year: 2003
   description: The Shabbaton Choir plays to packed houses in concert; performing before thousands of people each year. Now you can bring the sound of the Shabbaton Choir into your living rooms. Recorded at studios in London this CD contains some of the Choir's best known concert repertoire and features soloists Lionel Rosenfeld and Shimon Craimer. The CD encapsulates the distinctive style of Jewish music as performed by the Shabbaton Choir. Many of the pieces are arranged by Stephen Glass and sung in the inimitable "Shabbaton style". From the modern to the old; the soft to the loud, the devotional to the celebratory this CD has something for everyone.
 - name: Shabbaton Sings Reuth
 - name: Selichot Live
   year: 2001
   description: Recorded in front of a packed Holy Law South Broughton Congregation in Manchester, this CD combines the talents of the Shabbaton Choir with soloists Lionel Rosenfeld and Shimon Craimer. The CD captures the atmosphere of the United Synagogue's Choral Midnight Selichot Service for which the Shabbaton Choir has become internationally renowned.


---

<div class="flex flex-wrap">
{%- for a in albums -%}
    {% include album name: a.name year: a.year description: a.description %}
{%- endfor -%}
</div>