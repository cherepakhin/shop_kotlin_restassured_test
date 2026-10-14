# Prompts

## 1
напиши тест для ответа http :8980/shop_kotlin/api/group_product/11111/subgroups
                       HTTP/1.1 500 
                       Access-Control-Allow-Headers: Content-Type, Authorization, Content-Length, X-Requested-With
                       Access-Control-Allow-Methods: POST, PUT, GET, OPTIONS, DELETE
                       Access-Control-Allow-Origin: *
                       Access-Control-Max-Age: 3600
                       Connection: close
                       Content-Type: application/json
                       Date: Wed, 14 Oct 2026 11:49:11 GMT
                       Transfer-Encoding: chunked
                       Vary: Origin
                       Vary: Access-Control-Request-Method
                       Vary: Access-Control-Request-Headers
                       
                       {
                           "error": "Internal Server Error",
                           "message": "Group product not found with id: 11111",
                           "path": "/shop_kotlin/api/group_product/11111/subgroups",
                           "status": 500,
                           "timestamp": "2026-10-14T11:49:11.836+00:00"
                       }

## 2
исправь тест getSubgroups_nonExistingId()

## 3
запусти тест getSubgroups_nonExistingId() и исправь его

## 4
commit

## 5
не все закоммичено

## 6
запиши все полученные prompts в файл PROMPTS.md
