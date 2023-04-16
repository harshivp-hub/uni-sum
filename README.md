TITLE
UNI-SUM

DESCRIPTION
A WEBSITE THAT SUMMARISES ALL THE THINGS YOU WANT, YOU CAN ENTER TEXT, FILES AND MAINLY YOU CAN ENTER ANY NEWS RELATED TOPICS TO GET THE SUMMARY OF IT.

IT USES DISTILLED BART MODEL FOR THE ABSTRACTIVE TEXT SUMMARIZATION TRAINED WITH NEWS DATASET

TECH USED
HTML, CSS, PYTHON, FLASK, DISTILLED BART 

INSTALLTION STEP
1) INSTALL ALL LIBRARIES
2) OPEN THE MAIN FILE AND RUN IT ON THE LOCAL HOST

DEPENDENCIES OR MODULES
from operator import methodcaller
from pydoc_data.topics import topics
from turtle import title
from pprint import pprint
from webbrowser import get
import requests
import urllib.parse as urlparse
from importlib.resources import contents
from bs4 import BeautifulSoup
from pprint import pprint
import requests_html
from posixpath import split
from cgitb import text
from os import link
from traceback import print_tb
from newspaper import Article
from flask_cors import CORS
from flask import Flask, render_template, request, url_for, redirect
import googletrans
from googletrans import *
from flask_cors import cross_origin
from summary import article_summary
from flask import Flask, render_template
from flask_wtf import FlaskForm
from wtforms import FileField, SubmitField
from werkzeug.utils import secure_filename
import os
from wtforms.validators import InputRequired
import PyPDF2 
from summary import article_summary
import os
from docx import Document




PREVIOUS WORK:
NO-WORK DONE
