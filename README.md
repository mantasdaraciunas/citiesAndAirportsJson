The file largeAirports.json contains cities which has large airports.<br>

The file mediumAirports.json contains information about cities with medium size airports.<br>

Obviously, there might be the same city which has some large and some medium size airports.<br>

The each object looks like this:
<br>
{<br>
“iso”:“BE”,<br>
“country”:“Belgium”,<br>
“continent”:“EU”,<br>
“city”:“Brussels”,<br>
“airports”:[{"iata":"BRU"}]<br>
},<br>

Where<br>

“iso” – country code;<br>
“country” – country name;<br>
“continent” – continent;<br>
“city” – city of airports or might be location in general<br>
“airports” – array of airports which belongs to the city<br>
“iata” – airport code<br>
