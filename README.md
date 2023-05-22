# feel-covid-db
* **defaultdb_public_country**: Contains a country name and a country id. Every datapoint is corrolated by the country id, which is only Israel. 

* **defaultdb_public_daily_ird**: Contains daily datapoints with information regarding IRD - **I**nfected, **R**ecovered and **D**eceased

* **defaultdb_public_daily_test_amount**: Contains daily datapoints with information regarding covid tests.

* **defaultdb_public_daily_vaccination**: Contains daily datapoints with information regarding covid vaccinations.

* **defaultdb_public_hourly_update**: Contains hourly reports that were published by Israel's MOH. Early datapoints were collected manually from MOH's Telegram channel, and later from MOH's offical website.

* **defaultdb_public_migrations**:  Contains info regarding migrations executed by TypeORM in `feel-covid-backend`.
