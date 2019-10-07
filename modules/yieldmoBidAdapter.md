# Overview

```
Module Name:  Yieldmo Bid Adapter
Module Type:  Bidder Adapter
Maintainer: opensource@yieldmo.com
```

# Description

Connects to Yieldmo Ad Server for bids.

Yieldmo bid adapter supports Banner.

# Test Parameters
```
var adUnits = [
   // Banner adUnit
   {
       code: 'div-gpt-ad-1460505748561-0', 
       sizes: [[300, 250], [300,600]],
       bids: [{
         bidder: 'yieldmo',
         params: {
           placementId: '1779781193098233305', // string with at most 19 characters (may include numbers only) 
           bidFloor: .28 // optional param
         }
       }]
   }
];
```