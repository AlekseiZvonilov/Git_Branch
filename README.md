1. На локальном репозитории сделать ветки для:   
* Postman - git branch Postman     
* Jmeter - git branch Jmeter  
* CheckList - git branch CheckList   
* Bug_Reports - git branch Bug_Reports   
* SQL - git branch SQL    
* Charles - git branch Charles     
* Mobile_testing - git branch Mobile_testing    
    
2. Запушить все ветки на внешний репозиторий  
* git push -u origin --all    

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта    
* git checkout Bug_Reports    
* cat > bug_report.txt   
  ►ID    
  ►Title   
  ►Componennts  
  ►Summary  
  ►Expected_result  
  ►Actual_result  
  ►Severity  
  ►Priority  
  ►Description  
  ►Attachment  
* Enter
* Ctrl + D
     
4. Запушить структуру багрепорта на внешний репозиторий   
* git add .    
* git commit -m "add bug_report.txt"
* git push 
   
5. Вмержить ветку Bug Reports в Main  
* git checkout main 
* git merge Bug_Reports  

6. Запушить main на внешний репозиторий  
* git add .    
* git commit -m "merge Bug_Reports"    
* git push    

7. В ветке CheckLists набросать структуру чек листа   
* git checkout CheckList   
* cat > checklist_my_morning.txt   
  ►woke up    
  ►washed up   
  ►breakfast    
  ►got dressed    
  ►ran away to work    
* Enter
* Ctrl + D

8. Запушить структуру на внешний репозиторий  
* git add .   
* git commit -m "add checklist_my_morning.txt"   
* git push   

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main   
* Pull Request   

10. Синхронизировать Внешнюю и Локальную ветки Main   
* git checkout main 
* git pull  
  
      
