# Angular-EventService
Angular service allowing to listen to variables between several components thus facilitating data management
## Publish 
```
Events.publish('variable_name',data);
```
## Subscribe
```
Events.subscribe('variable_name',(data:type)=>{
###  Treatment ###
});
```
