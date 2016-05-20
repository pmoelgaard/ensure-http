# ensure-http
Just a small convenience, based entirely and only on this little script block

---

    function addhttp(url) {
    	if (!/^(?:f|ht)tps?\:\/\//.test(url)) {
        	url = "http://" + url;
    	}
    	return url;
    }

All tributable to this post on StackOverflow:
[http://stackoverflow.com/questions/24657463/how-to-add-http-to-url-if-no-protocol-is-defined-in-javascript](http://stackoverflow.com/questions/24657463/how-to-add-http-to-url-if-no-protocol-is-defined-in-javascript)
