# django-fun
This repo is for me to become more familiar with Django, create examples with which to teach my students, and more.

# Requirements
1. written in latest stable python as of 20240509
2. using different Django elements (e.g.: REST, authentication, ListView, DetailView, etc)
3. should include examples of:
    - [One to One](https://docs.djangoproject.com/en/5.0/topics/db/examples/one_to_one/)
    - [Many To One](https://docs.djangoproject.com/en/5.0/topics/db/examples/many_to_one/)
    - [Many to Many](https://docs.djangoproject.com/en/5.0/topics/db/examples/many_to_many/)
4. models to include:
    - business model with business name, business description, established date
    - entrepreneur model with name, birth date, and ManyToMany toward business
    - URL model for unique social media links with ForeignKey to human
