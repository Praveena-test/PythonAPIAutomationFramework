### Python API Automation using pytest
#### Tech Stack

- Python 3.12
- Requests - HTTP Requests
- PyTest - Testing Framework
- Reporting - Allure Report, PyTest HTML
- Test Data - CSV, Excel, JSON, Faker
- Advance API Testcase - jsonschema
- Parallel Execution - x distribute (xdist)

How to Install Packages 
- pip install pytest requests pytest-html faker allure-pytest jsonschema pytest-xdist python-dotenv pandas

How to run your Testcase Parallel 
- pip install pytest-xdist

How to run the Basic Test with Allure report 
- pytest tests/tests/crud/test_create_booking.py --alluredir=allure_result -s