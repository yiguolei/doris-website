---
{
    "title": "USE DATABASE",
    "language": "en"
}
---

<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->




## Description

The USE command allows us to use the database

grammar:

```SQL
USE <[CATALOG_NAME].DATABASE_NAME>
```

illustrate:
1. `USE CATALOG_NAME.DATABASE_NAME` will switch the current catalog into `CATALOG_NAME` and then change the current database into `DATABASE_NAME`

## Examples

1. If the demo database exists in current catalog, try accessing it:

    ```sql
    mysql> use demo;
    Database changed
    ```
2. If the demo database exists in catalog hms_catalog, try switching the catalog and accessing it:

    ```sql
    mysql> use hms_catalog.demo;
    Database changed
    ```

## Keywords

    USE

## Best Practice

