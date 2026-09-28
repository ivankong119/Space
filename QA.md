## Reservation Store list 
 Cancellation charge per head with Grace Period (1hr) - 3221_test  
 Cancellation charge per head without Grace Period - 4195_test  
 Cancellation (Fixed rate) with Grace Period (1hr) - 2929_test  
 No Cancellation - 3220_test  
 Prepaid with cut off time (1hr)- 3218_test  
 Event Time Slot - 3219_test  
 Service Based <Head Count> - 6259_test, 8003_test  
 Questions - 5179_test  
 Section Based - 3220_test  
 Service Based - 1392_test  
 cancellation cancellationPartySizeThreshold 4939_test (BC timezone)  
<https://gosnappy.atlassian.net/browse/DEV-9938

## RA Store list
6685_test  
1637_test  
7373_test   
2979_test  
6416_test  
4966_test  
2929_test  
3220_test  

## Map Direction
Andriod - Google and Waze  
iOS - Apple, Google and Waze

## KDS Report
https://gosnappy.atlassian.net/browse/DEV-10119


## Follow up ticket  (Implenmentation not complete)
https://gosnappy.atlassian.net/browse/DEV-10100


0122_demo BC demo store
301_demo TOR demo store 

## OWA Test Scope
store.settings.orderSettings.scheduledOrderTimeLimitInHours  
>>Allow how many hours for pick up schedule order

store.settings.orderSettings.scheduledDeliveryTimeLimitInHours  
>>Allow how many hours for delivery schedule order

store.settings.orderSettings.allowOffHourPickup  
>>Allow how many hours schedule order for pick up when the store is closed

store.settings.orderSettings.allowOffHourDelivery 
>>Allow how many hours schedule order for delivery when the store is closed 

store.settings.orderSettings.advanceBookingMinInMinutes
>>the number of minutes from now that an user can start scheduling an order for delivery orders. 

store.settings.orderSettings.advanceBookingAfterStoreOpenInMinutes  
>>How many minutes after opening the store can begin accepting its first order  
>>The minimum booking time after opening hours of the store, for scheduling orders in genera

store.settings.orderSettings.advanceBookingBeforeStoreCloseInMinutes  
>>How many minutes before closing the store can begin accepting its last order  
>>The minimum booking time before closing hours of the store, for scheduling orders in genera

scheduleTakeoutDatetimeManually  
>> Customer need to manually select the date and time when check out, ASAP dsiabled

store.features.pickupSupported   
>>The store allow pick up order

store.features.deliverySupported  
>>The store allow delivery order

store.features.dineInSupported  
>>The store allow dine ine order

store.settings.owaSettings.skipCheckout  
>>The store allow customer check out without login for dine in order

store.settings.owaSettings.allowAnonymousDineInOrder  
>>work with flag store.settings.owaSettings.skipCheckout 

store.settings.owaSettings.enableDineInSharedCart
>>customer can be sharded cart when they using scran dine in  QR code order

store.settings.owaSettings.disableGroupOrder 
>> disable Group order feature for pick up and delviery