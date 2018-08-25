# MALib
MALib is an open-source dataset that can be used to recommend new third-party libraries for mobile app development.
## Content
Similar to classical recommendation databases, MALib contains three table / files, namely Apks.csv, Libs.csv and Relation.csv respectively.

## Data Format
### Libs.csv
|Column 1|Column 2|column 3
|---|---|---|
|Library Id|Library Name|Standard Package|

### Apks.csv
|Column 1|Column 2|column 3
|---|---|---|
|App Id|Apk filename|Category|

### Relation.csv
|Column 1|Column 2|column 3
|---|---|---|
|App Id|Library Id|Relations|

Relations is always 1 as we only include the positive invoking relation.
