# django-package-compatibility-matrix
A compatibility matrix for django packages. Either use the matrix contained here or visit https://django-package-compatibility-matrix.glitch.me/ for a much better UX with search!

## What is this

This is a compatibility matrix for Django packages. For each Django version, starting from Django 1.4 you will find a version of each django package that is guaranteed to work with that specific Django version. All the info that is entered until now comes from my own projects. Contributions are more than welcome since I don't have projects for *all* Django versions nor I use all Django packages in all my projects.

!!!

## The Matrix

|           Django               | 1.4   | 1.5   | 1.6    | 1.7    | 1.8    | 1.9     | 1.10    | 1.11    | 2.0   | 2.1   | 2.2   | 3.0   |   3.1 |
| -------------------            |:---:  |:---:  |:---:   |:---:   |:---:   |:---:    |:---:    |:---:    |:---:  |:---:  |:---:  |:---:  |  :---:| 
| django-admin-bootstrapped      |1.6.4  |       |2.3.5   |        |        |         |         |         |       |       |       |       |       |
| django-adminplus               |       |       |0.3     |        | 0.3    |         |         |         |       |       |       |       |       |
| django-allauth                 |       |       |        |        |0.30.0  |         |         |         |       |       |0.39.1 |       |       |
| django-auth-ldap               |1.2.0  |       |1.2.0   |1.2.4   |1.2.4   |1.2.8    |         | 1.2.16  |1.3.0  |       |       |       |       |
| django-autocomplete-light      |       |       |        |        |3.1     |         |         |3.2.10   |       |       | 3.3.2 |       |       |
| django-bootstrap-form          |       |       |        |        |0.30.0  |         |         |         |       |       |       |       |       |
| django-braces                  |       |       |        |        |1.4.0   |         |         |         |       |       |       |       |       |
| django-celery                  |       |       |3.1.10  |        |3.1.10  |         |         |         |       |       |       |       |       |
| django-celery-email            |       |       |1.0.4   |        |        |         |         |         |       |       |       |       |       |
| django-classy-tags             |       |       | 0.6.1  |0.6.1   |0.6.1   |         |         | 0.8.0   |       |       | 0.8.0 |       |       |
| django-cms                     |3.0.18 |3.0.18 | 3.2.5  | 3.2.5  | 3.5.2  | 3.5.2   |  3.5.2  | 3.5.2   |       |       |       |       |       |
| django-compressor              |1.3    |       | 1.4    | 1.4    |1.4     |2.0      |         |  2.2    |2.2    |       | 2.2   |       |       |
| django-constance               |       |       |        |        |        |         |         |2.0.0    |       |       |       |       |       |
| django-crispy-forms            |       |       | 1.4.0  |1.4.0   |1.6.1   |1.6.1    |         | 1.6.1   |1.7.2  |       |1.7.2  |       |       |
| django-debug-toolbar           |0.9.4  |       |1.3.0   |1.3.0   |        |1.6.7    |         |         |       |       |1.10.1 |       |       |
| django-extensions              |1.3.3  |       |1.5.1   |1.5.1   |1.5.1   |1.6.7    |         |  1.9.1  |2.0.6  |       | 2.1.6 |       |       |
| django-extra-views             |0.7.0  |       |        |        |        |         |         |  0.9.0  |       |       |       |       |       |
| django-filter                  |0.11.0 |       |0.11.0  |0.11.0  |0.15.3  |0.15.3   |         |1.0.4    |1.1.0  |       |2.0.0  |       |       |
| django-floppy-forms            |       |       |        |        |1.4.0   |         |         |         |       |       |       |       |       |
| django-generic-scaffold        | 0.2   | 0.2   | 0.5.2  | 0.5.2  | 0.5.2  | 0.5.2   | 0.5.2   | 0.5.2   |  0.5.2|       |       |       |       |
| django-import-export           |0.2.1  |       |        |        |        |         |         |         |       |       |       |       |       |
| django-localflavor             |       |       |  1.1   |        |        |         |         |         |       |       | 2.1   |       |       |
| django-maintenance-mode        |       |       |        |        |        | 0.11.0  |         |0.13.1   |       |       |       |       |       |
| django-memcached               |0.1.2  |       |        |        |        |         |         |         |       |       |       |       |       |
| django-model-utils             |       |       |        |2.2     |  2.2   |2.5      |         | 3.1.2   |       |       | 3.1.2 |       |       |
| django-model-translation       |       |       |        | 0.8    |0.12.1  |         |         |         |       |       |       |       |       |
| django-registration            |       |       |        |        |2.3     |         |         |         |       |       |       |       |       |
| django-dynamic-raw-id          |       |       |        |        |        |         |         | 2.5     |       |       |       |       |       |
| django-rest-auth               |       |       |        |        |        |         |         |         | 0.9.3 |       |       |       |       |
| django-rest-framework          |2.3.13 |       |        |3.0.3   |3.3.3   |3.3.3    |         | 3.6.4   | 3.7.7 |       |       |       |       |
| django-reversion               |1.6.6  |       | 1.8.5  |        |1.8.7   |2.0.6    |         |2.0.10   |2.0.13 |       |3.0.2  |       |       |
| django-reversion-compare       |0.3.5  |       |        |        |        |0.7.1    |         |         |       |       |       |       |       |
| django-rq                      |       |       |        |        |        |0.9.2    |         |  0.9.6  |       |       |       |       |       |
| django-rules-light             | 0.2.0 |       | 0.2.0  |        |0.2.0   |0.2.0    |         |         |       |       | 0.3.0 |       |       |
| django-salmonella              |0.6. 1 |       |        |        |        |         |         |         |       |       |       |       |       |
| django-sendfile                |0.3.11 |       |        |        |        |0.3.11   |         | 0.3.11  |       |       |       |       |       |
| django-simple-history          |1.5.3  |       |        |        |        |         |         |         |       |       |       |       |       |
| django-simple-captcha          |       |       |        |0.5.3   |        |         |         |         |       |       |       |       |       |
| django-smoketest               |       |       | 1.1.0  |        |        |         |         | 1.1.0   |       |       |1.1.0  |       |       |
| django-tables2                 |0.15.0 |       | 0.15.0 |0.15.0  |1.0.7   |1.2.3    |         | 1.21.2  |1.21.2 |       |2.0.3  |       |       |
| django-tables2-column-shifter  |       |       |        |        |        |         |         | 0.4.0   |       |       |       |       |       |
| django-taggit                  |       |       |        |0.15.0  |        |         |         | 0.22.1  |       |       |       |       |       |
| django-verbatim                |       |       |        | 0.1    |        |         |         |         |       |       |       |       |       |
| django-waffle                  |0.10.1 |       |        |        |        |         |         |         |       |       |       |       |       |
| django-widget-tweaks           |       |       | 1.3    | 1.3    | 1.3    |1.4.1    |         |1.4.1    |1.4.1  |       |1.4.3  |       |       |
| django-xhtml2pdf               |       |       | 0.0.3  |        |        |0.0.3    |         |   0.0.3 |       |       |       |       |       |
| easy-thumbnails                |       |       |        |  2.2   |        |         |         |   2.6   |       |       |       |       |       |
| whitenoise                     | 2.0.6 |       |        |        |        |         |         |         |       |       |       |       |       |
| **Django**                     |**1.4**|**1.5**|**1.6** |**1.7** |**1.8** |**1.9**  |**1.10** |**1.11** |**2.0**|**2.1**|**2.2**|**3.0**|**3.1**|


!!~

## Rationale

One huge PITA for me is when I need to install a django package (add-on) to a non-current Django version. Yes, I am totally aware that right now, only Django 1.11 (LTS) and Django 2.0 are supported. However, I have to confess that there are projects that I support and run Django versions 1.4, 1.6, 1.8 and 1.9. These are old projects that cannot be upgraded for a number of reasons, mainly because there are too few resources. So, although there are no resources for upgrading a Django 1.4 project to 1.11, there usually *are* resources to add some autocomplete features. Deciding which version of (for instance) django-autocomplete-light to install on your old Django 1.6 project is usually *not* trivial and, unless the django package has a very good changelog most of the time you'll need to do some trial and error by installing different versions to find out one that actually works. This matrix wants to improve this.

**Warning** I know that I should not use unsupported Django versions. **I believe that you also know it and I warn you in case you are doing it.** However, usually it's not that easy :/

Actually, if it was in my hand I would upgrade all projects to Django 2.0 before adding even one feature, however I am not a decision maker and usually decision makers prefer adding features instead of upgrading to newer versions. Ok that depends on the decision maker but if you're in my shoes you'll get it. Also, if that makes you more comfortable, almost all (especially the old ones) of the projects using unsupported Django versions are for projects that are internal to the organization I work for so they are not visible to the public internet.



## How to contribute

Just do a ``pip freeze`` for your project and inspect the version of Django and of the packages that it uses. If the version of a package for your Django version is missing (or is less than your own but you know that it works) then add a PR with your change 
