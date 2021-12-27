# onlinebookstore_comp3005
final project for comp3005
#download and extract it
#

```
chang db connect info
run db_init.js
run dbserver.js
```
There's 2 bugs found:
1. On admin role, dont press back to last page when viewing a book, to fixed this, can change line 23 on project/pug/adminbook.pug
```
a( href='/admin'): button(type ='submit') Back To Last Page
```
2. delete console.log(res) in db_init.js which is error naming
