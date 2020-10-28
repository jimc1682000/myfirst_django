Polls
=====

Polls is a Django app to conduct Web-based polls. For each question,
visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

BUILD
-----------
building your package with `python setup.py sdist` (run from inside django-polls).
This creates a directory called dist and builds your new package, django-polls-0.1.tar.gz.
Changing `setup.cfg` can modify the version or other settings.

Quick start
-----------

1. Add "polls" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'polls',
    ]

2. Include the polls URLconf in your project urls.py like this::

    path('polls/', include('polls.urls')),

3. Run ``python manage.py migrate`` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/polls/ to participate in the poll.


TroubleShooting
-----------
How to remove django secret key:
https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/removing-sensitive-data-from-a-repository#purging-a-file-from-your-repositorys-history

Adding Webhook
-----------
https://medium.com/@zoejoyuliao/%E9%80%8F%E9%81%8E-github-webhook-%E8%A7%B8%E7%99%BC%E6%9C%AC%E5%9C%B0-jenkins-pipeline-%E8%AE%93%E4%BD%A0-push-code-%E5%88%B0-github-%E5%B0%B1%E6%9C%83%E8%87%AA%E5%8B%95%E8%B7%91-ci-cd-7c4bd7a22446

Note
-----------
!!!Remeber to remove SECRET_KEY from settings.py!!!
