# Pentaho_lab1

Ссылка на датасет: https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset
<br> Скрипт для создания таблицы в MySQL:
                            <br>DROP TABLE IF EXISTS transactions;
                            <br>CREATE TABLE transactions (
                              <br>id INT AUTO_INCREMENT PRIMARY KEY,
                              <br>gender TINYINT(1) DEFAULT 0,
                              <br>product_category VARCHAR(100),
                              <br>total_amount_transactions INT,
                              <br>total_quantity INT,
                              <br>total_sales INT,
                              <br>max_sales INT,
                              <br>min_sales INT,
                              <br>avarege_sales INT,
                              <br>median_sales INT
                            <br>);
