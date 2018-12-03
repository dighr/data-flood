---
layout: page
title: Participants
description: All the participants in the event.
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
---
<h1>Participants</h1>

<div id="row" class="row">

</div>


<script>
var array = [
  ["Mark Adkins"," York University"  ],
  ["Daliah Adler"," York University"  ],
  ["Raphael Aguiar"," York University"  ],
  ["Syed Imran Ali"," York University"  ],
  ["Nasser Alsadhan"," Queen's University"  ],
  ["Aijun An"," York University"  ],
  ["Matt Arnold"," York University"  ],
  ["Ali Asgary"," York University"  ],
  ["Prativa Baral"," York University"  ],
  ["Lauren Bateman"," American Red Cross"  ],
  ["Anna Bellos"," Global Public Health Consultant"  ],
  ["Eden Burton"," Seneca College"  ],
  ["Elena Chopyak"," International Rescue Committee"  ],
  ["Francois Claveau"," Université de Sherbrooke"  ],
  ["Michelle Cochrane"," Groundswell Projects"  ],
  ["J.L. Crosbie"," MSF Canada"  ],
  ["Jana Daher"," Action Against Hunger"  ],
  ["Deborah Damaso"," York University"  ],
  ["Guillaume Dandurand"," Université de Sherbrooke"  ],
  ["Heidar Davoudi"," York University"  ],
  ["Aaron de Mello"," Full Stack Developer"  ],
  ["Theresa Dinh"," York University"  ],
  ["Robert DiRaddo"," National Research Council Canada"  ],
  ["Jean-Francois Dubé"," Université de Sherbrooke"  ],
  ["Donna Dupont"," Purple Compass"  ],
  ["Tarek Elgebely"," OCHA"  ],
  ["Mazyar Fallah"," York University"  ],
  ["Elena Gianni"," The New York Times"  ],
  ["Tamara Glazer"," University of Chicago"  ],
  ["Parke Godfrey"," York University"  ],
  ["Gabriela Gonzalez Martinez"," York University"  ],
  ["Emmanuel Guillard"," MSF Canada"  ],
  ["Kusum Hachhethu"," World Food Programme"  ],
  ["Ben Harvey"," UNHCR"  ],
  ["Farzaneh Heidari"," York University"  ],
  ["Cecilie Hestbæk"," Elrha"  ],
  ["Chris Houston"," Grand Challenges Canada"  ],
  ["Jimmy Huang"," York University"  ],
  ["Michaela Hynie"," York University"  ],
  ["Aria Ilyad Ahmad"," York University"  ],
  ["Oren Jalon"," Independent Consultant"  ],
  ["Dan Joseph"," American Red Cross"  ],
  ["Rahmah Khalid"," York University"  ],
  ["Usman Khan"," York University"  ],
  ["Netta Kornberg"," York University"  ],
  ["Tino Kreutzer"," York University"  ],
  ["Gautham Krishnaraj"," McMaster University"  ],
  ["Xuan Li"," York University"  ],
  ["James Madhier"," Rainmaker Enterprise"  ],
  ["Maxym Malynowsky"," REACH"  ],
  ["Mikaela Maquiling"," York University"  ],
  ["William Martin"," Catholic Relief Services"  ],
  ["Richard Matthew"," University of California - Irvine"  ],
  ["Seyed Moghadas"," York University"  ],
  ["Georges Monette"," York University"  ],
  ["Bobi Morris"," International Rescue Committee"  ],
  ["Michael Moszczynski"," ImmerLearn"  ],
  ["Fatima Mussa"," CIHR-IPPH"  ],
  ["Pavel Nabutovsky"," Quoin Inc."  ],
  ["James Orbinski"," York University"  ],
  ["Serafima Ostrovskaya"," Pivotal"  ],
  ["Spiros Pagiatakis"," York University"  ],
  ["Catherine Pagiatakis"," National Research Council Canada"  ],
  ["Manos Papagelis"," York University"  ],
  ["Asma Paracha"," Seneca College"  ],
  ["Tilemachos Pechlivanoglou"," York University"  ],
  ["Jennie Phillips"," University of Toronto"  ],
  ["Mathieu Poirier"," Global Strategy Lab"  ],
  ["Peter Potsepp"," Canadian Red Cross"  ],
  ["Josephene pynadath"," Pivotal"  ],
  ["Quazi Rahman"," York University"  ],
  ["Ruwan Rataynake"," London School of Hygiene & Tropical Medicine"  ],
  ["Sifat Reazi"," University of California - Irvine"  ],
  ["Eileen Santiago"," York University"  ],
  ["Victoria Sauveplane"," University of Toronto"  ],
  ["Fatima Sayedi"," York University"  ],
  ["Jochen Schubert"," University of California - Irvine"  ],
  ["Daniel Sellen"," University of Toronto"  ],
  ["Harpreet Singh"," York University"  ],
  ["Patrick Vinck"," Harvard Humanitarian Initiative"  ],
  ["Edmond Wach"," CartONG"  ],
  ["Sandie Walton-Ellery"," ACAPS"  ],
  ["Steven Wang"," York University"  ],
  ["Mary Wiktorowicz"," York University"  ]
]

array.sort(function(a, b) {
    var textA = a[0].toUpperCase();
    var textB = b[0].toUpperCase();
    return (textA < textB) ? -1 : (textA > textB) ? 1 : 0;
});

var x = document.getElementById("row");
for (let i = 0; i < array.length; i++) {
    var div = document.createElement('div');
    div.className = "4u 12u$(small)";
    div.classList.add("boxes");
    
    var item = document.createElement('span');
    item.className = "name";
    item.appendChild(document.createTextNode(array[i][0]));
    item.appendChild(document.createElement("br"));
    div.appendChild(item);
    
    var org = document.createElement('span');
    org.className = "org";
    org.appendChild(document.createTextNode(array[i][1]));
    div.appendChild(org);
   
    x.appendChild(div);
}
</script>


