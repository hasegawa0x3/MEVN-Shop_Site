## Vue-Shop

An online-shop designed and developed by VueJS and NodeJS, along with their related tech stacks.

vue-shop，An online store designed and developed with VueJS and NodeJS and its related technology stack.

## technology stack

Vue2 + VueRouter + Vuex + ElementUI + Webpack + ES6 + Axios + SCSS + NodeJS + MongoDB + ...

## About interface data

Due to the tight development of the project, in order to save time, I will temporarily use the interface provided by another developer on github this time, and write the obtained data into the database as a cache through the crawler script for future use.

Note: The product data is captured and written into the database (eventproxy + superagent) by crawlers. Because the data structure is very complex, the data is simplified by forwarding and packaging in the popular part of the homepage. __If you find that some products are missing, it may be the original one. The data structure has changed__.

This is just a stopgap measure. In the future, I will use my spare time to independently design and build a complete small database server.


## run

```shell

git clone https://github.com/Geolage/vue-shop.git

cd vue-shop

npm install    

npm run dev

http://127.0.0.1:6666     //  localhost:6666

```

## account

__Note: In order to better experience the entire store service process, please register an account and log in to use__

The default account is as follows：

```txt
 account: admin  password: admin
```

## Function

- [x] Login, logout functions
- [x] Registration
- [x] add, delete, modify shopping
- [x] Add, modify, delete shipping address
- [x] Order function
- [x] Payment function -- Since there is no permission to apply for the Alipay development interface of Ant Financial Services, it is only a simulated payment
- [x] product details
- [x] Personal center
- [x] order list
- [x] Change avatar -- the avatar is temporarily uploaded to Qiniuyun

## to be continued

> More functions are under development and will be added later
> Details and bugs will also be continuously improved and fixed
> If you have better ideas or any questions, welcome to Issues, I will always maintain a positive learning attitude, thank you!

## project structure

```txt
  ... vue-shop
  │
  ├── client                                          
  │   ├── build                                      
  │   ├── config                                      
  │   ├── dist                                        
  │   ├── src                                        
  │   │   ├── api                                   
  │   │   ├── common                                  
  │   │   ├── components                            
  │   │   ├── page                                   
  │   │   │   └── Cart                            
  │   │   │   └── Checkout                            
  │   │   │   └── Goods                               
  │   │   │       ├── goods                          
  │   │   │       ├── goodsDetails                   
  │   │   │   └── Home                                
  │   │   │   └── Login                              
  │   │   │   └── Order                              
  │   │   │       ├── order                          
  │   │   │       ├── payment                        
  │   │   │       ├── paysuccess                     
  │   │   │   └── User                                
  │   │   │       ├── children
  │   │   │       │   ├── addressList                 
  │   │   │       │   ├── information                
  │   │   │       │   └── order                      
  │   │   │   └── index.vue                          
  │   │   ├── store                                  
  │   │   │   ├── action.js                          
  │   │   │   ├── index.js                           
  │   │   │   ├── modules                             
  │   │   │   ├── mutation-types.js                  
  │   │   │   └── mutations.js                      
  │   │   ├── App.vue                                
  │   │   ├── main.js                               
  │   ├── favicon.ico                                 
  │   ├── index.html                               
  │
  ├── server                                        
  │   ├── bin                                        
  │   │    └── www                                   
  │   ├── image                                    
  │   ├── init                                       
  │   │     └── admin.js                              
  │   │     └── getGoods.js                           
  │   │     └── initData.js                          
  │   ├── models                                      
  │   │     └── goods.js                             
  │   │     └── user.js                             
  │   ├── public                                     
  │   │     ├── stylesheets                           
  │   ├── routes                                     
  │   │     └── goods.js                              
  │   │     └── index.js                            
  │   │     └── users.js                             
  │   ├── util                                       
  │   │     └── dateFormat.js                       
  │   ├── views                                      
  │   │     └── error                                 
  │   │     └── index                                 
  │   │     └── layout                               
  │   ├── app.js                                     

```

## More content is being perfected ...
