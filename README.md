CREATE TABLE product (
    id BIGINT PRIMARY KEY,
    name VARCHAR(255),
    price DECIMAL(10, 2)
);

INSERT INTO product (id, name, price) VALUES (1, 'Product A', 100.00);
INSERT INTO product (id, name, price) VALUES (2, 'Product B', 150.00);
