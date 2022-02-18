### JSON
 1. Создать внешний репозиторий c названием JSON:
      + GitHub > repository > new> JSON> add a README file> create repository 
 2. Клонировать репозиторий JSON на локальный компьютер:
      + копировать ссылку на репозиторий > GitBash > git clone https://github.com/DaryaShramko/JSON.git > ls -la чтобы проверить наличие папки в директории
 3. Внутри локального JSON создать файл “new.json”:
      + cd JSON cat > new.json (TEXT) CTRL + C
 4. Добавить файл под гит:
      + git status ,  git add new.json 
 5. Закоммитить файл:
      + git commit -m "add json file" 
 6. Отправить файл на внешний GitHub репозиторий:
      + git push
 7.  Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON:
    + cat > new.json 
```
        {
"AboutMe" : [

    {  "name":"Darya Shramko",
    
      "age" : 25,
     
    
      "MyPets" : 
{   
      "DogName" : "Roki",
      
      "Rat1" : "Shura",
      
      "Rat2" : "Mura",
      
      "Fish" : "Eduard"
      
      }, 

      "startsalary" : "500"  
  } ] 
}
CTRL + C
````

 8.  Отправить изменения на внешний репозиторий:
      +  git status , git add new.json, git status, git commit -m "change" git push 
 9.  Создать файл preferences.json:
      + cat > preferences.json 
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON:
````     
{
"Preferences" : [ 
    {  "season":"Abdolotely love every season",

      "Music" : 
{      "genre" : "iammeloman",
      "genre2" : "pop",
      "genre" : "hardcore_deathcore_rapcore",
      "genre" : "deephouse"
      }, 

      "movie" : 
{      "genre": "itdoesentmetter",
       "dontlike": "horrormovie" 
       },
      "country" :
{      "cntr1": "Czech",
       "cntry": "Spain",
       "cntr3": "Georgia" 
}   
  } ] 
}

  CTRL +C
  ````

 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON:
      +  cat > sklls.json > 
````      
{
"Myskills_after_course" : [ 
    {  "I_wish_i_could_work_with":"example_below",

      "sklls": 
{      "sklls1" : "Jmeter",
      "sklls2" : "GitBash",
      "sklls3" : "some_script",
      "sklls4" : "AndroidStudio",
      "sklls5": "Postman",
      "sklls6": "Xcode"  
}   
  } ] 
}

 > CTRL + C
 ````
 12. Отправить сразу 2 файла на внешний репозиторий:
      +  git status, git add . , git status , git commit -m "some information" git push  
 13. На веб интерфейсе создать файл bug_report.json:
     + GitHub > repozitory> add new
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
     + CommitsChanges
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON:
     + зайти в репозиторий, нажать на bug_report.xml > edit file 
````
     {
	"bug_report": [{
		"i_found_bug": "report_below",
		"bugs": {
			"summary": "PHP_error_appears_in_window_after_input_SQL_request_in_lield_of_login",
			"description": "if_enter_SQL_request_in_lield_of_login_and_press_Поехали_button_PHP_error",
			"Requirement_ID": "no",
			"Reproduced_on": "Chrome",
			"Reproducibility": "always",
			"Workaround": "no",
			"steps_to_reproduce": "Open_page_via_URL_http:megatask_Enter_DB_request_(SELECT_FROM_users_WHERE_u_ul_LIKE_in_field_Enter_correct_password__in_field_Press_Поехали_button",
			"severity": "minor",
			"priority": "no"
		}
	}]
}

````
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
     + commit changes
 17. Синхронизировать внешний и локальный репозиторий JSON:
     + git pull
