<p align="left">
  <a href="https://www.linkedin.com/in/rathan-kumar492" target="_blank"><img alt="LinkedIn" title="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://www.youtube.com/channel/UCYesptHRU1QZ2pHZkAqdQTw/videos" target="_blank"><img alt="YouTube" title="YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
  <a href="https://www.buymeacoffee.com/rathankumar" target="_blank"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me A Coffee"></a>
  <a href="https://www.udemy.com/course/django-ecommerce-project-based-course-python-django-web-development/?referralCode=BAD74EA99BCC2E331D13" target="_blank"><img src="https://img.shields.io/badge/Udemy-EC5252?style=for-the-badge&logo=Udemy&logoColor=white" alt="Udemy"></a>
</p>

# About The Project
GreatKart is an eCommerce application built with Python Django Framework. Some of the features of this project includes custom user model, categories and products, Carts, Incrementing, Decrementing and removing car items, Unlimited Product image gallery, Orders, Payments, after-order functionalities such as reduce the quantify of sold products, send the order received email, clearing the cart, Order completion page as well as generating an invoice for the order. Also we have a Review and Rating system with the interactive rating stars that even allows you to rate a half-star rating. My account functionalities for the customer who can easily edit his profile, profile pictures, change his account password, and also manage his orders and much more. Finally hosted this application on AWS Elastic Beanstalk [Check Demo](http://djangogreatkart.com/)

_Learn how to build these [complex functionalities from the scratch](https://www.udemy.com/course/django-ecommerce-project-based-course-python-django-web-development/?referralCode=BAD74EA99BCC2E331D13)_
<p align="left">
  <a href="https://www.udemy.com/course/django-ecommerce-project-based-course-python-django-web-development/?referralCode=BAD74EA99BCC2E331D13" target="_blank"><img src="https://img.shields.io/badge/Udemy-5624D0?style=for-the-badge&logo=Udemy&logoColor=white" alt="Udemy"></a>
</p>

<img src="https://github.com/dev-rathankumar/greatkart-pre-deploy/blob/main/media/greatkart-screenshot.jpg">

# Setup Instructions

1. Clone the repository `git clone https://github.com/dev-rathankumar/greatkart-pre-deploy.git`
2. Navigrate to the working directory `cd greatkart-pre-deploy`
3. Open the project from the code editor `code .` or `atom .`
4. Create virtual environment `python -m venv env`
5. Activate the virtual environment `source env/Scripts/activate`
6. Install required packages to run the project `pip install -r requirements.txt`
7. Rename _.env-sample_ to _.env_
8. Fill up the environment variables:
    _Generate your own Secret key using this tool [https://djecrety.ir/](https://djecrety.ir/), copy and paste the secret key in the SECRET_KEY field._

    _Your configuration should look something like this:_
    ```sh
    SECRET_KEY=47d)n05#ei0rg4#)*@fuhc%$5+0n(t%jgxg$)!1pkegsi*l4c%
    DEBUG=True
    EMAIL_HOST=smtp.gmail.com
    EMAIL_PORT=587
    EMAIL_HOST_USER=youremailaddress@gmail.com
    EMAIL_HOST_PASSWORD=yourStrongPassword
    EMAIL_USE_TLS=True
    ```
    _Note: If you are using gmail account, make sure to [use app password](https://support.google.com/accounts/answer/185833)_
9. Create database tables
    ```sh
    python manage.py migrate
    ```
10. Create a super user
    ```sh
    python manage.py createsuperuser
    ```
    _GitBash users may have to run this to create a super user - `winpty python manage.py createsuperuser`_
11. Run server
    ```sh
    python manage.py runserver
    ```
12. Login to admin panel - (`http://127.0.0.1:8000/securelogin/`)
13. Add categories, products, add variations, register user, login, place orders and EXPLORE SO MANY FEATURES


[Check Live Demo](http://djangogreatkart.com/)

_Learn how to build these [complex functionalities from the scratch](https://www.udemy.com/course/django-ecommerce-project-based-course-python-django-web-development/?referralCode=BAD74EA99BCC2E331D13)_

## Support
💙 If you like this project, give it a ⭐ and share it with friends!

<p align="left">
  <a href="https://www.youtube.com/channel/UCYesptHRU1QZ2pHZkAqdQTw/videos"><img alt="YouTube" title="YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
  <a href="https://www.buymeacoffee.com/rathankumar" target="_blank"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me A Coffee"></a>
  <a href="https://www.udemy.com/course/django-ecommerce-project-based-course-python-django-web-development/?referralCode=BAD74EA99BCC2E331D13" target="_blank"><img src="https://img.shields.io/badge/Udemy-5624D0?style=for-the-badge&logo=Udemy&logoColor=white" alt="Udemy"></a>
</p>

## Contact Me
<p align="left">
  <a href="https://www.linkedin.com/in/rathan-kumar492"><img alt="LinkedIn" title="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:developer.rathan@gmail.com"><img alt="Gmail" title="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

##
Made with ❤️ and Python
