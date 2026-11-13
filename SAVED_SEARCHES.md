# CDGC Saved Searches

Reusable **Informatica CDGC saved searches** — ready-to-import query + filter definitions, classified by use case, source system and asset type. A dashboard Search widget can point at one of these, or you can recreate them directly. Import with the [`cdgc-dashboard-export-import`](https://github.com/fboulbellout/claude-cdgc-skills) skill (saved searches are recreated and auto-normalized to structured mode when needed).

> **Tested CDGC release:** `IDMC-202610-10M`

## Catalog (180 saved searches)

### 🤖 AI Governance

| Saved search | Scope | Asset types | Source systems | Method |
|---|---|---|---|---|
| [AI Metrics definitions](saved-searches/ai-governance/ai-metrics-definitions.json) | — | AI Model, Domain, Metric | — | Dynamic |
| [AI Model using PII Data](saved-searches/ai-governance/ai-model-using-pii-data.json) | — | AI Model, Classification, Risk, Table | — | Dynamic |
| [AI Model without stakeholders](saved-searches/ai-governance/ai-model-without-stakeholders.json) | — | AI Model | — | Precise |
| [AI Model without stakeholders - shared with other users](saved-searches/ai-governance/ai-model-without-stakeholders-shared-with-other-users.json) | — | AI Model | — | Precise |
| [AI Model without stakeholders v2](saved-searches/ai-governance/ai-model-without-stakeholders-v2.json) | — | AI Model | — | Precise |
| [AI models with 'Risk Category' 'Unknown'](saved-searches/ai-governance/ai-models-with-risk-category-unknown.json) | — | AI Model | — | default |
| [AI Use Cases](saved-searches/ai-governance/ai-use-cases.json) | — | Use Case | — | Dynamic |
| [All assets related to data models and updated in the last 90 days](saved-searches/ai-governance/all-assets-related-to-data-models-and-updated-in-the-last-90.json) | last90Days | AI Model | — | Dynamic |
| [all business assets without dq occurrences](saved-searches/ai-governance/all-business-assets-without-dq-occurrences.json) | — | AI Model, AI System, Business Term, DQ Rule, Domain, Metric, Policy, Process | — | Dynamic |
| [any ai model for sales forecast ?](saved-searches/ai-governance/any-ai-model-for-sales-forecast.json) | — | AI Model | — | nl |
| [AWS AI Inventory](saved-searches/ai-governance/aws-ai-inventory.json) | Amazon Bedrock, Amazon SageMaker AI | — | AWS | Dynamic |
| [High Risk AI Models Not Classified as High Risk](saved-searches/ai-governance/high-risk-ai-models-not-classified-as-high-risk.json) | — | AI Model, Business Term, Policy, Risk, Table | — | default |
| [Risk Assessment Questionnaires](saved-searches/ai-governance/risk-assessment-questionnaires.json) | — | Questionnaire, Risk | — | Dynamic |
| [risk templates](saved-searches/ai-governance/risk-templates.json) | — | Mitigation, Questionnaire, Risk | — | nl |
| [sales forecast AI models](saved-searches/ai-governance/sales-forecast-ai-models.json) | Modello IA | AI Model | — | Precise |
| [Technical dataset with sensitive data](saved-searches/ai-governance/technical-dataset-with-sensitive-data.json) | — | Classification, Risk, Table | — | Dynamic |

### 🔐 Privacy & Classification

| Saved search | Scope | Asset types | Source systems | Method |
|---|---|---|---|---|
| [_columns related to data classification 'Postal Code'](saved-searches/privacy-classification/columns-related-to-data-classification-postal-code.json) | — | Classification, Column | — | Query |
| [All related to PII](saved-searches/privacy-classification/all-related-to-pii.json) | — | Classification | — | Dynamic |
| [all related to policy "Privacy of Personal Data Policy" - PII - GDPR](saved-searches/privacy-classification/all-related-to-policy-privacy-of-personal-data-policy-pii-gd.json) | — | Policy | — | Dynamic |
| [all related to policy 'Personally Identifiable Information (PII) Data Terms of Use'](saved-searches/privacy-classification/all-related-to-policy-personally-identifiable-information-pi.json) | — | Policy | — | default |
| [Asset classificati sensibili](saved-searches/privacy-classification/asset-classificati-sensibili.json) | — | Classification | — | default |
| [Assets with classification category 'Contacts Details'](saved-searches/privacy-classification/assets-with-classification-category-contacts-details.json) | Business Term | Classification | — | Dynamic |
| [Classified Data Elements](saved-searches/privacy-classification/classified-data-elements.json) | — | Classification | — | Query |
| [COH-STRUC - identifie inconsistance métadata et data](saved-searches/privacy-classification/coh-struc-identifie-inconsistance-m-tadata-et-data.json) | — | Classification, Column, Table | — | Dynamic |
| [Confidential tagged data elements](saved-searches/privacy-classification/confidential-tagged-data-elements.json) | — | Policy | — | Query |
| [data element related to data classification 'email'](saved-searches/privacy-classification/data-element-related-to-data-classification-email.json) | — | Classification | — | Query |
| [data element related to data classification email](saved-searches/privacy-classification/data-element-related-to-data-classification-email.json) | — | Classification | — | Dynamic |
| [data elements related to classification](saved-searches/privacy-classification/data-elements-related-to-classification.json) | — | Classification | — | Query |
| [Dataset Effected by General Data Protection Regulation (GDPR)](saved-searches/privacy-classification/dataset-effected-by-general-data-protection-regulation-gdpr.json) | — | Table | — | Query |
| [Document Classifications](saved-searches/privacy-classification/document-classifications.json) | Document Classification | Classification | — | nl |
| [find PII related assets](saved-searches/privacy-classification/find-pii-related-assets.json) | — | Classification | — | default |
| [generated classifications not promoted](saved-searches/privacy-classification/generated-classifications-not-promoted.json) | — | Classification | — | Dynamic |
| [oracle tables with PII](saved-searches/privacy-classification/oracle-tables-with-pii.json) | Oracle | Classification, Table | Oracle | Dynamic |
| [PDF Files related to Data Entity classification PII](saved-searches/privacy-classification/pdf-files-related-to-data-entity-classification-pii.json) | — | Classification | — | nl |
| [PII](saved-searches/privacy-classification/pii.json) | Data Entity Classification | — | — | Dynamic |
| [PII Classifications](saved-searches/privacy-classification/pii-classifications.json) | — | Classification | — | Dynamic |
| [PII classifications](saved-searches/privacy-classification/pii-classifications.json) | — | Classification | — | Flexible |
| [PII data element](saved-searches/privacy-classification/pii-data-element.json) | — | Classification | — | Dynamic |
| [PII Entity Classification](saved-searches/privacy-classification/pii-entity-classification.json) | — | Classification | — | Dynamic |
| [PII without Stakeholders](saved-searches/privacy-classification/pii-without-stakeholders.json) | — | — | — | Flexible |
| [promoted generated classifications](saved-searches/privacy-classification/promoted-generated-classifications.json) | — | Classification | — | Dynamic |
| [Rejected Classification](saved-searches/privacy-classification/rejected-classification.json) | — | Classification | — | Dynamic |
| [Search With AND](saved-searches/privacy-classification/search-with-and.json) | — | Classification | — | default |
| [show me technical assets which are linked to data element classification](saved-searches/privacy-classification/show-me-technical-assets-which-are-linked-to-data-element-cl.json) | — | Classification | — | nl |
| [Table with Emails](saved-searches/privacy-classification/table-with-emails.json) | — | Classification, Table | — | Dynamic |
| [technical dataset related to data entity classifications "PII"](saved-searches/privacy-classification/technical-dataset-related-to-data-entity-classifications-pii.json) | — | Classification, Table | — | Dynamic |
| [unstructured files classified as Document classification "Aadhaar Application"](saved-searches/privacy-classification/unstructured-files-classified-as-document-classification-aad.json) | — | Classification | — | nl |
| [unstructured files classified as Document classification "US Individual Income tax returns"  and without stakeholders](saved-searches/privacy-classification/unstructured-files-classified-as-document-classification-us-.json) | — | Classification | — | nl |
| [unstructured files related to Data Entity classification PII](saved-searches/privacy-classification/unstructured-files-related-to-data-entity-classification-pii.json) | — | Classification | — | nl |
| [what business glossaries relate to GDPR Policy](saved-searches/privacy-classification/what-business-glossaries-relate-to-gdpr-policy.json) | — | Policy | — | nl |

### 🎯 Data Quality

| Saved search | Scope | Asset types | Source systems | Method |
|---|---|---|---|---|
| [CDE DQ owned by Data Scientists Group](saved-searches/data-quality/cde-dq-owned-by-data-scientists-group.json) | jkATDF8IYMGfN1LTflGMAd | Business Term, DQ Rule, Table | — | Query |
| [CDE With Low Data Quality Score](saved-searches/data-quality/cde-with-low-data-quality-score.json) | — | Business Term, DQ Rule, Table | — | default |
| [CDE with low DQ](saved-searches/data-quality/cde-with-low-dq.json) | — | Business Term, DQ Rule, Table | — | default |
| [Country DQ rules with over 10K failed rows](saved-searches/data-quality/country-dq-rules-with-over-10k-failed-rows.json) | Data Quality Rule Occurrence, greater than | DQ Rule | — | Precise |
| [Data Quality Rule Occurence in (table EU_CUSTOMERS_CLEANSED)](saved-searches/data-quality/data-quality-rule-occurence-in-table-eu-customers-cleansed.json) | — | DQ Rule, Table | — | nl |
| [Data Quality Rule Occurence in resource CDQ_DEMO](saved-searches/data-quality/data-quality-rule-occurence-in-resource-cdq-demo.json) | — | Catalog Source, DQ Rule | — | nl |
| [data quality rule occurences with stakeholder AI DQ Steward](saved-searches/data-quality/data-quality-rule-occurences-with-stakeholder-ai-dq-steward.json) | 6h7bs2sOqauk9WKdq7AjWD | DQ Rule | — | nl |
| [Databricks DQ](saved-searches/data-quality/databricks-dq.json) | — | Catalog Source, DQ Rule | Databricks | nl |
| [dq occurences result](saved-searches/data-quality/dq-occurences-result.json) | 3afd50T5yU2gjVLnIkXZe2, Consistency, Data Quality Rule Occurrence, Validity | — | — | default |
| [dq rule  related to data element related to business term which are cde](saved-searches/data-quality/dq-rule-related-to-data-element-related-to-business-term-whi.json) | — | Business Term, DQ Rule | — | Dynamic |
| [DQ rule occurrence related to (technical asset related to business term 'Email Address')](saved-searches/data-quality/dq-rule-occurrence-related-to-technical-asset-related-to-bus.json) | — | Business Term, DQ Rule | — | nl |
| [dq rules](saved-searches/data-quality/dq-rules.json) | — | DQ Rule | — | Dynamic |
| [dq rules for completeness](saved-searches/data-quality/dq-rules-for-completeness.json) | Completeness, Data Quality Rule Occurrence | DQ Rule | — | Dynamic |
| [dq rules with score NOT ACCEPTABLE](saved-searches/data-quality/dq-rules-with-score-not-acceptable.json) | Data Quality Rule Occurrence, Not Acceptable | DQ Rule, Table | — | Dynamic |
| [DQ Templates related to a system.](saved-searches/data-quality/dq-templates-related-to-a-system.json) | — | Column, DQ Rule | Snowflake | default |
| [DQ Templates related to all columns in a source](saved-searches/data-quality/dq-templates-related-to-all-columns-in-a-source.json) | — | Column, DQ Rule | Snowflake | default |
| [Oracle Retail Till Data Quality under 70%](saved-searches/data-quality/oracle-retail-till-data-quality-under-70.json) | efe732a3537d993380aff0b90d5b8f8b | DQ Rule | Oracle | Dynamic |

### 🔗 Lineage & Impact

| Saved search | Scope | Asset types | Source systems | Method |
|---|---|---|---|---|
| [Complexe Lineage Assets](saved-searches/lineage-impact/complexe-lineage-assets.json) | — | Table | — | Dynamic |
| [Databricks Lineage](saved-searches/lineage-impact/databricks-lineage.json) | — | Catalog Source, Table | Databricks | nl |
| [ORACLE LINEAGE___SALES_STORES_EMEA](saved-searches/lineage-impact/oracle-lineage-sales-stores-emea.json) | Oracle | — | Oracle | Dynamic |
| [Relational Tables Without Lineage](saved-searches/lineage-impact/relational-tables-without-lineage.json) | — | Table | — | Dynamic |

### 📖 Glossary & Governance

| Saved search | Scope | Asset types | Source systems | Method |
|---|---|---|---|---|
| [all in domain "Product Data"](saved-searches/glossary-governance/all-in-domain-product-data.json) | — | Domain | — | default |
| [Anonymised DataSets](saved-searches/glossary-governance/anonymised-datasets.json) | — | Business Term, Policy, Table | — | default |
| [Assets with "Betty" as a stakeholder](saved-searches/glossary-governance/assets-with-betty-as-a-stakeholder.json) | 3m8hM7lOkyqkwwJ5x6OZOp, kyrjPaTr42XciLUPNFZzIM | — | — | Query |
| [AUTO_ACCEPTED glossary curation](saved-searches/glossary-governance/auto-accepted-glossary-curation.json) | — | Business Term | — | Dynamic |
| [business asset without stakeholder](saved-searches/glossary-governance/business-asset-without-stakeholder.json) | 7a1fec19f38f8f5d74c2d3b67c6a6747, e6be8b86bdfc15ed8dc90dfa44e772f6 | — | — | Dynamic |
| [business assets without stakeholders](saved-searches/glossary-governance/business-assets-without-stakeholders.json) | — | — | — | nl |
| [business term](saved-searches/glossary-governance/business-term.json) | — | Business Term | — | default |
| [Business terms CDE](saved-searches/glossary-governance/business-terms-cde.json) | — | Business Term | — | Dynamic |
| [business terms which are critical data element](saved-searches/glossary-governance/business-terms-which-are-critical-data-element.json) | — | Business Term | — | Query |
| [CDE Glossary Without Stakeholders](saved-searches/glossary-governance/cde-glossary-without-stakeholders.json) | — | Business Term | — | nl |
| [data element related to business terms which are cde](saved-searches/glossary-governance/data-element-related-to-business-terms-which-are-cde.json) | — | Business Term | — | default |
| [data element related to glossary country](saved-searches/glossary-governance/data-element-related-to-glossary-country.json) | — | Business Term | — | Query |
| [data elements related with curation status in ('ACCEPTED', AUTO_ACCEPTED) to glossary](saved-searches/glossary-governance/data-elements-related-with-curation-status-in-accepted-auto-.json) | — | Business Term | — | Dynamic |
| [Data Set senza stakeholder](saved-searches/glossary-governance/data-set-senza-stakeholder.json) | — | — | — | default |
| [Dataset in domain Product Data](saved-searches/glossary-governance/dataset-in-domain-product-data.json) | — | Domain, Table | — | default |
| [domain 'Party Data'](saved-searches/glossary-governance/domain-party-data.json) | — | Domain | — | default |
| [Element with declined BG Term curation](saved-searches/glossary-governance/element-with-declined-bg-term-curation.json) | — | Business Term | — | default |
| [Element with declined BG Term curation demo](saved-searches/glossary-governance/element-with-declined-bg-term-curation-demo.json) | Column | Business Term | — | default |
| [Glossary (CDEs)](saved-searches/glossary-governance/glossary-cdes.json) | — | Business Term | — | nl |
| [PAT_Know Your Client (KYC) Process](saved-searches/glossary-governance/pat-know-your-client-kyc-process.json) | — | Process | — | nl |
| [PDF Files without stakeholders](saved-searches/glossary-governance/pdf-files-without-stakeholders.json) | — | — | — | nl |
| [policies without stakeholder](saved-searches/glossary-governance/policies-without-stakeholder.json) | — | — | — | Dynamic |
| [policy related to policy  "AI/ML Regulations"](saved-searches/glossary-governance/policy-related-to-policy-ai-ml-regulations.json) | — | Policy | — | default |
| [show me glossary link to policy](saved-searches/glossary-governance/show-me-glossary-link-to-policy.json) | — | Business Term, Policy | — | nl |
| [show me growth metrics](saved-searches/glossary-governance/show-me-growth-metrics.json) | — | Metric | — | nl |
| [tabelle collegate a customer](saved-searches/glossary-governance/tabelle-collegate-a-customer.json) | — | Business Term | — | nl |
| [Technical asset  related to all in domain "Product Data"](saved-searches/glossary-governance/technical-asset-related-to-all-in-domain-product-data.json) | — | Domain | — | default |
| [unstructured files without stakeholders](saved-searches/glossary-governance/unstructured-files-without-stakeholders.json) | — | — | — | nl |

### 🧹 Curation

| Saved search | Scope | Asset types | Source systems | Method |
|---|---|---|---|---|
| [Claire Co-Pilot - Asset description](saved-searches/curation/claire-co-pilot-asset-description.json) | — | — | — | Dynamic |

### 🗂 Inventory

| Saved search | Scope | Asset types | Source systems | Method |
|---|---|---|---|---|
| [(table, view) in Catalog Source 'snowflake_retail_dwh'](saved-searches/inventory/table-view-in-catalog-source-snowflake-retail-dwh.json) | — | Catalog Source, Table | Snowflake | Query |
| [AI regulations](saved-searches/inventory/ai-regulations.json) | — | — | — | Dynamic |
| [AIGOV_MI_ sales_forecast_model - Version 34](saved-searches/inventory/aigov-mi-sales-forecast-model-version-34.json) | — | — | — | Precise |
| [All assets related to Reports that were updated in the last 90 days](saved-searches/inventory/all-assets-related-to-reports-that-were-updated-in-the-last-.json) | last90Days | — | — | Dynamic |
| [all assets updated within last 60 day](saved-searches/inventory/all-assets-updated-within-last-60-day.json) | — | — | — | Query |
| [all assetsd](saved-searches/inventory/all-assetsd.json) | — | — | — | nl |
| [all with resource type tableau](saved-searches/inventory/all-with-resource-type-tableau.json) | — | Catalog Source, Table | Tableau | Dynamic |
| [assets not related to asset groups](saved-searches/inventory/assets-not-related-to-asset-groups.json) | — | — | — | Dynamic |
| [Auto-Field8-Completeness-Email Address - Completeness](saved-searches/inventory/auto-field8-completeness-email-address-completeness.json) | — | — | — | default |
| [Available Data Products](saved-searches/inventory/available-data-products.json) | Data Marketplace | — | — | default |
| [AWS Data Assets](saved-searches/inventory/aws-data-assets.json) | Amazon Athena, Amazon S3, Redshift | — | AWS | Dynamic |
| [AWS Glue Inventory](saved-searches/inventory/aws-glue-inventory.json) | Amazon Glue | — | AWS | Dynamic |
| [Claims Catalog Sources](saved-searches/inventory/claims-catalog-sources.json) | — | Catalog Source | — | default |
| [contoso](saved-searches/inventory/contoso.json) | — | — | — | default |
| [customer](saved-searches/inventory/customer.json) | — | — | — | Dynamic |
| [Customer Master_with_preview_failed_rows](saved-searches/inventory/customer-master-with-preview-failed-rows.json) | Added To, Column, Snowflake, Table | — | Snowflake | Precise |
| [Customer Success Responsibility List](saved-searches/inventory/customer-success-responsibility-list.json) | kl9FPetFNOphReoJkHj0SE | — | — | Dynamic |
| [data element in "Delta Lake AdventureWorks"](saved-searches/inventory/data-element-in-delta-lake-adventureworks.json) | — | Catalog Source | — | default |
| [data element in catalog source snowflake_retail_dwh](saved-searches/inventory/data-element-in-catalog-source-snowflake-retail-dwh.json) | — | Catalog Source | Snowflake | default |
| [data element with name email in catalog source snowflake_retail_dwh](saved-searches/inventory/data-element-with-name-email-in-catalog-source-snowflake-ret.json) | — | Catalog Source | Snowflake | default |
| [Data Elements used in China business Unit](saved-searches/inventory/data-elements-used-in-china-business-unit.json) | — | — | — | Query |
| [Data Obs Systems](saved-searches/inventory/data-obs-systems.json) | — | — | — | Dynamic |
| [Databricks Tables](saved-searches/inventory/databricks-tables.json) | Databricks Notebooks | Table | Databricks | nl |
| [DG Projects](saved-searches/inventory/dg-projects.json) | Project | — | — | Precise |
| [DIM_Customer](saved-searches/inventory/dim-customer.json) | Snowflake, Table | — | Snowflake | default |
| [dimCustomer](saved-searches/inventory/dimcustomer.json) | — | — | — | Flexible |
| [Expense Claims Table](saved-searches/inventory/expense-claims-table.json) | Table | Table | — | default |
| [Fact Internet Sales Enriched](saved-searches/inventory/fact-internet-sales-enriched.json) | — | — | — | Dynamic |
| [Highly Rated](saved-searches/inventory/highly-rated.json) | 4 | — | — | Dynamic |
| [Human Resources Catalog Sources](saved-searches/inventory/human-resources-catalog-sources.json) | Catalog Source | Catalog Source | — | default |
| [Human Resources Tables](saved-searches/inventory/human-resources-tables.json) | — | Catalog Source, Table | — | default |
| [match_percentage](saved-searches/inventory/match-percentage.json) | — | — | — | default |
| [my developer statements](saved-searches/inventory/my-developer-statements.json) | Snowflake | — | Snowflake | Dynamic |
| [op1145580](saved-searches/inventory/op1145580.json) | — | — | — | default |
| [order data Datset - Snowflake](saved-searches/inventory/order-data-datset-snowflake.json) | Data Set | — | Snowflake | default |
| [Order Details](saved-searches/inventory/order-details.json) | — | — | — | Precise |
| [orders data - filter on only table data](saved-searches/inventory/orders-data-filter-on-only-table-data.json) | — | Table | — | default |
| [PAT_employee details](saved-searches/inventory/pat-employee-details.json) | Added To, Microsoft SQL Server | — | — | Precise |
| [PAT_Employee_TABLEAU_Employee (inc. historic)](saved-searches/inventory/pat-employee-tableau-employee-inc-historic.json) | Tableau | Table | Tableau | Precise |
| [pipeline_load_enriched_internetofsales](saved-searches/inventory/pipeline-load-enriched-internetofsales.json) | — | — | — | default |
| [Powercenter items](saved-searches/inventory/powercenter-items.json) | Informatica PowerCenter | — | — | Precise |
| [Product data](saved-searches/inventory/product-data.json) | Table | — | — | Dynamic |
| [product information](saved-searches/inventory/product-information.json) | — | — | — | Dynamic |
| [PRODUCT_NAME](saved-searches/inventory/product-name.json) | — | — | — | Dynamic |
| [Rated Databricks Assets](saved-searches/inventory/rated-databricks-assets.json) | 1, Databricks Notebooks | — | Databricks | nl |
| [RD Finance data sets](saved-searches/inventory/rd-finance-data-sets.json) | — | — | — | nl |
| [retrieve pdf files](saved-searches/inventory/retrieve-pdf-files.json) | — | — | — | Dynamic |
| [Sales / Order Details](saved-searches/inventory/sales-order-details.json) | — | — | — | Dynamic |
| [sales detail](saved-searches/inventory/sales-detail.json) | — | — | — | Precise |
| [sales order details](saved-searches/inventory/sales-order-details.json) | — | — | — | default |
| [Sales Transactions](saved-searches/inventory/sales-transactions.json) | — | — | — | default |
| [search 🚫 PROHIBITED](saved-searches/inventory/search-prohibited.json) | Regulation, 🚫 PROHIBITED | — | — | Dynamic |
| [see observaibility on V_TEMP_FACTSTORESALES_DETAILED_EUROPE](saved-searches/inventory/see-observaibility-on-v-temp-factstoresales-detailed-europe.json) | — | — | — | default |
| [show me table without description](saved-searches/inventory/show-me-table-without-description.json) | — | Table | — | nl |
| [Snowflake dataset not updated within last 30 days](saved-searches/inventory/snowflake-dataset-not-updated-within-last-30-days.json) | — | Catalog Source, Table | Snowflake | default |
| [snowflake mappings](saved-searches/inventory/snowflake-mappings.json) | Mapping | — | Snowflake | default |
| [Snowflake table Customer Master](saved-searches/inventory/snowflake-table-customer-master.json) | Snowflake, Table | Table | Snowflake | Dynamic |
| [Snowflake technical datasets](saved-searches/inventory/snowflake-technical-datasets.json) | — | Catalog Source, Table | Snowflake | default |
| [Sony demo - enriched sales forecast](saved-searches/inventory/sony-demo-enriched-sales-forecast.json) | Table | — | — | Precise |
| [Sony demo - Notebook](saved-searches/inventory/sony-demo-notebook.json) | Notebook Instance | — | — | Precise |
| [SQLSERVER_dbo](saved-searches/inventory/sqlserver-dbo.json) | Microsoft SQL Server | — | — | Dynamic |
| [SQLSERVER_TABLE](saved-searches/inventory/sqlserver-table.json) | Microsoft SQL Server, Table | Table | — | Dynamic |
| [Store Orders](saved-searches/inventory/store-orders.json) | View | — | — | Dynamic |
| [table Customer Master](saved-searches/inventory/table-customer-master.json) | — | Table | — | Dynamic |
| [Table Expense_Claims](saved-searches/inventory/table-expense-claims.json) | — | Table | — | default |
| [table product_data](saved-searches/inventory/table-product-data.json) | — | Table | — | default |
| [Tableau 5* Reports](saved-searches/inventory/tableau-5-reports.json) | 5, Tableau | Table | Tableau | Query |
| [Tableau Assets](saved-searches/inventory/tableau-assets.json) | Tableau | Table | Tableau | Dynamic |
| [Tables and views in 
snowflake_retail_dwh](saved-searches/inventory/tables-and-views-in-snowflake-retail-dwh.json) | — | Table | Snowflake | nl |
| [tables in resource "human resources"](saved-searches/inventory/tables-in-resource-human-resources.json) | — | Catalog Source, Table | — | default |
| [tables or views in snowflake_retail_dwh](saved-searches/inventory/tables-or-views-in-snowflake-retail-dwh.json) | — | Table | Snowflake | nl |
| [tables related to column Email](saved-searches/inventory/tables-related-to-column-email.json) | — | Column, Table | — | default |
| [Technical Assets](saved-searches/inventory/technical-assets.json) | — | — | — | nl |
| [technical dataset with catalog source name 'snowflake_retail_dwh' and not 'Data Freshness' within last 30 day](saved-searches/inventory/technical-dataset-with-catalog-source-name-snowflake-retail-.json) | — | Catalog Source, Table | Snowflake | Dynamic |
| [unstructured file Modified within last 365](saved-searches/inventory/unstructured-file-modified-within-last-365.json) | — | — | — | nl |
| [unstructured file with Modified On within last 90 days](saved-searches/inventory/unstructured-file-with-modified-on-within-last-90-days.json) | — | — | — | nl |
| [unstructured files](saved-searches/inventory/unstructured-files.json) | — | Catalog Source | — | Dynamic |
| [View Online & Store Orders](saved-searches/inventory/view-online-store-orders.json) | — | — | — | default |
| [YOY Growth Revenue](saved-searches/inventory/yoy-growth-revenue.json) | — | — | — | Dynamic |
| [YOY Growth Revenue Report](saved-searches/inventory/yoy-growth-revenue-report.json) | — | — | — | default |

## Tags

**Use cases:** ai-governance, curation, data-quality, glossary-governance, inventory, lineage-impact, privacy-classification  
**Source systems:** AWS, Databricks, Oracle, Snowflake, Tableau  
**Asset types:** AI Model, AI System, Business Term, Catalog Source, Classification, Column, DQ Rule, Domain, Metric, Mitigation, Policy, Process, Questionnaire, Risk, Table, Use Case

## Privacy

All saved searches are **sanitized** before publishing: emails, phones, IPs, known person names and org/pod deep-links are masked. Only the portable query + filter definition is kept — no org id, pod host or internal asset ids.
