# flaskapps
Learned 
1. About python -i option (I did not know that this existed) which is pretty cool for debugging applications. 
2. How to build and convert a Python app to a flask app (pretty cool)
3. https://financialmodelingprep.com/developer/docs/pricing/ for the stock app. Seems like an interesting api. Using the free tier. 

Misc:
All files are in projects/flaskapps. Need to move them out. 
Rignt now creating a virtual env for each app. That is too much stuff to put on git. Need to discuss with Ashish
Hosting on Heroku

Issues:
Heroku installation first failed with an obscure message 1025>1024 in path environment variable. 
Figured out that my path is full of junk and got rid of a couple of apps and freed up the space. The third shot at Heroku installation went through. 
gunicorn  - fcntl issue (many are facing these on windows). Ashish gave a workaround but I need to understand some of the solutions. 

