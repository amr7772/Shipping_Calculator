# Free Delivery Decision Program

A simple Python program that calculates whether an order qualifies for free delivery based on the order value and delivery day. It is designed for beginners learning Python conditional statements and multi-input decisions.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Run

```bash
python app.py
```

## Example

```text
Please enter the order value: 600
Please enter the day of purchase: Monday
It's free delivery
```

Another example:

```text
Please enter the order value: 100
Please enter the day of purchase: Tuesday
The delivery fee for the order you made on Tuesday with $100.0 is $10
```

## Known limitations

* The day must be entered correctly (for example, `Saturday` or `Sunday`).
* The delivery fee is fixed at $10 for orders that do not qualify for free delivery.

