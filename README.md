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
│   ├── staging_models/
│   │   └── tbl_stg_order.sql
        └── tbl_stg_order_details.sql
        └── tbl_stg_product.sql
        └── tbl_stg_users.sql
│   ├── curated/
│   │   ├── dimensions/
│   │   │   └── tbl_dim_order.sql
            └── tbl_dim_product.sql
            └── tbl_dim_user.sql
│   │   └── facts/
│   │       └── tbl_fact_order_product.sql
│   └── schema.yml
│   ├── metric/
│   │   │   └── tbl_metric_order.sql
│   │   │   └── tbl_metric_product.sql
│   │   │   └── tbl_metric_user.sql
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
![Flowchart (3)](https://github.com/user-attachments/assets/36d5d7ab-56b4-44f6-89f5-5fb851d7a2d1)



