<h1 align="center">
	<img
		width="450"
		alt="RedirectExplorer"
		src="https://cdn.discordapp.com/attachments/772368890927644692/791859271649460245/yeeet.png">
</h1>


<h3 align="center">
	Tracing URL redirects has never been easier!
</h3>

<p align="center">
	<strong>
		<a href="https://github.com/IlluminatiFish/RedirectExplorer/blob/main/README.md#how-to-use">Usage</a>
		•
		<a href="https://github.com/IlluminatiFish/RedirectExplorer/releases">Download</a>
	</strong>
</p>
  
<p align="center">
	<a href=""><img
		alt="Python version"
		src="https://img.shields.io/badge/Python-v3.0+-red"></a>
    <a href=""><img
    	alt="Project version"
        src="https://img.shields.io/badge/Current%20Version-v0.7-red"></a>
	<a href=""><img alt="Codacy Grade" src="https://app.codacy.com/project/badge/Grade/06c8bdaa68414b7b84c096dbd47c0944"></a>
</p>  

<p align="center">
	<img src="https://i.gyazo.com/b82c8b2e36a5ecefdc0a3251ff3176f0.png" width="550">
	<img src="https://cdn.discordapp.com/attachments/361528084161232902/803697134125056090/unknown.png" width="550">
</p>

## Use Cases

- To see where an affiliate link ends up 
- To see what affiliate network is being used in this process
- Ensure that your own redirects work correctly as intended to
- To analyse suspicious URLs from various sources
- To avoid being tracked by companies
- To avoid being redirected to malicious websites
- Discover how many times a site can redirect your request
- Check if URL shortening services such as bitly and adfly redirect to legitimate websites

To learn more about the uses of redirects, and what redirects are, please read [this article](https://en.ryte.com/wiki/Redirect).


## How To Use

RedirectExplorer requires you to have ![Python](https://img.shields.io/badge/Python-informational?style=plastic&logo=python&logoColor=black&color=228ff5) on your system. The recommended version of your ![Python](https://img.shields.io/badge/Python-informational?style=plastic&logo=python&logoColor=black&color=228ff5) installation is version 3 or above.
You will also be required to install some Python modules from [here](https://pypi.org/) unless otherwise stated in this README. To install all the required modules listed here, please just follow the installation instructions found in the next section.

All you have to do, to use this script is run the ``start.py`` script and enter the URL you want to check and the results should be printed to your console or IDE.

⚠️ This is a alpha version and may have a few bugs, so be aware.


## Installation 

To have the RedirectExplorer to work properly without any hiccups, please follow the instructions below.

- Download each module from this repository (``contentparser.py``, ``utils.py`` and ``start.py``)
- Make sure each module is in the **same directory level** 
- After you have setup the modules, you will have to install each module used in this project by doing the following

	- ``pip install bs4`` in order to download the HTML parser for the contentparser.py module
	- ``pip install urllib3`` in order to parse URLs that we encounter in the redirect chains, used for both start.py and utils.py modules
	- ``pip install ssl`` in order to make SSL requests to HTTPS websites in the start.py module
	- ``pip install socket`` in order to create HTTP & HTTPS requests to be sent to the websites in the start.py module 
	- ``pip install requests`` in order to send requests to the IP information API (<a href="https://ip-api.com">IP-API</a>) used in the utils.py module which is used in the displaying of the results in the start.py module
	- ``pip install re`` in order to look for URLs in website DOM objects used in the contentparser.py module
	- ``pip install execjs`` in order to execute javascript-based redirects used in the contentparser.py module
	- ``pip install ast`` in order to make a string back into a list used for tracking cookies displayed in start.py module
	- ``pip install folium`` in order to create the URL traceroute map seen from versions above 0.6
	
## Credits & Acknowledgements

- The developers of the modules used in this project (<a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/">bs4</a>, <a href="https://github.com/urllib3/urllib3">urllib3</a>, <a href="https://github.com/python/cpython">ssl</a>, <a href="https://github.com/python/cpython">socket</a>, <a href="https://github.com/psf/requests">requests</a>, <a href="https://github.com/python/cpython">re</a>, <a href="https://python-visualization.github.io/folium/">folium</a>, <a href="https://github.com/python/cpython">ast</a> & <a href="https://github.com/doloopwhile/PyExecJS">execjs</a>)
- The developers of the <a href="https://ip-api.com">IP-API</a> website
