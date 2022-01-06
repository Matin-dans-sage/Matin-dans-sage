- 👋 Hi, I’m @Matin-dans-sage
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Matin-dans-sage/Matin-dans-sage is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

* --- GUIDE --- 
* 1. need jQuery lib
* 2. forminejs load  <script src="https://mitw.ml/forminejs/forminejs.pack.js" data-lang="ko" type="text/javascript"></script>
*    -> data-lang : ko , en 
* 3. add data-forminejs-form="true" to the form tag
*    -> data-forminejs-form : true / false 
* 4. cover input tag with another tag 
*    -> example)  <label><input /></label>, <div><input /></div>
* 5. how to use
*    -> add data-forminejs='true'			> null check
*    -> add data-forminejs-minlength='3'	> min length check / param : number
*    -> add data-forminejs-maxlength='7'	> max length check / param : number
*    -> add data-forminejs-num='true'		> only number check
*	 -> add data-forminejs-ko='true'		> only korean check
*	 -> add data-forminejs-en='true'		> only english check
*	 -> add data-forminejs-id='true'		> only alphanumeric check (id pattern)
*	 -> add data-forminejs-mail='true'		> Mail pattern check : xxx@xxx.xxx
*    -> value of data type 
*       => false => not checking 
*       => true  => checking  
*	example) <input name="name" data-forminejs='true' data-forminejs-ko="true"/>
*
*/
