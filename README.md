# Pentaho_lab1

Ссылка на датасет: https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset
Скрипт для создания таблицы в MySQL:
                            DROP TABLE IF EXISTS transactions;
                            CREATE TABLE transactions (
                              id INT AUTO_INCREMENT PRIMARY KEY,
                              gender TINYINT(1) DEFAULT 0,
                              product_category VARCHAR(100),
                              total_amount_transactions INT,
                              total_quantity INT,
                              total_sales INT,
                              max_sales INT,
                              min_sales INT,
                              avarege_sales INT,
                              median_sales INT
                            );
