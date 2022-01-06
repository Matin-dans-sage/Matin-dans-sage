# forminejs
> form value check js


[![Netlify Status](https://api.netlify.com/api/v1/badges/7005dc0b-dc49-474b-9f65-34743cd088a0/deploy-status)](https://app.netlify.com/sites/forminejs/deploys)

## setting 

```sh
 1. need jQuery lib
 2. forminejs load 
   # <script src="https://mitw.ml/forminejs/forminejs.pack.js" data-lang="en" type="text/javascript"></script>
 3. language config
   # data-lang : en, ko 
```

## guide 

```sh
 1. add data-forminejs-form="true" to the form tag
   # data-forminejs-form : true, false
 2. cover input tag with another tag 
   # example)  <label><input /></label>, <div><input /></div>
 3. how to use in input tag
   # add data-forminejs='true'        > null check
   # add data-forminejs-minlength='3' > min length check / param : number
   # add data-forminejs-maxlength='7' > max length check / param : number
   # add data-forminejs-num='true'    > only number check
	 # add data-forminejs-ko='true'     > only korean check
	 # add data-forminejs-en='true'     > only english check
	 # add data-forminejs-id='true'     > only alphanumeric check (id pattern)
	 # add data-forminejs-mail='true'   > Mail pattern check : xxx@xxx.xxx
 4. attribute value
   # false => not checking 
   # true  => checking  
   # example) <form name="form" data-forminejs-form="true"></form>
	 # example) <input name="name" data-forminejs='true' data-forminejs-ko="true" />

```

![](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FcdiHyB%2FbtrpTe7VwDe%2F4TJ4DMG8LOQHrCDkyuRCw0%2Fimg.png)

## update history

* 1.0
    * release (study)

## info

License : ALL FREE

Blog : [https://mitw.tistory.com](https://mitw.tistory.com/)

## report

funny js
