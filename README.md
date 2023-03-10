
#Top 50 Global Youtube Trending 

Live Demo : https://mgyoutube.mobagenie.my.id/global-most-trending

API Endpoint : https://mgyoutube.mobagenie.my.id/index.php?api=globalMostTrending

Json Response : 

{"iBuTEywEQ6U":{"0":{"c":"AE","p":12},"1":{"c":"AL","p":46},"2":{"c":"BA","p":47},"3":{"c":"BE","p":5},"4":{"c":"BH","p":11},"5":{"c":"CZ","p":22},"6":{"c":"DK","p":2},"7":{"c":"EG","p":21},"8":{"c":"HR","p":15},"9":{"c":"IE","p":35},"10":{"c":"IQ","p":46},"11":{"c":"IS","p":1},"12":{"c":"JO","p":37},"13":{"c":"KH","p":47},"14":{"c":"KW","p":19},"15":{"c":"LU","p":5},"16":{"c":"MA","p":40},"17":{"c":"MT","p":1},"18":{"c":"MY","p":5},"19":{"c":"NP","p":29},"20":{"c":"PL","p":18},"21":{"c":"PT","p":11},"22":{"c":"QA","p":6},"23":{"c":"SI","p":7},"24":{"c":"TZ","p":2},"25":{"c":"YE","p":24},"iCo":"iBuTEywEQ6U","vTCo":"SElHSExJR0hUUzogTGl2ZXJwb29sIDctMCBNYW4gVW5pdGVkIHwgU2FsYWggYnJlYWtzIGNsdWIgcmVjb3JkIGFzIFJlZHMgc2NvcmUgU0VWRU4h","cCo":26,"pCo":514,"cTCo":1678410860}

Basic Json :

iBuTEywEQ6U = Video ID
c = Country
p  Position

Extended Json :

iCo = Video ID
vTCo = Video Title in base64 encode. 
cCo = Country Count Total
pCo = Position Count Total
cTCo = Cached Time timestamp ( we only update data one time / day ). you can convert to ex 2023-02-01 18.15.00 with built in php, js or node js.

we limit data only for top 50 global.