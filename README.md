# Project-Debugging-a-Sales-Data-Workflow
The aim of this project is to identify and resolve issues in the sales data pipeline to ensure data integrity and accurate calculations, ultimately improving the workflow and functionality of the system.

Tasks:
Run the load_and_check() function first. Look for any error messages in the output - these will point you to what needs fixing. You should aim for exactly two success messages: "Data loaded successfully" and "Data integrity check was successful!"
Review the load_and_check() function code, paying special attention to the two if checks:
The first check validates the column count
The second check tests data integrity based on Condition_1 (Total values) and Condition_2 (Tax calculations at 5%) Fix any issues by adjusting the existing columns or function logic, but don't create new columns. Ensure the function only returns two success messages when completed.


In this scenario, the load_and_check() function, in charge of managing sales data, encounters issues after the latest update. Unfortunately, your colleague who usually handles this code is currently on holiday, leaving you to troubleshoot.

Your task is to identify and address the issues in the sales data pipeline without getting into every line of code. The load_and_check() function loads the sales.csv dataset and performs several checks. Initially, it verifies the dataset's shape, ensuring it matches expectations. Subsequently, integrity checks are conducted to maintain data consistency and flag any anomalies.

The sales.csv dataset has various columns, focusing on critical fields such as Total, Quantity, Unit price, Tax, and Date. It's essential that the Tax column accurately represents 5% of the subtotal, calculated from the Unit Price multiplied by Quantity.

Your goal is to sort out the pipeline issues, aiming for the code to return 2 success messages upon completion. While at it, try to keep the original structure as much as possible. Only change existing columns if necessary, and make sure the data remains accurate. Be mindful of updating any relevant if statements in the checks as needed
