CREATE TABLE Employees (
    EmpID INT PRIMARY KEY,
    Name VARCHAR(50),
    Department VARCHAR(30),
    Salary DECIMAL(10,2),
    JoiningDate DATE,
    ManagerID INT
);


INSERT INTO Employees (EmpID, Name, Department, Salary, JoiningDate, ManagerID) VALUES
(1, 'Alice', 'HR', 50000, '2020-01-15', NULL),
(2, 'Bob', 'IT', 60000, '2019-03-20', 5),
(3, 'Charlie', 'Finance', 55000, '2021-07-10', 6),
(4, 'David', 'IT', 70000, '2018-11-05', 5),
(5, 'Eve', 'IT', 90000, '2017-06-25', NULL),
(6, 'Frank', 'Finance', 80000, '2016-04-18', NULL),
(7, 'Grace', 'HR', 48000, '2022-08-30', 1),
(8, 'Hannah', 'Marketing', 52000, '2021-01-10', NULL),
(9, 'Ian', 'Marketing', 58000, '2019-12-01', 8),
(10, 'Jack', 'IT', 75000, '2020-05-05', 5);
