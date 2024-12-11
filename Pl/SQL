set serveroutput on

DECLARE 

	TYPE employee_record IS RECORD (emp_id NUMBER, emp_name VARCHAR2(50), emp_salary NUMBER(8,2)); v_emp employee_record; 
	BEGIN v_emp.emp_id := 100; v_emp.emp_name := 'John Doe'; v_emp.emp_salary := 5000; 
	DBMS_OUTPUT.PUT_LINE('Employee ID: ' || v_emp.emp_id); 
	DBMS_OUTPUT.PUT_LINE('Employee Name: ' || v_emp.emp_name);
	DBMS_OUTPUT.PUT_LINE('Employee Salary: ' || v_emp.emp_salary); 
	END;
