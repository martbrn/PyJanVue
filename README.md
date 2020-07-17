<p align="center">
<h1> 🧶  Python Django + Vue 🧶 </h1>
</p>

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcT9SGDufHZC9FzOFoNkyOi4PPNWTx26X9EEtA&usqp=CAU">
</p>

## Technologies
- [Python 3](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [VueJS](https://vuejs.org/)
- [NPM](https://www.npmjs.com/)
- [Pip-Env](https://pipenv.pypa.io/en/latest/install/#installing-pipenv)

<pre><code> Before, on cmd: git clone https://github.com/martbrn/PyJanVue.git </code></pre>

## Install FrontEnd
<pre><code> 
$ cd /PyJanVue/client
$ npm install
$ npm run serve
</code></pre>
<h4> Enter on http://localhost:8080/ in your Browser. </h4>

## Install Backend
<pre><code> 
$ python -m venv myenv
$ cd myenv
$ scripts/activate
$ pip install django
$ pip install djangorestframework
$ python -m pip install django-cors-headers
$ python manage.py createsuperuser

Now enter:
username: username  
mail: username@username.com
password: password

$ python manage.py migrate
$ python manage.py runserve
</code></pre>

