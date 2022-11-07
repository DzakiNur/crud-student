SQL code:
CREATE TABLE students (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR (100) NOT NULL,
    email VARCHAR (200) NOT NULL UNIQUE,
    phone VARCHAR(20) NULL,
    address VARCHAR(200) NULL,
    created_at DATETIME NOT NULL DEFAULT CURRENT_TIMESTAMP
);


INSERT INTO students (name, email, phone, address)
VALUES
('Johan Liebert', 'johan@gmail.com', '+6212345678', 'Berlin, Jerman'),
('Gustavo Fring', 'gustavo@gmail.com', '+6211223344', 'London, England'),
('Homlander', 'homlander@vought.com', '+623897459873', 'California, USA'),
('Messi', 'messi@gmail.com', '+111555999', 'Ngawi, Ciawi'),
('David Martinez', 'david@gmail.com', '+628974357934', 'Ciawi, Indonesia'),
('Syala', 'boris.johnson@gmail.com', '+4499778855', 'Ciawi, Indonesia');
