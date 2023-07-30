# Calendar


## ENDPOINTS
| METHOD | URI       | Response | Comment
| GET    | /                  | String | Not make any | 
| POST   | /                  | return statics & all stored data == refresh the tables | Store all calculation | 
| GET    | /statics           | JSON | Return top 1 statics datas | MIN MAX AVG SUM and Most used Operand
| GET    | /getAllCalculates  | JSON | Return all rows of mysql database
