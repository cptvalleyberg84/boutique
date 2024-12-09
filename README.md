Feedback to outdated video:
https://www.youtube.com/watch?v=pwmJLp2jots

Allauth Setup 1
Project - Boutique Ado  Authentication & Authorisation  Allauth Setup 1



1. I couldn't install the recommended older version of allauth so I installed new one.
it upgraded automatically django to the newest

the course is again outdated - this time severly



2. they said to take from aaluth documentation an dput into setttings  installed_apps:

djanngo.contrib.sites

but it does not exist in documentation anymore / added just in case.


3. this line:
allauth.account.middleware.AccountMiddleware
needed to be added to the middleware in settings for the migration to be possible.

4. You may need to add to settings.py:
CSRF_TRUSTED_ORIGINS = ['the same adress as to the Allowed Hosts here']
