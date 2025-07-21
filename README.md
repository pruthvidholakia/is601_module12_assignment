# Module 12
---


## My DockerHub Image
[Visit the DockerHub Page](https://hub.docker.com/r/pruthvidholkia/601_module12)


---

## Running Tests Locally

Make sure your virtual environment is activated and dependencies installed.


```bash
python3 -m venv venv

source venv/bin/activate
```

---


### Install Dependencies

```bash
pip install -r requirements.txt
```

---


## Clone the Repository
```bash
git clone https://github.com/pruthvidholakia/is601_module12_assignment

cd is601_module12_assignment
```


---


## Create & Activate Virtual Environment
```bash
python3 -m venv venv

source venv/bin/activate  # On Windows: venv\Scripts\activate
```


---


## Install Dependencies

```bash
pip install -r requirements.txt
```


---


## Run All Tests

```bash
pytest
```


---


## Build Docker Image

```bash
docker build -t <image-name> .
```

---


## Run Docker Container
```bash
docker run -it --rm <image-name>
```


---

## User Registration

/auth/register

![Github action](/screenshots/auth_registration.png)


---


## User login

/auth/login

![Github action](/screenshots/login.png)


---


## Create Calculation

POST/calculations

![Github action](/screenshots/calculation_ss.png)


---


## Get Calculation by {calc_id}

GET/calculations/{calc_id}

![Github action](/screenshots/get_calculation_byID.png)


---


## Update Calculation

PUT/calculations/{calc_id}

![Github action](/screenshots/update_calculation.png)


---


## Delete Calculation

DELETE/calculations/{calc_id}

![Github action](/screenshots/delete_calculation.png)


---


## pytest

What it does: 

=> Runs all tests in your project:

Unit tests (e.g., test_calculator)

Integration tests (e.g., test_user, test_user_auth)

End‑to‑end tests (e.g., UI tests with Playwright)

=> Applies any pytest.ini settings and command line flags.

When to use: When you're doing a full verification before submission or after major changes.

