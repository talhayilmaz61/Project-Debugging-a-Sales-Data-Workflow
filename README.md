# Project-Debugging-a-Sales-Data-Workflow
The aim of this project is to identify and resolve issues in the sales data pipeline to ensure data integrity and accurate calculations, ultimately improving the workflow and functionality of the system.

Tasks:

In this scenario, the load_and_check() function, in charge of managing sales data, encounters issues after the latest update. Unfortunately, your colleague who usually handles this code is currently on holiday, leaving you to troubleshoot.

Your task is to identify and address the issues in the sales data pipeline without getting into every line of code. The load_and_check() function loads the sales.csv dataset and performs several checks. Initially, it verifies the dataset's shape, ensuring it matches expectations. Subsequently, integrity checks are conducted to maintain data consistency and flag any anomalies.

The sales.csv dataset has various columns, focusing on critical fields such as Total, Quantity, Unit price, Tax, and Date. It's essential that the Tax column accurately represents 5% of the subtotal, calculated from the Unit Price multiplied by Quantity.

Your goal is to sort out the pipeline issues, aiming for the code to return 2 success messages upon completion. While at it, try to keep the original structure as much as possible. Only change existing columns if necessary, and make sure the data remains accurate. Be mindful of updating any relevant if statements in the checks as needed
