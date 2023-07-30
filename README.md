# Calendar


## ENDPOINTS
| METHOD | URI               | Response | Comment <br>
| GET    | /                  | String | Not make any |  <br>
| POST   | /                  | return statics & all stored data == refresh the tables | Store all calculation | <br>
| GET    | /statics           | JSON | Return top 1 statics datas | MIN MAX AVG SUM and Most used Operand <br>
| GET    | /getAllCalculates  | JSON | Return all rows of mysql database <br>
