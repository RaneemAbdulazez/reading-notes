# EJS :

>EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript.


## EJS FEATURES 

-Use plain JavaScript
-Speedy execution
-Fast development time
-Easy debugging
-Simple syntax
-Active development


## FILE STRUCTURE 

- views
----- partials
---------- footer.ejs
---------- head.ejs
---------- header.ejs
----- pages
---------- index.ejs
---------- about.ejs
- package.json
- server.js


-db config 




## in terminal :

- nmp init 
-npm install --save express body-parser cors ejs 


## in js file  : 

```

//require all of them 
const app=express();
app.use(cors());
app.set('views',path.join(___dirname,'views'));
app.set('view engine','ejs');

app.listen(8000,function(){
    console.log('heared)
})

app.get('/',function(req,res){
res.render('index'); //file name 


}
)

```
for docs:


```

let template = ejs.compile(str, options);
template(data);
// => Rendered HTML string

ejs.render(str, data, options);
// => Rendered HTML string

ejs.renderFile(filename, data, options, function(err, str){
    // str => Rendered HTML string
});

```


















