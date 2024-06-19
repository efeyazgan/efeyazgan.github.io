---
layout: page
permalink: /publications/
title: publications
description: 
years: [2024, 2023,2022,2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009, 2008, 2007, 2006, 2005, 2004, 2003, 2002, 2001]
nav: true
---

### List of publications from different databases
* [Almost full list of papers from Inspire](https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=yazgan)
* [Preprints in arXiv](https://arxiv.org/search/advanced?advanced=&terms-0-operator=AND&terms-0-term=yazgan&terms-0-field=author&terms-1-operator=NOT&terms-1-term=albayrak&terms-1-field=author&terms-2-operator=NOT&terms-2-term=ege&terms-2-field=author&terms-3-operator=NOT&terms-3-term=chip&terms-3-field=title&terms-4-operator=NOT&terms-4-term=Al-hiyasat&terms-4-field=author&terms-5-operator=NOT&terms-5-term=paladugu&terms-5-field=author&terms-6-operator=NOT&terms-6-term=ayhan+yazgan&terms-6-field=author&terms-7-operator=OR&terms-7-term=%22Theory+of+Collider+Phenomena%22&terms-7-field=title&classification-physics_archives=all&classification-include_cross_list=include&date-filter_by=all_dates&date-year=&date-from_date=&date-to_date=&date-date_type=submitted_date&abstracts=show&size=50&order=-announced_date_first](https://arxiv.org/search/advanced?advanced=&terms-0-operator=AND&terms-0-term=yazgan&terms-0-field=author&terms-1-operator=NOT&terms-1-term=albayrak&terms-1-field=author&terms-2-operator=NOT&terms-2-term=ege&terms-2-field=author&terms-3-operator=NOT&terms-3-term=chip&terms-3-field=title&terms-4-operator=NOT&terms-4-term=Al-hiyasat&terms-4-field=author&terms-5-operator=NOT&terms-5-term=paladugu&terms-5-field=author&terms-6-operator=NOT&terms-6-term=ayhan+yazgan&terms-6-field=author&terms-7-operator=OR&terms-7-term=%22Theory+of+Collider+Phenomena%22&terms-7-field=title&terms-8-operator=NOT&terms-8-term=graf&terms-8-field=author&classification-physics=y&classification-physics_archives=all&classification-include_cross_list=include&date-filter_by=all_dates&date-year=&date-from_date=&date-to_date=&date-date_type=submitted_date&abstracts=show&size=50&order=-announced_date_first)](https://arxiv.org/search/advanced?advanced=&terms-0-operator=AND&terms-0-term=yazgan&terms-0-field=author&terms-1-operator=NOT&terms-1-term=albayrak&terms-1-field=author&terms-2-operator=NOT&terms-2-term=ege&terms-2-field=author&terms-3-operator=NOT&terms-3-term=chip&terms-3-field=title&terms-4-operator=NOT&terms-4-term=Al-hiyasat&terms-4-field=author&terms-5-operator=NOT&terms-5-term=paladugu&terms-5-field=author&terms-6-operator=NOT&terms-6-term=ayhan+yazgan&terms-6-field=author&terms-7-operator=NOT&terms-7-term=melih+yazgan&terms-7-field=author&terms-8-operator=OR&terms-8-term=%22Theory+of+Collider+Phenomena%22&terms-8-field=title&terms-9-operator=NOT&terms-9-term=melih+yazgan&terms-9-field=author&classification-physics_archives=all&classification-include_cross_list=include&date-filter_by=all_dates&date-year=&date-from_date=&date-to_date=&date-date_type=submitted_date&abstracts=show&size=50&order=-announced_date_first))
* [CMS Collaboration preprints in arXiv](https://arxiv.org/search/?query=cms+collaboration&searchtype=author&abstracts=show&order=-announced_date_first&size=50)
* [List of publications from CERN Document Sercer](https://cds.cern.ch/search?ln=en&as=1&m1=e&p1=Yazgan%2C+E.&f1=author&op1=n&m2=e&p2=1975&f2=year&op2=a&m3=a&p3=&f3=&action_search=Search&c=CERN+Document+Server&sf=&so=a&rm=&rg=10&sc=1&of=hb)
* [List of publications from NASA ADS](https://ui.adsabs.harvard.edu/search/q=(%20%20author%3A%22Yazgan%22%20AND%20year%3A2001-2090)&sort=date%20asc%2C%20bibcode%20asc&p_=0)
* [Publications in Zenodo](https://zenodo.org/search?page=1&size=20&q=%22yazgan,%20efe%22)
* [List of publications from Google Scholar](https://scholar.google.ch/citations?hl=en&user=PV7HGdgAAAAJ&view_op=list_works&sortby=pubdate) 

And below is a selected set of publications:

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
