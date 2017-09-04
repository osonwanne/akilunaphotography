# Akiluna Photography

Akiluna Photography - portraits and landscape photography. http://akilunaphotography.com

[![Akiluna Photography](https://s3-us-west-2.amazonaws.com/akilunaphotography/AkilunaPhotography.PNG "Website")](http://akilunaphotography.com)

**Set-up and installation:**

1. git clone https://github.com/osonwanne/akilunaphotography.git

2. cd akilunaphotography

3. virtualenv .

4. source bin/activate

5. pip install -r requirements.txt

(Optional - resolves ImportErrors on Ubuntu)
* sudo apt-get build-dep python-imaging
* sudo apt-get install libjpeg62 libjpeg62-dev
* pip install Pillow
* easy_install django-treebeard 
* sudo apt-get install python-unicodecsv
* pip install glue

6. python manage.py migrate

7. python manage.py collectstatic

8. python manage.py runserver