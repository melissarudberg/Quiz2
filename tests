from selenium import webdriver
import os
import unittest

class NewVisitorTest(unittest.TestCase):  

    def setUp(self):
        if os.name=='nt':
            # You might need to put the path to chromedriver.exe in
            # the following line as an argument to Chrome()
            # like webdriver.Chrome("C:\Program Files\Chrome") for instance

            self.browser = webdriver.Chrome()
        else:
            self.browser = webdriver.Firefox()
        self.browser.implicitly_wait(3)
