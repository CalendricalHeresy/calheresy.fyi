---
layout: page
title:  "Data for my University Funding Post"
---

Data and tables used for my post on university funding in Germany

---

Download the data here:
- [Combined Dataset](/assets/uni_funding/data.csv)
- [Student Dataset](https://genesis.destatis.de/datenbank/online/table/21311-0002/)
- [Funding Dataset](/assets/uni_funding/funding.csv)

---

## Tables


| Name                     | Explanation                    |
| ------------------------ | ------------------------------ |
| hochschul_name           | Name of the University         |
| Ausgaben                 | Expenses (in 1000 Euros)            |
| Studierende              | Students                       |
| ausgabenprostudi_rounded | Expenses per student (rounded, in Euros) |

---

{% include tables.html src="/assets/uni_funding/data.csv" hide="hochschul_code, art_code, ausgabenprostudi" %}