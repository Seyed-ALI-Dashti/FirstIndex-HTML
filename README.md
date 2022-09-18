# MyCodes
My exercises and mini projects
Form

<!DOCTYPE html>
<html>

<head>
     <meta charset="UTF-8">
     <title> Web Design </title>
</head>

<body>
     
     <form dir="rtl" style="font-family: b yekan">
          <fieldset>
               <legend align="center" style="color: rgb(5, 218, 200) ; font-size: 22px;"> فرم ثبت سفارش طراحی سایت  </legend>
               <p style="color: red ; font-size: 13px;"> نکته 1 : خدمات مندرج در این فرم میتواند از سوی مشتری خصوصی سازی شود !</p>
               <p style="color: red ; font-size: 13px;"> نکته 2 : فیلد هایی که دارای علامت <b> * </b> هستند ، باید توسط کاربر کامل شود ! </p>
               <p style="color: red ; font-size: 13px;"> نکته 3 : حتما در تکمیل فیلد ها ازجمله انتخاب نوع وب سایت دقت نمایید ! </p>
               <br>
               <form>
                    <label for="first name"><b> * </b>نام : </label>
                         <input type="text" name="first name" id="first name" placeholder="نام خود را وارد نمایید . . ." required>
               <br><br>
                    <label for="last name"><b> * </b>نام خانوادگی :  </label>
                         <input type="text" name="last name" id="last name" placeholder="نام خانوادگی خود را وارد نمایید . . ." required>
               <br><br>
                    <label for="email"><b> * </b> پست الکترونیکی : </label>
                         <input type="email" name="email" id="email" placeholder="ایمیل خود را وارد نمایید . . ." size="30" required>
               <br><br>
                    <label for="phone"> شماره منزل / محل کار: </label>
                         <input type="tel" name="phone" id="phone" placeholder="شماره منزل یا محل کار خود را وارد نمایید . . ." size="30">
               <br><br>
                    <label for="phone2"> شماره همراه : </label>
                         <input type="tel" name="phone2" id="phone2" placeholder="شماره همراه خود را وارد نمایید . . ." size="30">
               <br><br>
                    <label for="color website"> تم موردعلاقه شما برای سایت تون : </label>
                         <input type="color" name="color website" id="color website" value="#ccff55">
               <br><br>
                    <p> بودجه شما برای انجام پروژه : </p>
                    <label for="1-5"> 1میلیون تا 5 میلیون تومان </span>
                         <input type="radio" name="bodje" id="1-5">
                    <label for="5-10"> 5 میلیون تا 10 میلیون تومان </span>
                         <input type="radio" name="bodje" id="5-10">
                    <label for="10"> 10 میلیون تومان به بالا </label>
                         <input type="radio" name="bodje" id="10" checked>
               <br><br>
                    <label> <b> * </b> نوع وب سایت شما : </label>
                         <select required>
                              <option style="color:green ; font-size: x-large;"><b> خدماتی </b></option>
                              <option style="color:rgb(255, 187, 0) ; font-size: x-large"> فروشگاهی </option>
                              <option style="color:rgb(121, 38, 121) ; font-size: x-large"> شرکتی </option>
                              <option style="color:rgb(228, 5, 161) ; font-size: x-large"> شخصی </option>
                              <option style="color:darkblue ; font-size: x-large"> سایر </option>
                         </select>
               <br><br>
                    <p> خدمات اضافه : </p>
                    <label for="seo"> SEO (سئو) </label>
                         <input type="checkbox" name="seo" id="seo">
                    <label for="bs"> Reactivity (واکنشگرایی) </label>
                         <input type="checkbox" name="bs" id="bs">
                    <label for="ads"> Google ads (تبلیغات گوگل) </label>
                         <input type="checkbox" name="ads" id="ads">
               <br><br>
                    <label> زمان مطلوب شما برای تحویل پروژه : </label>
                    <span> 20 روز </span>
                         <input type="range" name="time">
                    <span> 40 روز </span>
               <br><br><br>
                    <textarea name="توضیحات اضافه" placeholder="توضیحات..." cols="30" rows="10"></textarea>
               <br><br>
                         <input type="submit" value="ثبت درخواست" name="submit">
                         <input type="reset" value="پاک کردن فرم">
               </form>
          </fieldset>
     </form>

</body>

</html>

