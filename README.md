# rescript-web-types
rescript general types for web entities package


## Types
```rescript
//WebTypes.res
type routeType =
    [ #checkout
    | #copy
    | #get
    | #delete
    | #head
    | #lock
    | #merge
    | #mkactivity
    | #mkcol
    | #move
    | #notify
    | #options
    | #patch
    | #post
    | #purge
    | #put
    | #report
    | #search
    | #subscribe
    | #trace
    | #unlock
    | #unsubscribe
    ]

type redirectStatus = 
    [ #301 
    | #302 
    | #303 
    | #304 
    | #306 
    | #307 
    | #308 
    ]

type errorStatus = 
    [ #400 
    | #401 
    | #402 
    | #403 
    | #404 
    | #405 
    | #406 
    | #407 
    | #408
    | #500
    | #501
    | #502
    | #503
    | #504
    ]

type baseAuth = {
    username: string,
    password: string
}
```

## Author
Anatoly Starodubtsev
tostar74@mail.ru

## License
MIT