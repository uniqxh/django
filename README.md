# django
django

## 静态文件部署问题

# url.py
  from django.contrib.staticfiles.urls import staticfiles_urlpatterns
  urlpatterns += staticfiles_urlpatterns()
  
# settings.py
  STATIC_DIRS = (
      #your dev static file path
  )
  
# templates
  {{ STATIC_URL }}
