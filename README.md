<h1>Set up project </h1>

<h3>Steps</h3>
<ul>
<li>
    Clone repository : <b>git clone https://github.com/obamwonyi/django_rest_framework_practice.git</b>
</li>
<li>
    Install mysqlclient : <b>pip install mysqlclient</b>
</li>
<li>
    set up a mysql database with , then update the database settings in the settings.py file in the storage folder, 
    and fill the parameters with the asteriks (*) with you actual database values as shown below.

    DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': '*(your own database name)',
        'USER': '*(your own database user)',
        'PASSWORD': '*(your own database password)',
        'HOST': 'localhost',
        'PORT': '3306'
    }}
</li>

<li>
    Start the server: <b>python3 manange.py runserver</b>
</li>

<li>
    open the project : 
    on the web url add <i>/api/location (http://127.0.0.1:8000/api/location)</i> to got to the location page ( for viewing(R) locations ), in this page there is a form field to add locations(C). When you pass the id giving in the view (<i>http://127.0.0.1:8000/api/location</i>) page json output to the url , you go to a page where you can update(U) and delete(D) a particular location.
</li>
<li>
        The same approach can be taken for creating , reading, updating and deleting items from the route <i/>http://127.0.0.1:8000/api/item</i>
</li>

</ul>