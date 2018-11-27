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
  ["Tino Kreutzer"," York University"  ],
  ["Prativa Baral"," York University"  ],
  ["Bobi Morris"," International Rescue Committee"  ],
  ["William Martin"," Catholic Relief Services"  ],
  ["Ruwan Rataynake"," London School of Hygiene & Tropical Medicine"  ],
  ["Paula Tenaglia"," Action Against Hunger"  ],
  ["Kusum Hachhethu"," World Food Program (mVAM)"  ],
  ["Sandie Walton-Ellery"," ACAPS"  ],
  ["Richard Matthew"," University of California - Irvine"  ],
  ["Jochen Schubert"," University of California - Irvine"  ],
  ["Sifat Reazi"," University of California - Irvine"  ],
  ["Lauren Bateman"," IFRC"  ],
  ["Patrick Vinck"," Harvard Humanitarian Initiative"  ],
  ["Pavel Nabutovsky"," Quoin Inc."  ],
  ["Chris Houston"," Grand Challenges Canada"  ],
  ["Cecilie Hestbæk"," Elrha"  ],
  ["Dan Joseph"," IFRC"  ],
  ["Daliah Adler"," York University"  ],
  ["Syed Imran Ali"," York University"  ],
  ["Aijun An"," York University"  ],
  ["Ali Asgary"," York University"  ],
  ["Mazyar Fallah"," York University"  ],
  ["Raphael Aguiar"," York University"  ],
  ["Parke Godfrey"," York University"  ],
  ["Michaela Hynie"," York University"  ],
  ["Rahmah Khalid"," York University"  ],
  ["Usman Khan"," York University"  ],
  ["James Orbinski"," York University"  ],
  ["Spiros Pagiatakis"," York University"  ],
  ["Quazi Rahman"," York University"  ],
  ["Steven Wang"," York University"  ],
  ["Mary Wiktorowicz"," York University"  ],
  ["Oren Jalon"," Independent"  ],
  ["Ben Harvey"," UNHCR"  ],
  ["Jennie Phillips"," University of Toronto"  ],
  ["Mathieu Poirier"," York University"  ],
  ["Aria Ilyad Ahmad"," York University"  ],
  ["Mark Adkins"," York University"  ],
  ["Georges Monette"," York University"  ],
  ["Elena Chopyak"," International Rescue Committee"  ],
  ["Manos Papagelis"," York University"  ],
  ["Seyed Moghadas"," York University"  ],
  ["Jana Daher"," Action Against Hunger"  ],
  ["Farzaneh Heidari"," York University"  ],
  ["Xuan Li"," York University"  ],
  ["Tilemachos Pechlivanoglou"," York University"  ],
  ["Francois Claveau"," Université de Sherbrooke"  ],
  ["Fatima Mussa"," York University"  ],
  ["Catherine Pagiatakis"," National Research Council Canada"  ],
  ["Guillaume Dandurand"," Université de Sherbrooke"  ],
  ["Jean-Francois Dubé"," Université de Sherbrooke"  ],
  ["Gautham Krishnaraj"," Humanitarian Health Ethics Research Group & Field Innovation Team"  ],
  ["Victoria Sauveplane"," University of Toronto"  ]
]

array.sort(function(a, b) {
    var textA = a[0].toUpperCase();
    var textB = b[0].toUpperCase();
    return (textA < textB) ? -1 : (textA > textB) ? 1 : 0;
});

var x = document.getElementById("row");
for (let i = 0; i < array.length; i++) {
    var div = document.createElement('div');
    div.className = "4u boxes";
    
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


