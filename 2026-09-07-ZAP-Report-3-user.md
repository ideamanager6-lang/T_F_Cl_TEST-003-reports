# ZAP by Checkmarx Scanning Report

ZAP by [Checkmarx](https://checkmarx.com/).


## Summary of Alerts

| Risk Level | Number of Alerts |
| --- | --- |
| High | 0 |
| Medium | 3 |
| Low | 6 |
| Informational | 4 |




## Insights

| Level | Reason | Site | Description | Statistic |
| --- | --- | --- | --- | --- |
| Low | Warning |  | ZAP warnings logged - see the zap.log file for details | 19    |
| Low | Exceeded High | https://t-f-cl-test-003.vercel.app | Percentage of slow responses | 96 % |
| Info | Informational | http://t-f-cl-test-003.vercel.app | Percentage of responses with status code 3xx | 100 % |
| Info | Informational | https://beacons.gcp.gvt2.com | Percentage of responses with status code 2xx | 100 % |
| Info | Informational | https://beacons.gcp.gvt2.com | Percentage of endpoints with content type application/javascript | 100 % |
| Info | Informational | https://beacons.gcp.gvt2.com | Percentage of endpoints with method POST | 100 % |
| Info | Informational | https://beacons.gcp.gvt2.com | Count of total endpoints | 2    |
| Info | Informational | https://beacons.gcp.gvt2.com | Percentage of slow responses | 50 % |
| Info | Informational | https://chromewebstore.googleapis.com | Percentage of responses with status code 2xx | 100 % |
| Info | Informational | https://chromewebstore.googleapis.com | Percentage of endpoints with content type application/x-protobuf | 100 % |
| Info | Informational | https://chromewebstore.googleapis.com | Percentage of endpoints with method POST | 100 % |
| Info | Informational | https://chromewebstore.googleapis.com | Count of total endpoints | 1    |
| Info | Informational | https://chromewebstore.googleapis.com | Percentage of slow responses | 100 % |
| Info | Informational | https://clientservices.googleapis.com | Percentage of responses with status code 2xx | 100 % |
| Info | Informational | https://clientservices.googleapis.com | Percentage of endpoints with content type text/plain | 100 % |
| Info | Informational | https://clientservices.googleapis.com | Percentage of endpoints with method POST | 100 % |
| Info | Informational | https://clientservices.googleapis.com | Count of total endpoints | 1    |
| Info | Informational | https://clientservices.googleapis.com | Percentage of slow responses | 100 % |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of responses with status code 2xx | 100 % |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of endpoints with content type text/plain | 100 % |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of endpoints with method GET | 100 % |
| Info | Informational | https://content-autofill.googleapis.com | Count of total endpoints | 3    |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of slow responses | 100 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of responses with status code 2xx | 56 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of responses with status code 3xx | 1 % |
| Info | Exceeded Low | https://t-f-cl-test-003.vercel.app | Percentage of responses with status code 4xx | 25 % |
| Info | Exceeded Low | https://t-f-cl-test-003.vercel.app | Percentage of responses with status code 5xx | 17 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of endpoints with content type application/javascript | 31 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of endpoints with content type font/woff2 | 8 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of endpoints with content type image/vnd.microsoft.icon | 2 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of endpoints with content type text/css | 2 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of endpoints with content type text/html | 2 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of endpoints with content type text/plain | 2 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of endpoints with content type text/x-component | 51 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of endpoints with method GET | 84 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Percentage of endpoints with method POST | 15 % |
| Info | Informational | https://t-f-cl-test-003.vercel.app | Count of total endpoints | 45    |
| Info | Informational | https://update.googleapis.com | Percentage of responses with status code 2xx | 100 % |
| Info | Informational | https://update.googleapis.com | Percentage of endpoints with content type application/json | 100 % |
| Info | Informational | https://update.googleapis.com | Percentage of endpoints with method POST | 100 % |
| Info | Informational | https://update.googleapis.com | Count of total endpoints | 5    |
| Info | Informational | https://update.googleapis.com | Percentage of slow responses | 100 % |







## Alerts

| Name | Risk Level | Number of Instances |
| --- | --- | --- |
| Content Security Policy (CSP) Header Not Set | Medium | 1 |
| Cross-Domain Misconfiguration | Medium | Systemic |
| Missing Anti-clickjacking Header | Medium | 1 |
| Cookie No HttpOnly Flag | Low | 4 |
| Cookie Without Secure Flag | Low | 4 |
| Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s) | Low | 1 |
| Server Leaks Version Information via "Server" HTTP Response Header Field | Low | 1 |
| Strict-Transport-Security Header Not Set | Low | 12 |
| X-Content-Type-Options Header Missing | Low | Systemic |
| Re-examine Cache-control Directives | Informational | 3 |
| Retrieved from Cache | Informational | Systemic |
| Session Management Response Identified | Informational | 5 |
| User Agent Fuzzer | Informational | Systemic |




## Alert Detail



### [ Content Security Policy (CSP) Header Not Set ](https://www.zaproxy.org/docs/alerts/10038/)



##### Medium (High)

### Description

Content Security Policy (CSP) is an added layer of security that helps to detect and mitigate certain types of attacks, including Cross Site Scripting (XSS) and data injection attacks. These attacks are used for everything from data theft to site defacement or distribution of malware. CSP provides a set of standard HTTP headers that allow website owners to declare approved sources of content that browsers should be allowed to load on that page — covered types are JavaScript, CSS, HTML frames, fonts, images and embeddable objects such as Java applets, ActiveX, audio and video files.

* URL: https://t-f-cl-test-003.vercel.app/
  * Node Name: `https://t-f-cl-test-003.vercel.app/`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``


Instances: 1

### Solution

Ensure that your web server, application server, load balancer, etc. is configured to set the Content-Security-Policy header.

### Reference


* [ https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CSP ](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CSP)
* [ https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html ](https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html)
* [ https://www.w3.org/TR/CSP/ ](https://www.w3.org/TR/CSP/)
* [ https://w3c.github.io/webappsec-csp/ ](https://w3c.github.io/webappsec-csp/)
* [ https://web.dev/articles/csp ](https://web.dev/articles/csp)
* [ https://caniuse.com/#feat=contentsecuritypolicy ](https://caniuse.com/#feat=contentsecuritypolicy)
* [ https://content-security-policy.com/ ](https://content-security-policy.com/)


#### CWE Id: [ 693 ](https://cwe.mitre.org/data/definitions/693.html)


#### WASC Id: 15

#### Source ID: 3

### [ Cross-Domain Misconfiguration ](https://www.zaproxy.org/docs/alerts/10098/)



##### Medium (Medium)

### Description

Web browser data loading may be possible, due to a Cross Origin Resource Sharing (CORS) misconfiguration on the web server.

* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/chunks/3o3-pqfgq6cb5.css
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/chunks/3o3-pqfgq6cb5.css`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/chunks/turbopack-3owek367tc1ue.js
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/chunks/turbopack-3owek367tc1ue.js`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-400-normal.19gbeb610ur4n.woff2
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-400-normal.19gbeb610ur4n.woff2`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-500-normal.25_05y-blbp24.woff2
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-500-normal.25_05y-blbp24.woff2`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/special-elite-latin-400-normal.2mza6l9y4lmq8.woff2
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/special-elite-latin-400-normal.2mza6l9y4lmq8.woff2`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`

Instances: Systemic


### Solution

Ensure that sensitive data is not available in an unauthenticated manner (using IP address white-listing, for instance).
Configure the "Access-Control-Allow-Origin" HTTP header to a more restrictive set of domains, or remove all CORS headers entirely, to allow the web browser to enforce the Same Origin Policy (SOP) in a more restrictive manner.

### Reference


* [ https://vulncat.fortify.com/en/detail?category=HTML5&subcategory=Overly%20Permissive%20CORS%20Policy ](https://vulncat.fortify.com/en/detail?category=HTML5&subcategory=Overly%20Permissive%20CORS%20Policy)


#### CWE Id: [ 264 ](https://cwe.mitre.org/data/definitions/264.html)


#### WASC Id: 14

#### Source ID: 3

### [ Missing Anti-clickjacking Header ](https://www.zaproxy.org/docs/alerts/10020/)



##### Medium (Medium)

### Description

The response does not protect against 'ClickJacking' attacks. It should include either Content-Security-Policy with 'frame-ancestors' directive or X-Frame-Options.

* URL: https://t-f-cl-test-003.vercel.app/
  * Node Name: `https://t-f-cl-test-003.vercel.app/`
  * Method: `GET`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``


Instances: 1

### Solution

Modern Web browsers support the Content-Security-Policy and X-Frame-Options HTTP headers. Ensure one of them is set on all web pages returned by your site/app.
If you expect the page to be framed only by pages on your server (e.g. it's part of a FRAMESET) then you'll want to use SAMEORIGIN, otherwise if you never expect the page to be framed, you should use DENY. Alternatively consider implementing Content Security Policy's "frame-ancestors" directive.

### Reference


* [ https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/X-Frame-Options ](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/X-Frame-Options)


#### CWE Id: [ 1021 ](https://cwe.mitre.org/data/definitions/1021.html)


#### WASC Id: 15

#### Source ID: 3

### [ Cookie No HttpOnly Flag ](https://www.zaproxy.org/docs/alerts/10010/)



##### Low (Medium)

### Description

A cookie has been set without the HttpOnly flag, which means that the cookie can be accessed by JavaScript. If a malicious script can be run on this page then the cookie will be accessible and can be transmitted to another site. If this is a session cookie then session hijacking may be possible.

* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token`
  * Attack: ``
  * Evidence: `Set-Cookie: sb-zznkykduwjrefvxoiwkx-auth-token`
  * Other Info: ``
* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token-code-verifier`
  * Attack: ``
  * Evidence: `Set-Cookie: sb-zznkykduwjrefvxoiwkx-auth-token-code-verifier`
  * Other Info: ``
* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token-flow-a519bb59447a891e20565b79169ca198-code-verifier`
  * Attack: ``
  * Evidence: `Set-Cookie: sb-zznkykduwjrefvxoiwkx-auth-token-flow-a519bb59447a891e20565b79169ca198-code-verifier`
  * Other Info: ``
* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token-flows-code-verifier`
  * Attack: ``
  * Evidence: `Set-Cookie: sb-zznkykduwjrefvxoiwkx-auth-token-flows-code-verifier`
  * Other Info: ``


Instances: 4

### Solution

Ensure that the HttpOnly flag is set for all cookies.

### Reference


* [ https://owasp.org/www-community/HttpOnly ](https://owasp.org/www-community/HttpOnly)


#### CWE Id: [ 1004 ](https://cwe.mitre.org/data/definitions/1004.html)


#### WASC Id: 13

#### Source ID: 3

### [ Cookie Without Secure Flag ](https://www.zaproxy.org/docs/alerts/10011/)



##### Low (Medium)

### Description

A cookie has been set without the secure flag, which means that the cookie can be accessed via unencrypted connections.

* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token`
  * Attack: ``
  * Evidence: `Set-Cookie: sb-zznkykduwjrefvxoiwkx-auth-token`
  * Other Info: ``
* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token-code-verifier`
  * Attack: ``
  * Evidence: `Set-Cookie: sb-zznkykduwjrefvxoiwkx-auth-token-code-verifier`
  * Other Info: ``
* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token-flow-a519bb59447a891e20565b79169ca198-code-verifier`
  * Attack: ``
  * Evidence: `Set-Cookie: sb-zznkykduwjrefvxoiwkx-auth-token-flow-a519bb59447a891e20565b79169ca198-code-verifier`
  * Other Info: ``
* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token-flows-code-verifier`
  * Attack: ``
  * Evidence: `Set-Cookie: sb-zznkykduwjrefvxoiwkx-auth-token-flows-code-verifier`
  * Other Info: ``


Instances: 4

### Solution

Whenever a cookie contains sensitive information or is a session token, then it should always be passed using an encrypted channel. Ensure that the secure flag is set for cookies containing such sensitive information.

### Reference


* [ https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/06-Session_Management_Testing/02-Testing_for_Cookies_Attributes.html ](https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/06-Session_Management_Testing/02-Testing_for_Cookies_Attributes.html)


#### CWE Id: [ 614 ](https://cwe.mitre.org/data/definitions/614.html)


#### WASC Id: 13

#### Source ID: 3

### [ Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s) ](https://www.zaproxy.org/docs/alerts/10037/)



##### Low (Medium)

### Description

The web/application server is leaking information via one or more "X-Powered-By" HTTP response headers. Access to such information may facilitate attackers identifying other frameworks/components your web application is reliant upon and the vulnerabilities such components may be subject to.

* URL: https://t-f-cl-test-003.vercel.app/
  * Node Name: `https://t-f-cl-test-003.vercel.app/`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `X-Powered-By: Next.js`
  * Other Info: ``


Instances: 1

### Solution

Ensure that your web server, application server, load balancer, etc. is configured to suppress "X-Powered-By" headers.

### Reference


* [ https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/01-Information_Gathering/08-Fingerprint_Web_Application_Framework ](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/01-Information_Gathering/08-Fingerprint_Web_Application_Framework)
* [ https://www.troyhunt.com/shhh-dont-let-your-response-headers/ ](https://www.troyhunt.com/shhh-dont-let-your-response-headers/)


#### CWE Id: [ 497 ](https://cwe.mitre.org/data/definitions/497.html)


#### WASC Id: 13

#### Source ID: 3

### [ Server Leaks Version Information via "Server" HTTP Response Header Field ](https://www.zaproxy.org/docs/alerts/10036/)



##### Low (High)

### Description

The web/application server is leaking version information via the "Server" HTTP response header. Access to such information may facilitate attackers identifying other vulnerabilities your web/application server is subject to.

* URL: https://clientservices.googleapis.com/uma/v2
  * Node Name: `https://clientservices.googleapis.com/uma/v2 ()(B2	É_ª¾Åz#	 2	...,	ït Ê<«E ¯õâÔ152.0.7977.82-64...,	$ª-Z!P®(0ùð	Nÿÿÿÿ2,	0ð
þ[¥RV2...,	Zñv,	\_$ÁêÅuïÔ
/@ïv¡2...,	¼ª*s)}NR2z...,	ÍËõ,ß*·å­ ùð	Nÿÿÿÿ2...,	áü®fAÎÛº    ¥
2..., 2	Vcé¶âÄ/ 2	õ>Çªrª...,*K S\eozµÈô ...,* 2	éäÍàu  2$	R¾`þûû...,; 20	èPEª%ªã³...,c    ...,6 	¥µ 
º¶Çí 
ÙêÎ ...,1¡?ÉQi Ò ô® Å...,R¬ ÖÒ%2	ÄÊ,1 
ô¢ 2	JØLÚ¦¾«Æô...,¬ 2	-a~}¹fø55<2	 ¹ó¾V~^¸¿...,Â 2	2Þ¦\G52	<ýîðÍÐ...,`Y 29	7Ás*·%µG   ...,Ë
ñw   2	ùÅ¦ A 12	...,2	ÛØU¼ã*fp2	½,ÐÊløk2	9¬×...,	2	?ÁÂ¡ßÆ*¨2...,ò)2	g5CHU 2	BÍ3æÃDQ...,'Á(¥)à*â*õ* à ...,'Á(¥)à*â*õ* à ...,â,â,   ,      ...,      ...,(2#	%íw+wýãJx  ...,(2#	¶þ\½hÁ}x  ...,H ,W *i   » ã ...,  » ã 	 Í ..., 2	K¯Aíë2	#þn-÷5..., 2	Õø!ÄÜ7 2	(Xû+DP..., 2	äÉD °£ 2<	r§5±Ê..., , 2	8ÜÿVBÄ¾2	Ï#µa*ÙA...,¬ ­1þ?îH¾z¼
Ú ...,øDÌS®eôzÂ 
Ðÿÿÿÿ2k	%...,¨*§. ¯ º£ï²2	ÐÞT³³ú...,¨*§. ¯ º£ï²2|	M }ß...,'; 2	 XCUh4x 2	ß,$ª...,/	 2	kh½Oµ4 $2	ø1;©Z@...,I2	3jcO l2	¦ûwï«q2	¥..., «)2	©´(ÈXxûû2	å[ÿM ..., Ðà/ 	ïÈ0 .ÚÃÜ2¾¿5 §..., 2	, 52	|Ü9ýà. 52m	Ñ[ÕoëËenè ...,#Z2	ý¶Yz,2	ÏmjG^rÞ "2c	ÚÁå³¨$<N ...,2	Ë$ú¥]v@ú 2	¿i¾ûøç¸ 2...,2.	±Ôù	°
 9D	...,2e	¼Ø§MÓe«a  
 ,7E³K   K2	iÙWó@»2x	E...,;,>èk 2.	Ì
÷ä¨bÜü k 
...,@çí×P8	 	2	×'/%Ñ"0P 2	­`£#...,B¦R¬ ÖÒ%2	ôHPÝóëGµ§o...,Fj.a 2	ùDÊ)]H2	...,KÇ«k<2	,P¹m|	,Wë;µ2	weQ½ î2	ßLéöS5...,Y2	Ð$¦DâÏß2	zË²ÿ×ÍeðîG
 þ...,báËD2	íµ;t]÷f\2	zÏ\®%U...,cuìÖÂè2	LdY/ª´j¤ÖÂè2	...,cðG·B2	ìÅ	û¢{2	;¸Mú©Ôº×þ...,eJø¨ 2	54{ dQ 2	7qAoÑª...,e\ùé9þ2	N].mB×þ 2	82©Qx6...,hÃ¾2	Ø*§Ìÿ 2	ÁD¬...,r%¾Dj 2	úå"ïà 2	ØAÔÓ¡+...,tØÖÒ®2	¼¬Asû\2	CpfÓÎê³...,x§Q ÈÉ2	}ýªóÈÉ2	°71ôò...,yüR¨oæÞJ
6¼¨oæÞJ
q¤¨oæÞJ
Ü¿qÿ...,{õ²¾`¼2	3|ôÖd»À2	8Ós2Ë...,| 2	Vð¹ï 2	yY@w_Õ...,~5 2	¶r'}_ð 2	ÐõÀàb$...,~¨mt2	,¹5xÊu¢ë2	%§Ä2...,¥­¯Ëº 2	áÛ2	¹?Ö°ýÞ...,¬¢ûû2	Ä#wâî2	{©6Þ zØ...,K8ò2	ý÷ó¶~û2	­GkbH8...,bR­ "C EGLQ ...,mÆ 2	ñÈÞ´z{2	i3,ó@Ë_0  2..., ÌD2	½K·pÿ§2	\ÒLþ2	..., Öª2	¦¿uÍàs2	QpL±K_...,£qË{|å2	3d­Õ£z:2	`GPhºÀ0...,¤ïºà	¯úÈ
2	¿Ã?Ôì½ÞÔIìCÿ...,¨§42	v	_]§"?2	¹§¼-Íß2...,ª¶×¸I"2	q8~A)Rïþ2	sµõQÏ6«...,«2	Þ35EkÂ2	,«HîH0@ 2	bÒÓåìoþ 2	...,®¨ìþh 2	zz	£ò.<çTØâ...,¯;ô2	^jøÐ×332	Cöôõ6Æ`2...,°!lñéòé2	.Oêâ)¦dèÌé...,´vX, 2Ã	RMºDg«ìã ...,ºC2	¯áòÉð02	v_,Ñ W...,»F÷}é¤Ú ,¿ÍÚÃ
 î 	   Õ...,ÅÍ¢müE\!@P2.	åÍ)>g...,Æ2	0Å[^Y{û2	][w°#UA...,Ê¼¯ 4BT ¾Ùô¢...,Î³ 2	Vn6ÞR¤E2	D«...,Îð:ªåÔPÒr
ëÓù 2	ZÚvÄê...,Ð~ ´h2	åð'(çØé­ 2	ÙÚáL...,Ñ¨¼2	}¸>1¸2	÷](.2	...,Ñ÷pÔ2	2"Lü~ý2	...,Ô¿2	Û]g«_cf2	¡­Ì}Kk2...,çBÏ 2	8(à,éy[,îIÄäÎäÌ 
(0D...,î¥v  2	Ù¼­A£÷A6E 
 	!...,ïÎzñó2	 í3 á2	D²ö...,ñ/2	.ÞÒ#¾¡2	bPÈ8Æ52	È...,õ,2	ò2^¶R2	¾;êÅïÝÈ...,÷R§ß÷°
 BTk ¾Ù...,úwªjù    ...,ýYGxôË¢2	y/ó%2TUØ+¥ ...,ÿTe§a¼`Ür2	æàòQÈÉëõ2	Ñ...)`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: `scaffolding on HTTPServer2`
  * Other Info: ``


Instances: 1

### Solution

Ensure that your web server, application server, load balancer, etc. is configured to suppress the "Server" header or provide generic details.

### Reference


* [ https://httpd.apache.org/docs/current/mod/core.html#servertokens ](https://httpd.apache.org/docs/current/mod/core.html#servertokens)
* [ https://learn.microsoft.com/en-us/previous-versions/msp-n-p/ff648552(v=pandp.10) ](https://learn.microsoft.com/en-us/previous-versions/msp-n-p/ff648552(v=pandp.10))
* [ https://www.troyhunt.com/shhh-dont-let-your-response-headers/ ](https://www.troyhunt.com/shhh-dont-let-your-response-headers/)


#### CWE Id: [ 497 ](https://cwe.mitre.org/data/definitions/497.html)


#### WASC Id: 13

#### Source ID: 3

### [ Strict-Transport-Security Header Not Set ](https://www.zaproxy.org/docs/alerts/10035/)



##### Low (High)

### Description

HTTP Strict Transport Security (HSTS) is a web security policy mechanism whereby a web server declares that complying user agents (such as a web browser) are to interact with it using only secure HTTPS connections (i.e. HTTP layered over TLS/SSL). HSTS is an IETF standards track protocol and is specified in RFC 6797.

* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJ0CVkm8CPDKamKEg8N77-NcyoICAcQBxgBIAMSDw0AoAvKKggIAhACGAEgBRIPDYOoWz0qCAgFEAUYBSAEEg8NEg_8aioICAcQBxgGIAQSDw2erW9sKggIBhAGGAcgBiFQnbrTyvMUEClQnbrTyvMUEDICIAA=%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJ0CVkm8CPDKamKEg8N77-NcyoICAcQBxgBIAMSDw0AoAvKKggIAhACGAEgBRIPDYOoWz0qCAgFEAUYBSAEEg8NEg_8aioICAcQBxgGIAQSDw2erW9sKggIBhAGGAcgBiFQnbrTyvMUEClQnbrTyvMUEDICIAA= (alt)`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJBCdeR6xd0dUEzEg8NEg_8aioICAMQBxgGIAQSDw2erW9sKggIABAGGAcgBSHz7xDDePCQqinyeyWc0LCwlDICIAU=%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJBCdeR6xd0dUEzEg8NEg_8aioICAMQBxgGIAQSDw2erW9sKggIABAGGAcgBSHz7xDDePCQqinyeyWc0LCwlDICIAU= (alt)`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJFCQJ1kIPXkKnYEhENg6hbPSoKCAIQBRgFIARIBRIRDc5BTHoqCggFEAIYAiAESAIhgRet93kpAKIp_Mpy3Q0joG8yAiAH%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJFCQJ1kIPXkKnYEhENg6hbPSoKCAIQBRgFIARIBRIRDc5BTHoqCggFEAIYAiAESAIhgRet93kpAKIp_Mpy3Q0joG8yAiAH (alt)`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://beacons.gcp.gvt2.com/domainreliability/upload
  * Node Name: `https://beacons.gcp.gvt2.com/domainreliability/upload ()({entries:[{failure_data:{custom_error},http_response_code,network_changed,protocol,request_age_ms,request_elapsed_ms,sample_rate,server_ip,status,url,was_proxied}],reporter})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://beacons.gcp.gvt2.com/domainreliability/upload
  * Node Name: `https://beacons.gcp.gvt2.com/domainreliability/upload ()({entries:[{http_response_code,network_changed,protocol,request_age_ms,request_elapsed_ms,sample_rate,server_ip,status,url,was_proxied}],reporter})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://chromewebstore.googleapis.com/v2/items/-/storeMetadata:batchGet
  * Node Name: `https://chromewebstore.googleapis.com/v2/items/-/storeMetadata:batchGet ()(
items/-4items/bepaeobkmdahlmcjllhlfob...)`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://clientservices.googleapis.com/uma/v2
  * Node Name: `https://clientservices.googleapis.com/uma/v2 ()(B2	É_ª¾Åz#	 2	...,	ït Ê<«E ¯õâÔ152.0.7977.82-64...,	$ª-Z!P®(0ùð	Nÿÿÿÿ2,	0ð
þ[¥RV2...,	Zñv,	\_$ÁêÅuïÔ
/@ïv¡2...,	¼ª*s)}NR2z...,	ÍËõ,ß*·å­ ùð	Nÿÿÿÿ2...,	áü®fAÎÛº    ¥
2..., 2	Vcé¶âÄ/ 2	õ>Çªrª...,*K S\eozµÈô ...,* 2	éäÍàu  2$	R¾`þûû...,; 20	èPEª%ªã³...,c    ...,6 	¥µ 
º¶Çí 
ÙêÎ ...,1¡?ÉQi Ò ô® Å...,R¬ ÖÒ%2	ÄÊ,1 
ô¢ 2	JØLÚ¦¾«Æô...,¬ 2	-a~}¹fø55<2	 ¹ó¾V~^¸¿...,Â 2	2Þ¦\G52	<ýîðÍÐ...,`Y 29	7Ás*·%µG   ...,Ë
ñw   2	ùÅ¦ A 12	...,2	ÛØU¼ã*fp2	½,ÐÊløk2	9¬×...,	2	?ÁÂ¡ßÆ*¨2...,ò)2	g5CHU 2	BÍ3æÃDQ...,'Á(¥)à*â*õ* à ...,'Á(¥)à*â*õ* à ...,â,â,   ,      ...,      ...,(2#	%íw+wýãJx  ...,(2#	¶þ\½hÁ}x  ...,H ,W *i   » ã ...,  » ã 	 Í ..., 2	K¯Aíë2	#þn-÷5..., 2	Õø!ÄÜ7 2	(Xû+DP..., 2	äÉD °£ 2<	r§5±Ê..., , 2	8ÜÿVBÄ¾2	Ï#µa*ÙA...,¬ ­1þ?îH¾z¼
Ú ...,øDÌS®eôzÂ 
Ðÿÿÿÿ2k	%...,¨*§. ¯ º£ï²2	ÐÞT³³ú...,¨*§. ¯ º£ï²2|	M }ß...,'; 2	 XCUh4x 2	ß,$ª...,/	 2	kh½Oµ4 $2	ø1;©Z@...,I2	3jcO l2	¦ûwï«q2	¥..., «)2	©´(ÈXxûû2	å[ÿM ..., Ðà/ 	ïÈ0 .ÚÃÜ2¾¿5 §..., 2	, 52	|Ü9ýà. 52m	Ñ[ÕoëËenè ...,#Z2	ý¶Yz,2	ÏmjG^rÞ "2c	ÚÁå³¨$<N ...,2	Ë$ú¥]v@ú 2	¿i¾ûøç¸ 2...,2.	±Ôù	°
 9D	...,2e	¼Ø§MÓe«a  
 ,7E³K   K2	iÙWó@»2x	E...,;,>èk 2.	Ì
÷ä¨bÜü k 
...,@çí×P8	 	2	×'/%Ñ"0P 2	­`£#...,B¦R¬ ÖÒ%2	ôHPÝóëGµ§o...,Fj.a 2	ùDÊ)]H2	...,KÇ«k<2	,P¹m|	,Wë;µ2	weQ½ î2	ßLéöS5...,Y2	Ð$¦DâÏß2	zË²ÿ×ÍeðîG
 þ...,báËD2	íµ;t]÷f\2	zÏ\®%U...,cuìÖÂè2	LdY/ª´j¤ÖÂè2	...,cðG·B2	ìÅ	û¢{2	;¸Mú©Ôº×þ...,eJø¨ 2	54{ dQ 2	7qAoÑª...,e\ùé9þ2	N].mB×þ 2	82©Qx6...,hÃ¾2	Ø*§Ìÿ 2	ÁD¬...,r%¾Dj 2	úå"ïà 2	ØAÔÓ¡+...,tØÖÒ®2	¼¬Asû\2	CpfÓÎê³...,x§Q ÈÉ2	}ýªóÈÉ2	°71ôò...,yüR¨oæÞJ
6¼¨oæÞJ
q¤¨oæÞJ
Ü¿qÿ...,{õ²¾`¼2	3|ôÖd»À2	8Ós2Ë...,| 2	Vð¹ï 2	yY@w_Õ...,~5 2	¶r'}_ð 2	ÐõÀàb$...,~¨mt2	,¹5xÊu¢ë2	%§Ä2...,¥­¯Ëº 2	áÛ2	¹?Ö°ýÞ...,¬¢ûû2	Ä#wâî2	{©6Þ zØ...,K8ò2	ý÷ó¶~û2	­GkbH8...,bR­ "C EGLQ ...,mÆ 2	ñÈÞ´z{2	i3,ó@Ë_0  2..., ÌD2	½K·pÿ§2	\ÒLþ2	..., Öª2	¦¿uÍàs2	QpL±K_...,£qË{|å2	3d­Õ£z:2	`GPhºÀ0...,¤ïºà	¯úÈ
2	¿Ã?Ôì½ÞÔIìCÿ...,¨§42	v	_]§"?2	¹§¼-Íß2...,ª¶×¸I"2	q8~A)Rïþ2	sµõQÏ6«...,«2	Þ35EkÂ2	,«HîH0@ 2	bÒÓåìoþ 2	...,®¨ìþh 2	zz	£ò.<çTØâ...,¯;ô2	^jøÐ×332	Cöôõ6Æ`2...,°!lñéòé2	.Oêâ)¦dèÌé...,´vX, 2Ã	RMºDg«ìã ...,ºC2	¯áòÉð02	v_,Ñ W...,»F÷}é¤Ú ,¿ÍÚÃ
 î 	   Õ...,ÅÍ¢müE\!@P2.	åÍ)>g...,Æ2	0Å[^Y{û2	][w°#UA...,Ê¼¯ 4BT ¾Ùô¢...,Î³ 2	Vn6ÞR¤E2	D«...,Îð:ªåÔPÒr
ëÓù 2	ZÚvÄê...,Ð~ ´h2	åð'(çØé­ 2	ÙÚáL...,Ñ¨¼2	}¸>1¸2	÷](.2	...,Ñ÷pÔ2	2"Lü~ý2	...,Ô¿2	Û]g«_cf2	¡­Ì}Kk2...,çBÏ 2	8(à,éy[,îIÄäÎäÌ 
(0D...,î¥v  2	Ù¼­A£÷A6E 
 	!...,ïÎzñó2	 í3 á2	D²ö...,ñ/2	.ÞÒ#¾¡2	bPÈ8Æ52	È...,õ,2	ò2^¶R2	¾;êÅïÝÈ...,÷R§ß÷°
 BTk ¾Ù...,úwªjù    ...,ýYGxôË¢2	y/ó%2TUØ+¥ ...,ÿTe§a¼`Ür2	æàòQÈÉëõ2	Ñ...)`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://update.googleapis.com/service/update2/json
  * Node Name: `https://update.googleapis.com/service/update2/json ()({request:{@os,@updater,acceptformat,apps:[{accept_locale,appid,cohort,cohortname,enabled,events:[{download_time_ms,downloaded,downloader,eventresult,eventtype,nextversion,pipeline_id,previousversion,total,url},{eventresult,eventtype,nextversion,pipeline_id,previousversion}..,{eventresult,eventtype,nextversion,previousversion}],installdate,lang,version}],arch,dedup,domainjoined,hw:{avx,physmemory,sse,sse2,sse3,sse41,sse42,ssse3},ismachine,os:{arch,platform,version},prodversion,protocol,requestid,sessionid...)`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://update.googleapis.com/service/update2/json
  * Node Name: `https://update.googleapis.com/service/update2/json ()({request:{@os,@updater,acceptformat,apps:[{appid,cohort,cohortname,enabled,events:[{download_time_ms,downloaded,downloader,eventresult,eventtype,nextversion,pipeline_id,previousversion,total,url},{eventresult,eventtype,nextversion,pipeline_id,previousversion},{eventresult,eventtype,nextversion,previousversion}],installdate,lang,version}],arch,dedup,domainjoined,hw:{avx,physmemory,sse,sse2,sse3,sse41,sse42,ssse3},ismachine,os:{arch,platform,version},prodversion,protocol,requestid,sessionid,updaterversion}})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://update.googleapis.com/service/update2/json
  * Node Name: `https://update.googleapis.com/service/update2/json ()({request:{@os,@updater,acceptformat,apps:[{appid,cohort,cohortname,enabled,events:[{download_time_ms,downloaded,downloader,eventresult,eventtype,nextversion,pipeline_id,previousversion,total,url},{eventresult,eventtype,nextversion,pipeline_id,previousversion}..,{eventresult,eventtype,nextversion,previousversion}],installdate,lang,version}],arch,dedup,domainjoined,hw:{avx,physmemory,sse,sse2,sse3,sse41,sse42,ssse3},ismachine,os:{arch,platform,version},prodversion,protocol,requestid,sessionid,updaterversion}})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://update.googleapis.com/service/update2/json%3Fcup2key=16:KqUgD40cQ5BgT17XatzPV8BXe5Hq-8ZqzJGUTuBn43k&cup2hreq=506e167b4fff6676192b1600c27b21d6dd4314116be70ef67b1e19f6ea433e9a
  * Node Name: `https://update.googleapis.com/service/update2/json (cup2hreq,cup2key)({request:{@os,@updater,acceptformat,apps:[{appid,enabled,installdate,ping:{ad,r},release_channel,updatecheck:{updatedisabled},version}],arch,dedup,domainjoined,hw:{avx,physmemory,sse,sse2,sse3,sse41,sse42,ssse3},ismachine,os:{arch,platform,version},prodchannel,prodversion,protocol,requestid,sessionid,updaterchannel,updaterversion}})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://update.googleapis.com/service/update2/json%3Fcup2key=16:fgDSB6mfLc6pfgc3wx2oLtBb8JKQuOnBI0Jel97FXag&cup2hreq=b1e864883af2a2967a4396d6414cbbbad86b4503d6b0b9bc5cc68490ca083505
  * Node Name: `https://update.googleapis.com/service/update2/json (cup2hreq,cup2key)({request:{@os,@updater,acceptformat,apps:[{appid,enabled,lang,ping:{r},updatecheck:{},version}..,{accept_locale,appid,enabled,lang,ping:{r},updatecheck:{},version},{appid,enabled,lang,ping:{r},updatecheck:{},version}..],arch,dedup,domainjoined,hw:{avx,physmemory,sse,sse2,sse3,sse41,sse42,ssse3},ismachine,os:{arch,platform,version},prodversion,protocol,requestid,sessionid,updaters:{autoupdatecheckenabled,ismachine,lastchecked,laststarted,name,updatepolicy,version},updaterversion}})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``


Instances: 12

### Solution

Ensure that your web server, application server, load balancer, etc. is configured to enforce Strict-Transport-Security.

### Reference


* [ https://cheatsheetseries.owasp.org/cheatsheets/HTTP_Strict_Transport_Security_Cheat_Sheet.html ](https://cheatsheetseries.owasp.org/cheatsheets/HTTP_Strict_Transport_Security_Cheat_Sheet.html)
* [ https://owasp.org/www-community/Security_Headers ](https://owasp.org/www-community/Security_Headers)
* [ https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security ](https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security)
* [ https://caniuse.com/stricttransportsecurity ](https://caniuse.com/stricttransportsecurity)
* [ https://datatracker.ietf.org/doc/html/rfc6797 ](https://datatracker.ietf.org/doc/html/rfc6797)


#### CWE Id: [ 319 ](https://cwe.mitre.org/data/definitions/319.html)


#### WASC Id: 15

#### Source ID: 3

### [ X-Content-Type-Options Header Missing ](https://www.zaproxy.org/docs/alerts/10021/)



##### Low (Medium)

### Description

The Anti-MIME-Sniffing header X-Content-Type-Options was not set to 'nosniff'. This allows older versions of Internet Explorer and Chrome to perform MIME-sniffing on the response body, potentially causing the response body to be interpreted and displayed as a content type other than the declared content type. Current (early 2014) and legacy versions of Firefox will use the declared content type (if one is set), rather than performing MIME-sniffing.

* URL: https://t-f-cl-test-003.vercel.app/
  * Node Name: `https://t-f-cl-test-003.vercel.app/`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/chunks/3o3-pqfgq6cb5.css
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/chunks/3o3-pqfgq6cb5.css`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-400-normal.19gbeb610ur4n.woff2
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-400-normal.19gbeb610ur4n.woff2`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-500-normal.25_05y-blbp24.woff2
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-500-normal.25_05y-blbp24.woff2`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/special-elite-latin-400-normal.2mza6l9y4lmq8.woff2
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/special-elite-latin-400-normal.2mza6l9y4lmq8.woff2`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://clientservices.googleapis.com/uma/v2
  * Node Name: `https://clientservices.googleapis.com/uma/v2 ()(B2	É_ª¾Åz#	 2	...,	ït Ê<«E ¯õâÔ152.0.7977.82-64...,	$ª-Z!P®(0ùð	Nÿÿÿÿ2,	0ð
þ[¥RV2...,	Zñv,	\_$ÁêÅuïÔ
/@ïv¡2...,	¼ª*s)}NR2z...,	ÍËõ,ß*·å­ ùð	Nÿÿÿÿ2...,	áü®fAÎÛº    ¥
2..., 2	Vcé¶âÄ/ 2	õ>Çªrª...,*K S\eozµÈô ...,* 2	éäÍàu  2$	R¾`þûû...,; 20	èPEª%ªã³...,c    ...,6 	¥µ 
º¶Çí 
ÙêÎ ...,1¡?ÉQi Ò ô® Å...,R¬ ÖÒ%2	ÄÊ,1 
ô¢ 2	JØLÚ¦¾«Æô...,¬ 2	-a~}¹fø55<2	 ¹ó¾V~^¸¿...,Â 2	2Þ¦\G52	<ýîðÍÐ...,`Y 29	7Ás*·%µG   ...,Ë
ñw   2	ùÅ¦ A 12	...,2	ÛØU¼ã*fp2	½,ÐÊløk2	9¬×...,	2	?ÁÂ¡ßÆ*¨2...,ò)2	g5CHU 2	BÍ3æÃDQ...,'Á(¥)à*â*õ* à ...,'Á(¥)à*â*õ* à ...,â,â,   ,      ...,      ...,(2#	%íw+wýãJx  ...,(2#	¶þ\½hÁ}x  ...,H ,W *i   » ã ...,  » ã 	 Í ..., 2	K¯Aíë2	#þn-÷5..., 2	Õø!ÄÜ7 2	(Xû+DP..., 2	äÉD °£ 2<	r§5±Ê..., , 2	8ÜÿVBÄ¾2	Ï#µa*ÙA...,¬ ­1þ?îH¾z¼
Ú ...,øDÌS®eôzÂ 
Ðÿÿÿÿ2k	%...,¨*§. ¯ º£ï²2	ÐÞT³³ú...,¨*§. ¯ º£ï²2|	M }ß...,'; 2	 XCUh4x 2	ß,$ª...,/	 2	kh½Oµ4 $2	ø1;©Z@...,I2	3jcO l2	¦ûwï«q2	¥..., «)2	©´(ÈXxûû2	å[ÿM ..., Ðà/ 	ïÈ0 .ÚÃÜ2¾¿5 §..., 2	, 52	|Ü9ýà. 52m	Ñ[ÕoëËenè ...,#Z2	ý¶Yz,2	ÏmjG^rÞ "2c	ÚÁå³¨$<N ...,2	Ë$ú¥]v@ú 2	¿i¾ûøç¸ 2...,2.	±Ôù	°
 9D	...,2e	¼Ø§MÓe«a  
 ,7E³K   K2	iÙWó@»2x	E...,;,>èk 2.	Ì
÷ä¨bÜü k 
...,@çí×P8	 	2	×'/%Ñ"0P 2	­`£#...,B¦R¬ ÖÒ%2	ôHPÝóëGµ§o...,Fj.a 2	ùDÊ)]H2	...,KÇ«k<2	,P¹m|	,Wë;µ2	weQ½ î2	ßLéöS5...,Y2	Ð$¦DâÏß2	zË²ÿ×ÍeðîG
 þ...,báËD2	íµ;t]÷f\2	zÏ\®%U...,cuìÖÂè2	LdY/ª´j¤ÖÂè2	...,cðG·B2	ìÅ	û¢{2	;¸Mú©Ôº×þ...,eJø¨ 2	54{ dQ 2	7qAoÑª...,e\ùé9þ2	N].mB×þ 2	82©Qx6...,hÃ¾2	Ø*§Ìÿ 2	ÁD¬...,r%¾Dj 2	úå"ïà 2	ØAÔÓ¡+...,tØÖÒ®2	¼¬Asû\2	CpfÓÎê³...,x§Q ÈÉ2	}ýªóÈÉ2	°71ôò...,yüR¨oæÞJ
6¼¨oæÞJ
q¤¨oæÞJ
Ü¿qÿ...,{õ²¾`¼2	3|ôÖd»À2	8Ós2Ë...,| 2	Vð¹ï 2	yY@w_Õ...,~5 2	¶r'}_ð 2	ÐõÀàb$...,~¨mt2	,¹5xÊu¢ë2	%§Ä2...,¥­¯Ëº 2	áÛ2	¹?Ö°ýÞ...,¬¢ûû2	Ä#wâî2	{©6Þ zØ...,K8ò2	ý÷ó¶~û2	­GkbH8...,bR­ "C EGLQ ...,mÆ 2	ñÈÞ´z{2	i3,ó@Ë_0  2..., ÌD2	½K·pÿ§2	\ÒLþ2	..., Öª2	¦¿uÍàs2	QpL±K_...,£qË{|å2	3d­Õ£z:2	`GPhºÀ0...,¤ïºà	¯úÈ
2	¿Ã?Ôì½ÞÔIìCÿ...,¨§42	v	_]§"?2	¹§¼-Íß2...,ª¶×¸I"2	q8~A)Rïþ2	sµõQÏ6«...,«2	Þ35EkÂ2	,«HîH0@ 2	bÒÓåìoþ 2	...,®¨ìþh 2	zz	£ò.<çTØâ...,¯;ô2	^jøÐ×332	Cöôõ6Æ`2...,°!lñéòé2	.Oêâ)¦dèÌé...,´vX, 2Ã	RMºDg«ìã ...,ºC2	¯áòÉð02	v_,Ñ W...,»F÷}é¤Ú ,¿ÍÚÃ
 î 	   Õ...,ÅÍ¢müE\!@P2.	åÍ)>g...,Æ2	0Å[^Y{û2	][w°#UA...,Ê¼¯ 4BT ¾Ùô¢...,Î³ 2	Vn6ÞR¤E2	D«...,Îð:ªåÔPÒr
ëÓù 2	ZÚvÄê...,Ð~ ´h2	åð'(çØé­ 2	ÙÚáL...,Ñ¨¼2	}¸>1¸2	÷](.2	...,Ñ÷pÔ2	2"Lü~ý2	...,Ô¿2	Û]g«_cf2	¡­Ì}Kk2...,çBÏ 2	8(à,éy[,îIÄäÎäÌ 
(0D...,î¥v  2	Ù¼­A£÷A6E 
 	!...,ïÎzñó2	 í3 á2	D²ö...,ñ/2	.ÞÒ#¾¡2	bPÈ8Æ52	È...,õ,2	ò2^¶R2	¾;êÅïÝÈ...,÷R§ß÷°
 BTk ¾Ù...,úwªjù    ...,ýYGxôË¢2	y/ó%2TUØ+¥ ...,ÿTe§a¼`Ür2	æàòQÈÉëõ2	Ñ...)`
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`

Instances: Systemic


### Solution

Ensure that the application/web server sets the Content-Type header appropriately, and that it sets the X-Content-Type-Options header to 'nosniff' for all web pages.
If possible, ensure that the end user uses a standards-compliant and modern web browser that does not perform MIME-sniffing at all, or that can be directed by the web application/web server to not perform MIME-sniffing.

### Reference


* [ https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/compatibility/gg622941(v=vs.85) ](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/compatibility/gg622941(v=vs.85))
* [ https://owasp.org/www-community/Security_Headers ](https://owasp.org/www-community/Security_Headers)


#### CWE Id: [ 693 ](https://cwe.mitre.org/data/definitions/693.html)


#### WASC Id: 15

#### Source ID: 3

### [ Re-examine Cache-control Directives ](https://www.zaproxy.org/docs/alerts/10015/)



##### Informational (Low)

### Description

The cache-control header has not been set properly or is missing, allowing the browser and proxies to cache content. For static assets like css, js, or image files this might be intended, however, the resources should be reviewed to ensure that no sensitive content will be cached.

* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJ0CVkm8CPDKamKEg8N77-NcyoICAcQBxgBIAMSDw0AoAvKKggIAhACGAEgBRIPDYOoWz0qCAgFEAUYBSAEEg8NEg_8aioICAcQBxgGIAQSDw2erW9sKggIBhAGGAcgBiFQnbrTyvMUEClQnbrTyvMUEDICIAA=%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJ0CVkm8CPDKamKEg8N77-NcyoICAcQBxgBIAMSDw0AoAvKKggIAhACGAEgBRIPDYOoWz0qCAgFEAUYBSAEEg8NEg_8aioICAcQBxgGIAQSDw2erW9sKggIBhAGGAcgBiFQnbrTyvMUEClQnbrTyvMUEDICIAA= (alt)`
  * Method: `GET`
  * Parameter: `cache-control`
  * Attack: ``
  * Evidence: `private,max-age=604800`
  * Other Info: ``
* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJBCdeR6xd0dUEzEg8NEg_8aioICAMQBxgGIAQSDw2erW9sKggIABAGGAcgBSHz7xDDePCQqinyeyWc0LCwlDICIAU=%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJBCdeR6xd0dUEzEg8NEg_8aioICAMQBxgGIAQSDw2erW9sKggIABAGGAcgBSHz7xDDePCQqinyeyWc0LCwlDICIAU= (alt)`
  * Method: `GET`
  * Parameter: `cache-control`
  * Attack: ``
  * Evidence: `private,max-age=604800`
  * Other Info: ``
* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJFCQJ1kIPXkKnYEhENg6hbPSoKCAIQBRgFIARIBRIRDc5BTHoqCggFEAIYAiAESAIhgRet93kpAKIp_Mpy3Q0joG8yAiAH%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJFCQJ1kIPXkKnYEhENg6hbPSoKCAIQBRgFIARIBRIRDc5BTHoqCggFEAIYAiAESAIhgRet93kpAKIp_Mpy3Q0joG8yAiAH (alt)`
  * Method: `GET`
  * Parameter: `cache-control`
  * Attack: ``
  * Evidence: `private,max-age=604800`
  * Other Info: ``


Instances: 3

### Solution

For secure content, ensure the cache-control HTTP header is set with "no-cache, no-store, must-revalidate". If an asset should be cached consider setting the directives "public, max-age, immutable".

### Reference


* [ https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html#web-content-caching ](https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html#web-content-caching)
* [ https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Cache-Control ](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Cache-Control)
* [ https://grayduck.mn/2021/09/13/cache-control-recommendations/ ](https://grayduck.mn/2021/09/13/cache-control-recommendations/)


#### CWE Id: [ 525 ](https://cwe.mitre.org/data/definitions/525.html)


#### WASC Id: 13

#### Source ID: 3

### [ Retrieved from Cache ](https://www.zaproxy.org/docs/alerts/10050/)



##### Informational (Medium)

### Description

The content was retrieved from a shared cache. If the response data is sensitive, personal or user-specific, this may result in sensitive information being leaked. In some cases, this may even result in a user gaining complete control of the session of another user, depending on the configuration of the caching components in use in their environment. This is primarily an issue where caching servers such as "proxy" caches are configured on the local network. This configuration is typically found in corporate or educational environments, for instance.

* URL: https://t-f-cl-test-003.vercel.app/
  * Node Name: `https://t-f-cl-test-003.vercel.app/`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Age: 0`
  * Other Info: `The presence of the 'Age' header indicates that a HTTP/1.1 compliant caching server is in use.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/chunks/3o3-pqfgq6cb5.css
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/chunks/3o3-pqfgq6cb5.css`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Age: 14878`
  * Other Info: `The presence of the 'Age' header indicates that a HTTP/1.1 compliant caching server is in use.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-400-normal.19gbeb610ur4n.woff2
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-400-normal.19gbeb610ur4n.woff2`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Age: 14878`
  * Other Info: `The presence of the 'Age' header indicates that a HTTP/1.1 compliant caching server is in use.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-500-normal.25_05y-blbp24.woff2
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/ibm-plex-mono-latin-500-normal.25_05y-blbp24.woff2`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Age: 14878`
  * Other Info: `The presence of the 'Age' header indicates that a HTTP/1.1 compliant caching server is in use.`
* URL: https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/special-elite-latin-400-normal.2mza6l9y4lmq8.woff2
  * Node Name: `https://t-f-cl-test-003.vercel.app/_next/static/immutable/media/special-elite-latin-400-normal.2mza6l9y4lmq8.woff2`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Age: 14878`
  * Other Info: `The presence of the 'Age' header indicates that a HTTP/1.1 compliant caching server is in use.`

Instances: Systemic


### Solution

Validate that the response does not contain sensitive, personal or user-specific information. If it does, consider the use of the following HTTP response headers, to limit, or prevent the content being stored and retrieved from the cache by another user:
Cache-Control: no-cache, no-store, must-revalidate, private
Pragma: no-cache
Expires: 0
This configuration directs both HTTP 1.0 and HTTP 1.1 compliant caching servers to not store the response, and to not retrieve the response (without validation) from the cache, in response to a similar request.

### Reference


* [ https://datatracker.ietf.org/doc/html/rfc7234 ](https://datatracker.ietf.org/doc/html/rfc7234)
* [ https://datatracker.ietf.org/doc/html/rfc7231 ](https://datatracker.ietf.org/doc/html/rfc7231)
* [ https://www.rfc-editor.org/rfc/rfc9110.html ](https://www.rfc-editor.org/rfc/rfc9110.html)


#### CWE Id: [ 525 ](https://cwe.mitre.org/data/definitions/525.html)


#### Source ID: 3

### [ Session Management Response Identified ](https://www.zaproxy.org/docs/alerts/10112/)



##### Informational (Medium)

### Description

The given response has been identified as containing a session management token. The 'Other Info' field contains a set of header tokens that can be used in the Header Based Session Management Method. If the request is in a context which has a Session Management Method set to "Auto-Detect" then this rule will change the session management to use the tokens identified.

* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token`
  * Attack: ``
  * Evidence: `sb-zznkykduwjrefvxoiwkx-auth-token`
  * Other Info: `cookie:sb-zznkykduwjrefvxoiwkx-auth-token`
* URL: https://t-f-cl-test-003.vercel.app/login%3Fnext=%252Fcheckout
  * Node Name: `https://t-f-cl-test-003.vercel.app/login (next)([{"email":"kevin007millford@gmail.com","...)`
  * Method: `POST`
  * Parameter: `sb-zznkykduwjrefvxoiwkx-auth-token-flows-code-verifier`
  * Attack: ``
  * Evidence: `sb-zznkykduwjrefvxoiwkx-auth-token-flows-code-verifier`
  * Other Info: `cookie:sb-zznkykduwjrefvxoiwkx-auth-token-flows-code-verifier
cookie:sb-zznkykduwjrefvxoiwkx-auth-token-code-verifier
cookie:sb-zznkykduwjrefvxoiwkx-auth-token-flow-a519bb59447a891e20565b79169ca198-code-verifier`
* URL: https://t-f-cl-test-003.vercel.app/products/3
  * Node Name: `https://t-f-cl-test-003.vercel.app/products/3 ()([3,1])`
  * Method: `POST`
  * Parameter: `cart`
  * Attack: ``
  * Evidence: `cart`
  * Other Info: `cookie:cart`
* URL: https://t-f-cl-test-003.vercel.app/products/3
  * Node Name: `https://t-f-cl-test-003.vercel.app/products/3 ()([5])`
  * Method: `POST`
  * Parameter: `cart`
  * Attack: ``
  * Evidence: `cart`
  * Other Info: `cookie:cart`
* URL: https://t-f-cl-test-003.vercel.app/products/5
  * Node Name: `https://t-f-cl-test-003.vercel.app/products/5 ()([5,1])`
  * Method: `POST`
  * Parameter: `cart`
  * Attack: ``
  * Evidence: `cart`
  * Other Info: `cookie:cart`


Instances: 5

### Solution

This is an informational alert rather than a vulnerability and so there is nothing to fix.

### Reference


* [ https://www.zaproxy.org/docs/desktop/addons/authentication-helper/session-mgmt-id/ ](https://www.zaproxy.org/docs/desktop/addons/authentication-helper/session-mgmt-id/)



#### Source ID: 3

### [ User Agent Fuzzer ](https://www.zaproxy.org/docs/alerts/10104/)



##### Informational (Medium)

### Description

Check for differences in response based on fuzzed User Agent (eg. mobile sites, access as a Search Engine Crawler). Compares the response statuscode and the hashcode of the response body with the original response.

* URL: https://t-f-cl-test-003.vercel.app/%3F_rsc=tXyZJ52UQVBCVsD3
  * Node Name: `https://t-f-cl-test-003.vercel.app/ (_rsc)`
  * Method: `GET`
  * Parameter: `Header User-Agent`
  * Attack: `Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1)`
  * Evidence: ``
  * Other Info: ``
* URL: https://t-f-cl-test-003.vercel.app/checkout
  * Node Name: `https://t-f-cl-test-003.vercel.app/checkout ()([{"phone":" 88012345678910","address":"C...)`
  * Method: `POST`
  * Parameter: `Header User-Agent`
  * Attack: `Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1)`
  * Evidence: ``
  * Other Info: ``
* URL: https://t-f-cl-test-003.vercel.app/user/005c9b24-b1d2-47b1-afe3-c98b4f4320b2
  * Node Name: `https://t-f-cl-test-003.vercel.app/user/005c9b24-b1d2-47b1-afe3-c98b4f4320b2 ()([{"first_name":"kevin","last_name":"mill...)`
  * Method: `POST`
  * Parameter: `Header User-Agent`
  * Attack: `Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1)`
  * Evidence: ``
  * Other Info: ``

Instances: Systemic


### Solution



### Reference


* [ https://owasp.org/wstg ](https://owasp.org/wstg)



#### Source ID: 1


