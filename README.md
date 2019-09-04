Its an web application developed using HTML, CSS, Flask and Python3.
This appliction also using API of http://data.fixer.io/api which provides us real time rate of currency of diifrernt country.
Application have two drop down form which we can select base and target currency and fill amount which is to be converted.

If you want to run this application on your own machine then first of all you should have Python3 and Flask in your system and you have to register 
at http://data.fixer.io to get API_KEY,
then made change in currencychange.py file replace each occurance of content inside parenthesis along with {} "  {os.environ.get("fixer_key")}   " == 
your_key obtained from fixer.io.
