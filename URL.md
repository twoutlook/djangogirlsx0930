
https://tutorial.djangogirls.org/en/django_urls/
    
     include
        urlconf_module = import_module(urlconf_module)
      File "/usr/lib/python3.5/importlib/__init__.py", line 126, in import_module
        return _bootstrap._gcd_import(name[level:], package, level)
      File "<frozen importlib._bootstrap>", line 986, in _gcd_import
      File "<frozen importlib._bootstrap>", line 969, in _find_and_load
      File "<frozen importlib._bootstrap>", line 958, in _find_and_load_unlocked
      File "<frozen importlib._bootstrap>", line 673, in _load_unlocked
      File "<frozen importlib._bootstrap_external>", line 665, in exec_module
      File "<frozen importlib._bootstrap>", line 222, in _call_with_frames_removed
      File "/home/ubuntu/workspace/djangogirls/mysite/blog/urls.py", line 5, in <module>
        url(r'^$', views.post_list, name='post_list'),
    AttributeError: module 'blog.views' has no attribute 'post_list'
    
https://tutorial.djangogirls.org/en/django_views/
add post_list to views


    TemplateDoesNotExist at /
    
    blog/post_list.html
    
    Request Method: 	GET
    Request URL: 	http://djangogirlsx0930-twoutlook.c9users.io/
    Django Version: 	1.10.1
    Exception Type: 	TemplateDoesNotExist
    Exception Value: 	
    
    blog/post_list.html
    
    Exception Location: 	/home/ubuntu/workspace/myvenv/lib/python3.5/site-packages/django/template/loader.py in get_template, line 25
    Python Executable: 	/home/ubuntu/workspace/myvenv/bin/python
    Python Version: 	3.5.2
    Python Path: 	
    
    ['/home/ubuntu/workspace/djangogirls/mysite',
     '/usr/lib/python3.5',
     '/usr/lib/python3.5/plat-x86_64-linux-gnu',
     '/usr/lib/python3.5/lib-dynload',
     '/home/ubuntu/workspace/myvenv/lib/python3.5/site-packages']


    
https://tutorial.djangogirls.org/en/dynamic_data_in_templates/