Meanstack
jasonplaceholder.com
https://cli.angular.io/


to install
npm install -g @angular/cli

to check >ng
>ng version

to updagte angular
>ng update @angular/cli @angular/core

to create new project
>ng new HelloAngular

to run project
>ng serve

http://127.0.0.1:4200

>ng serve --open

to create new component 
>ng g c "component name"

> ng g c "component name" -it -is

create todo and todo1 component

go to todo.component.html for html code
todo.component.ts for define variable and all
variable
array
addition
forloop
if  added 


routing in app-routing file

create array
 {path:'',component:HomeComponent},
  {path:'about',component:AboutComponent},
  {path:'contact',component:ContactComponent},
  {path:'todo',component:TodoComponent},
  {path:'todo1',component:Todo1Component}
  
  
added all links in app.component.html
<a routerLink=''>Home</a> | 
<a routerLink='about'>About</a> | 
<a routerLink='contact'>Contact</a> | 
<a routerLink='todo'>todo</a> | 
<a routerLink='todo1'>todo1</a> |   