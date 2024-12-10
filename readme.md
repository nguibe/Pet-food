# Dataset Documentation

## Overview

This repository contains multiple datasets related to the brand's transactional and advertising data. Each dataset serves a specific purpose, as described below.

---

### Datasets

#### **FR (Français)**

1. **`retailer.csv`**  
   Cette table contient les données transactionnelles de la marque.

2. **`tv_publisher.csv`**  
   Cette table contient les données issues de la publicité télévisée de la marque.

3. **`programmatic_publisher.csv`**  
   Cette table contient les données issues de la publicité programmatique (publicité en ligne) de la marque.

4. **`socio_demo.csv`**  
   Cette table contient des informations socio-démographiques sur les personnes exposées aux médias programmatiques.

5. **`mapping_transac_publisher_tv.csv`**  
   Table de mapping permettant de relier les différentes tables.

---

#### **EN (English)**

1. **`retailer.csv`**  
   This table contains the brand's transactional data.
   - **`sales`** Column:
   - Represents the total monetary amount of the product(s) involved in a transaction.
   - Useful for:
     - Calculating total revenue.
     - Analyzing sales trends and patterns over time.
     - Comparing the total value of transactions.

3. **`tv_publisher.csv`**
   This table contains data from the brand's television advertising.
   - **`quantity`** Column
   - Represents the quantity or number of products in a transaction.
   - Indicates the total units/items sold in each transaction.
   - Used for:
      - Assessing product demand and popularity.
      - Calculating average quantity per transaction.
      - Evaluating stock turnover and inventory needs.

5. **`programmatic_publisher.csv`**  
   This table contains data from the brand's programmatic advertising (i.e., online).

6. **`socio_demo.csv`**  
   This table contains socio-demographic information about individuals exposed to programmatic media.

7. **`mapping_transac_publisher_tv.csv`**  
   This mapping table is used to link the other tables together.

---

### Additional Resources

You will find the **table dictionary** in the `TO_READ_dict.csv` file, which provides detailed information about the structure and fields of each dataset.
