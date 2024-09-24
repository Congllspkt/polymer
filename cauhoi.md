

1. How do you group and process Vallidator processing? (5 points)


validate 


validategroup 


validate-group


```validation-group```

2. What event is called when the status value of the selected row changes? (5 points)

http://techdocs.emro.co.kr/display/SF10/sc-grid+API

※ See sc-grid API


changeItemState


stateChanged


itemChanged


```itemStateChanged```





3. This is a technology that packages front-end resources used by clients into jar fils. Representative examples include sc-component.jar, sc-upload.jar, and sc-upload.jar. What is this technology? (5 points)


FrontEndJars


RsourceJars


WebJars


JsJars


4. What class is responsible for handling all errors that occur in the application? (5 points)

http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80381595

※ Refer to the error page designation


AllExceptionHandler


ConsoleExceptionHandler


DefaultExceptionHandler


```SpringWebExceptionHandler```

5. Which of the following is a correct description of the 'stateful' option in scheduler management? (5 points)

http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80380815

※ 1. See Batch Scheduler Registration


This is an option to check whether the scheduler was executed normally.


Option to have multiple instances when running the scheduler.



```This is n option to prevent the same job from being executed before the previous task is finished when the scheduler is executed.```



This is n option to run the same job at the same time even if the previously executed task has not finished when the scheduler is executed.





6. When using multiple transactions, all defined data source connections are secured, resultingin an excessive connection pool. What class should be used to create a connection at the time the data source is used? (5 points)


AfterConnectionDataSourcePorxy


AsyncConnectionDataSourcePorxy


LaterConnectionDataSourcePorxy


LazyConnectionDataSourcePorxy



7. The following are common services that are absolutely necesary after login authentication and before the initial Main (MDI) screen. What is wrong with the service request URL? (5 points)

Check the information called when logging in (using developer tools)

Multilingual information (getByLastUpdated.do)


Session information (getSessionUser.do)


User permissions information (getUserRoles.do)


Multilingual information (getAvailableLocalizedLocales.do)


Menu information (findListMenu.do)

8. tr hidden=(5 points)

https://smartx-10.emro.co.kr/devops.do

※ See Other > Dynamic Screen Control


{{formula('isView')}}


{formula('isView')}


`[[formula('isView')]]`


[formula('isView')]


![alt text](image-4.png)


9. 10.0 What file checks the contents of the XSS filter applied in the solution? (5 points)

http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80381575 

※ Refer to Cross-site Scripting (XSS)

[text](http://techdocs.emro.co.kr/pages/viewpage.action?pageId%3D80381575)
web.xml


```security-context.xml```


web.xml/security-context.xml


web.xml / security-context.xml / trasaction-context.xml

10. How do you use es-date-field to receive a date in string format? (5 points)

https://smartx-10.emro.co.kr/devops.do

※ Field > See main fields


string format


string_format


`string-date`


string_date

![alt text](image-5.png)



11. Regarding the database, wehave a default propagation/isolation setting so that all services have the same transaction. What is the default setting? (5 points)


`REQUIRED`


REQUIRES_NEW


MANDATORY


NEVER


12. What event is called when an element is selected when calling tab-navigation? (5 points)

https://smartx-10.emro.co.kr/devops.do

※ Refer to module configuration

![alt text](image-1.png)


item-active


active-item


`?????item-select`


select-item



13. This is an attack that causes a user to request a specific website to perform an action (modification, deletion, registration, etc.) intended by the attacker without te user's consent. This is also called cross-site request forgery. What verification method is being used to prevent this? (5 points)

http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80381583

※ See CSRF defense


Referer Verification


```CSRF Token Verification```


XSS Verification


Use CAPTCHA


14. How do I set up the grid copy protection function? (5 points)

http://techdocs.emro.co.kr/display/SF10/sc-grid+API

※ See sc-grid API


copyDisabled


```copyEnabled```


disabledCopy


enabledCopy



15. Here are the log settings: 


logging.destination=C://smartsuite logging.level=INFO logging.lightLogging=false logging.includeControllerParameter=true logging.includeServiceParameter=false logging.forceLoggigList=\ 


Which of the following options would reduce the information in the log due to performance or capacity issues? (5 points)

http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80382319

※ Refer to Execution Log

Subjective answer: `logging.lightLogging`

16. How to call only the [readOnly] formula again in Event after saving? (5 points)

https://smartx-10.emro.co.kr/devops.do

※ See Other > Dynamic Screen Control

Subjective answer [[formula('readOnly')]]

me.applyFormula("readOnly")


17. When the myFunction functin is defined as shown below in JavaScript, describe the result value that appears when calling the myFunction function (20 points)

{code}


myFnction: function(data1, data2){
 
  
 
 

var result = null;


 if (data1 && data2){
 
  
 
 

result = data1 + data2;

  

}

 


 

result;

 
 }

{code}

The result when calling myFunction(-1, 1); is: 0

The result when calling myFunction(0, 1); is: null

The result when calling myFunction(null, 2); is: null

The result when calling myFunction("1", 2); is: "12"

The result when calling myFunction("", 2); is: null

5. What TransactionManager object are you using to use multiple transactions? (5 points)

http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80382828

※ Refer to Development Environment Settings (Database)


`ChainedTransactionManager`


DataSourceTransactionManager



DefaultTransactionManagerLookup

 

JtaTransactionManager


7. How to set an extension that cannot be attached in the attachment component? (5 points)

https://smartx-10.emro.co.kr/devops.do 

※ Other > See attached file


limit-extension


restrict-extention


ban extension


prohibit-extension

11. What component is used when indicating From-To for year/month? (5 points)

https://smartx-10.emro.co.kr/devops.do

※ Field > See main fields


sc-period-date-filed


sc-date-period-field


`sc-period-month-field`


sc-month-period-field

![alt text](image-2.png)

12. Which property sets additional options for downloading Excel from the grid function? (5 points)

http://techdocs.emro.co.kr/display/SF10/sc-grid+API

※ See sc-grid API


excelOptions


downloadExcelOptions


`exportOptions`


exportExcelOptions


16. How do I allow only PDF attachments in my attachments? (5 points)

https://smartx-10.emro.co.kr/devops.do

※ Other > See attached file

Subjective answer: = extension="pdf"

![alt text](image-3.png)



17. The module below is not currently being printed. The purpose of the em-test module is to call the load unction of the es-test module at initialization time. Please find the cause of the non-printing, fix it, and submit it. (20 points)

- Assuming that there are no errors in the es-test module, the load function is defined in the es-test module.

- 1 hint script error, 2 html related errors


{code}

<sc-link rel="import" href="es-test.html" />

<dom-module id="em-test">


<style>

 

:host {

  

@apply(--vbox-layout);



}

  

</style>

 



<template>

 

<es-test style="esTest" ></es-test>

  

</template>

 



<script>

 


  

Polymer({

  

is: 'em-test',



properties : {



resultList: {

 
 
 

 type:Array
 

  
  

}

 
 
 

},



initialized : function(){
me.$.esTest.load("test");

},



myTestFunction : function(){

}

});

  

</script>
 </dom-module>

{code}

Descriptive answer



Regarding the atabase, we have a basic propagation/isolation setting so that all services have the same transaction. What is the default setting

`REQUIRED`

REQUIRES_NEW

MANDATORY

NEVER

4. How to apply after modifying multiple rows of grid data? (5 points)

http://techdocs.emro.co.kr/display/SF10/sc-grid+DataProvider+API

※ See sc-grid DataProvider

setCellValue

setCellBatch

setItemAt

setItemAtBatch

8. What is the top priority for style when setting up a column? (5 points)

http://techdocs.emro.co.kr/display/SF10/sc-grid+API

※ See sc-grid API

`required`

itemStyleFuction

rowStyleFunction

editable

15. Which option is set when applying duplication among the Quartz scheduler options? (5 points)

http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80380813

※ Refer to the developer guide

Subjective answer: `org.quartz.jobStore.clusterCheckinInterval`

16. I want to change the background color of the column based on the top value in the grid. Please write which function should I use. (5 points)

http://techdocs.emro.co.kr/display/SF10/sc-grid+API

※ See sc-grid API

Subjective answer: me.applyFormula("readOnly")

17. I want to output a query on the order details from the ERD structure below.
Please complete the query. (20 points)
 

![alt text](961f032ba4f6f6ecc74581d5ffca8193_1623976966_5925.png)

SELECT


   orderHeader.orderNumber orderItem.orderNumber

   orderHeader.orderTitle

   orderItem.itemCode

   orderItem.itemAmount

   purchaseRequestDetail.purchaseRequestAmount FROM orderHeader

   …


Descriptive answer


1. Which context.xml defines Cross-site Scripting (XSS) related settings? (5 points)
http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80381575

※ Refer to Cross-site Scripting (XSS)

①
attachment-context.xml

②
security-context.xml

③
application-context.xml

④
dispatcher-context.xml
2. Which property sets additional options for downloading Excel from the grid function? (5 points)
http://techdocs.emro.co.kr/display/SF10/sc-grid+API
※ See sc-grid API

①
excelOptions

②
downloadExcelOptions

③
exportOptions

④
exportExcelOptions

3. This is an attack that causes a user to request a specific website to perform an action (modification, deletion, registration, etc.) intended by the attacker without the user's consent. This is also called cross-site request forgery. What verification method is being used to prevent this? (5 points)
http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80381583

※ See CSRF defense

①
Referer Verification

②
CSRF Token Verification

③
XSS Verification

④
Use CAPTCHA


4. How to apply after modifying multiple rows of grid data? (5 points)
http://techdocs.emro.co.kr/display/SF10/sc-grid+DataProvider+API
※ See sc-grid DataProvider

①
setCellValue

②
setCellBatch

③
setItemAt

④
```setItemAtBatch```

5. What class is responsible for handling all errors

nt is called when an element is selected when callin


10.0 What file checks the contents of the XSS filter applied in the solution? (5 points)



8. How do you group and process Vallidator processing? (5 points)

 do I set up the grid copy protection fun


11. When using multiple transactions, all defined data source connections are secured, resulting in an excessive connection pool. What class should be used to create a connection at the time the data source is used? (5 points)


14. How do you use es-date-field to receive a date in string format? (5 points)

15. Here are the log settings: logging.destination=C://smartsuite logging.level=INFO logging.lightLogging=false logging.includeControllerParameter=true logging.includeServiceParameter=false logging.forceLoggingList=\ Which of the following options would reduce the information in the log due to performance or capacity issues? (5 points)


16. Which option is set when applying duplication among the Quartz scheduler options? (5 points)
http://techdocs.emro.co.kr/pages/viewpage.action?pageId=80380813

isDuplicate


17. I want to output a query on the order details from the ERD structure below.












The module below is not currently being printed. The purpose of the em-test module is to call the load function of the es-test module at initialization time. Please find the cause of the non-printing, fix it, and submit it. (20 points)
Assuming that there are no errors in the es-test module, the load function is defined in the es-test module.

1 hint script error, 2 html related errors

{code}

<style> 
   :host { @apply(--vbox-layout); } 
</style>
<script> 
   Polymer({ is: 'em-test', 
      properties : { 
         resultList: { type:Array } 
      }, 
      initialized : function(){ 
            var me = this;
            me.$.esTest.load("test"); 
      }, 
      myTestFunction : function(){ 
      } 
      }); 
      </script>
{code}


3. I want to change the color of the user's ID column according to the top value in the grid. Please write which function should be used. (20 points) (20 points)
http://techdocs.emro.co.kr/display/SF9/grid+configs

See Grid Configs

3. 그리드 내에 상단 값에 따라서 사용자의 아이디 컬럼의 색을 변경하려고 합니다. 어떤 Function 을 사용해야하는지 작성해 주세요.(20점)(20점)
http://techdocs.emro.co.kr/display/SF9/grid+configs

그리드 Configs 참조

주관식답



2. Which of the following is a correct description of the 'stateful' option in scheduler management? (5 points)



ent is called when an element is selected when calling tab-



8. This is a technology that packages front-end resources used by clients into jar files. Representative examples include sc-component.jar, sc-upload.jar, and sc-upload.jar. What is this technology? (5 points)

FrontEndJars


RsourceJars


WebJars


JsJars

9. 다음은 로그인 인증 후, 초기 Main(MDI) 화면 전에 반드시 필요로 하는 공통 서비스입니다. 서비스 요청 URL이 잘못된 것은 무엇인가요?(5점)
로그인 시 호출하는 정보 확인 (개발자 도구 활용)

다국어 정보(getByLastUpdated.do)

①
세션 정보(getSessionUser.do)

②
`사용자 권한정보(getUserRoles.do)`

③
다국어 정보(getAvailableLocalizedLocales.do)

④
메뉴 정보(findListMenu.do)

o you group and process Vallidator pro



ent is called when the status value of 


lled when the status value of the sele

tionManager object are you using to use multip

to call only the [readOnly] formula again in Event

rowStyleFunction

when indicating From-To for year/m


s additional options for downloading Excel fro

. javascript에서 아래와같이 myFunction함수가 정의 됐을때 myFunction 함수를 호출 할경우 나오는 결과값을 기술하세요.(20점)(20점)
{code}



myFunction: function(data1, data2){



 var result = null;



 



 if(data1 && data2){



  result = data1 + data2;



 }



 



 result;



}



{code}



myFunction(-1, 1); 호출시 나오는 결과 값 : 



myFunction(0, 1); 호출시 나오는 결과 값 : 



myFunction(null, 2); 호출시 나오는 결과 값 : 



myFunction("1", 2); 호출시 나오는 결과 값 : 



myFunction("", 2); 호출시 나오는 결과 값 : 
