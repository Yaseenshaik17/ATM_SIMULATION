CREATE DATABASE atm;
USE atm;

-- Creating the accounts table
CREATE TABLE accounts (
    account_number VARCHAR(10) PRIMARY KEY,
    balance DOUBLE NOT NULL
);

-- Creating the transactions table
CREATE TABLE transactions (
    id INT AUTO_INCREMENT PRIMARY KEY,
    account_number VARCHAR(10),
    detail VARCHAR(255),
    FOREIGN KEY (account_number) REFERENCES accounts(account_number) ON DELETE CASCADE
);

-- Inserting 10 sample account holders
INSERT INTO accounts (account_number, balance) VALUES
('123456', 5000.0),
('654321', 7000.0),
('111111', 6000.0),
('222222', 8000.0),
('333333', 5500.0),
('444444', 6200.0),
('555555', 7100.0),
('666666', 4300.0),
('777777', 3900.0),
('888888', 4800.0),
('999999', 5200.0);
