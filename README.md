# My-Notebook
> A blog app

Blog made in Django web framework in backend and Bootstrap in front. It also have newsletter feature. Have a look <a href="https://my-notebook.herokuapp.com" target="_blank">My-Notebook</a>.

## Installation

OS X & Linux:

```sh
pip install -r requirements.txt
python manage.py runserver
```

## Development setup

Before running the app make sure you complete the following steps :-<br>
* Create a <strong>SENDGRID API</strong>.
* Copy the contents of <strong>settings/base.py</strong> and make a new file <strong>settings/local.py</strong>.
* Replace SENDGRID_API_KEY variable value with your created API.

## Credits

This repo was downloaded from <a href="https://github.com/hrsvrdhn/blog_django" target="_blank">HarshVardhan's Github</a> 