---
layout: page
title: Testing Participants Page
description: This is a test page.
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
---
<h1>Participants</h1>

<div id="participants"></div>

<script>
var array = [
  ["Tino Kreutzer"," DIGHR"  ],
  ["Prativa Baral"," York University"  ],
  ["Bobi Morris"," International Rescue Committee"  ],
  ["William Martin"," Catholic Relief Services"  ],
  ["Ruwan Rataynake"," London School of Hygiene & Tropical Medicine"  ],
  ["Paula Tenaglia"," ACF Canada"  ],
  ["Kusum Hachhethu"," WFP"  ],
  ["Sandie Walton-Ellery"," ACAPS"  ],
  ["Richard Matthew"," University of California - Irvine"  ],
  ["Jochen Schubert"," University of California - Irvine"  ],
  ["Sifat Reazi"," University of California - Irvine"  ],
  ["Lauren Bateman"," George Washington University"  ],
  ["Patrick Vinck"," Harvard Humanitarian Initiative"  ],
  ["Pavel Nabutovsky"," Quoin"  ],
  ["Chris Houston"," Grand Challenges Canad"  ],
  ["Cecilie Hestbæk"," Elrha"  ],
  ["Dan Joseph"," American Red Cross"  ],
  ["Daliah Adler"," York University"  ],
  ["Syed Imran Ali"," Dahdaleh Institute for Global Health Research"  ],
  ["Ali Asgary"," York University"  ],
  ["Mazyar Fallah"," York University"  ],
  ["Raphael Aguiar"," York University"  ],
  ["Parke Godfrey"," York University"  ]
]

var list = document.createElement('ul');
for (let i = 0; i < array.length; i++) {
    var item = document.createElement('li');
    item.appendChild(document.createTextNode(array[i][0] + " from " + array[i][1]));
    list.appendChild(item);
}

document.getElementById('participants').appendChild(list);
</script>