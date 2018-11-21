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

<div id="participants"></div>

<script>
var array = [
  ["Tino Kreutzer"," York University"  ],
  ["Prativa Baral"," York University"  ],
  ["Bobi Morris"," International Rescue Committee"  ],
  ["William Martin"," Catholic Relief Services"  ],
  ["Ruwan Rataynake"," London School of Hygiene & Tropical Medicine"  ],
  ["Paula Tenaglia"," Action Against Hunger Canada"  ],
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
  ["Ali Asgary"," York University"  ],
  ["Mazyar Fallah"," York University"  ],
  ["Raphael Aguiar"," York University"  ],
  ["Parke Godfrey"," York University"  ]
]

array.sort(function(a, b) {
    var textA = a[0].toUpperCase();
    var textB = b[0].toUpperCase();
    return (textA < textB) ? -1 : (textA > textB) ? 1 : 0;
});

var list = document.createElement('ul');
for (let i = 0; i < array.length; i++) {
    var item = document.createElement('li');
    item.appendChild(document.createTextNode(array[i][0] + ", " + array[i][1]));
    list.appendChild(item);
}

document.getElementById('participants').appendChild(list);
</script>