# Pytest (Python Testing Framework)
<u>Python Pytest and Django </u>
<br>
Reference: https://pytest-django.readthedocs.io/en/latest/
<!-- 
pytest 
pytest-x test failed running after first failure found
pytest -rP (report function)
pytest tests/test_ex1.py::test_example
pytest -m "slow" Those marked slow.
@pytest.mark.slow
To skip: @pytest.mark.slow-->

Pytest mark-> a way of adding metadata to test.
<br>
Reference: https://docs.pytest.org/en/stable/mark.html

A pattern of writing any test:<br>
1. Arrange (fixtures are applied here. preparing data or where actions are to be performed)
2. Act (some sort of response)
3. Assert (test it against expected outcomes)

## Pytest Fixtures
Are functions that run before/after each test function to which the fixture is applied.<br>
Fitures are used to feed data to the tests such as database connections, URLs to test and input data.

## Fixture replacement - Factory Boy and Faker
