# Scrape data from the New York Times's real estate section
Currently, this program will scrape listings prices of current properties (more features coming soon!) - based upon your search criteria - and output the data in csv format. Head to the [New York Times real estate section] (http://www.nytimes.com/pages/realestate/index.html?action=click&pgtype=Homepage&region=TopBar&module=HPMiniNav&contentCollection=Real%20Estate&WT.nav=page) and enter in a neighbord, city or state and any desired price, bed, bath constraints. Copy and paste the url into the python code and type the program file into the command line: 

<pre><code>python nytimes_listings.py</code></pre>

For the program to work, the last three characters in the url must be 'p=1', as shown in the image below: 

![Image of nytimes website](https://cloud.githubusercontent.com/assets/16641405/12241734/a83352ac-b849-11e5-9755-50e662099980.png)

If your url does not currently end with 'p=1', use the 'Sort By' function, as shown in the image above. This will generate a new url that ends with 'p=1'.
