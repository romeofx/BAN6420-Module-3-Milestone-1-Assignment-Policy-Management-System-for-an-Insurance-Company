# BAN6420-Module-3-Milestone-1-Assignment-Policy-Management-System-for-an-Insurance-Company


## Project Overview
This project is an implementation of a basic Policy Management System for an insurance company. The system manages policyholders, products, and payments. It allows policy managers to perform operations like registering, suspending, and reactivating policyholders, as well as managing products and processing payments.

## File Structure

- `policyholder.py`: Contains the `Policyholder` class, which manages the registration, suspension, reactivation, and details of policyholders.
- `product.py`: Contains the `Product` class, which allows creating, updating, and removing products.
- `payment.py`: Contains the `Payment` class, which handles payment processing, reminders, and penalty applications.
- `policy_management_system.ipynb`: The Jupyter notebook that ties everything together, showcasing how the system works with example code.
- `README.md`: This file, providing instructions and details about the project.
- `Policy Management.zip`: A zipped file containing all the above Python files for easy sharing or deployment.


## Classes Overview

### 1. Policyholder Class (`policyholder.py`)
This class represents a policyholder in the insurance system. Key methods include:
- `register_policyholder()`: Registers the policyholder.
- `suspend_policyholder()`: Suspends the policyholder.
- `reactivate_policyholder()`: Reactivates the suspended policyholder.
- `display_details()`: Displays the policyholder's account details.
- `pay_for_product()`: Marks the product as paid for by the policyholder.

### 2. Product Class (`product.py`)
This class manages the insurance products. Key methods include:
- `create_product()`: Creates a new insurance product.
- `update_product()`: Updates the product's name or price.
- `remove_product()`: Removes an existing product.

### 3. Payment Class (`payment.py`)
This class manages payments for policyholders. Key methods include:
- `process_payment()`: Processes the payment for the policyholder.
- `send_reminder()`: Sends a payment reminder.
- `apply_penalty()`: Applies a penalty for late payments.


## How to Use

1. **Clone the repository**:
   - Download or clone the project from GitHub.

2. **Extract the zip file**:
   - The file `Policy Management.zip` contains the necessary Python files. Unzip the file to access `policyholder.py`, `product.py`, and `payment.py`.

3. **Run the System**:
   - Import the classes from the files and use them to manage policyholders, products, and payments as needed.

## License
This project is open-source and free to use for educational purposes.


## Author
Developed by Calistus Chukwuebuka Ndubuisi.

