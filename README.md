# input-pattern-controller-for-mobiles-in-iran
input pattern controller for mobiles in Iran

در این نمونه در

##  form.html
 
 در قسمت
 
    <input type="number" class="form-control" name="phone" value="{{ phone | default('')}}" pattern="09(0[1-2]|[0-9][0-9]|3[0-9]|2[0-1])-?[0-9]{3}-?[0-9]{4}" maxlength="10" size="10" placeholder="موبایل ،مثلا: 09981152407" required>
      
 
attribute با استفاده از اتریبیوت 
     
##   pattern

     شماره موبایل صحیح از کاربر دریافت میکنیم.
   
   ###
     
     بدون نیاز به 
     css
     یا
     js
     
     
     با تشکر از برنامه
     https://www.regextester.com/
     
     @RegExTester
     
