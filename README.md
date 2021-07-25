# Majasdarbs-26.07.2021
import pandas as pd
from bs4 import BeautifulSoup
import requests
r = requests.get("https://lv.wikipedia.org/wiki/Latvijas_dabas_rezerv%C4%81ti")
soup = BeautifulSoup(r.text, 'lxml')
print (soup.table.text)
print (soup.table.text)
