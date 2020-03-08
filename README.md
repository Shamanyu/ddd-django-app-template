# ddd-django-app-template
App templates for Django projects using domain driven design

## Usage
1) Create a new pull request with the name of the template, e.g. 'springboard-template-march-2020'
2) Use the newly created template to create your sub-context, 
  e.g. 'python manage.py startapp --template=https://github.com/shamanyu/ddd-django-app-template/archive/springboard-template-march-2020.zip mysubcontext'
3) Move the newly created subcontext to your context of choice.

## Limitations
1) In Django version 1.9, for the 'startapp' command, the 'directory' argument doesn't work correctly when a custom 
template is passed.
2) Github only allows downloading archives of entire repositories, not sub-folders. This is why we store different 
templates in different pull requests, rather than as folders in master branch.
