# Hybrid-Office
FaceIt company required interactive floor map for their customers. Here you will have availability book a desk or room with a different payment plans.


# Backend requirements

 - [ ] create folder `hybrid-office-be` and working there on backeend part
 - [ ] use version api prefix `/v1/rest-path-of-api`
 - [ ] use single api response (examples below)

### response type 
```
{
    is_success: boolean,
    data: any (null by default),
    errors: [
        {code: number, message: string},...
    ]
}
```

### succes
```
{
    is_success: true,
    data: "any date you can put here. for example this string",
    errors: [ ]
}
```

### succes
```
{
    is_success: false,
    data: null,
     errors: [
        {code: 404, message: "api not found"}
    ]
}
```