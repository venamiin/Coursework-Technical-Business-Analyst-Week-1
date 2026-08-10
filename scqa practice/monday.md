# Monday – The Catalogue Problem at RetailCo

## Situation

RetailCo’s e-commerce channel generates around 40% of its revenue and relies on a complex product catalogue containing approximately 70,000 current, discontinued and seasonal SKUs. In March, RetailCo replaced its outdated PIM system with a modern SaaS platform to improve product management and reduce reliance on IT. The migration was completed on time, but the existing product data had significant quality issues, including duplicates, incorrect SKUs and inconsistent structures.

## Complication

After the migration, SKU mappings between the new PIM and the OMS became inconsistent. This caused customers to receive incorrect products, affecting over 1,200 orders and reducing NPS from 42 to 17. Although a temporary fix restored the old data, RetailCo now has two systems operating in parallel, creating uncertainty over which system is authoritative. The investigation also revealed three separate, unmanaged OMS mapping files, unclear ownership and undocumented workarounds. With the summer sale only six weeks away, the current process is not reliable enough to handle increased order volumes.

## Question

How can RetailCo establish a reliable, controlled product-data process and resolve the PIM/OMS inconsistencies before the summer sale, while preventing similar migration and data-quality failures in the future?

## Answer

RetailCo should first map the complete product-data journey from product creation to website publication and fulfilment, identifying all systems, mappings, owners and failure points. Chloe should use this to establish a single source of truth for product data, consolidate the three OMS mapping files, assign clear ownership and introduce version control and validation checks. The existing data should then be prioritised and cleansed based on business risk, particularly high-volume and high-value SKUs.

Before the summer sale, RetailCo should conduct end-to-end testing using realistic sales volumes and reconcile the PIM, OMS and website data before fully relying on the new system. This approach addresses the immediate customer and operational risks while also creating stronger data governance to prevent the same problem recurring.
