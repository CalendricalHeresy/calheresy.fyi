---
layout: page
title:  "Data for my University Funding Post"
---

Data and tables used for [my post on university funding in Germany]({% post_url 2026-11-18-university-funding-in-germany %}). The data is for 2024 (or 2024/2025 semester when applicable).

---

Download the data here:
- [Combined Dataset](/assets/uni_funding/data.csv)
- [Student Dataset](https://genesis.destatis.de/datenbank/online/table/21311-0002/)
- [Funding Dataset](/assets/uni_funding/funding.csv)

For the full datasets please contact me.

---

## Tables


| Name                     | Explanation                    |
| ------------------------ | ------------------------------ |
| hochschul_name           | Name of the University         |
| Ausgaben                 | Expenses (in 1000 Euros)            |
| Studierende              | Students                       |
| ausgabenprostudi_rounded | Expenses per student (rounded, in Euros) |

The dataset is very inaccurate with data of private universities and colleges and they are not included. Also not included are university hospitals.

The below table is further filtered to only show higher education facilities with over 1000 students.

---

{% include tables.html src="/assets/uni_funding/data1k.csv" hide="hochschul_code, art_code, ausgabenprostudi, changed_funding, changed_studizahl, art_name" %}

Use the column "Type" of the table below in the search above to sort by different types of higher education.


| Type | Name                               | Translation                                  |
| ---- | ---------------------------------- | -------------------------------------------- |
| OU   | Öffentliche Universität            | Public University                            |
| KU   | Kirchliche Universität             | Church University                            |
| UB   | Universität der Bundeswehr         | Military University                          |
| OH   | Öffentliche Hochschule             | Public University of Applied Science/College |
| PH   | Pädagogische Hochschule            | Pedagogic College                            |
| KTH  | Kirchliche Theologische Hochschule | Church Theology College                      |
| KFH  | Kirchliche Fachhochschule          | Church University of Applied Science/College |
| KKH  | Kirchliche Kunsthochschule         | Church Art College                           |
| OKH  | Öffentliche Kunsthochschule        | Public Art College                           |
| VHB  | Verwaltungshochschule Bund         | Federal College for Administration           |
| VHL  | Verwaltungshochschule Länder       | State College for Administration             |

It is important in Germany to differentiate between universities ("Universitäten") and colleges/universities of applied science ("Hochschulen"). The latter are open to people from more backgrounds than universities, but they cannot offer PhD programs.