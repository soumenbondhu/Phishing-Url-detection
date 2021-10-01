# Phishing-Url-detection
phishing URLs detection using  Various Machine Learning method and verious neural network model 

A Special thanks to Author of the paper: https://ieeexplore.ieee.org/document/8730309

URL is made up of four components: the protocol, the domain name, the file path and the query parameters.
Most web browsers display the URL of a web page above the page in an address bar. A common syntax of URL is describe on the figure

![Url Segment](https://github.com/soumenbondhu/Phishing-Url-detection/blob/main/url.PNG)
As an example of common URL looks like http://www.exampleurl.com/info/about.html, which indicates a protocol (http), a host name (www.exampleurl.com) includes top level
Domain (.com), 2nd level domain (exampleurl) and 3rd, level domain or sub-domain (www.), directory (info) and a file name (about.html).



# Sensitive Feature Extraction from URLs
Illegal URLs are generally disguised as legitimate ones by phishing attackers. By doing
so, the attacker can lure users to click to illegal website. Only sensitive features is able to
identify the URL is phishing URLs or not. The sensitive features are categorized into four classes:
• The address bar relevant features
• The abnormal features
• The HTML and JavaScript relevant features
• The domain relevant features.
Each feature is assigned with a number from three values (1, 0 or 1) for each of them.

The Data set link is : http://archive.ics.uci.edu/ml/index.php
