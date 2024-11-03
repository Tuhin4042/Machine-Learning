

# What is Encoding?

**Encoding** is a crucial process in data science and machine learning, used to transform categorical data into numerical formats that models can interpret and process. Encoding is indeed a part of feature engineering. Encoding techniques such as **Label Encoding**, **Ordinal Encoding**, and **One-Hot Encoding** are commonly applied when working with categorical data to prepare it for machine learning algorithms.

## Key Encoding Techniques

- **Label Encoding**: This technique converts each category in a feature to a unique integer label. Label encoding is particularly useful for categorical data with no inherent order but should be used with caution, as it can introduce unintended ordinal relationships.
  - **Example**:
    | Category | Label |
    |----------|-------|
    | Apple    | 0     |
    | Banana   | 1     |
    | Orange   | 2     |

- **Ordinal Encoding**: Ordinal encoding is similar to label encoding but specifically applied when the categories have a meaningful order. Each category is assigned a number based on its rank or position.
  - **Example**:
    | Size     | Ordinal Encoding |
    |----------|-------------------|
    | Small    | 0                |
    | Medium   | 1                |
    | Large    | 2                |

- **One-Hot Encoding**: One-hot encoding creates binary columns for each category in a feature, with a "1" representing the presence of a specific category and "0"s in the remaining categories. This method is ideal for categorical data without a natural order and helps prevent the model from interpreting any ranking among categories.
  - **Example**:
    | Category | Apple | Banana | Orange |
    |----------|-------|--------|--------|
    | Apple    | 1     | 0      | 0      |
    | Banana   | 0     | 1      | 0      |
    | Orange   | 0     | 0      | 1      |

---

These encoding techniques help transform categorical data into numeric formats, making it suitable for machine learning models. Choosing the appropriate encoding technique depends on the nature of the data and the specific requirements of the model being used.
