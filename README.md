# circus_analytics
Repository Containing End to End DBT Circus analytics pipelines 

Links to Looker Dashboard : 

Finance View  : https://lookerstudio.google.com/reporting/5a0c6966-2c79-419a-acf5-1cf39ee2815d

Marketing View : https://lookerstudio.google.com/u/0/reporting/3af541dc-d8cc-4509-85d7-efcc08df5a8e/page/yHlaF/edit

Operations View : TBA

## 📁 Project Structure

```bash
.
├── models/
│   ├── staging/
│   │   └── tbl_stg_order.sql
│   ├── curated/
│   │   ├── dimensions/
│   │   │   └── tbl_dim_order.sql
│   │   └── facts/
│   │       └── tbl_fact_order_details.sql
│   └── schema.yml
├── macros/
│   └── tests/
│       └── date_not_future.sql
├── tests/
│   └── test_order_date_not_future.sql
├── README.md
└── dbt_project.yml
```


## 📁 DBT Datapipeline achitecture 
<img width="707" height="344" alt="image" src="https://github.com/user-attachments/assets/0b259819-865b-4a7c-a5d3-dd428c618310" />

