# AH-Database


### Notes

* Set your item prices in the items.csv file (see below)


### Item Database

* Item data is stored in *items.csv*
* *items.csv* is just a simple text file that you can edit with excel
* You can change many properties be editing the *items.csv.* manually with notepad++

| column   | description                     | value             |
| ---------|---------------------------------|-------------------|
| itemid   | unique item id                  | integer >=0       |
| name     | item name                       | string            |
| sell01   | sell single?                    | 1=true            |
| buy01    | buy single?                     | 1=true            |
| price01  | price for single                | 100               |
| stock01  | restock count (single)          | 15                |
| rate01   | buy rate (single) **not used**  | 1                 |
| sell12   | sell stack?                     | 1=true            |
| buy12    | buy stack?                      | 1=true            |
| price12  | price for stack                 | 100               |
| stock12  | restock count (stack)           | 1                 |
| rate12   | buy rate (stack) **not used**   | 1                 |


##### Sample

| itemid | name               | sell01 | buy01 | price01 | stock01 | rate01 | sell12 | buy12 | price12 | stock12 | rate12 |
|--------|--------------------|--------|-------|---------|---------|--------|--------|-------|---------|---------|--------|
| 2      | Simple Bed         | 1      | 1     | 100     | 15      | 1      | 1      | 1     | 100     | 10      | 1      |
| 3      | Oak Bed            | 1      | 1     | 100     | 15      | 1      | 1      | 1     | 100     | 10      | 1      |
| 1200   | Eastern Pottery    | 1      | 1     | 100     | 15      | 1      | 1      | 1     | 100     | 10      | 1      |
| 1201   | Southern Mummy     | 1      | 1     | 100     | 15      | 1      | 1      | 1     | 100     | 10      | 1      |
| 1462   | Lancewood Lbr      | 1      | 1     | 100     | 15      | 1      | 1      | 1     | 100     | 10      | 1      |
| 1463   | Chronos Tooth      | 1      | 1     | 100     | 15      | 1      | 1      | 1     | 100     | 10      | 1      |
| 1703   | Kunwu Ore          | 1      | 1     | 100     | 15      | 1      | 1      | 1     | 100     | 10      | 1      |
| 1704   | Kunwu Iron         | 1      | 1     | 100     | 15      | 1      | 1      | 1     | 100     | 10      | 1      |
