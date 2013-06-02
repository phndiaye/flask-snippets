# Python Flask Snippets for Sublime Text 2

This snippet library provides completions for Flask Python web framework.
Sublime Text uses fuzzy searching for snippets and completions therefore you don’t have to write triggers.

## Installation

- Package Control: install the package "Flask Snippets" (not yet available)
- Manual: copy files to your Sublime Text User folder



<table>
	<tr><th>trigger</th><th>completion</th></tr>
	<tr><th>copyright</th><td><pre>"""
    [app name]
    --------------------------------------

    [app desc]

    :copyright: (c) [app creation date] by [creator's name].
    :license: [app licence]
"""</pre></td></tr>

	<tr><th>config</th><td><pre>class Config(object):
    DEBUG = False
    CSRF_ENABLED = True


class ProductionConfig(Config):
    SECRET_KEY = 'kanyewestisprobablyfromgodsfamily'


class DevelopmentConfig(Config):
    DEBUG = True
    SECRET_KEY = 'iamnotreallysafe'
    SQLALCHEMY_DATABASE_URI = 'mysql://user:password@development_server/database_name'</pre></td></tr>	

    	<tr><th>init</th><td><pre>"""Initialize the Flask Object."""

from flask import Flask

app = Flask(__name__)</pre></td></tr>	

    	<tr><th>route</th><td><pre>@app.route('/')
def route_name():
    pass</pre></td></tr>	

    	<tr><th>route</th><td><pre>app.add_url_rule('/', 'route_name', views.route_name)</pre></td></tr>	
	
</table>

## Something to add ?
I am aware that i probably forgot lot of snippets.So please, help me add more :) 

Email: me@iamphinson.com

Twitter: @phndiaye
