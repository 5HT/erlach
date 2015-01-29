AVZ Login System for N2O
========================

Authentication methods for N2O sites. Supports both JavaScript based
logins (like Google and Facebook) and redirect based OAuth logins (Twitter, Github)
in a sane and simple manner. Compatible with but not limited to Nitrogen and N2O.

Supported Methods
-----------------

* Twitter
* Google
* Facebook
* Github
* Microsoft

API
---

    sdk/0                % JavaScript for page embedding for JavaScript based login methods
    login_button/0       % HTML Button for page embedding
    event/1              % Page Event for HTTP redirect based login methods
    api_event/3          % Page Event for JavaScript based login methods
    callback/0           % Callback part of HTTP redirect based login methods
    registration_data/3  % Process Parameters
    
Usage
-----

Pretty short example is given at http://maxim.livejournal.com/421845.html (Russain) along
with discussion how to design pages with N2O. Example of Login also could be found in [http://github.com/5HT/skyline](http://github.com/5HT/skyline) project.

Credits
-------

* Andrii Zadorozhnii
* Maxim Sokhatsky

OM A HUM
