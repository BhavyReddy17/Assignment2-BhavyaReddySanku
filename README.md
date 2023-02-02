# Assignment2-BhavyaReddySanku
# Bhavya Reddy Sanku
###### Indian Cricket team
> Cricket is one of the most interesting games that every indian likes. 
>> This game consists of **11 players** on each, **two members from one team will be batting** and one member from opposite team will be bowling others will be feilding.
---
# Indian Cricket Team
### Three best players on the team
1. M.S.Dhoni
2. Virat Kholi
3. Hardik Pandiya
---
### other teams that would be good to watch play

* Pakistan 
* England 
* Newzeland

[www.aboutme.com](AboutMe.md)

---

| Name of the country | Purpouse of Visit| No of Days |
| --- | --- | ---: |
| United States| Disney has been bringing happiness to children and adults since 1937 | 25 |
| Canada | A visit to any city with a sports bar during a hockey season | 20 |
| Australia |  Sydney opera House| 15 |
| Finland | The Happiest Country in the World, as well as having the world's best education system and cleanest air. | 30 |

---
### Pithy Quotes
> The first step is to establish that something is possible; then probability will occur - *Elon Musk* <br>
> It's hard to soar with the eagles when you're surrounded by turkeys - *Adam Sandler*

---
```
var userAgent = navigator.userAgent.toLowerCase(),
    browser   = '',
    version   = 0;

$.browser.chrome = /chrome/.test(navigator.userAgent.toLowerCase());

// Is this a version of IE?
if ($.browser.msie) {
  userAgent = $.browser.version;
  userAgent = userAgent.substring(0,userAgent.indexOf('.'));	
  version = userAgent;
  browser = "Internet Explorer";
}

// Is this a version of Chrome?
if ($.browser.chrome) {
  userAgent = userAgent.substring(userAgent.indexOf('chrome/') + 7);
  userAgent = userAgent.substring(0,userAgent.indexOf('.'));	
  version = userAgent;
  // If it is chrome then jQuery thinks it's safari so we have to tell it it isn't
  $.browser.safari = false;
  browser = "Chrome";
}

// Is this a version of Safari?
if ($.browser.safari) {
  userAgent = userAgent.substring(userAgent.indexOf('safari/') + 7);	
  userAgent = userAgent.substring(0,userAgent.indexOf('.'));
  version = userAgent;	
  browser = "Safari";
}

// Is this a version of Mozilla?
if ($.browser.mozilla) {
	//Is it Firefox?
	if (navigator.userAgent.toLowerCase().indexOf('firefox') != -1) {
		userAgent = userAgent.substring(userAgent.indexOf('firefox/') + 8);
		userAgent = userAgent.substring(0,userAgent.indexOf('.'));
		version = userAgent;
		browser = "Firefox"
	}
	// If not then it must be another Mozilla
	else {
	  browser = "Mozilla (not Firefox)"
	}
}

// Is this a version of Opera?
if ($.browser.opera) {
	userAgent = userAgent.substring(userAgent.indexOf('version/') + 8);
	userAgent = userAgent.substring(0,userAgent.indexOf('.'));
	version = userAgent;
	browser = "Opera";
}
```