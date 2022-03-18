# Django_basic_store_stripe
Django eCommerce basic store setup with Stripe payments.

Features: Cart, Products, Accounts. Products can be added to store via django admin panel.

### Setup
- `git clone git@github.com:rsleyland/Django_basic_store_stripe.git`
- `cd Django_basic_store_stripe`
- create virtual env of your choice ex. `virtualenv -p python3 myenv`
- start virtual env ex. `source myenv/bin/activate`
- install dependencies from requirements.txt `pip install -r requirements.txt`
- Start server `python manage.py runserver`
- Admin account already configured as email: admin@admin.com pass: admin
### Configuration:
- stripe api-keys need to be added
- stripe webhook endpoint need to be added
- Django secret need to be added
