# DataScrapping
Sample Solution to scrape data from Lawyat Forum

List of Libraries that has been used:

from selenium import webdriver
from bs4 import BeautifulSoup
import pandas as pd
driver = webdriver.Chrome(executable_path=r'C:/webdrivers/chromedriver.exe')
