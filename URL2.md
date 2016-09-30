
# NoReverseMatch
https://tutorial.djangogirls.org/en/extend_your_application/

    NoReverseMatch at /
    
    Reverse for 'post_detail' with arguments '()' and keyword arguments '{'pk': 1}' not found. 0 pattern(s) tried: []
    
    Request Method: 	GET
    Request URL: 	http://djangogirlsx0930-twoutlook.c9users.io/
    Django Version: 	1.10.1
    Exception Type: 	NoReverseMatch
    Exception Value: 	
    
    Reverse for 'post_detail' with arguments '()' and keyword arguments '{'pk': 1}' not found. 0 pattern(s) tried: []
    
    Exception Location: 	/home/ubuntu/workspace/myvenv/lib/python3.5/site-packages/django/urls/resolvers.py in _reverse_with_prefix, line 392
    Python Executable: 	/home/ubuntu/workspace/myvenv/bin/python
    Python Version: 	3.5.2
    Python Path: 	
    
    ['/home/ubuntu/workspace/djangogirls/mysite',
     '/usr/lib/python3.5',
     '/usr/lib/python3.5/plat-x86_64-linux-gnu',
     '/usr/lib/python3.5/lib-dynload',
     '/home/ubuntu/workspace/myvenv/lib/python3.5/site-packages']
     
     
# add url

    urlpatterns = [
        url(r'^$', views.post_list, name='post_list'),
        url(r'^post/(?P<pk>\d+)/$', views.post_detail, name='post_detail'),
    ]

## new error

          File "<frozen importlib._bootstrap>", line 986, in _gcd_import
          File "<frozen importlib._bootstrap>", line 969, in _find_and_load
          File "<frozen importlib._bootstrap>", line 958, in _find_and_load_unlocked
          File "<frozen importlib._bootstrap>", line 673, in _load_unlocked
          File "<frozen importlib._bootstrap_external>", line 665, in exec_module
          File "<frozen importlib._bootstrap>", line 222, in _call_with_frames_removed
          File "/home/ubuntu/workspace/djangogirls/mysite/blog/urls.py", line 6, in <module>
            url(r'^post/(?P<pk>\d+)/$', views.post_detail, name='post_detail'),
        AttributeError: module 'blog.views' has no attribute 'post_detail'
     
     